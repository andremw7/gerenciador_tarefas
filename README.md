# Gerenciador de Tarefas

Sistema de gerenciamento de tarefas desenvolvido para a disciplina.

## Integrantes
- André Marcelino Watanabe - 14558311
- Nome  - NUSP
- Nome  - NUSP

## Funcionalidades
- Criar tarefas
- Editar tarefas
- Deletar tarefas
- Marcar como concluída
## Fluxo da Aplicação

```mermaid
flowchart TD

A[Início] --> B[Login]

B -->|Criar conta| C[Cadastro]
C --> B

B -->|Login válido| D[Lista de Tarefas]

D --> E[Adicionar nova tarefa]
E --> D

D --> F[Selecionar tarefa]
F --> G[Detalhes da tarefa]

G --> H[Editar tarefa]
H --> D

G --> I[Marcar como concluída]
I --> D

G --> J[Excluir tarefa]
J --> D

D --> K[Filtrar tarefas]
K --> D
