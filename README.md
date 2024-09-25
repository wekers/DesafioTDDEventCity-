<h1 align="center">
  DESAFIO: TDD - Test Driven Development
</h1>
<br>

<p align="left">
  <img src="https://img.shields.io/static/v1?label=Tipo&message=Desafio&color=8257E5&labelColor=000000" alt="Desafio" />
</p>

Implemente as funcionalidades necessárias para que os testes do projeto abaixo passem (veja vídeo explicativo).

![](https://raw.githubusercontent.com/wekers/DesafioTDDEventCity-/refs/heads/main/img/desafio.png)

---
### Critérios de correção:
#### Testes manuais no Postman
Para ver as requisições, segue (link da collection Postman
abaixo).:
<br>
importe no Postman: <br>

Arquivo Postman: [Aqui](https://github.com/wekers/DesafioTDDEventCity-/blob/main/Desafio%20TDD%20Event%20City.postman_collection.json?raw=true)

---
<br>

**Mínimo para aprovação: 6 de 7**

- DELETE /cities/{id} deve retornar 404 Not Found quando id não existir

- DELETE /cities/{id} deve retornar 204 No Content quando id for independente

- DELETE /cities/{id} deve retornar 400 Bad Request quando id for dependente

- POST /cities deve inserir recurso

- GET /cities deve retornar recursos ordenados por nome

- PUT /events deve atualizar recurso quando id existir

- PUT /events deve retornar 404 Not Found quando id não existir


---


#### Competências avaliadas:

- Desenvolvimento TDD de API Rest com Java e Spring Boot

- Implementação de cenários de busca, inserção, deleção e atualização

- Tratamento de exceções em API com respostas HTTP customizadas


