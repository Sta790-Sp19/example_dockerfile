FROM ubuntu:18.10

ENV DEBIAN_FRONTEND=noninteractive

RUN apt update \
 && apt install -y r-base \
 && Rscript -e "install.packages('tibble')"

CMD ["R"]
