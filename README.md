# Relatório de Vendas Twilio

Este script em Python analisa os dados de vendas mensais armazenados em arquivos Excel e notifica por SMS os vendedores que superaram a meta de vendas.

## Uso

1. Configure as credenciais Twilio:
   - Abra o script e substitua os valores de `account_sid` e `auth_token` pelos fornecidos pela sua conta Twilio.

2. Execute o script:
   - Certifique-se de ter instalado as bibliotecas necessárias do Python. Consulte o arquivo `requirements.txt` para obter detalhes.
   - Execute o script em um ambiente Python.

3. Resultados:
   - O script verifica os arquivos Excel correspondentes a cada mês.
   - Se um vendedor superou a meta de vendas de 55.000, uma mensagem SMS é enviada com os detalhes da conquista.
   - Os resultados são exibidos no console.

## Instalação

1. Clone o repositório:

   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   cd seu-repositorio
