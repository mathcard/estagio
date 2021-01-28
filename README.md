# Desafio 
## Frontend - REACTJS
### Construção de componentes para realização dos crud.
- **Produtor:** inserção, edição, listagem e exclusão, exibição das propriedades vinculadas. 
- **Propriedade:** inserção. (Necessário vincular algum produtor.)
- **Propriedades por Produtor:** listar as propriedades que pertencem a um produtor.

## Backend - NODEJS
### Construir API para realização do crud com as seguintes rotas:

- **GET - producers:** Retornar todos os produtores.
- **POST - producer:** Enviar os dados necessarios para cadastrar os produtores.
- **PUT - producer:** Editar os dados do produtor.
- **DELETE - producer:** Excluir o produtor informado.

- **POST - farms:** Enviar os dados necessarios para cadastrar as propriedades.
- **GET - producers/farms/:id:** Enviar o ID do produtor e retornar as propriedades vinculados ao mesmo.

## Banco de Dados - POSTGRES
Será necessario criar duas tabelas **producer** e **farm** , onde todos os campos devem ser obrigatórios. 
#### producer
- id __(primary_key)__
- name
- email
- phone

#### farm
- id __(primary_key)__
- nameFarm
- **idProducer** __(fk)__ 

![](/assets/table.png)




