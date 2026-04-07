FROM almalinux
RUN useradd -m josh && \
     mkdir /folder1
USER  josh

WORKDIR /folder1
#WORKDIR logs
COPY index.html /folder1/
CMD [ "sleep","2000" ]
