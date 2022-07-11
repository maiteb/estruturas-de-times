---
title: Como estruturar times de forma a reduzir carga cognitiva
template: extended-template.html
theme: css/extended-robot-lung.css
highlight-theme: 'monokai'
revealOptions:
    transition: 'fade'
---

### Como estruturar times de forma a reduzir carga cognitiva

<div class="author"> Maitê Balhester </div>

---

#### Maitê Balhester

Bacharel em Ciência e Tecnologia & Ciência da Computação pela UFABC

+10 anos trabalhando com desenvolvimento de software, +5 liderando times

Atualmente Diretora de Engenharia de Software no [Nubank](https://www.nubank.com.br)

---

#### Tipos comuns de problemas que times em crescimento enfrentam

1. Time com muito escopo e sem conseguir iterar e evoluir em soluções e arquitetura;

2. Times com sobreposição de escopo que leva a nenhum deles agir como dono de fato;

3. Novas pessoas integrantes tem muita dificuldade em ganhar contexto e de se sentirem produtivas;

4. Pessoas gerentes e líderes técnicas sobrecarregadas pelo contexto e pela quantidade de pessoas a suportar;

5. Outros times tem dificuldade de entender e de ter a ajuda necessária por conta dos itens anteriores.
---
#### Resumindo, todos esses pontos acarretam em alta carga cognitiva

Carga cognitiva: [John Sweller](https://link.springer.com/chapter/10.1007/978-1-4419-8126-4_6) define como a quantidade total de esforço mental sendo usada na memória do trabalho, e é bem difícil de ser metrificada, mas que impacta profundamente o time e o produto que está sendo desenvolvido.

---
#### Três momentos de carga cognitiva

1. **Intrínseca:** Carga para começar algo novo, como um projeto. Queremos **simplificá-la**;
2. **Irrelevante:** Carga que cria distrações e impede o bom funcionamento da memória de trabalho, como um código mal organizado. Queremos **reduzí-la**;
3. **Relevante:** Carga de um processo cognitivo mais profundo, onde é possível processar assuntos mais complexos, acessar memória de longo prazo. Queremos **buscá-la** e **maximizá-la**.

---
#### Consegue reconhecer esses problemas no seu time? 
##### Talvez seja hora de uma reorganização

---

#### Objetivos de uma reorganização

1. Encontrar o melhor equilíbrio de carga cognitiva, facilitando o aprendizado e aumentando eficiência do time (não apenas produtividade);
2. Ser justa e dar oportunidade para as pessoas do time se desenvolverem.

---
#### Passo #1: Agrupar escopos 

Um time deve ser responsável por um escopo coeso e que minimize a dependência entre times.
Técnicas para agrupar escopos: [Jobs to be done](https://www.toptal.com/designers/ux/jobs-to-be-done-framework), [Segmentos de Clientes](https://www.zenvia.com/blog/segmentacao-de-clientes/), Tipos de Produto, Plataformas gerais, etc

É importante garantir que os sistemas atuais também estejam bem distribuídos nesses escopos, e não apenas novas iniciativas.

---

#### Passo #2: Pelo grupo de escopo, definir melhor estrutura de time

Dado os escopos agrupados, como saber o melhor tipo de estrutura de time para atendermos as necessidades do negócio.
No livro Team Topologies, os autores propõe quatro tipos de estruturas para representar estes grupos de escopos.

---

#### Tipo #1: _Stream-aligned_ (Vertical)

É o time cujo escopo é altamente conectado ao domínio do negócio ou capacidade organizacional, cujo fluxo contínuo envolve entrega de valor direta ao cliente final do negócio, podendo ser desde um simples produto de ponta a ponta, ou até responsável por parte da jornada do usuário, de um Job to be Done, etc. 

---

#### Tipo #2: _Enabling_ (Habilitador)

Time composto por pessoas especialistas, seja tecnicamente ou de negócio, que constroem pontes para capacitar os times verticais que estão focados na entrega de valor. Esperado que seja um time capaz de gerar muito conhecimento e ser altamente colaborativo de forma a habilitar diversos times.

---

#### Tipo #3: _Complicated subsystem_ (Subsistema Complicado) 

Time responsável por uma parte do sistema que é bem complicada e depende de algum conhecimento muito específico. Importante para isolar esta complexidade do resto da organização, deve ser formado por especialistas do domínio.

---

#### Tipo #4: _Platform_ (Plataformas)

Time cuja responsabilidade é abstrair conceitos técnicos e de negócios em plataformas de forma a simplificar e acelerar a entrega de valor pelos times verticais, mas sem criar acoplamento e dependência forte entre os times.

---

#### Exemplo de organização composta pelas diversas arquiteturas

<img alt="Team topologies" src="https://i0.wp.com/engineering.pipefy.com/wp-content/uploads/2022/04/1_Tqpo_Ni3hxeDKtReXPIV8w-1.png" width="700" height="400">

---

#### Passo #3: Como compor esses times?

Como vimos, tipos diferentes de estruturas têm diferente requerimentos de perfis, porém existem algumas dicas baseadas na minha experiência:

---
#### Dica #1

Especialistas não necessariamente significam "pessoas seniores", é importante garantir um bom mix de senioridade em todos os times;

---

#### Dica #2.1

Mix de senioridade depende muito do tipo de time sendo formado:

- Times verticais usualmente são times onde é possível se desenvolver de maneira mais ampla, mas não necessariamente profunda (_T-shaped_), logo uma razão de uma pessoa lider técnica/senior para até cinco pessoas juniores/plenas costuma funcionar bem

---

#### Dica #2.2

- Para times habilitadores e plataformas, por estarem trabalhando com grandes abstrações de domínio e de tecnologias, a razão deve ser um pouco diferente, cerca de uma pessoa líder técnica/senior para até três pessoas juniores/plenas pode ser uma boa medida.
- Para times que cuidam de um subsistema complexo, uma razão próxima à dos times verticais (1:5) pode funcionar, mas até mais importante que mix de senioridade, é importante que o time tenha um bom tempo de casa (_tenure_) médio para fomentar conhecimento no time e na organização.   

---

#### Dica #3.1

Razão pessoa gerente para pessoas lideradas vai variar muito mais pelo tempo de experiência da pessoa gerente do que qualquer outra coisa:
- Pessoas na sua primeira até segunda experiência como gerente precisam de tempo para consolidar conhecimentos de gestão de pessoas e de processos, e para isso um time com máximo seis pessoas lideradas que cresce aos poucos é ideal.
- Pessoas já mais experientes e com processos mais estabelecidos usualmente se sentem confortáveis em liderar até dez pessoas

---

#### Dica #3.2

**Opinião Pessoal**: Para que pessoas gerentes também consigam se desenvolverem em outros pontos, especialmente em quesitos técnicos e de processos, liderar sete pessoas (máximo oito) se mostrou o ideal.

---

#### Dica #4

Por todo este conteúdo, assumimos que estamos falando de equipes multidisciplinares que devem conter todas as especialidades necessárias para entregar o valor necessário. Com isso, minha sugestão é sempre de uma pessoa gerente de produto e pessoa designer para cada oito pessoas desenvolvedoras, por exemplo.

Como líderes é nosso papel também encontrar caminhos de influenciar a liderança das nossas organizações para garantir esse equílibrio entre papéis e ter um processo de _upstream/downstream_ (descoberta/entrega) bem azeitado.

---

#### Dica Final

Nós enquanto pessoas gerentes precisamos garantir que nossos times sejam diversos e inclusivos, não importando o tipo de time.

---

#### Passo #4: Definir rituais e métodos de comunicação entre times

Mais até que ter padrões bem definidos para comunicação entre sistemas, é importante que a organização tenha rituais muito bem definidos para que os times consigam mitigar as dependências e compartilhar conhecimento/experiências

---

#### Exemplo de rituais 

Existem dois rituais do Kanban, as chamadas [Kanban Cadences](https://getnave.com/blog/kanban-meetings/), que agregam muito valor para a comunicação entre times (e recomendo olharem todas os rituais)

1. **Strategy Review:** Uma vez por trimestre, os times revisitam a estratégia e se está alinhado com o que desejamos enquanto negócio, e traz visibilidade de operação e dependências. Importante para times entenderem como roadmaps se comunicam e alinhar priorização de longo prazo.

2. **Operations Review:** A cada mês, a organização revisa o sistema global, demanda e capacidade do todo e de cada um dos times que a formam, com foco em dependências.

---

#### Passo Final: Garanta que o processo de melhoria contínua está no lugar

Conforme a organização cresce e mais times são formados, é muito fácil não conseguirmos observar problemas que em times menores emergeriam mais rapidamente, dado a frequência das retrospectivas dos times serem mais recorrentes. 
Ideias para coletar _feedback_ sobre a organização:

1. Retrospectiva da Organização, com representantes dos times;
2. Pesquisas de clima e engajamento.

---

#### Obrigada!

- Twitter: [@mbalhester](https://twitter.com/mbalhester)
- Linkedin: [@mbalhester](https://www.linkedin.com/in/mbalhester/)
- Github: [@maiteb](https://github.com/maiteb/)

Essa apresentação está disponível neste [repositório](https://github.com/maiteb/estruturas-de-times)