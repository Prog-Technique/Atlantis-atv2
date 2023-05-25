<div align="center" id=topo>
<h1> Atlantis </h1>
<h3> Sistema gerenciador de parques aquáticos, clubes e hotéis </h3>

![atlantis](https://github.com/Prog-Technique/Atlantis-atv1/assets/100284976/3478a0c8-d044-4c74-a36c-70d8d9f384a5)
  
<a href="https://www.typescriptlang.org/" target="blank">
<img align="center" src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" alt="typescript"/></a> 

<a href="https://nodejs.org/en/about/" target="blank">
<img align="center" src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white" alt="nodejs"/></a>

<a href="https://code.visualstudio.com/" target="blank">
<img align="center" src="https://img.shields.io/badge/Visual_Studio_Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white" alt="vsc"/></a> 

</div>

<br>

> 🔗 **Link** <br>
> - Documento: [Atlantis](https://github.com/Prog-Technique/Atlantis-atv2/files/11568391/atvii-atlantis-water-park.pdf)

<br>

## 📝 Contextualização
Encontrar desafios é algo comum durante o desenvolvimento de um software. Mas, conforme se adquire experiência percebe-se que determinados problemas são recorrentes, mesmo em projetos diferentes. Estes problemas recorrentes foram estudados e para cada um uma solução padrão foi proposta. Estas soluções são denominadas de padrões de projeto (design patterns).

Para uma versão melhorada, com mais funcionalidades, nesta versão utilizou-se dois padrões de projetos e princípios SOLID. Os padrões utilizados foram o Singleton e o Strategy.

A nova versão segue como um sistema do tipo CLI, não há comunicação SGBD, portanto, utilizou-se uma classe para armazenar as informações enquanto o sistema é executado, como uma base de dados em memória. Esta classe foi denominada de “Armazém”. Esta classe implementa o padrão Singleton, por isso possui o método construtor privado.  

O  padrão  Strategy fica evidenciado no diagrama de classe mostrado na Figura 1. Percebe-se uma interface, denominada Menu, a partir da interface, vários outros algoritmos são definidos por classes que implementação a interface Menu.

![strategy](https://github.com/Prog-Technique/Atlantis-atv2/assets/100284976/6916d427-cbe6-4acd-b55b-59b13b4d37db)

Padrões de projeto não são um framework ou um código pronto, são uma definição de alto nível de como um problema comum pode ser solucionado. Então, o padrão  Strategy foi aplicado de um modo diferente, com uma classe abstrata, denominada de Processo. Um processo defini qualquer ação ou comportamento que o sistema deva fazer. Esta aplicação diferenciada é evidenciada no diagrama de classe mostrado na Figura 2.

![strategyAbstrato](https://github.com/Prog-Technique/Atlantis-atv2/assets/100284976/063b76dd-49d6-4a53-aca6-0b62665586b2)

<br>

## 🎯 Objetivo
Implementar as seguintes funcionalidades:
- CRUD de cliente, incluindo clientes dependentes.
- Listagem de clientes dependentes para um titular específico.
- Listagem do titular para o cliente dependente específico.

<br>

## :scroll: Manual do Usuário

Clone o repositório pelo link: 

~~~
https://github.com/Prog-Technique/Atlantis-atv2.git
~~~

No terminal digite:

~~~
cd atlantis
~~~

~~~
npx tsc
~~~

~~~
node .\js\teste\index.js
~~~
<br>

→ [Voltar ao topo](#topo)
