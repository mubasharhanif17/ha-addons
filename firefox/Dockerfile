FROM jlesage/firefox:v25.03.1

COPY rootfs/startapp.sh /startapp.sh
# Makes sure that the line endings are correct
RUN sed -i 's/\r$//' /startapp.sh
RUN chmod +x /startapp.sh
