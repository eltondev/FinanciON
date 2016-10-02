# FinanciON

Requires at least: 2.0
Tested up to: 2.1
Stable tag: 2.10
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

FinanciON é um sistema básico para controle financeiro e Ordens de Serviço feito com code Iginiter.

#### Informações

1. **Cadastro de Clientes**
2. **Cadastro de Produtos e Serviços**
3. **Financeiro**
    * Entrada
    * Saída
    * Contas a Pagar e Receber
4. **Gerenciamento de OS**
5. **Backup**

#### Configurações

Primeiramente imposte a base de dados que está dentro da pasta DB, feioto isso 
teremos que editar alguns arquivos!

Dentro da pasta ```applications/config/``` abra o arquivo ```config.php``` encontra alinha 17, veja:

```
$config['base_url']	= 'http://eltondev.com.br/financeiro';
```
Altere para a URL de onde está instalando o sistema, feito isso ainda na pasta config
abra o ```database.php``` altere da linha 51 até a 54 para as configurações de seu servidor, veja:

```
$db['default']['hostname'] = 'localhost';
$db['default']['username'] = 'USUARIO';
$db['default']['password'] = 'SENHA';
$db['default']['database'] = 'BANCO_DE_DADOS';
```

Pronto, acesse a URL informada e logue com os seguintes dados:

Usuário: ```eltondeveloper@gmail.com```

Senha: ```1425361020```

###Dúvidas

Caso tenha alguma dificuldade em usar o sistema, abra uma issue com a duvida, problema ou idéia.

###Faça uma doação

Contribua com este projeto, caso queira doar envie para o Paypal: eltondeveloper@gmail.com


