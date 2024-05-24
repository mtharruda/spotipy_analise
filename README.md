# spotipy_analise
Código para analisar atributos musicais, como valência, energia, "dançabilidade", tempo, etc (leia mais abaixo), utilizando as bibliotecas *spotipy* para extrair dados da API do Spotify.

**Como começar?**
Acessando a API: Client ID, Cliente Secret e o Spotipy
Para ter acesso a API, é necessário que você se cadastre no site do Spotify que é dedicado a desenvolvedores (é possível utilizar tanto uma conta Premium quanto gratuita).
Após o cadastro e login, é necessário criar um app para obter um Client ID e Client Secret, que são necessários para conseguir o token de acesso.Não se assuste com palavras desconhecidas, caso nunca tenha usado uma API, que isto é relativamente fácil de fazer.
Para criar um app, basta ir na sua dashboard e clicar no “Create app”, inserindo os dados pedidos.
No “Redirect URI” apenas insira http://localhost:3000 conforme indica a documentação oficial.
Com seu app criado podemos conseguir o token de acesso. Como citado, precisaremos do Client ID e o Client Secret para extrair os dados. Essas duas chaves podem ser encontradas clicando botão “Settings” na página principal do app.
Essa página fornece o Client ID e clicando nas letras miúdas também podemos ter acesso ao Client Secret:

**Bibliotecas**
*Spotipy:* biblioteca do Python que utiliza a API do Spotify e extrai dados de músicas e usuários da plataforma de streaming. 
