<!-- ![logo_ProjTestes](Images/Img1.jpg) -->

<hr>

<!-- <p align="center">
   <img src="http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=RED&style=for-the-badge" #vitrinedev/>
</p> -->

### Tópicos 

- [Descrição do projeto](#descrição-do-projeto)

- [Implantação](#implantação)

- [Test end points](#test-end-points)

- [Ferramentas utilizadas](#ferramentas-utilizadas)

## Descrição do projeto 

<p align="justify">
Esta API foi desenvolvida para consumir a 
<a href="https://github.com/medinasp/APIsourceAPI">APIsourceAPI</a>

Seu conteúdo é composto apenas das 4 funcionalidades CRUD, sem controle de acesso, com banco de dados Sql Server.
</p>
<br>

## Implantação
<div style="width:100%">


`Preparação:`
<!-- ![Tela de abertura](Images/abertura.jpg) -->
* Primeiro clone, prepare e execute a <a href="https://github.com/medinasp/APIsourceAPI">APIsourceAPI</a> que será consumida por esta.

* Clone o repositório desta <a href="https://github.com/medinasp/APItoAPI">APItoAPI</a>, abra a solução no Visual Studio ou em alguma IDE de sua preferência e execute.

`Execução:`
   * Com os 2 projetos rodando, abra o testador de sua preferência e execute os endpoints:

      ✅ `Create:`
      * Exemplo de json para end point "Create":<br>
         Post: https://localhost:7100/api/CreateProd<br>
         Json Content:<br>
            {<br>
               "Descricao":"Registro 9",<br>
            }<br><br>

      ✅ `List:`
      * Exemplo de json para end point "List":<br>
         Post: https://localhost:7100/api/ListProd<br>
         Json Content:<br>
            {<br>
               "codigo": 0,<br>
               "descricao": "",<br>
               "dataCriacao": "",<br>
               "dataAtualizacao": ""<br>
            }<br><br>

      ✅ `Update:`
      * Exemplo de json para end point "Update":<br>
         Post: https://localhost:7100/api/UpdateProd<br>
         Json Content:<br>
            {<br>
               "codigo": 1002,<br>
               "descricao": "Updated Register" <br>
            }<br><br>

      ✅ `GetOne`
      * Exemplo de json para end point "GetOne":<br>
         Post: https://localhost:7100/api/GetOne/1004<br>
         Json Content:<br>
            não é necessário json, basta passar o código na url, como no exemplo, código 1004<br><br>

      ✅ `Delete`
      * Exemplo de json para end point "Delete":<br>
         Post: https://localhost:7100/api/DeleteProd/1004<br>
         Json Content:<br>
            não é necessário json, basta passar o código na url, como no exemplo, código 1004<br>
</div>   
</br>

## Ferramentas utilizadas

<a href="https://www.w3schools.com/cs/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg" alt="csharp" width="40" height="40"/></a>
<a href="https://dotnet.microsoft.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/dot-net/dot-net-original-wordmark.svg" alt="dotnet" width="40" height="40"/></a>
