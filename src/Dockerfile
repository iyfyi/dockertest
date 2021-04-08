FROM php
WORKDIR /code
COPY index.php index.php
ENTRYPOINT                                                                     \
  ["php"]
CMD                                                                            \
  ["-f","index.php","-S","0.0.0.0:8080"]
