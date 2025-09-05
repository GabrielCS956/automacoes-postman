# automacoes-postman

Este repositório contém automações de testes para a **PetStore API** (Swagger) — uma API **fictícia**, utilizada para fins de aprendizado e prática de automações.  
Os testes foram implementados em **Postman** e estão integrados a pipelines **GitHub Actions**.  
A cada *push* ou *pull request*, a pipeline executa as coleções automaticamente para garantir a qualidade e a consistência dos cenários de teste.  

As **APIs foram estruturadas de forma independente**, ou seja, cada cenário de teste cria e manipula seus próprios dados.  
Por exemplo: a API de **DELETE** primeiro cria um usuário para depois excluí-lo, ao invés de depender de um recurso previamente criado por outra requisição (como a de **POST**). Isso garante maior isolamento e confiabilidade nos testes.

