# Documentação e GDDs

Um dos principais documentos utilizados durante o desenvolvimento de jogos é o **documento de game design** (ou *game design document* / **GDD**). Nesse documento, estão detalhados diferentes aspectos do jogo, voltados a explicar a experiência desejada pelos designers, assim como seu funcionamento, objetivos e regras, principais decisões estéticas e outras considerações. Não existe um único padrão ou abordagem para a elaboração desse tipo de documento, então vamos ver alguns métodos diferentes para lidar com essa documentação.

### Vantagens e objetivos de GDDs

- Comunicar a visão do designer de forma clara
- Ajudar a esclarecer dúvidas em relação a diferentes aspectos do jogo, principalmente escopo
- Marcar detalhes importantes para manter o caráter único do jogo
- Dar uma base comum para que as diferentes especialidades desenvolvam suas áreas

### Desvantagens e problemas de GDDs

- Incentiva uma ideia de que jogos podem ser pensados completamente "de antemão" e não evoluídos aos poucos
- Pode ficar desatualizado rapidamente  
- Pode ficar grande demais e não ser lido
- Nível de detalhe incoerente: toda a vida de um personagem, poucos detalhes sobre mecânica principal
- Podem ser uma grande perda de tempo de desenvolvimento
- Podem engessar ideias que ainda não foram comprovadas por testes
- Designers se apegam a GDDs

## Em Proj2

Na disciplina vamos adotar o uso do game design macro para entrega de conceitos, num primeiro momento, e do SGDD como forma consolidada de GDD mais adiante. As metodologias estão listadas abaixo.

## Metodologias

### [Short Game Design Document (ShGDD)](http://www.sbgames.org/sbgames2013/proceedings/artedesign/15-dt-paper_SGDD.pdf)

![SiGDD](../imgs/sgdd.PNG)

Formato reduzido e simples, focado na escrita, voltado para game jams e trabalhos escolares que precisam de documentação resumida e que já incorpora elementos de gestão de projetos.

### GDDs "canvas" de uma página

 - [Game Design Macro (em excel)](../materiais/gd-macro.xlsx) e [em PDF](../materiais/gd-macro.pdf).

Estes são formatos para criação de game designs de alto nível (menos detalhes, mais ideias gerais). O foco está numa apresentação resumida em que seja fácil diferenciar ideias e apresentar todos os principais aspectos de uma ideia de jogo, seja de forma textual ou visual.

O formato acima é baseado nas [idéias de Stone Librande, que cunhou o termo One-Page Design](http://stonetronix.com/gdc-2010/OnePageDesigns.ppt) para identificar abordagens que comunicam ideias sobre um jogo através de diagramas e imagens de forma resumida e atrativa em formatos grandes para facilitar apropriação e discussão.

![Diagrama mostrando funcionamento de Diablo 2](../imgs/diablo2_combate.jpg)

*Diagrama mostrando o sistema de combate em Diablo 2 (Stone Librande).*

## Como criar um GDD?

1. Usar ferramentas que facilitem colaboração, seja presencial ou à distância (comentários, marcar pessoas, histórico). *Exemplos: Google Docs / Planilhas, Trello*.
2. Tornar uma pessoa responsável pela manutenção e atualização do GDD, mas aberta aos inputs de todos.
3. Use imagens (próprias ou com licenças adequadas) quando possível, pois às vezes um diagrama ou mockup explica melhor uma feature do que muitas palavras.
4. Lembre-se: cada jogo vai acabar tendo um GDD diferente, para atender suas necessidades específicas. Pense no que é mais importante para seu jogo.

> Por exemplo, um documento de Super Mario Bros. possivelmente teria um capítulo sobre 1) Movimentação, 2) Inimigos, 3) Elementos do level, 4) Levels, 5)Limitações de gameplay e 6)Feedback sonoro e visual. No primeiro capítulo, seria descrito a movimentação do Mario, no que ela era semelhante a outros jogos plataforma da sua época e no que ela era diferente. No segundo, cada um dos inimigos seria descrito e como eles funcionavam. No terceiro, o funcionamento das estruturas do mundo como os buracos, os tubos, as plataformas que podem ser atravessadas ou não, destruídas ou não e a bandeira de fim de fase. O capítulo de levels daria uma intro de quantos mundos e quantos levels por mundo existem, mencionando as mudanças estéticas e de level design em cada um deles. O quinto capítulo falaria do sistema de vidas, de pontos e de tempo, ou seja, tudo que limita o jogador e adiciona dificuldade ao jogo que é externo ao level design. Por fim, o capítulo de feedback explicaria a musica e efeito visual de pegar uma estrela, os efeitos de morte, o som de pegar uma moeda, a aceleração da musica quando o tempo está acabando etc. (*Thais Weiller*)

---
### Referências

- COOK, D. Lost Garden: **Game Design Logs**, [s.d.]. Disponível em: <http://www.lostgarden.com/2011/05/game-design-logs.html>. Acesso em: 30 ago. 2016
- SCHELL, J. **A arte do game design: o livro original.** [s.l.] CRC Press, 2010.
- WEILLER, T. **GDD: quando, onde e como.** Disponível em: <http://gamestartlivro.net/post/138084851042/gdd-quando-onde-e-como>. Acesso em: 30 ago. 2016.
