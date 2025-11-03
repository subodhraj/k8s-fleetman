FROM nginx:1.29.3-alpine

MAINTAINER Richard Chesterwood "richard@inceptiontraining.co.uk"

RUN rm -rf /usr/share/nginx/html/*

COPY /dist /usr/share/nginx/html

CMD ["nginx", "-g", "daemon off;"]
