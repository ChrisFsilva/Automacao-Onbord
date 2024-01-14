<h1 align="center">ONBOARD / PROCESSO DE ADMISSÃO</h1>			
<br>
<h4 align="center"> 🚀 Concluído 🚀 </h4>
	

Tabela de conteúdos
=================
<!--ts-->
   * [Sobre o projeto](#-sobre-o-projeto)
   * [Layout](#-layout)
   * [Como executar o projeto](#-como-executar-o-projeto)
     * [Pré-requisitos](#pré-requisitos)
     * [Rodando a aplicação](#-Rodando-a-aplicação-Web)
   * [Tecnologias](#-tecnologias)
   * [Autor](#-autor)
   * [Licença](#-licença)
<!--te-->


## 💻 Sobre o projeto

  * Situação
- O processo de onboard do colaborador envolvia a entrega do equipamento (notebook ou desktop).
- Processo realizado totalmente de forma manual onde dependia de um colaborador do RH enviar os dados do funcionario admitido via e-mail para a gerencia de t.i, a gerencia por sua encaminhava essas informações para o técnico da região onde o colaborador viria a ser admitido.
  * Problema enfrentado
- Frequentes falhas nas comunicações entre RH/gerencia ou gerencia/Técnico.
- Informação transmitida sem tempo para atuação.
- Falta de visibilidade da gestão na preparação do equipamento.
  * Execução da solução
- Através de uma API e comandos JavaScript a informação de admissão aprovada do colaborador é coletada imediatamente do site da Gupy.
- Os dados coletados são implantados em um banco de dados do Sharepoint da empresa.
- O processo ativa uma automação desenvolvida via Power Automate que irá identificar a unidade em que o colaborador irá atuar e disparar um e-mail para todos os técnicos locais.
- Uma notificação tambem chegará ao Teams dos técnicos e da gerencia, evitando assim que a informação não seja visualizada.
- Dentro do Sharepoint haverá um botão que o técnico deverá posicionar o status da preparação do equipamento.
- No dia anterior a admissão será enviado um lembrete via teams para os técnicos e gerencia.
- Após a data de admissão, caso os técnicos não posicionem o equipamento como entregue durante o periodo da manhã será enviado uma mensagem de alerta de atraso para a gerencia.
- Caso o técnico posicione como equipamento entregue irá iniciar a automação do termo de posse

 
---

## 🎨 Layout

O layout da aplicação está disponível no LinkedIn:

<a href="#">
  <img alt="Automação do Onboard By Christopher Silva" src="https://img.shields.io/badge/Acessar%20Layout%20-aqui-%2304D361?style=flat-square">
</a>

<p align="center" style="display: flex; align-items: flex-start; justify-content: center;">
  <img alt="https://www.linkedin.com/in/chris-f-silva/" title="#moments-automacao" src="https://media.licdn.com/dms/image/D4D2DAQFKJLTQMo1J0Q/profile-treasury-image-shrink_800_800/0/1703905254094?e=1705874400&v=beta&t=WrgsgezB5HhRPBuT6sKw80Uhrliq7PA9MLLAq3CGgto" />
</p>

---

## 🚀 Como executar o projeto

### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
 - Navegador

Devido ao conteúdo sensivel presente na codificação, os códigos responsaveis pelo Power Automate e API Gupy não serão publicados.

#### 🧭 Rodando a aplicação Web
```bash

# Clone este repositório
$ git clone https://github.com/ChrisFsilva/Automacao-Onbord



```



## 🛠 Tecnologias

As seguintes tecnologias foram usadas na construção do projeto:

-   **[JavaScript](https://www.javascript.com/)** 
-   **[TypeScript](https://www.typescriptlang.org/)** 
-   **[Power Automate](https://www.microsoft.com/pt-br/power-platform/products/power-automate)**
-   **[SharePoint](https://www.microsoft.com/pt-br/microsoft-365/sharepoint/collaboration)**
---

## 🦸🏻‍♂️ Autor

 <br>
  <sub><b><p>Christopher Silva</p></b></sub></a>
 <br />

[![Linkedin Badge](https://img.shields.io/badge/-Christopher%20Silva-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/chris-f-silva//)](https://www.linkedin.com/in/chris-f-silva/) 
[![Gmail Badge](https://img.shields.io/badge/-chrisspfc.silva@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:daniel.rodrigues.soarees@gmail.com)](mailto:chrisspfc.silva@gmail.com)

---

## 📝 Licença

Este projeto esta sobe a licença [MIT](./LICENSE)

Feito por: Christopher Silva
