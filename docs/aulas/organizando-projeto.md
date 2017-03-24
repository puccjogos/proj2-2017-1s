# Organizando um projeto de jogo digital

Já falamos sobre [GDDs e documentação](../aulas/documentacao.md), a elaboração de documentos para comunicar a visão de como deve ser o jogo sendo desenvolvido. Hoje, vamos tratar das principais etapas, documentos e métodos para organizar esse processo de produção. A metodologia que utilizaremos como base chama-se [Scrum](http://pt.wikipedia.org/wiki/Scrum), e vamos utilizá-la de forma adaptada em nossos projetos.

## Pré-produção

Na pré-produção, além de protótipos e decisões de design, é essencial consolidar o planejamento do projeto. Para conseguir isso, as etapas abaixo podem ajudar.

![](https://raw.githubusercontent.com/puccjogos/ProjIntegrado2-2015/master/Imgs/fluxo_plano.png)

*Fluxo básico de planejamento.*

### Objetivos

Defina todos os objetivos que devem ser alcançados para que seu projeto ocorra como o desejado. Lembre-se de marcar tanto objetivos técnicos quanto da experiência do jogador.

### Entregas / produtos

Quais materiais / produtos serão desenvolvidos ao longo do projeto? Alfas, versões jogáveis, trabalho de arte, ferramentas de criação, etc. Toda produção que for necessária para alcançar os objetivos do projeto devem ser definidas e previstas.

## Documentos

As duas principais dimensões do planejamento, além da equipe, envolvem sua organização no tempo (*calendário*) e a organização de recursos (*orçamento*). As duas são discutidas em mais detalhes abaixo.

### Calendário

1. Defina, para cada entrega, uma lista de tarefas e requisitos para que seja alcançada.
2. Defina quanto tempo será necessário para que cada tarefa ou recurso seja produzido.
3. Defina datas iniciais e finais para cada tarefa, levando em consideração sua ordenação.

Um tipo de documento bastante utilizado para a organização de calendários é um [**diagrama de Gantt**](http://pt.wikipedia.org/wiki/Diagrama_de_Gantt). Esse formato ajuda a entender as diferentes dependências e durações de cada ciclo visualmente, assim como pode ser facilmente implementado numa planilha.

![](https://raw.githubusercontent.com/puccjogos/ProjIntegrado2-2015/master/Imgs/gantt.png)

*Exemplo de diagrama de Gantt.*

### Orçamento

Consiste em um documento que nos permite estimar e calcular os diferentes custos envolvidos na produção de um jogo. Custos aqui devem englobar todos os investimentos necessários à produção: equipamentos, mão-de-obra, licenças, espaço de trabalho, despesas de promoção, etc. Uma boa maneira de proceder é atribuir valores aos diferentes elementos listados no calendário e nas entregas e criar uma planilha que permita sua análise e alteração de forma consistente e clara.

![](https://raw.githubusercontent.com/puccjogos/ProjIntegrado2-2015/master/Imgs/orcamento.png)

*Exemplo de planilha de orçamento.*

## Gerenciamento de projeto

Qualquer projeto sempre envolve o equilíbrio dinâmico entre escopo, recursos e capacidade produtiva. Além desses fatores *internos*, temos que pensar em fatores *externos* que alteram o processo, como mudanças grandes de contexto ou novas necessidades repentinas.

Para organizar o trabalho, é necessário planejamento e método, o que também não significa que tudo deve ser rigorosamente planejado de antemão. Aliás, no desenvolvimento de jogos, é cada vez mais comum que projetos adotem métodos ágeis, que enfatizam a flexibilidade, a iteração (refinamentos cíclicos) e a interação com clientes e jogadores.

### Desenvolvimento ágil

> A maioria dos métodos ágeis tenta minimizar o risco pelo desenvolvimento do software em curtos períodos, chamados de iteração, os quais gastam tipicamente menos de uma semana a até quatro. Cada iteração é como um projeto de software em miniatura de seu próprio, e inclui todas as tarefas necessárias para implantar o mini-incremento da nova funcionalidade: planejamento, análise de requisitos, projeto, codificação, teste e documentação. Enquanto em um processo convencional, cada iteração não está necessariamente focada em adicionar um novo conjunto significativo de funcionalidades, um projeto de software ágil busca a capacidade de implantar uma nova versão do software ao fim de cada iteração, etapa a qual a equipe responsável reavalia as prioridades do projeto.

Para metodologias de desenvolvimento ágil, existem algumas prioridades, listadas abaixo:

> **Indivíduos e interações** mais que processos e ferramentas
>
> **Software em funcionamento** mais que documentação abrangente
>
> **Colaboração com o cliente** mais que negociação de contratos
>
> **Responder a mudanças** mais que seguir um plano

Esse texto vem do *Manifesto para Desenvolvimento Ágil de Software* de 2001, disponível [aqui](http://agilemanifesto.org/iso/ptbr/). Pensando no nosso contexto, podemos pensar em outros objetivos mais concretos:

+ Ter um melhor entendimento do próprio progresso e controlar melhor seu cronograma
+ Focar em interação frequente com jogadores e ter uma versão jogável sempre
+ Melhor entendimento de como entender e usar os conceitos de escopo, recursos e capacidade produtiva.
+ Conseguir se adaptar a contingências e colaborar de forma efetiva

## Scrum

Scrum é uma metodologia para organizar equipes trabalhando em um projeto. Ela define desde diferentes papéis para os membros da equipe até como organizar calendários e cronogramas (sprints de uma/duas semanas).

### Papéis

+ *Mestre do scrum.* Organiza as reuniões diárias e mantém a equipe em dia. É o papel intermediário entre a equipe e o representante do produto. É o responsável pela aplicação da metodologia. *NÃO É CHEFE DE NINGUÉM*.
+ *Representante do Produto.* Representa os jogadores do seu jogo, assim como os diferentes interesses envolvidos. Seu papel é priorizar os objetivos do cliente e os adicionar para no product backlog. Recomenda-se que este papel não seja combinado com o de *mestre de scrum*.
+ *Equipe*. É um grupo multifuncional que fazem a análise, projeto, implementação, teste, etc.

### Backlogs

Todo o trabalho do projeto é organizado em um **backlog do produto (PBL)** (ou *product backlog*), onde todos os requisitos estão listados e priorizados. O backlog do produto é mantido pelo representante do produto e é uma lista de requisitos que tipicamente vêm dos clientes/jogadores. O PBL pode ser alterado a qualquer momento pelo representante do produto.

O **backlog do sprint (SBL)** é uma lista de itens selecionados do backlog do produto e contém tarefas concretas que serão realizadas durante o próximo sprint (período de uma ou duas semanas). É de responsabilidade da *equipe*. Muitas vezes toma a forma de um mural (físico ou virtual) onde a equipe controla suas tarefas.

![Exemplo de mural de sprint](http://upload.wikimedia.org/wikipedia/commons/1/1b/Scrum_task_board.jpg)

### Reuniões

#### Scrum diário

Cada dia durante o sprint, uma reunião de status do projeto ocorre. Isso é chamado de **scrum diário**. Esta reunião tem diretrizes específicas:

+ A reunião começa precisamente no horário marcado.
+ Todos são bem-vindos, mas apenas "poucos" podem falar.
+ O encontro tem duração determinada e dura 15 minutos.
+ A reunião deve acontecer no mesmo local e mesma hora todos os dias

Durante a reunião, cada membro da equipe responde a três perguntas:

+ O que você tem feito desde ontem?
+ O que você está planejando fazer hoje?
+ Você tem algum problema impedindo você de realizar seu objetivo?

#### Planejamento de Sprint

Esta reunião é realizada no início do ciclo de cada sprint.

+ Revisar o trabalho que foi concluído ou não.
+ Refletir sobre como foi o trabalho nesse período.
+ Selecione o trabalho que está sendo feito.
+ Prepare o backlog de sprint que detalha o tempo que levará para fazer esse trabalho (toda a equipe).
+ Priorizar o backlog de produto (representante do produto).
+ Apresentar o trabalho realizado para as partes interessadas ("demo").

### Métodos e ferramentas

A transparência e boa comunicação são fundamentais. Para facilitar isso, é importante usar ferramentas adequadas para marcar o progresso e o estado do projeto. Abaixo estão algumas destas ferramentas:

+ Ferramenta: [Trello](http://trello.com)
+ Ferramenta: [Google Docs](http://drive.google.com)
+ Ferramenta: [GitHub Project e Issues](https://github.com/enricllagostera/LevelDesign-Platformer/projects) (exemplo)

## Referências

FULLERTON, T. **Game design workshop: a playcentric approach to creating innovative games.** 2a ed. Boston: Elsevier Morgan Kaufmann, 2008.
