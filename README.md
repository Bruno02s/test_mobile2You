# DOCPOST API

## Versão de Ruby e Rails

- Ruby 3.0.1
- Rails 6.1.4

## Instruções para acessar a aplicação°

Como foi configurado um subdominio 'api' nesta aplicação o método de acesso por 'api.mobile2you'
e preferencial.

Siga as instruções abaixo para configurar o address

### Config Windows
    Abra o bloco de notas no modo ADMINISTRADOR

    Vá em abrir e acesse a seguint rota: 'C:\Windows\System32\drivers\etc\' e selecione o arquivo 'hosts'

    na última linha do arquivo cole o código entre aspas abaixo:

    "#setup subdomain for rails applications"

    "127.0.0.1 api.mobile2you"

### Config Linux
    O processo e o mesmo! Acesse 'etc/host' na raiz do linux e cole os código entre aspas:

    "#setup subdomain for rails applications"

    "127.0.0.1 api.mobile2you"

Após ter feito os passos levante o servidor normalmente

e acesse a aplicação por _http://api.mobile2you:3000_ 
