FROM grafana/grafana

ADD ./provisioning /etc/grafana/provisioning
COPY ./grafana.ini /etc/grafana/grafana.ini
COPY ./entrypoint.sh /entrypoint.sh

USER root
RUN chmod +x /entrypoint.sh
USER grafana

ENTRYPOINT ["/entrypoint.sh"]
