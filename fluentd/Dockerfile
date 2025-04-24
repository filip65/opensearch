FROM fluent/fluentd:v1.16-1

USER root
RUN gem install fluent-plugin-opensearch --no-document

COPY fluent.conf /fluentd/etc/

USER fluent
