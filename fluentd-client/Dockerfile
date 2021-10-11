FROM fluent/fluentd
CMD ["chmod", "-R" , "777", "/var/log/*.pos"]
RUN ["gem", "install", "fluent-plugin-grok-parser", "-v 2.1.4"]