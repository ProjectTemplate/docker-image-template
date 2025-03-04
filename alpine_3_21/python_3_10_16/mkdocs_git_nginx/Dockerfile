FROM python:3.10.16-alpine3.21

# 安装
RUN apk update && \
    apk add git && \
    apk add nginx && \
    pip install mkdocs && \
    pip install mkdocs-material && \
    pip install mkdocs-git-revision-date-localized-plugin && \
    pip install mkdocs-awesome-pages-plugin && \
    pip install mkdocs-git-committers-plugin-2 && \
    pip install mkdocs-git-authors-plugin && \
    pip install mkdocs-git-revision-date-localized-plugin

# docker build -t sunfeilong1993/mkdocs-git-nginx:0.0.1 .
# docker push sunfeilong1993/mkdocs-git-nginx:0.0.1