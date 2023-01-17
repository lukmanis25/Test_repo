FROM alpine as intermediate

RUN apk update
RUN apk add git

RUN git clone --single-branch https://github.com/lukmanis25/Test_repo


FROM prestashop/prestashop:1.7.8.7

COPY --from=intermediate /Test_repo/test_html/test.html /var/www/html
