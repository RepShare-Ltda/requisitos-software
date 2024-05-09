


# Projeto Disciplina: Requisitos de Software

[](https://github.com/RepShare-Ltda/requisitos-software#projeto-disciplina-requisitos-de-software)

Olá! Este repositório faz parte do projeto da disciplina de Requisitos de Software da UTFPR - Campus Cornélio Procópio.

## 1. Introdução

[](https://github.com/RepShare-Ltda/requisitos-software#1-introdução)

_**1.1. Grupo 4**_

Felipe Maciel Scalco

Matheus Vinicius Engelesberger

Pablo Alonso Latapiat de Freitas

Pedro Lucas da Silva Mota

Raphael dos Santos Souza

Vitor Akio Suguimoto Kaneko

_**1.2. RepShare**_

RepShare - Aplicativo de gerenciamento de repúblicas.

_**1.3. Propósito do Sistema**_

Este documento apresenta os requisitos dos usuários a serem desenvolvidos pelo _`Grupo 4`_, fornecendo aos desenvolvedores as informações necessárias para o projeto e implementação, assim como para a realização dos testes e homologação do sistema.

O objetivo do sistema `RepShare` é facilitar o gerenciamento financeiro e distribuição de tarefas entre os integrantes de uma república por meio de relatórios, controle de recursos, sistema de votações.

_**1.4. Público Alvo**_

Este documento se destina aos arquitetos de software, engenheiros de software, testadores, clientes e estudantes universitários.

_**1.5. Descrição dos usuários**_

![image](https://github.com/RepShare-Ltda/requisitos-software/assets/164585988/f49b14d1-cd70-4255-a989-754f436c4c70)
![JOAO](https://github.com/RepShare-Ltda/requisitos-software/assets/164586099/abdbb039-a564-4b45-bba3-02cf91190d13)
![MARCIA](https://github.com/RepShare-Ltda/requisitos-software/assets/164586099/8571a741-93df-46c2-b047-b12c01bd1ca1)
![Peter](https://github.com/RepShare-Ltda/requisitos-software/assets/164586099/12f2235e-2298-4eac-890b-1c057e024c06)

_**1.5. Cenários**_

_*1.5. Cenário Antes*_

Peter Parker é um recém universitário e decide morar em uma república com seus amigos, ao longo do tempo eles não gerenciam muito bem os gastos de sua casa, as vezes alguém esquece pagar o outro por alguma compra ou gasto conjunto.
Peter tem o contrato do aluguel em seu nome, seu amigo Clark Kent tem a energia, seu outro amigo Fred Flinston tem a conta de internet e seu outro amigo Albert Einstein tem a conta de água da casa, algumas contas vencem no mesmo dia e outras em dias variados, sempre que chega o dia de pagar elas acontece uma confusão de quem for pagar quem, porque as vezes alguns que tem a conta no seu nome paga ela e pede para descontar nas outras contas, o que gera uma bagunça e uma má gestão da casa, ocasinando em conflitos.

_*1.5. Cenário Depois*_

Peter Parker é um recém universitário e decide morar em uma república com seus amigos, e agora com o RepShare eles gerenciam os gastos da sua casa. 
Peter tem o contrato do aluguel em seu nome, seu amigo Clark Kent tem a energia, seu outro amigo Fred Flinston tem a conta de internet e seu outro amigo Albert Einstein tem a conta de água da casa, algumas contas vencem no mesmo dia e outras em dias variados, sempre que chega o dia de pagar as contas agora é bem simples, eles lançam as contas no app, que calcula automaticamente quanto cada um deve pagar e lembra cada um quando estiver próximo de pagar as contas, e desde que começaram a usar o app, eles sabem o quanto devem pagar e para quem devem pagar e alem disso evitam comflitos. 
Agora ficou bem mais simples, para gerenciar as contas da casa e também conseguir gerenciar as coisas internas da casa.

## 2. Documentos gerais no repositório

[](https://github.com/RepShare-Ltda/requisitos-software#2-documentos-gerais-no-repositório)
_**2.1. Requisitos de usuário e sistema**_
https://padlet.com/pablo2004_1/repshare-3bqo072xbvkg9crg

_**2.2. Requisitos funcionais**_

| Identificador | Descrição | Prioridade |
| --- | --- | --- |
| RF01 | O software deve permitir que o administrador possa realizar restrições de acesso no sistema. | Alta |
| RF02 | O software deve permitir que o usuário possa cadastrar e gerenciar a casa. | Alta |
| RF03 | O software deve permitir que o usuário possa cadastrar e gerenciar pessoas. | Alta |
| RF04 | O software deve permitir que o usuário possa cadastrar e gerenciar insumos da casa. | Alta |
| RF05 | O software deve permitir que o usuário possa cadastrar e gerenciar despesas. | Alta |
| RF06 | O software deve disponibilizar um dashboard de visualização JIT para o usuário acerca das relações de entrada e saída de dinheiro. pessoas, insumos, entre outros. | Media |
| RF07 | O software deve permitir que o usuário inicie votações (anônimas) para decisões gerais na república. | Baixa |
| RF08 | O software deve permitir que o usuário crie avisos para notificar os demais usuários. | Media |
| RF09 | O software deve permitir que o usuário remova e/ou atualize os dados cadastrados. | Alta |
| RF10 | O software deve permitir que o usuário adicione comprovantes de pagamento no gerenciamento de despesas para que o administrador possa realizar a validação | Media |
| RF11 | O software deve permitir que o usuário crie e gerencie um painel de divisão de tarefas | Baixa | 
_**2.3. Requisitos não funcionais**_

| Identificador | Descrição | Prioridade |
| --- | --- | --- |
| RNF01 | O sistema deve intuitivo para que os usuários sejam capazes de utilizar o App dentro de 30 minutos. | Alta |
| RNF02 | O sistema deve estar sincronizado com toda a rede de usuários. | Alta |
| RNF03 | O sistema deve recuperar os dados em caso de falha. | Alta |
| RNF04 | O sistema deve ter portabilidade em sistema operacional Android e IOS. | Alta |
| RNF05 | O sistema deve abrir nos Browsers: Chrome, Safari, Edge, Firefox, Opera. | Alta |
| RNF06 | O sistema deve possuir seus documentos contendo o cabeçalho e rodapé definido pela empresa. | Baixa | 
| RNF07 | O sistema deve ser implementado em HTML, CSS, e JavaScript. | Alta |
| RNF08 | O sistema deve possuir uma aplicação mobile gerada através de WebApp. | Alta |
| RNF09 | O sistema deve utilizar o banco de dados em SQL. | Alta |
| RNF10 | O sistema deve possuir a documentação dos diagramas desenvolvidos no Astah. | Alta |
| RNF11 | O sistema deve ser desenvolvido com o framework React. | Alta |
| RNF12 | O sistema deve ser desenvolvido utilizando a arquitetura atômica. | Alta |
| RNF13 | O sistema deve ocultar as informações pessoais dos clientes aos operadores. | Alta |
| RNF14 | O sistema deve proteger os dados através da LGPD. | Alta |


_**2.4. Protótipos**_

_<Link para a pasta com os protótipos.>_

## Referências

[](https://github.com/RepShare-Ltda/requisitos-software#referências)

_<Esta seção é destinada à descrição das referências utilizadas pelo documento, como por exemplo, URLs e livros. Ver exemplo a seguir:>_

[1] “Glossário da _USina_”, <_id_doc glossário_>, Versão <_versão_>. Localização: <_localização_>.

## Link para entrevista com moradores de republica

[](https://drive.google.com/file/d/1H9f2fjk-glpAx_PSIeCtIgViPlK_Z8ED/view?usp=sharing)
