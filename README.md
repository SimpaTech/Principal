<span id="topo"></span>
<h1 align="center">Software de Processamento de Dados de Estações Meteorológicas </h1>
<h2 align="center">FATEC Prof Jessen Vidal, São José dos Campos - 1º Semestre de 2024</h2>
<p align="center">
    <a href="#sobre">Sobre</a> | 
    <a href="#tecnologias">Tecnologias</a> |
    <a href="#equipe">Equipe</a> | 
<!--     <a href="#entregas">Entregas</a> |  -->
    <a href="#epics">Epics</a> |
    <a href="#backlogs">backlogs</a> |
<!--     <a href="#links">Links</a> | -->
<!--     <a href="#versao">Versionamento</a> | -->
<!--     <a href="#gif">Gif</a> | -->
</p>
<span id="sobre"></span>
<h1 align="center">Sobre:</h1>

<p>
  A Tecsus é uma startup que trabalha com coleta e processamento de dados através de redes de sensores sem fio, conhecidos como Internet das Coisas (IoT), na área de utilidades (água, energia e gás). Com o intuito de expandir seu portfólio para o monitoramento ambiental, a empresa optou pelo desenvolvimento de estações meteorológicas de baixo custo. Essas estações serão equipadas com sensores para medir direção e velocidade do vento, índice pluviométrico, umidade, temperatura e pressão atmosférica. Os dados coletados serão enviados periodicamente para um servidor e processados para serem exibidos em um portal, fornecendo relatórios e dashboards. O portal, além de informar as condições meteorológicas, irá destacar a importância do monitoramento ambiental na prevenção de desastres naturais através da geração de alertas. 
</p>

<span id="tecnologias"></span>
<h1 align="center">Tecnologias/Pré-Requisitos:</h1>

<p align="center">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E.svg?style=for-the-badge&logo=JavaScript&logoColor=black"></img>&nbsp;
  <img src="https://img.shields.io/badge/TypeScript-3178C6.svg?style=for-the-badge&logo=TypeScript&logoColor=FFF"></img>&nbsp;
  <img src="https://img.shields.io/badge/React-61DAFB.svg?style=for-the-badge&logo=React&logoColor=black"></img>&nbsp;
  <img src="https://img.shields.io/badge/CSS3-1572B6.svg?style=for-the-badge&logo=CSS3&logoColor=white"></img>&nbsp;
  <img src="https://img.shields.io/badge/Tailwind%20CSS-06B6D4.svg?style=for-the-badge&logo=Tailwind-CSS&logoColor=white"></img>&nbsp;
  <img src="https://img.shields.io/badge/MySQL-4479A1.svg?style=for-the-badge&logo=MySQL&logoColor=white"></img>&nbsp;
</p>

