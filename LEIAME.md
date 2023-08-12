# Dia do Juízo Solar ==============

#### Quem teria imaginado? Dispositivos de Juízo Final consomem MUITA energia. A Comandante Lambda quer complementar o núcleo do reator de antimatéria quântica do LAMBCHOP com matrizes solares, e você foi encarregado de instalar os painéis solares. Devido à natureza do revestimento exterior da estação espacial, todos os seus painéis solares devem ser quadrados. Felizmente, você possui uma área muito grande e plana de material solar, um par de tesouras industrial de alta resistência e fita solar MegaCorp(TM) suficiente para juntar qualquer excesso de material dos painéis em mais quadrados. Por exemplo, se você tiver uma área total de 12 jardas quadradas de material solar, você poderia fazer um painel quadrado de 3x3 (com uma área total de 9).

#### Isso deixaria 3 jardas quadradas, então você poderia transformá-las em três painéis solares quadrados de 1x1. Escreva uma função solution(area) que receba como entrada uma única unidade de medida representando a área total dos painéis solares que você possui (entre 1 e 1000000, inclusive) e retorne uma lista das áreas dos maiores quadrados que você poderia formar com esses painéis, começando pelos maiores quadrados primeiro.

#### Portanto, seguindo o exemplo acima, solution(12) retornaria [9, 1, 1, 1].

### Linguagens =========
Para fornecer uma solução em Python, edite solution.py
Para fornecer uma solução em Java, edite Solution.java

### Casos de teste ==========
Seu código deve passar pelos seguintes casos de teste. Note que ele também pode ser executado em casos de teste ocultos não mostrados aqui.
-- Casos em Python --

Entrada:solution.solution(15324)Saída: 15129,169,25,1
Entrada:solution.solution(12)Saída: 9,1,1,1
-- Casos em Java --

Entrada:Solution.solution(12)Saída: 9,1,1,1
Entrada:Solution.solution(15324)Saída: 15129,169,25,1