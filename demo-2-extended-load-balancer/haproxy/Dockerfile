FROM haproxy:3.0.5

USER root
RUN mkdir -p /run/haproxy/
RUN chown haproxy:haproxy /var/run/haproxy/

# Change to user haproxy
USER haproxy
COPY haproxy.cfg /usr/local/etc/haproxy/haproxy.cfg