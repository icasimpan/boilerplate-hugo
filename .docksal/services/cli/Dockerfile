# Use a stock Docksal image as the base
FROM docksal/cli:2.6-php7.3

# Install hugo 0.76.3
RUN wget -q https://github.com/gohugoio/hugo/releases/download/v0.76.3/hugo_0.76.3_Linux-64bit.deb -O /tmp/hugo.deb \
    && dpkg -i /tmp/hugo.deb
