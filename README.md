# http://sahatyalkabov.com/create-a-character-voting-app-using-react-nodejs-mongodb-and-socketio/

# Instalando node

```sh
# Instalando dependências para o Node.js (Linux Ubuntu ~)
sudo apt-get install build-essential g++

# Instalando no nvm (gerenciador de instalação do nodejs)
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.29.0/install.sh | bash

# Instalando o nodejs 
nvm ls-remote            # listando todas as versões disponíveis
nvm install v5.2.0       # instalando a última versão
nvm alias default v5.2.0 # setando a versão como padrão

# Instalando depedências globais
npm install -g nodemon   # para uso no desenvolvimento, irá escutar os arquivos e diretórios e quando alterados irá fazer o restart automático do node
npm install -g bower     # gereciador de dependências de componentes front-end
npm install -g gulp      # automatizador de tarefas (concorrente do Grunt)
npm install -g node-gyp  # Ferramenta de build nativa do Node.js 
```

# Iniciando seu projeto

```sh
# Iniciando um projeto node
npm init

# Instalando dependências
npm install alt async body-parser colors compression express history mongoose morgan react react-dom react-router request serve-favicon socket.io swig underscore xml2js --save

# Instalando dependências para desenvolvimento
npm install babel-loader babel-core babel-preset-es2015 babel-preset-react babelify bower browserify gulp gulp-autoprefixer gulp-concat gulp-cssmin gulp-if gulp-less gulp-plumber gulp-streamify gulp-uglify gulp-util vinyl-source-stream watchify --save-dev

# Instalando os pacotes
npm install

# Iniciando aplicação
npm start # acesse http://localhost:3000/

# Iniciando o projeto bower
bower init

# Instalando dependências front-end
bower install jquery bootstrap magnific-popup toastr --save # ou "bower install" quando tiver o arquivo bower.json
```

# Referências

- [Node.js](https://nodejs.org/en/docs/)
- [nvm](https://github.com/creationix/nvm)
- [npm](https://docs.npmjs.com/)
- [nodemon](http://nodemon.io/)
- [bower](http://bower.io/)
- [gulp](http://gulpjs.com/)
- [babel](https://babeljs.io/)
- [browserify](http://browserify.org/)
- [webpack](http://webpack.github.io/)

# Dicas

- [Create a character voting app using React, Node.js, MongoDB and Socket.IO](http://sahatyalkabov.com/create-a-character-voting-app-using-react-nodejs-mongodb-and-socketio/)
- [Gulp o novo automatizador](http://tableless.com.br/gulp-o-novo-automatizador/)
- [Bower na prática](http://tableless.com.br/bower-na-pratica/)

# Troubleshooting

Trocar protocolo git:// por https:// do github

```sh
git config --global url.https://github.com/.insteadOf git://github.com/
```
