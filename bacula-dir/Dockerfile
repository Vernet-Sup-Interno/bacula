FROM vernetsupinterno/bacula-base:11.0.6

VOLUME ["/opt/bacula/etc"]

EXPOSE 9101/tcp

ENTRYPOINT ["bacula-dir"]

CMD ["-f", "-c", "/opt/bacula/etc/bacula-dir.conf"]
