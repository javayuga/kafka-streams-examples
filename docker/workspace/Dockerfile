FROM maven:3.3-jdk-8

LABEL maintainer="Marco Silva <marcosilva.poa.br>"

ENV JAVA_TOOL_OPTIONS -agentlib:jdwp=transport=dt_socket,address=8000,server=y,suspend=n

CMD mvn --version && tail -f /dev/null