# Target: Use golang as base for CRUD API
# Some of the following frameworks:
# https://www.moesif.com/blog/api-product-management/api-analytics/Top-5-GO-REST-API-Frameworks/
# https://nordicapis.com/7-frameworks-to-build-a-rest-api-in-go/
FROM golang:1.18

RUN go install github.com/beego/bee/v2@v2.1.0
WORKDIR /go/src/app

ENTRYPOINT [ "bee" ]
CMD [ "run", "-downdoc=true", "-gendoc=true" ]
