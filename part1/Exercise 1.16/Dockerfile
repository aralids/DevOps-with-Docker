# This is a copy of the image at https://hub.docker.com/layers/devopsdockeruh/coursepage/latest/images/sha256-042995863c486f9579bceb18e9ff428f5b1dd48125f5518a6e558a61ac6d3bf2?context=explore

ADD file ... in /

CMD ["/bin/sh"]

ENV NODE_VERSION=22.2.0

/bin/sh -c addgroup -g 1000

ENV YARN_VERSION=1.22.19

/bin/sh -c apk add --no-cache

COPY file:4d192565a7220e135cab6c77fbc1c73211b69f3d9fb37e62857b2c6eb9363d51 in /usr/local/bin/

ENTRYPOINT ["docker-entrypoint.sh"]

CMD ["node"]

ENV PORT=80

RUN /bin/sh -c npm install

COPY /usr/src/app/build /usr/src/html # buildkit

CMD ["/bin/sh" "-c" "serve -l
