ARG version
FROM almalinux:${version:-9}   
ENV year="2025" \
    month="april" \
    day="18th Friday"

ARG USERNAME=Rohitth
ENV USERNAME=${USERNAME}
RUN echo "HELLO USER: ${USERNAME} image version:${version}" >/tmp/devops.txt
CMD ["sleep","100"]