FROM python:latest
ARG UNAME=user1001
ARG UID=1001
ARG GID=1001
RUN groupadd -g $GID -o $UNAME
RUN useradd -m -u $UID -g $GID -o -s /bin/bash $UNAME
USER $UNAME
WORKDIR /app
EXPOSE 8000
CMD python -m http.server 8000