## Web Service

São soluções para aplicações se comunicarem independente de linguagem, softwares e hardwares utilizados.

Foram criados para troca de mensagens utilizando a linguagem XML sobre o protocolo HTTP identificado por URI

Atualmente, pode-se dizer que são APIs que se comunicam por meio de redes sobre o protocolo HTTP.

Vantagens:

    - Linguagem comum;
    - Integração;
    - Reutilização de implementação;
    - Segurança;
    - Custos.

Principais Tecnologias:
    - SOAP
    - REST
    - XML
    - JSON

# SOAP - Simple Object Access Protocol
É baseado em XML para acessar serviços web principalmente por HTTP;

Definição de como o web service se comunica;

Foi desenvolvido para facilitar integrações entre aplicações.

Vantagens:

Permite integração entre aplicações, independente da linguagem pois usa como linguagem comum o XML;

É independete de plataforma e software;

Meio de transporte genérico, ou seja, pode ser usado por protocolos além do HTTP;

# XML - Extensible Markup Language
Sempre usada com SOAP.

É uma linguagem de marcação criana nos anos 90 pela W3C;

Facilita a sepração de conteúdo;

Não tem limitação de criação de tags;

Linguagem comum para integrações entre aplicações;

<img src=" " >

SOAP Envelope é o primeiro elemento do documento e é usado para encapsular toda a mensagem SOAP.

SOAP Header é o elemento onde possui informações de atributos e metadados da requisição.

SOAP Body é o elemento que contém os detalhes da mensagem.

# WSDL - Wev Services Description Language
Usado para descrever Web Services, funciona como um contrato de serviço.

Descrição feita em documento XML, onde é descrito o serviço, especificações de acesso, operações e métodos.

# XSD - XML Schema Definition
É um schema no formato CML usado para definir a estrutura de dados que será validada no XML.

Funciona como uma documentação de como deve ser montado o SOAP Message (XML) que será enviado através de Web Service.

# Rest - Representational State Transfer
É um estilo de arquitetura de software que define a implementação de um web service.

Podem trabalhar com os formatos XML, JSON ou outros.

Vantagens:

Permite Integrações entre aplicações e também entre cliente e servidor em páginas web e aplicações.

Utiliza dos métodos HTTP para definir a operação que está sendo efetuada.

Arquitetura de fácil compreensão.

<img src=" " >

# API - Application Programming Interface
São conjuntos de rotinas documentados e disponibilizados por uma aplicação para que outras aplicações possam consumir suas funcionalidades

Ficou popular com o aumento dos serviços web

As maiores plataformas de tecnologia disponibilizam APIs para acessos de suas funcionalidades, algumas delas são: Facebook, Twitter, Telegram, Whatsapp, GitHub.

# Principais métodos HTTP
GET - Solicita a representação de um recurso;
POST - Solicita a criação de um recurso;
DELETE - Solicita a exclusão de um recurso;
PUT - Solicita a atualização de um recurso;

# JSON - JavaScript Object Notation
Formatação elve utilizada para troca de mensagens entre sistemas.

Usa-se de uma estrutura de chave-valor e também de listas ordenadas.

Um dos formatos mais populares e mais utilizados para troca de mensagens entre sistemas.

# States Code
É usado pelo servidor para avisar o cliente sobre o estado da operação solicitada.

1xx - Informativo
2xx - Sucesso
3xx - Redirecionamento
4xx - Erro do Cliente
5xx - Erro do Servidor

