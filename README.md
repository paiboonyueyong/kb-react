How to setup Node.js and Npm behind a corporate web proxy

npm config set proxy http://proxy:80 //office <br/>
npm config set proxy http://proxy.trueinternet.co.th:8080 //home

for HTTPS
npm config set https-proxy http://proxy.company.com:8080
