<p align="center">
  <a href="http://www.climatempo.com.br">
      <img src="http://i.imgur.com/Q9lCAMF.png" alt="Climatempo" width="300px"/>
  </a>
</p>

___


# Sobre a DIWE

A DIWE ....

# Sobre o Desafio
O desafio consistente na criação de de um aplicativo em React Native para gerenciamento de uma lista de contatos seguindo o layout do Figma. Atente-se aos estilos do protótipo e detalhes de usabilidade do usuário.

### Autenticação
O aplicativo deve possuir um login obrigatório para acesso aos recursos sendo que todas as requisições seguintes devem ser interepctadas pelo token do tipo Bearer.

#### Autenticar/logar
```javascript
POST '/auth/login'
```

Body
```json
{
  "email": "user@diwe.com.br",
  "password": "password"
}
```

### Contatos
Após autenticado, o usuário deve conseguir listar os contatos cadastrados, criar um novo contato, editar um contato existente e excluir um contato existente.


#### Recuperar todos os contatos
```javascript
GET '/contacts'
```

#### Recuperar um contato por ID
```javascript
GET '/contacts/:id'
```

#### Criar novo contato
```javascript
POST '/contacts'
```
Body (todos campos obirgatórios)
```json
{
  "name": "Glauber",
  "email": "glauber.castro@diwe.com.br",
  "mobile": "00999999999"
}
```

#### Editar um contato
```javascript
PUT '/contacts/:id'
```
Body (todos campos opcionais)
```json
{
  "name": "Glauber",
  "email": "glauber.castro@diwe.com.br",
  "mobile": "00999999999"
}
```

#### Excluir um contato por ID
```javascript
DELETE '/contacts/:id'
```
 
###### uso de bibliotecas é livre.
  

## Avaliação

O que vamos avaliar:

- Layout;
- Boas práticas
- Manutenibilidade;
- Usabilidade;
- Prazo estabelecido;
- Raciocínio lógico;
- Git flow; 

## Comece

O processo do desafio deve ser:

1. Crie um repositório para seu projeto

2. Crie um **README.md** com a explicação de como devemos executar o projeto e com o máximo de detalhes possível do que foi feito.
___


Qualquer dúvida e/ou problemas entre em contato com nossa equipe.