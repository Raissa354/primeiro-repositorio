# primeiro-repositorio
apresentacao 27/05/2026

grupo:Raissa Helena, Bianka Vieira, Samuel Henrique, Lucas Rafael, Camila Patrussi

Apresentação no canva https://www.canva.com/design/DAHKw9nknr0/qhttzJfRDVeage8ja1yd6g/view?utm_content=DAHKw9nknr0&utm_campaign=designshare&utm_medium=link&utm_source=viewer

resumo preve sobre a apresentaçao:

Sistema de Controle de Versões Distribuído
O Git é uma ferramenta utilizada para controlar versões de projetos, permitindo registrar alterações no código e facilitar o trabalho em equipe. Sua evolução trouxe mais segurança, rapidez e colaboração no desenvolvimento de software, já que cada desenvolvedor possui uma cópia completa do repositório.
Comandos Iniciais
Os principais comandos do Git são:


git init → cria um repositório;


git add → adiciona arquivos para versionamento;


git status → mostra o estado atual dos arquivos;


git config → configura nome e e-mail do usuário;


git commit → salva alterações no histórico;


git log → exibe o histórico de commits realizados.


Versionamento em Floresta
O versionamento em floresta representa a comunicação entre vários repositórios distribuídos, permitindo sincronização entre desenvolvedores e servidores remotos.
Serviços de Hospedagem
As principais plataformas para hospedagem de repositórios Git são:


GitHub


Bitbucket


Azure DevOps


Esses serviços oferecem recursos como armazenamento de código, colaboração, revisão de código e integração contínua.
Pull Requests
Os Pull Requests são solicitações de integração de alterações entre branches. Eles permitem revisão de código, discussão entre desenvolvedores e validação antes da união das alterações ao projeto principal.
Resolução de Conflitos
Conflitos acontecem quando diferentes alterações são feitas no mesmo trecho de código. Nesse caso, é necessário analisar manualmente as mudanças, escolher a versão correta e realizar um novo commit para concluir a resolução.

# Git - Sistema de Controle de Versões Distribuído

O Git é um sistema de controle de versões distribuído utilizado para registrar alterações em projetos e facilitar o trabalho em equipe. Ele permite que vários desenvolvedores trabalhem simultaneamente no mesmo projeto, mantendo um histórico completo das modificações realizadas.

## 6.1 Evolução

O Git surgiu como uma evolução dos sistemas de versionamento centralizados, oferecendo mais velocidade, segurança e flexibilidade. Diferente dos sistemas antigos, cada desenvolvedor possui uma cópia completa do repositório.

---

# 6.2 Comandos Iniciais

## 6.2.1 InicializaçãoCria

um novo repositório Git.
   bashgit init
   
## 6.2.2 AdicionarAdiciona arquivos para a área de versionamento.
   bashgit add. 
   
## 6.2.3 StatusMostra o estado atual dos arquivos do projeto.
   bashgit status
   
## 6.2.4 ConfiguraçãoConfigura o nome e e-mail do usuário no Git.
   bashgit config --global user.name "Seu Nome"
   git config --global user.email "email@exemplo.com"
   
##6.2.5 CommitSalva as alterações no histórico do projeto.
   bashgit commit -m "Mensagem do commit"
   
## 6.2.6 LogExibe o histórico de commits realizados.
   bashgit log
   
---

# 7 Versionamento em Floresta

O versionamento em floresta representa vários repositórios distribuídos conectados entre si, permitindo colaboração entre equipes e sincronização de alterações.

---

# 7.1 Serviços

## 7.1.1 GitHub

Plataforma popular para hospedagem de repositórios Git, permitindo colaboração, Pull Requests e controle de versões.
## 7.1.2 BitBucket

Serviço de hospedagem Git focado em integração com ferramentas corporativas da Atlassian.

## 7.1.3 Repositório do Azure

Serviço da Microsoft para gerenciamento de código, integração contínua e colaboração em projetos.

---

# 7.2 Pull Requests

Pull Requests são solicitações para integrar alterações de uma branch em outra, permitindo revisão e validação do código antes da união ao projeto principal.

---

# 7.3 Resolução de Conflitos

Conflitos acontecem quando duas alterações modificam o mesmo trecho de código. Para resolver, é necessário analisar as mudanças, escolher a versão correta e realizar um novo commit.
