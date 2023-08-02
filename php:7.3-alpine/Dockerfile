FROM php:7.3-alpine
#FROM php:7.4-fpm


#ENV EXPOSE 80




RUN apk add nginx
#STOPSIGNAL SIGQUIT
EXPOSE 80
#ENTRYPOINT ["entrypoint"]
#CMD ["php-fpm"]
#CMD ["php", "-a"]
CMD ["nginx", "-g", "daemon off;"]