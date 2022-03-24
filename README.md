# protecaodiferencial
Protecao diferencial percentual de transformadores

Algoritmo do relé de proteção de transformadores de potência.

1. Analisa os sinais de corrente provenientes dos TCs do primário e secundário do transformador.
2. Corrige a fase e amplitude dos sinais.
3. alcula os fasores pelo método de Fourirer recursivo.
4. Analisa-se se há a ocorrência de falta.

- Faltas internas devem fazer o relé atuar.
- Faltas externas não devem fazer o relé atuar.
