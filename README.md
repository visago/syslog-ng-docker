# Syslog-ng Remote UDP syslogger
docker run -d --name syslog-ng -p 514:514 -p 514:514/udp -v /opt/syslog-ng/:/data visago/syslog-ng

Note: There's no file pruning, this will eat up your whole drive !
