# BibliotecaDigital-frontend

# Frontend - Biblioteca Digital

## Tecnologias Utilizadas

* React Native
* Expo
* Axios

## Instalação

Acesse a pasta do frontend:

```bash
cd frontend
```

Instale as dependências:

```bash
npm install
```

ou

```bash
npm install axios
```

caso o projeto tenha sido criado recentemente com Expo.

## Configuração

Abra o arquivo:

```text
services/api.js
```

Altere o IP para o endereço da máquina onde o backend está executando:

```javascript
baseURL: 'http://192.168.0.100:3000'
```

Substitua pelo IP correto da sua rede local.

## Execução

Inicie o projeto:

```bash
npx expo start
```

Depois:

* Pressione `a` para abrir no Android Emulator
* Ou leia o QR Code pelo aplicativo Expo Go

## Funcionalidades

* Cadastro de livros
* Listagem de livros
* Atualização de livros
* Exclusão de livros

## Estrutura

```text
frontend/
│
├── App.js
└── services/
    └── api.js
```
