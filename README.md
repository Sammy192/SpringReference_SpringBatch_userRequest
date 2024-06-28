# Projeto User Request Spring Batch - 

Link projeto referência: 
https://github.com/devsuperior/user-request-spring-batch

Projeto desenvolvido para abordar conhecimento sobre Spring Batch. 
Case study to implement a job to read data from a remote API and save to the database using Spring Batch

Job responsável fazer requisição a uma API e buscar dados de usuários e em seguida, gravá-los em um BD.
Um DB 'spring_batch' responsável para gravar os metadados
Outro DB 'app' responsável para gravar os dados processados pela aplicação. 

## Techs utilizadas.

Docker para subir container de MySQL e PhpAdmin

Projeto de api pronto para consumo, pasta clients.

Postman

## oBjetivos
● Visão geral dos componentes que compõem o Spring batch;
● Compreender o ciclo de vida do Job e seus Steps;


![image](https://github.com/Sammy192/SpringReference_SpringBatch_userRequest/assets/53224915/d792e2bb-3e4e-4274-b222-8555d1ac4434)

![image](https://github.com/Sammy192/SpringReference_SpringBatch_userRequest/assets/53224915/2705107d-1bfe-43fd-885c-ec44a636f0ab)

![image](https://github.com/Sammy192/SpringReference_SpringBatch_userRequest/assets/53224915/412b08de-a36a-4073-a367-c7130bbcbbcc)

![image](https://github.com/Sammy192/SpringReference_SpringBatch_userRequest/assets/53224915/1e793b56-cd4a-4337-bb2a-a1f7a86e6386)


```
CREATE DATABASE app;
DROP TABLE IF EXISTS tb_user;
CREATE TABLE tb_user(login VARCHAR(30), name VARCHAR(60), avatar_url VARCHAR(100), PRIMARY KEY(login));
```
