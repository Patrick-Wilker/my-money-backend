<h1 align="center">My Money Backend</h1>

<h2>Projeto</h2>

Esse projeto é uma aplicação de controle financeiro. 

<h3>Rotas</h3>

| URL | Método | Operação
| ----- | ----- | ----- |
|/api/billingCycles | GET | Consulta todos os Ciclos |
|/api/billingCycles/1 | GET | Consulta o Ciclo de ID = 1 |
|/api/billingCycles | POST | Cria um novo Ciclo |
|/api/billingCycles/2 | PUT | Altera o Ciclo de ID = 2 |
|/api/billingCycles/3 | DELETE | Remove o Ciclo de ID = 2 |
|/api/billingCycles/count | GET | Consulta a quantidade de Ciclos |
|/api/billingCycles/summary | GET | Consulta o Sumário de Ciclos |

<h2>Configuração do MongoDB</h2>

Instale o MongoDB. 

Após a instalação, adione no PATH do sistema ``` C:\Program Files\MongoDB\Server\4.4\bin; ```
ou um caminho relativo na qual o mongo foi instalado.

Ao executar ```mongod``` no terminal você perceberá que o mongo exigirá que haja o seguinte diretório ```C:data\db\ ```. Para isso vá no disco local (C) e 
crie uma nova pasta com o nome <strong>data</strong> e dentro dela crie uma pasta com o nome <strong>db</strong>

Execute ```mongod``` novamente e tudo deverá funcionar perfeitamente.


<h2>Como rodar o projeto</h2>

<h3>Instalação</h3>

Você deve instalar as dependências do projeto com o seguinte comando ``` npm install ```.

<h3>Uso</h3>

Após as instalações, rode ``` npm run dev ```.

<strong>Lembre-se de o MongoDB está rodando. Para isso execute ```mongod``` no terminal.</strong>

<h2>Autores</h2>

* [Patrick Mota](https://github.com/Patrick-Wilker) - Desenvolvimento e documentação

<h2>Licença</h2>

Esse projeto está sob licença MIT.
