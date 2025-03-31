# 🛒 Sistema OLTP para E-Commerce

## 📖 Visão Geral
Um sistema OLTP (Online Transaction Processing) é projetado para gerenciar transações em tempo real, garantindo integridade e performance. Este projeto simula um sistema de e-commerce para demonstrar boas práticas de modelagem relacional e governança de dados.

Foco principal:
- **Modelagem relacional avançada** (3NF/BCNF).
- **Governança de dados** (RLS, auditoria, backups).
- **Monitoramento** com Grafana.
- **Documentação profissional** para aprendizado e portfólio.

## 📂 Estrutura do Projeto
```plaintext
ecommerce_oltp/
├── 📁 docs/                      # Documentação detalhada
│   ├── visao.md                  # Documento de visão do projeto
│   ├── backlog.md                # Backlog priorizado
│   ├── diagrama_er.png           # Diagrama ER (imagem)
│   ├── decisoes_tecnicas.md      # Registro de escolhas técnicas
│   └── dicionario_dados.md       # Dicionário de dados
├── 📁 infra/                     # Configuração Docker
│   ├── docker-compose.yml        # Arquivo de configuração do Docker Compose
│   └── Dockerfile                # Dockerfile para o ambiente
├── 📁 scripts/                   # Scripts SQL e Python
│   ├── gerador_dados.py          # Gerador de dados sintéticos
│   └── sql/                      # Scripts SQL
│       ├── 01_esquema.sql        # Criação do esquema do banco
│       ├── 02_indices.sql        # Criação de índices
│       └── 03_dados_teste.sql    # Inserção de dados de teste
├── 📁 monitoramento/             # Configuração de monitoramento
│   ├── dashboard_grafana.json    # Dashboard do Grafana
│   └── queries_monitoramento.sql # Queries para monitoramento
├── [CHANGELOG.md]                # Histórico de mudanças
├── LICENSE                       # Licença do projeto
└── [README.md]                   # Documentação principal
```

## 📌 Documentação Completa
- **Visão do Projeto**: [docs/visao.md](docs/visao.md)
- **Backlog**: [docs/backlog.md](docs/backlog.md)
- **Decisões Técnicas**: [docs/decisoes_tecnicas.md](docs/decisoes_tecnicas.md)
- **Histórico de Versões**: [CHANGELOG.md](CHANGELOG.md)

## 🚀 Status Atual
- **Planejamento**: Concluído ✅
- **Modelagem de Dados**: Em andamento 🚧
  - Definição de entidades principais.
  - Estabelecimento de relacionamentos.
  - Criação do diagrama ER.

## 🛠️ Tecnologias Planejadas
- **PostgreSQL**: Banco de dados relacional.
- **Docker**: Para configuração e execução do ambiente.
- **Grafana**: Monitoramento de métricas do banco de dados.

## 🧑‍💻 Como Contribuir
1. Faça um fork do repositório.
2. Crie uma branch para sua feature:
   ```bash
   git checkout -b minha-feature
   ```
3. Faça um commit:
   ```bash
   git commit -m "feat: minha nova feature"
   ```
4. Envie para o repositório remoto:
   ```bash
   git push origin minha-feature
   ```
5. Abra um Pull Request.

## 📝 Licença
Este projeto está licenciado sob a Licença MIT. Consulte o arquivo [LICENSE](LICENSE) para mais detalhes.

