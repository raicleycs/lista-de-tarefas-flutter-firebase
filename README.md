# app_fire

# Projeto desenvolvido para a turma de TDS do SENAC SOROCABA

## Projeto base para de uma lista de tarefas construido com Flutter e backend em nuvem com firebase. 

Atividade:
- Criar um banco no firestore e conectar ao projeto
- Verificar a conectividade criando novas tarefas no aplicativo base
- Adicionar botão em cada tarefa da lista criada para remover a tarefa no Firestore
- Implementar a atualização de tarefa, por exemplo (concluída, em desenvolvimento, pendente, etc...)
- Realizar a estilização do aplicativo com mais widgets do Flutter.  

Obs: Toda a estrutura front-end do projeto está na main principal


Data de entrega: 03/10/2025

## Como criar a estrutura do aplicativo?

# Comando CMD para criar projeto Flutter + FireBase

### Criar projeto flutter
```bash
flutter create app_firebase
 ```
###  Abra o cmd na pasta do projeto
```bash
cd app_firebase
```
## Crie um projeto no firebase e crie um banco no firestore
### Instale o CLI do Firebase
 ```bash
npm install -g firebase-tools
 ```
### Faça login no console do firebase
 ```bash
firebase login
 ```

### Instale o CLI do flutterfire
 ```bash
dart pub global activate flutterfire_cli
 ```
### Configure o projeto
 ```bash
flutterfire configure
 ```
### Configure o pubspac.yaml
 ```bash
dependencies:
   flutter:
      sdk: flutter
   firebase_core: ^2.32.0
   cloud_firestore: ^4.17.0
 ```
### Instale os pacotes
 ```bash
flutter pub get
 ```
