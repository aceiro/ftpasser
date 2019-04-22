# FTP
Registro das aulas

Este é o FTP utilizado na Faculdade ASSER pelo professor Cristiano José Cecanho para organizar um cronograma do que será lecionado em cada aula.


* **Clone do projeto**

``$ git clone https://github.com/aceiro/ftpasser.git``

* **Baixar o Node.js**

``$ curl -sL https://deb.nodesource.com/setup_11.x | sudo bash -``

* **Verificar se existe os pacotes de dev para C++**

``$ apt-get install gcc g++ make``

* **Instalar o Node.js**

``$ sudo apt-get install -y nodejs ``

* **Configurar o yarm**

``$ curl -sL https://dl.yarnpkg.com/debian/pubkey.gpg | apt-key add -``

``$ echo "deb https://dl.yarnpkg.com/debian/ stable main" | tee /etc/apt/sources.list.d/yarn.list``

``$ apt-get update && sudo apt-get install yarn``

* **Verificar a instação**

``$ node -v ``

``$ npm -v ``

* **Instalar o BrowserSync**

``$ npm install -g browser-sync``

* **Iniciar o servidor**

``$ browser-sync start --server --files "css/*.css"``



