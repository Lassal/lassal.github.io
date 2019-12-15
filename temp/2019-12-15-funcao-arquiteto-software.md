
## Draft: Ideia inicial
------------------------------
Descrever o que faz um arquiteto de software de forma suscinta, explicar quando a atividade se tornou relevante, e explicar o que um arquiteto deveria fazer pelo contexto de quando o arquiteto falha.
 
  1. Visão geral do arquiteto [ver wiki](https://en.wikipedia.org/wiki/Software_architecture)
  
> Software architecture refers the fundamental structures of a software system and the discipline of creating such structures and systems. Each structure comprises software elements, relations among them, and properties of both elements and relations.[1] The architecture of a software system is a metaphor, analogous to the architecture of a building.[2] It functions as a blueprint for the system and the developing project, laying out the tasks necessary to be executed by the design teams.[3]
> Software architecture is about making fundamental structural choices that are costly to change once implemented.

2. Explicar que a atividade se tornou relevante com a adoção de OO e necessidade de componentização, reaproveitamento e redução de custos.

3. O arquiteto de software falha quando:
  1. projeta algo que é difícil do time trabalhar
  2. não entende o problema que "os verdadeiros" usuários (aqueles que vão usar ela de fato) querem solucionar
  3. não entende os volumes de acesso esperados para a aplicação, nem suas formas de uso
  4. não entende as perspectivas de futuro para a aplicação e como ela pode evoluir
  5. não entende como esta aplicação pode ser mantida e evoluída após sua concepção original
  
4. Ligar o quanto estes pontos tem a ver com comunicação, e entendimento de todos stakeholders, e mostrar que um arquiteto tem que ser um bom comunicador, conciliador, e não um cara que só manja de tecnologia. Ele precisa entender diversas tecnologias e entender os problemas que elas solucionam mas o mais importante é identificar os problemas que devemos solucionar, e para isso precisamos olhar pra as pessoas pois quem tem problemas a resolver são as pessoas.

-------------------------------

## Para que serve um arquiteto de software

Trabalho como arquiteto de software a mais de 15 anos e toda vez que falo que sou um arquiteto de software para alguém que não é de TI as pessoas se impressionam com o título. Apesar do título bonito há bastante falta de clareza de qual é a função de um arquiteto de sofware. Neste artigo vou explicar minha visão sobre arquitetura de software e como o arquiteto de software pode ser mais útil aos contextos que atua.
o porquê esta competência deveria estar instalada nos seus times de produtos e sistemas.

De forma bem resumida a função da arquitetura de software é fazer escolhas estruturais que serão mais baratas de alterar uma vez implementadas. O arquiteto de software é responsável por definir estas estruturas fundamentais que irão habilitar que os diversos grupos de interesse envolvidos na construção de uma aplicação sejam atendidos.

Quando me refiro aos diversos grupos de interesse me refiro obviamente ao demandante do software, mas também a quem efetivamente vai usar a aplicação, ao time que está construíndo a aplicação, a gestão que está conduzindo o projeto de construção, e ao time que vai manter a aplicação uma vez ela criada. Todos tem expectativas diferentes mas são afetados pela aplicação.

Acho mais fácil descrever o que um arquiteto de software faz pelo impacto de suas ações do que por um modelo prescritivo. Na minha visão o arquiteto de software falha quando:

  1. projeta algo que é difícil do time trabalhar
  2. não entende o problema que "os verdadeiros" usuários (aqueles que vão usar ela de fato) querem solucionar
  3. não entende os volumes de acesso esperados para a aplicação, nem suas formas de uso
  4. não entende as perspectivas de futuro para a aplicação e como ela pode evoluir
  5. não entende como esta aplicação pode ser mantida e evoluída após a fase de criação (projeto)

A função de arquiteto de software se consolidou no começo dos anos 2000 com a adoção das linguagens orientadas a objeto nas empresas, notadamente Java e .Net., e com a promessa de reaproveitamento de código e componentização (que aparentemente deu muito certo pelo avanço da tecnologia nos últimos 10 anos). Metodologias como RUP ajudaram a definir o papel do arquiteto de software suas funções e responsabilidades. 
Ao longo deste período a função já foi "glorificada" em alguns casos na forma de um profissional que detêm o conhecimento absoluto de como as aplicações devem ser construídas, à banalização das empresas terem a posição de arquitetos de software nos times mas sem a definição clara de suas funções.

Já quase em 2020, não faz sentido ter profissionais que detenham todo o conhecimento (até porque eles não existem). No ambiente altamente colaborativo que vivemos a função do arquiteto é mais de interlocutor entre os aspectos técnicos do software e as diversas partes atingidas por aquele software. Sua função é mais entender a necessidade humana, seja performance, segurança, facilidade de desenvolvimento, e traduzir em soluções economicamente viáveis do que bolar soluções de alta complexidade técnica compreendidas por poucos.

Este profissional precisa sim ter uma boa bagagem técnica mas precisa principalmente saber ouvir os outros e enriquecer a solução técnica com as diversas perspectivas. Saber os detalhes de como uma tecnologia funciona é importante mas o mais importante é saber quais problemas ela endereça, os custos dela ao longo do tempo  e mais importante é saber avaliar quando é adequado utiliza-la. E para esta última análise precisamos falar com as pessoas, entender suas necessidades e limitações de recursos. O trabalho que inicialmente parece um trabalho muito técnico depende de um foco em pessoas muito grande.

É muito comum os desenvolvedores se interessarem pela disciplina de arquitetura de software pelas possibilidades de aprendizado e poder aplicar novas tecnologias, que vão acontecer, mas não perceberem que função envolve muito mais comunicação do que tecnologia e que a tecnologia só faz sentido quando traz beneficio à alguém. A tecnologia mais avançada pode não ser a mais adequada ao seu contexto de trabalho e negócio, saber dosar o que vai ser mais economicamente viável (em custos financeiros diretos e indiretos como desenvolvimento de pessoal) deve ser o foco principal do arquiteto de software.


