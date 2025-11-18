# Projeto com LocalStorage | JavaScript

Este projeto foi desenvolvido utilizando **HTML**, **CSS** e **JavaScript**, com foco no uso do **LocalStorage** para armazenar e recuperar dados diretamente no navegador.  
A aplicação funciona 100% no lado do cliente, sem necessidade de banco de dados ou backend.

---

## Funcionalidades

-  **Armazenamento de dados no LocalStorage**
-  Persistência mesmo após recarregar ou fechar o navegador
-  Adicionar novos itens
-  Remover itens
-  Editar dados (opcional)
-  Possível implementação de tema claro/escuro usando LocalStorage
-  Layout responsivo

---

##  O que é LocalStorage?

O **LocalStorage** é uma API do navegador que permite salvar dados em formato **chave–valor**.  
Os dados:

- Não expiram automaticamente  
- São exclusivos por domínio  
- Podem armazenar strings, arrays e objetos (convertidos com JSON)

Exemplo básico usado no projeto:

```js
    localStorage.setItem("dados", JSON.stringify(dados));
    const voltar = JSON.parse(localStorage.getItem('dados'));
