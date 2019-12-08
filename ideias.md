## Estrutura do blog
  - Perfil: apresentação sobre mim e descrição do que faço
  - Anuário: timeline dos meus últimos anos com principais conquistas e desafios, agrupados em quarters
  - Artigos
     - Opinião/análise de arquitetura
     - Conceitos: performance, técnicas
     - Blueprint de projetos (visão genérica)
     - Miscelania: viagens, coisas legais

## Layouts possíveis
  - https://html5up.net/story
  - https://html5up.net/editorial
  - https://html5up.net/solid-state
  - https://html5up.net/spectral
  - https://html5up.net/hyperspace
  - https://html5up.net/forty


## Ideias de temas para artigos

------------------------------
### Para que server um arquiteto de software
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


-----------------------------------
### Porquê nossas aplicações são lentas ?

- Explicar que não projetamos aplicações para serem rápidas
   - Que não aprendemos sobre as limitações físicas de processamento
   - Sobre as medidas de tempo: cabe um 1 bilhão de nanos em 1 segundo  (1s = mmm.uuu.nnn)
   - Trazer exemplos de tempo de processamento: leitura de disco, de memória, ciclo de CPU
   - Explicar que a performance esperada não ocorre por acaso, mas a aplicação pode performar por acaso
   
------------------------------------
### Software uma história de falha
 - falar sobre as diversas aplicações que surgiram e morreram ao longo do tempo
 - falar sobre criar diversas aplicações que resolvem o mesmo problema, e como a seleção natural garante a escolha das melhores soluções
 - explicar que as melhores soluções são consequência de trazer beneficios para quem a utiliza; a tecnologia tem que trazer vantagens sobre as outras soluções que se propõem a solucionar um mesmo problema.
 
