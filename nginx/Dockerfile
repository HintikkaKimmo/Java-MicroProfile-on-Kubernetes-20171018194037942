FROM nginx:1.23.1

# Copy custom configuration file from the current directory
COPY nginx.conf /etc/nginx/nginx.conf
COPY ./entry.sh /
RUN chmod 755 /entry.sh
ENTRYPOINT ["/entry.sh"]
