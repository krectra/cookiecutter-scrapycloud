FROM scrapinghub/scrapinghub-stack-scrapy:2.0-latest

WORKDIR /app
ADD . /app
RUN set -x \
    && pip --no-cache-dir \
      --disable-pip-version-check \
      install -r /app/requirements.txt

CMD ["scrapy", "list"]
