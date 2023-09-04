# App

GymPass style app.

## RFs

- [x] Deve ser possivel se cadastrar;
- [x] Deve ser possivel se autenticar;
- [x] De ser possivel obter o perfil de um usuário logado;
- [x] Deve ser possivel obter o número de check-ins realizados pelo usuário;
- [x] Deve ser possivel o usuário obter seu histórico de check-ins
- [x] Deve ser possivel o usuário buscar academias próximas;
- [x] Deve ser possivel o usuário buscar academias pelo nome;
- [x] Deve ser possivel o usuário realizar check-in na academia;
- [x] Deve ser possivel validar o check-in de um usuário;
- [x] Deve ser possivel cadastrar uma academia;  

## RNs

- [x] O usuário não deve poder se cadastrar com um e-mail duplicado;  
- [x] O usuário não pode fazer 02 check-ins no mesmo dia;
- [x] O usuário não pode fazer check-in se não estiver perto (100m) da academia;
- [x] o check-in só pode ser validado até 20 minutos após criado;
- [x] o check-in só pode ser validado por administradores;
- [x] A academia só pode ser cadastrada por administradores;

## RNFs

- [x] A senha do usuário precisa estar criptografada;
- [x] Os dados da aplicação precisam estar persistidos em um banco PostgreSQL;
- [x] Todas  listas de dados precisam estar paginadas com 20 itens por página;
- [x] O usuário deve ser identificado por um JWT (JSON Web Token);