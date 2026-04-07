FROM almalinux
ENV APP_HOME=/my_folder \
    APP_USER=ROBOSSHOP

RUN mkdir -p $APP_HOME && \
    useradd -m $APP_USER

WORKDIR $APP_HOME
CMD [ "mkdir",$APP_HOME ]
