# Watson Assistant 101

Crie a sua conta gratuita (sem a necessidade de um cartão de crédito): [ibm.biz/Bdz7nW](https://ibm.biz/Bdz7nW)

Após o cadastro, se você não for redirecionado para o Dashboard, acesse: https://cloud.ibm.com

## Custo

Custo mensal -> Watson Assistant cobra por chamada de API (em produção). O valor atual é de R$0,007343 por mensagem enviada pelo usuário, não o número de mensagens enviadas pelo Watson.

Todas instâncias do serviço de Watson Assistant tem 10.000 mensagens gratuitas por mês, independente do plano (Lite, Plus Trial, Standard, Plus ou Premium).

## Expressões regulares ou RegEx

### CEP

- [0-9]{5}-[0-9]{3}
- [0-9]{8}

### E-mail

- [A-Za-z0-9._%+-]+@[A-Za-z0-9.-]+\.[A-Za-z]{2,}

### Nome da pessoa

- ^[a-zA-Z]+(([',. -][a-zA-Z ])?[a-zA-Z]*)*$

## Imprimir “dado literal”

Salvar um “dado literal” em um Slot dentro de um Dialog Node com a sua Entidade

- Aparente e local: \<? @cliente.literal ?\>
- Invisível e dinâmico:  { “context”: { “cep”: “@cliente.literal” } }

## Conteúdos e recursos extras

### Watson SDK

Para conectar a sua aplicação (front-end ou back-end), utilize o SDK do serviço do Watson.  Veja aqui: https://github.com/watson-developer-cloud

Linguagens disponíveis:

- Node.js
- Python
- .NET
- Java
- Android
- Swift
- Ruby
- Unity
- Salesforce
- ABAP

### Repositórios de chatbots

- [Victor Shinya](https://bit.ly/wa-skills)
- [IBM Bot Asset Exchange](https://developer.ibm.com/code/exchanges/bots/)

### Mais conteúdos

- [Como criar o seu Chatbot usando Watson Assistant](https://bit.ly/como-criar-seu-chatbot)
- [Como integrar o seu Chatbot no Facebook com a integração na plataforma](https://bit.ly/watson-com-facebook)
- [Como integrar o seu Chatbot no Facebook com Chatfuel](https://bit.ly/watson-com-chatfuel)
- [O que é a IBM Cloud](https://bit.ly/o-que-e-ibm-cloud)
- [Blog da IBM Watson](https://medium.com/ibm-watson)
