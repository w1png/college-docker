FROM alpine:latest

ENV INNER_HELLO="INNER WORLD"

RUN echo "INNER_HELLO=$INNER_HELLO"

RUN echo "HELLO=$HELLO"

CMD ["sh", "-c", "echo $HELLO $INNER_HELLO"]

