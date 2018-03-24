# mermaid

Código da relação de dependências e durações das tarefas.

| Tarefa |             Nome           | Dependências   | Tempo | 
| ------ |:--------------------------:|:--------------:| -----:|
|   T1   | Levantamento de Requisitos |                |  15   |
|   T3   | Github                     |                |  1    |
|   T4   | Backlog                    | T1             |  6    |
|   T5   | Slack                      |                |  1    |
|   T6   | Ambiente                   | T1             |  5    |
|   T7   | Trello                     | T4             |  1    |
|   T2   | Apresentação Inicial       | T1             |  3    |
|   T8   | Modelos a Utilizar         | T1             |  5    |
|   T9   | Front-end                  | T3, T6, T4, T8 |  120  |
|   T10  | Back-end                   | T3, T6, T4, T8 |  120  |
|   T11  | Testes                     | T3, T6, T4, T8 |  90   |
|   T12  | Entrega Relatório          | T11, T10,T9    |  30   |
