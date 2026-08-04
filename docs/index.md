# Visão Geral — moodle-tool_dbmigrate

O **`moodle-tool_dbmigrate`** é uma ferramenta CLI de administração para o Moodle projetada para efetuar a **migração de banco de dados** da plataforma entre diferentes SGBDs (com suporte testado e validado de migrações MySQL/MariaDB para PostgreSQL).

---

## 🚀 Principais Recursos

- **Migração Transversal de SGBD**: Transfere dados de tabelas e sequências do Moodle mantendo integridade relacional.
- **Execução via Terminal (CLI)**: Processa grandes volumes de dados sem estourar limites de memória ou tempo do servidor web.
- **Suporte a MySQL e PostgreSQL**: Homologado para ambientes de produção.

---

## 📚 Tópicos da Documentação

- 📦 **[Instalação](installation.md)** — Como colocar o plugin em `/admin/tool/dbmigrate`.
- ⚙️ **[Configuração de Origem e Destino](configuration.md)** — Parâmetros de conexão e preparação do banco.
- 📖 **[Guia de Execução](usage.md)** — Passo a passo para migrar um banco MySQL para PostgreSQL.
