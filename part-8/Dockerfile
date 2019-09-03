FROM php:cli

COPY index.php /app/index.php
WORKDIR /app

ENTRYPOINT [ "php" ]
CMD ["-S", "0.0.0.0:8080", "index.php"]
