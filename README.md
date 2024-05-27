# spotipy_analise
Código para analisar atributos musicais, como valência, energia, "dançabilidade", tempo, etc (leia mais abaixo) de discos. Para a tarefa, utiizamos a bibliotecas *spotipy* para extrair dados da API do Spotify.

**Como começar?**
Acessando a API: _https://developer.spotify.com/documentation/web-api/tutorials/getting-started_ 
Para acessar e utilizar os recursos da API, é necessário que você se cadastre no site acima. Após se cadastrar, é necessário criar um app para obter um _client ID_ e _client Secret_, que são necessários para gerar o token de acesso.
Seguindo o tutorial, para criar um app, basta ir na sua dashboard e clicar em _Create app_ e inserir os dados solicitados.

**Atenção: ** Na caixa _Redirect URI_, devemos inserir o endereço **"http://localhost:3000"**, conforme a documentação.

Após seguir os passos listados acima, o app está pronto e podemos solicitar o token de acesso.
Com seu app criado podemos conseguir o token de acesso. Como citado, precisaremos do Client ID e o Client Secret para extrair os dados. 

*Características musicais*
_Documentação > https://developer.spotify.com/documentation/web-api/reference/get-audio-features_

**Bibliotecas**
*Spotipy:* biblioteca do Python que utiliza a API do Spotify e extrai dados de músicas e usuários da plataforma de streaming. 
