FROM 192.168.22.11/kubernetes/openjdk:8-jre-alpine

COPY target/ROOT /ROOT

ENTRYPOINT ["sh", "/ROOT/bin/start-in-docker.sh"]
