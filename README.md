# Introdução ao framework NHibernate para a plataforma .NET

[Introdução ao framework NHibernate para a plataforma .NET (2011)](https://stahe.github.io/pt-nhibernate-dotnet-dec-2011/)

Este repositório acompanha um curso introdutório sobre o **NHibernate**, apresentado como o equivalente em .NET do framework **Hibernate** de Java. O documento oferece uma visão geral concisa sobre a utilização de um **ORM** (*Object Relational Mapper*) no ecossistema .NET.

## Descrição geral

Um ORM é um conjunto de bibliotecas que permite a uma aplicação baseada em bases de dados manipular a base de dados **sem escrever explicitamente consultas SQL** e **sem depender das características específicas do SGBD utilizado**.

Este material serve como uma **breve introdução** ao NHibernate. Para um estudo mais aprofundado, o documento recomenda o seguinte livro:

- **NHibernate in Action**
- **Autor**: Pierre-Henri Kuaté
- **Editora**: Manning
- **ISBN-13**: 978-1932394924

## Nível e pré-requisitos

Numa escala de **iniciante / intermédio / avançado**, este documento situa-se no nível **intermédio**.

Para o compreender, são necessários vários pré-requisitos, entre os quais se incluem:

1. **C# 2008**  
   *Aprender a linguagem C# 3.0 com o .NET Framework 3.5*

2. **Spring IoC para .NET**  
   Introdução aos conceitos básicos de **inversão de controlo (IoC)** e **injeção de dependências** com **Spring.NET**

O documento também inclui, no início de alguns parágrafos, referências de leitura recomendada a estes recursos prévios.

## Ferramentas utilizadas  
  
O caso prático baseia-se em ferramentas disponíveis gratuitamente na web, nas versões indicadas à data de **dezembro de 2011**:  
  
- **NHibernate 3.2**  
- **Spring.NET 1.3.2**  
  Utilizado aqui para bibliotecas que facilitam a utilização do NHibernate  
- **log4net 1.2.10**  
  Framework de registo utilizado pelo NHibernate  
- **NUnit 2.5**  
  Framework de testes unitários, o equivalente em .NET do JUnit
- **Controlador ADO.NET 6.4.4 para MySQL 5**  
  
## Objetivo do curso  
  
Este curso tem como objetivo apresentar os fundamentos do **NHibernate** num contexto .NET, mostrando como simplificar o acesso aos dados através de uma abordagem orientada a objetos, ao mesmo tempo que se aproveitam ferramentas complementares de configuração, registo e testes.

Serge Tahé, dezembro de 2011