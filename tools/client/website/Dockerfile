#a simple nginx site with index page
FROM nginx:1.13.3-alpine
COPY index.html /usr/share/nginx/html
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]

