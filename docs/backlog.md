## (EPIC) Planejamento
1. [x] Criar o documento de visão do projeto (`docs/visao.md`).
2. [x] Definir o escopo e o não escopo do projeto.
3. [x] Criar o roadmap visual no formato `mermaid`.

## (EPIC) Modelagem de Dados
4. [ ] Definir entidades principais (usuários, produtos, pedidos, etc.).
5. [ ] Estabelecer relacionamentos entre entidades.
6. [ ] Criar o diagrama ER inicial (`docs/diagrama_er.dbml`).
7. [ ] Implementar o esquema no PostgreSQL (`scripts/sql/01_esquema.sql`).
    - [ ] Criar tabelas principais (usuários, produtos, pedidos, etc.).
    - [ ] Adicionar constraints (chaves primárias, estrangeiras, etc.).
    - [ ] Validar o esquema com dados de teste.
8. [ ] Adicionar índices otimizados para consultas frequentes (`scripts/sql/02_indices.sql`).

## (EPIC) Governança
9. [ ] Configurar roles e permissões no PostgreSQL.
10. [ ] Implementar Row-Level Security (RLS) para dados sensíveis.
11. [ ] Criar triggers para auditoria básica (log de alterações).

## (EPIC) Monitoramento
12. [ ] Configurar painel no Grafana para monitorar métricas do PostgreSQL.
13. [ ] Criar queries de monitoramento (`monitoramento/queries_monitoramento.sql`).
    - [ ] Consultar transações por minuto.
    - [ ] Identificar deadlocks.
    - [ ] Monitorar uso de índices.
14. [ ] Testar o monitoramento com dados sintéticos.

## (EPIC) Documentação
15. [ ] Criar o dicionário de dados (`docs/dicionario_dados.md`).
16. [ ] Registrar decisões técnicas no arquivo (`docs/decisoes_tecnicas.md`).
17. [ ] Atualizar o README com links para a documentação.
18. [ ] Criar um vídeo curto explicando a arquitetura do projeto.

## (EPIC) Dados de Teste
19. [ ] Criar script Python para gerar dados sintéticos (`scripts/gerador_dados.py`).
20. [ ] Popular o banco com dados de teste (`scripts/sql/03_dados_teste.sql`) (depende da tarefa 19).

## (EPIC) Refinamento
21. [ ] Revisar e otimizar queries com `EXPLAIN ANALYZE`.
    - [ ] Garantir que 95% das queries tenham tempo de execução < 200ms.
22. [ ] Validar a normalização (3NF/BCNF) e documentar trade-offs.
23. [ ] Atualizar o `CHANGELOG.md` com as mudanças realizadas.

---

## Prioridades
- **Alta**: Planejamento, Modelagem de Dados, Governança.
- **Média**: Monitoramento, Documentação.
- **Baixa**: Dados de Teste, Refinamento.
