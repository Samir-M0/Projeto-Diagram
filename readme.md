# Projeto Diagram

Editor visual de esquemas de banco de dados (Diagram)

## Resumo

Projeto open-source para criar, editar e exportar esquemas de banco de dados de forma visual com suporte a: parser simples de DSL (Chimera-like), conversão entre código ↔️ nó/aresta (nodes/edges), exportação para SQL/JSON e visualização de relacionamentos (cardinalidades). O projeto está dividido em dois submódulos: **Back-end** e **FrontEnd**.

## Principais funcionalidades

- Parser de linguagem tipo *Chimera* → converte texto para tabelas e referências.  
- Conversão de tabelas para nós (nodes) e referências para arestas (edges) para uso no editor visual.  
- Geração de código a partir dos nós (serialização) e reconversão para estrutura de tabelas.  
- Visualização de cardinalidades e metadados (PK, FK, UNIQUE, DEFAULT, etc.).  
- Estrutura pronta para integrar frontend em React com backend em PHP e PostgreSQL.

## Tecnologias

- **Frontend:** React + TypeScript, `@xyflow/react` (fluxo/visualização de grafos), Vite, Tailwind (opcional).  
- **Backend:** PHP (puro), PostgreSQL, Nginx, Docker.  
- **Ferramentas dev:** Docker, Docker Compose, Git, DBeaver, Redis.
