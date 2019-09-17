# RocketSeat-BootCamp

### Instalação do Yarn
No mac é possível instalar yarn usando [homebrew](https://yarnpkg.com/en/docs/install#mac-stable)
```
brew install yarn
```
### Conceitos do Node.js
O que é NodeJS?
- Javascript no back-end;
- Plataforma (não linguagem);
- construída em cima do V8;

O que é o NPM?
- Instalar biblioteca de terceiros;
- Fornecer bibliotecas;

Características do Node
- Arquitetura Event-loop
  - Baseada em eventos (Rotas na maioria da vezes);
  - Call Stack (Pilha de eventos);
  - > Na pilha o último que entra é o primeiro que sai, Last IN, First OUT (LIFO)
- Node single-thread;<br>
  > Ele executa em apenas uma thread do processador, se o processador tiver 4 cores ele vai ficar alocado em apenas um core.
  - C++ por trás com libuv;
  - >A libuv permite usar mais threads para processamento
  - Background threads;
- Non-blocking I/O;
  >input e output não bloqueante, quando é feita uma requisição para o servidor, não é necessário retornar todos os dados de uma só vez, é possível retornar em partes

Frameworks<br>
- ExpressJS
  - Sem opinião;
  - > Permite criar a estrutura da forma que desejar
  - Ótimo para iniciar, por que é um microframework;
  - Micro-serviços;

Frameworks opinados<br>
- AdonisJS;
- NestJS;