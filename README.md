# Desafio 
## Frontend - REACTJS
### Construção de componentes para realização dos crud.
- **Produtor:** inserção, edição, listagem e exclusão, exibição das propriedades vinculadas. 
- **Propriedade:** inserção. (Necessário vincular algum produtor.)
- **Propriedades por Produtor:** listar as propriedades que pertencem a um produtor.

## Backend - NODEJS
### Construir API para realização do crud com as seguintes rotas:
- **GET - producers:** Retornar todos os produtores.
- **POST - producers:** Enviar os dados necessarios para cadastrar  os produtores.
- **POST - farms:** Enviar os dados necessarios para cadastrar as propriedades.
- **POST - producers_farms:** Enviar o ID do produtor e retornar as propriedades vinculados ao mesmo.
- **PUT - producer-edit:** Editar os dados do produtor.
- **DELETE - producer-delete:** Excluir o produtor informado.


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




