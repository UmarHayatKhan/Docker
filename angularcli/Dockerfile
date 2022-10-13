FROM node:14.17.5

LABEL authors=Umar Hayat khan <umarhayatmail@gmail.com>

RUN npm install -y -g @angular/cli@v13.3.11
   &&  npm npm install -y -g @angular/cdk@13.3.9
   &&  rm -rf /tmp/* /var/cache/apk/* *.tar.gz ~/.npm
   &&  npm cache clear --force
   &&  sed -i -e "s/bin\/ash/bin\/sh/" /etc/passwd
