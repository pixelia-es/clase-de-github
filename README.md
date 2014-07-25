clase-de-github
===============

Este es un repositorio de prueba correspondiente a las clases de github de #mejorandola

Una vez instalas GIT, debes configurarlo:

git config --global user.name "Christian"
git config --global user.email "cvander@mejorando.la"

ssh-keygen

- agregarle un password

- Leyendo tu llave para copiarla en github (o en bitbucket)
cat ~/.ssh/github_rsa.pub

- Copias todo el texto

- Arrancando tu proyecto:

git init

touch README.md

git add README.md

git commit -m "tu primer commit"

git push origin master