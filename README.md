# Desafio-net-documentacao-de-testes


#Plano de testes para funcionalidade de PIX

## Objetivo:

Testar a funcionalidade de PIX de acordo com os requisitos da user story definida.

## Escopo:

- Dados da transação: valor, chave PIX do destinatário e mensagem opcional.
- Autenticação da transação: senha ou biometria.
- Registro da transação: valor, data e hora da transação, chave PIX do destinatário e mensagem opcional.

## Prioridade:
Alta

## Critérios de aceitação:
- Todos os requisitos da user story devem ser atendidos.
- A funcionalidade deve ser testada em diferentes cenários, incluindo:
    - Valores válidos e inválidos.
    - Chaves PIX válidas e inválidas.
    - Mensagens opcionais válidas e inválidas.
    - Métodos de autenticação válidos e inválidos.
- A funcionalidade deve ser testada de forma automatizada, sempre que possível.

## Metodologia:
- Os testes serão realizados usando uma combinação de testes manuais e automatizados.
- Os testes manuais serão realizados por um QA manual.
- Os testes automatizados serão realizados usando uma ferramenta de teste de software.

##Cronograma:
- Os testes manuais serão realizados durante o período de desenvolvimento da funcionalidade.
- Os testes automatizados serão realizados durante o período de testes da funcionalidade.

##Recursos:
- QA manual
- Ferramenta de teste de software
- 
## Riscos:
- Os testes podem não detectar todos os erros na funcionalidade.
- Os testes podem não ser executados em todos os cenários possíveis.

## Métricas:
- Número de testes executados
- Número de erros detectados
- Porcentagem de cobertura de testes

  
## Ações corretivas:
- Todos os erros detectados devem ser corrigidos.
- O plano de testes deve ser atualizado para incluir novos testes para os erros detectados.
  
## Aprovação:

O plano de testes deve ser aprovado pelo gerente de projeto e pelo QA manual antes de iniciar os testes.

## Exemplos de testes:

Testes de dados:
  - Testar se o valor da transação é um número válido.
  - Testar se a chave PIX do destinatário é um formato válido.
  - Testar se a mensagem opcional é um texto válido.
Testes de autenticação:
  - Testar se a autenticação da transação é bem-sucedida com uma senha válida.
  - Testar se a autenticação da transação é bem-sucedida com biometria válida.
  - Testar se a autenticação da transação é negada com uma senha inválida.
  - Testar se a autenticação da transação é negada com biometria inválida.
Testes de registro:
  - Testar se a transação é registrada no sistema com os dados corretos.
  - Testar se a transação é registrada no sistema com a data e hora corretas.

## Observações:

- Os testes podem ser personalizados de acordo com as necessidades específicas do sistema.
- É importante testar a funcionalidade de PIX em todos os cenários possíveis para garantir que ela funcione corretamente.
