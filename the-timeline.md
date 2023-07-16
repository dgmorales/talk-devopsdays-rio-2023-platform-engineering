# A Linha do Tempo

## Os velhos tempos

Deploy manual na Stone quando eu entrei.

O pen drive.

Problemas do deploy manual:

- Inconsistência: no build da app, nos testes (manuais tb), e na publicação
- Lentidão --> **_slow feedback loop_**. Além de ser manual, tem que arranjar um horário que uma pessoa de Dev e outra de Ops esteajm disponíveis, etc.

## Agile Manifesto (2001)

Em um Resort de Ski nos Estados Unidos, os pioneiros da agilidade escreveram:

- Individuals and interactions over processes and tools
- Working software over comprehensive documentation
- Customer collaboration over contract negotiation
- Responding to change over following a plan

_while there is value in the items on the right, we value the items on the left more._

Não, agilidade não é (só) sobre o seu board Scrum ou Kanban.
--> link para artigo enfatizando a importância das práticas técnicas de agilidade.

Mas a agilidade não acabou com o deploy manual. Naturalmente, ela causou **atrito**.

Note: queremos nos adaptar mais rápido, trabalhar mais iterativamente, encurtar feedback loops, leva a deploys mais frequentes (que precisam funcionar sem causar problemas)

## Cloud (2006)

AWS lança o S3 e o EC2.

## DevOps (2008-2009)

DevOps é a resposta encontrada para superar esse atrito. Ele é o resultado do impacto da agilidade na disciplina de Operações. Resultado que mudou Operações e Desenvolvimento para sempre, aproximando esses mundos, e trazendo um caminhão de práticas e tecnologias novas para viabilizar essa aproximação.

- 2008: Conferência sobre Agile Infrastructure em Toronto. Patrick Debois e Andrew Shafer debatem sobre as dores que agilidade trás para Ops.
- 2009: 10k Deploys a day (Allspaw & Hammond, Flickr), Debois organiza o 1o DevOpsDays em Ghent, na Bélgica.

A minha entrada na Stone, os tempos do Evolução Infra (sem citar nomes)


You build it, You run it


tools timeline:

- docker
- puppet
- terraform
- kubernetes

Histograma por ano dos first commit date de cada item na https://landscape.cncf.io/

