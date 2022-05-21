FROM livebook/livebook:0.6.1

RUN groupadd -g 5000 livebook
RUN useradd -u 5000 -g 5000 -M -d /home/livebook -r livebook

RUN chmod -R go=u /app

USER livebook
