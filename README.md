# Docker Container MongoDB

- Criando o volume MongoDB
<pre>
# docker volume create --name MongoDB
</pre>

- Iniciando o container
<pre>
# cd $PWD/Docker_Container-MongoDB/
# docker build -f build/Dockerfile -t mongodb:1.0.0 .
# docker-compose up -d
</pre>
- Para acessar o container (user: root / pass: root)
<pre>
# ssh root@127.0.0.1 -p2200
</pre>
