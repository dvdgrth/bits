FROM gcc:9
COPY . /usr/src/myapp
WORKDIR /usr/src/myapp
RUN gcc -o main main.c
CMD ["./main"]