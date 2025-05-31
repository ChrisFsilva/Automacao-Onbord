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
     * [Funcionalidades](#Funcionalidades)
   * [Tecnologias](#-tecnologias)
   * [Autor](#-autor)
   * [Licença](#-licença)
<!--te-->


## 💻 Sobre o projeto

Descrição:
Este projeto visa automatizar o processo de onboarding de novos funcionários usando Power Automate. O fluxo automatizado gerencia tarefas como concessão de acesso a sistemas internos, envio de materiais de boas-vindas e configuração de reuniões introdutórias. O projeto também utiliza uma API JavaScript para comunicação com a Gupy, facilitando a integração dos dados dos novos funcionários, e personaliza e-mails de boas-vindas através de programação.

Tecnologias Utilizadas:
Power Automate: Para a criação e gerenciamento dos fluxos automatizados.
Microsoft 365: Integração com Outlook, Teams, SharePoint e outros serviços da Microsoft.
SharePoint: Armazenamento e gerenciamento de documentos e listas de tarefas.
JavaScript API da Gupy: Integração com a plataforma de recrutamento Gupy para transferência de dados dos novos funcionários.

 
---

## 🎨 Layout

O layout da aplicação está disponível no pinteres:
<p align="center" style="display: flex; align-items: flex-start; justify-content: center;width="10"">
  <img alt="Automação do Onboard By Christopher Silva" title="#onboard-automacao" src="https://i.pinimg.com/1200x/ab/48/46/ab48462bf56c2444d846a3efe38ce9f1.jpg" style="width:500px;/>
</p>
```bash
Componentes Principais:
AssignAccessFlow: Fluxo para concessão de acesso a sistemas e grupos.
SendWelcomeEmailFlow: Fluxo para envio de e-mails de boas-vindas personalizados.
ScheduleMeetingsFlow: Fluxo para agendamento de reuniões no Teams.
GupyIntegration.js: Script JavaScript para integração com a API da Gupy

	  ```
---

## 🚀 Como executar o projeto

### Pré-requisitos

- Conta Microsoft 365 com permissões de administrador.
- Licença Power Automate.
- Configuração do SharePoint e Microsoft Teams.
- API key da Gupy para integração.
### Instalação:
- Certifique-se de que sua conta Microsoft 365 tem permissões de administrador.
- Crie um site no SharePoint para armazenar documentos de onboarding e listas de tarefas.
- Obtenha e configure a API key da Gupy para comunicação com a plataforma de recrutamento.
- No Power Automate, crie um novo fluxo e configure os gatilhos e ações conforme descrito nas funcionalidades.

#### Funcionalidades
```bash

Coleta de Informações:
  Recebe dados do novo funcionário diretamente da Gupy via API.
  
Integração com Gupy:
  Utiliza a API JavaScript para importar dados dos novos funcionários da plataforma Gupy.
  
Configuração de Acessos:
  Concede acesso a sistemas e grupos necessários.
  
Envio de E-mails Personalizados:
  Envia e-mails de boas-vindas personalizados usando programação.
  
Tarefas no SharePoint:
  Cria tarefas no SharePoint para o acompanhamento do processo de onboarding.
  
Configuração de Reuniões:
  Agenda reuniões de introdução no Microsoft Teams

```

### Guia do Usuário:

``` bash
Integração com Gupy:
  A API JavaScript coleta automaticamente os dados do novo funcionário da plataforma Gupy.

Automatização Iniciada:
  O fluxo de Power Automate é disparado automaticamente ao receber novos dados da Gupy.

Monitorar Tarefas:
  O responsável pelo onboarding pode monitorar as tarefas no SharePoint.

Receber Notificações:
  O novo funcionário e os responsáveis recebem notificações por e-mail conforme o processo avança.
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

Este projeto está licenciado sob a licença MIT - veja o arquivo LICENSE para mais detalhes. [MIT](./LICENSE)

Feito por: Christopher Silva
