ARG NODE_VERSION
FROM node:${NODE_VERSION}

EXPOSE 1337

RUN wget https://github.com/libvips/libvips/releases/download/v8.12.1/vips-8.12.1.tar.gz
RUN tar xf vips-8.12.1.tar.gz
RUN cd vips-8.12.1 && ./configure && make && make install && ldconfig
