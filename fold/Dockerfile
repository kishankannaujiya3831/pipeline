FROM fluentd:v1.9.1-1.0
USER root
RUN fluent-gem install fluent-plugin-s3
COPY fluentd.conf /fluentd/etc/fluent.conf

