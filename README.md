<h2> How to setup Node.js and Npm behind a corporate web proxy </h2>

npm config set proxy http://proxy:80 //office <br/>
npm config set proxy http://proxy.trueinternet.co.th:8080 //home

for HTTPS
npm config set https-proxy http://proxyNPM Package registry from .company.com:8080


<h2> NPM Fails Worldwide With "ERR! 418 I'm a Teapot" Error </h2> 

Change NPM Package registry from registry.npmjs.org to registry.npmjs.org:443
> npm config set registry https://registry.npmjs.org:443

Print current NPM Package registry
> npm config get registry

