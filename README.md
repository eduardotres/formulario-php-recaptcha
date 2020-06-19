# fomulario-php-recaptcha
Exemplo de formulário de contato em PHP com reCAPTCHA e Boostrap 4.

Faz verificação dos campos do formulário e retorna uma lista de erros (campos faltando, e-mail inválido), caso haja algum. O Bootstrap 4 é usado como base do layout do formulário e do alerta de erros.

## Instruções
Baixe o arquivo e coloque-o na pasta desejada do seu site. Baixe também o recaptchalib.php e coloque-o na mesma pasta.
https://raw.githubusercontent.com/google/recaptcha/1.0.0/php/recaptchalib.php

Altere as variáveis no início do arquivo conforme as instruções do código. Ajuste a parte em HTML para se ajustar ao estilo do seu site.
O formulário tem 5 campos, além do reCAPTCHA:
- nome
- e-mail
- cidade
- assunto
- mensagem

Coloque o atributo "required" nos campos do formulário que quiser marcar como de preenchimento obrigatório, ou remova-os nos campos opcionais. O próprio browser vai verificar se foram preenchidos e, caso não, vai bloquear o envio dos dados.
