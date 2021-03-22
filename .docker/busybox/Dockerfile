FROM busybox

COPY .docker/busybox/getter_script.sh /getter_script.sh
RUN chmod a+x /getter_script.sh
CMD ["/getter_script.sh"]