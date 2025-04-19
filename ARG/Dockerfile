FROM almalinux:9   
ENV year="2025" \
    month="april" \
    day="18th Friday"
ARG USER ${username:-some_user}

RUN echo "HELLO ${username}" > /tmp/devops.txt
CMD["sleep","100"]