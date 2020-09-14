# Projeto Base

## Instalação

1. Inicialmente, corrija as permissões para o usuário do Docker. Na raiz do projeto, execute:

<pre><code>
bash fix_permissions.sh
</code></pre>


2. Para iniciar o container, dê o seguinte comando na raiz do projeto:

<pre><code>
docker-compose up -d
</code></pre>

3. Para obter o link para o Jupyter:

<pre><code>
docker exec jupyter_container jupyter notebook list
</code></pre>