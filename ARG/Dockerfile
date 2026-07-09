FROM almalinux:9
ENV course="DevOps with AWS" \
    trainer="krishna" \
    duration="100HRS"
#here user1 is key, someuser is default value
ARG USERNAME=krishna
RUN echo "Hello User: ${USERNAME}" > /tmp/devops.txt
CMD ["sleep", "100"]