<span id="equipe"></span>
<h1 align="center">Equipe:</h1>

  | Função | Foto | Nome | GitHub | LinkedIn |
  | :-: | :-: | :-: | :-: | :-: |
  | Scrum Master | <img src="docs/images/fotoAugusto.png" alt="Foto Augusto"> | Augusto Henrique Buin | [GitHub](https://github.com/AugustoBuin) | [LinkedIn](https://www.linkedin.com/in/augusto-henrique-buin-a58bb0208/) |
  | Product Owner | <img src="docs/images/fotoFelipe.png" alt="Foto Felipe" width="100px" height="100px" > | Felipe Augusto Graciano | [GitHub](https://github.com/Yetgvg) | [LinkedIn](https://www.linkedin.com/in/felipe-augusto-graciano-2b796026a/) |
  | Front End Dev | <img src="docs/images/fotoGabi.png" alt="Foto Gabi"> | Gabriela da Silva Barbosa | [Github](https://github.com/gabidsbarbosa) | [LinkedIn](https://www.linkedin.com/in/gabrieladsbarbosa) |
  | Front End Dev | <img src="docs/images/fotoIgor" alt="Foto Igor"> | Igor da Silva Pereira | [Github](https://github.com/igorpereira28) | [LinkedIn](https://www.linkedin.com/in/igor-da-silva-pereira-119794159/) |
  | Back End Dev | <img src="docs/images/fotoJean" alt="Foto Jean"> | Jean Lucas de Faria Silva | [Github](https://github.com/jeejinf) | [LinkedIn](https://www.linkedin.com/in/jean-faria-5a4b201b9/) |
  | Back End Dev | <img src="docs/images/fotoVitor" alt="Foto Vitor"> | Vitor Garcez de Oliveira | [Github](https://github.com/Vitaog) | [LinkedIn](https://www.linkedin.com/in/vitorgarcezdeoliveira/) |

<span id="epics"></span>
<h1 align="center">Epics</h1>

| Sprint |  | Epics |
| :-: | :-: | :-: |
| **1** | **1** | Implementar um sistema de gestão de usuários. |
| **1** | **2** | Implementar CRUD de estações, parâmetros e usuários. |
| **2** | **3** | Criar um sistema para coleta, armazenamento e tratamento de dados. |
| **3** | **4** | Criar relatórios personalizáveis para análise. |
| **4** | **5** | Desenvolver dashboards para visualização dos dados. |
| **4** | **6** | Desenvolver Documentação e Informações Públicas |

<span id="backlogs"></span>
<h1 align="center">Backlogs</h1>

| Sprint | Epics | User Storys |
| :-: | :-: | :-: |
| **1** | **1** | Como Administrador, eu quero cadastrar e gerenciar estações meteorológicas, para adicionar, editar e remover estações do sistema. |
| **1** | **1** | Como Administrador, eu quero cadastrar e gerenciar parâmetros meteorológicos, para definir os dados que serão coletados pelas estações. |
| **1** | **1** | Como Administrador, eu quero cadastrar e gerenciar usuários, para criar e gerenciar contas de usuários no sistema. |
| **1** | **1** | Como Publico, eu quero poder receber Alertas dentro do sistema, para que eu possa me manter em alerta sobre as mudanças. |
| **1** | **2** | Como Administrador, eu quero implementar mecanismos de autenticação e autorização seguros, para garantir a segurança dos dados e do sistema. |
| **1** | **2** | Como Administrador, eu quero gerenciar permissões de acesso para diferentes funcionalidades do sistema, para controlar o que cada tipo de usuário pode fazer no sistema. |
| **2** | **3** | Como Administrador, eu quero implementar o datalogger para coleta de dados dos sensores, para garantir a coleta precisa e confiável dos dados meteorológicos. |
| **2** | **3** | Como Administrador, eu quero estabelecer comunicação com o serviço de recepção de dados, para garantir a transmissão segura e eficiente dos dados coletados. |
| **2** | **3** | Como Administrador, eu quero validar e armazenar os dados coletados de forma segura, para garantir a integridade e confiabilidade dos dados para análises posteriores. |
| **2** | **3** | Como Administrador, eu quero implementar pipeline de integração contínua (CI) para automatizar o processo de coleta e armazenamento, para garantir a eficiência e escalabilidade do sistema. |
| **3** | **4** | Como Administrador, eu quero criar dashboards customizáveis para diferentes perfis de usuário (administrador, público), para atender às necessidades específicas de cada tipo de usuário. |
| **3** | **4** | Como Administrador, eu quero implementar visualizações de dados atraentes e informativas (gráficos, tabelas, mapas), para facilitar a compreensão e análise dos dados. |
| **3** | **4** | Como Administrador, eu quero integrar recursos interativos para exploração dos dados (filtros, drill-down), para permitir análises mais profundas e personalizadas. |
| **3** | **4** | Como Administrador, eu quero priorizar a acessibilidade e usabilidade para todos os usuários, para garantir que o sistema seja acessível. |
| **3** | **4** | Como Usuário Público, eu quero acessar e visualizar os dados meteorológicos de forma simples e intuitiva, para acompanhar o clima da minha região de forma fácil e rápida. |
| **4** | **5** | Como Administrador, eu quero implementar um gerador de relatórios dinâmico, para criar relatórios personalizados de acordo com as necessidades do momento. |
| **4** | **6** | Como Administrador, eu quero elaborar documentação detalhada das rotas das APIs . |
| **4** | **6** | Como Usuário Público, eu quero ver os alertas em caso de falhas ou problemas técnicos, para ser notificado de problemas. |
| **4** | **6** | Como Usuário Público, eu quero poder visualizar informações dos sensores, para que eu possa entender e aprender sobre esses sensores |
