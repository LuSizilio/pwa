# Resumo

## info

**Aluno:** Luciano Sizilio   
**Livro:** Progressive WebApp

## Objetivo
- Resumir o 1° cap. do livro

## Meu resumo

PWA é o conceito de que uma aplicação progressiva, ou seja, funcional sem restrições de software, podendo funcionar em celulares, computadores e até mesmo sem internet.

**Uma aplicação em PWA deve:**

- Fazer com que requisições recebam status 200 mesmo sem internet, por meio de local storage, aplication cache e IndexedDb.
- Exibir conteúdo quando mesmo quando o javascript estiver desabilitado.
- Usar protocolo HTTPS para que evite ser interceptado por um "man in the middle", redirecionando para o HTTPS caso entre no HTTP.
- Carregar rapidamente mesmo com baixa conexão, visando o processo "3 seconds and go", que carrega de forma agradável sem fazer os usuários esperarem.
- Questionar os usuários caso queiram instalar a aplicação
- Utilizar o conceito de responsividade e deixar a aplicação compativel com a maior quantidade de browsers possivel
- Fazer com que as transições entre páginas não sejam sensíveis a conexão do usuário, pois isso poderia inclusive quebrar a regra do "3 seconds and go", portanto deve ser utilizada a renderização do DOM.
