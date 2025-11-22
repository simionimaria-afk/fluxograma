```mermaid
flowchart TD
    A[Início] --> B{A tarefa foi concluída?}
    B -- Sim --> C[Encerrar processo]
    B -- Não --> D[Executar tarefa]
    D --> B
