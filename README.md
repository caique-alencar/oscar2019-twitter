<h1>Oscar 2019 no Twitter</h1>

Scraping de palavras mais usadas no Twitter durante durante a cerimônia do Oscar2019.

Para acessar a API, usei minhas credenciais em um arquivo separado que não subi para o repositório. Para definir as credenciais, rode o seguinte o código antes:

<pre><code>import json<br>
twitter_credentials = {}<br>
twitter_credentials['consumer_key'] = 'DIGITE AQUI SEU CONSUMER KEY'<br>
twitter_credentials['consumer_secret'] = 'DIGITE AQUI SEU CONSUMER SECRET'<br>
twitter_credentials['access_token'] = 'DIGITE AQUI SEU ACCESS TOKEN'<br>
twitter_credentials['access_token_secret'] = 'DIGITE AQUI SEU ACCESS TOKEN SECRET'<br>
with open('credenciais_twitter.json', 'w') as secret_info:<br>
  json.dump(twitter_credentials, secret_info, indent=4, sort_keys=True)<br></code></pre>
