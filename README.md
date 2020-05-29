# API para acompanhamento da Covid19 em Vilhena - RO

Para rodar a API na porta padrão 3000:
Utilizar o pm2 para gerenciar
```
json-server db.json --read-only
```

Rodar o front-end no Nginx
/ => front-end
/api => API

Para capturar dados da planilha:
```
node get-data.js
```
Precisa do arquivo `credentials.json`

Criar script.sh para parar o json-server, capturar os dados e ativar novamente
