# 🧠 Oracle SQL Enterprise Project
### Administração, Automação e Segurança de Banco de Dados

<p align="center">
  <img src="https://img.shields.io/badge/Oracle-Database-red?style=for-the-badge&logo=oracle">
  <img src="https://img.shields.io/badge/SQL-Advanced-blue?style=for-the-badge&logo=postgresql">
  <img src="https://img.shields.io/badge/PLSQL-Automation-orange?style=for-the-badge">
  <img src="https://img.shields.io/badge/Status-Production%20Ready-success?style=for-the-badge">
</p>

---

## 📌 Sobre o Projeto

Este projeto simula um ambiente corporativo completo utilizando **Oracle SQL**, aplicando práticas utilizadas em empresas para:

- Administração de banco de dados
- Automação de processos
- Segurança e auditoria
- Organização de dados em larga escala

💡 O objetivo foi construir uma estrutura robusta, escalável e alinhada com cenários reais de produção.

---

## 🏗️ Arquitetura do Projeto
📦 oracle-sql-project<br>
┣ 📂 scripts<br>
┃ ┗ 📜 banco.sql<br>
┣ 📂 imagens<br>
┃ ┣ 📸 tablespace.png<br>
┃ ┣ 📸 select.png<br>
┃ ┣ 📸 auditoria.png<br>
┃ ┗ 📸 relatorio.png<br>
┗ 📜 README.md<br>


---

## 🧱 Funcionalidades Implementadas

### 📁 Tablespaces (Administração)

- Criação e expansão automática
- Separação por domínio (RH / Marketing)
- Controle físico de armazenamento

---

### 👨‍💼 Gestão de Dados

- Tabela de funcionários
- Tabela de campanhas
- Tabela de alunos com controle salarial

✔ Uso de **SEQUENCE** para geração automática de IDs

---

### 💰 Automação com Procedure

```sql
CALL BONUS(3,10);
✔ Atualiza salários automaticamente
✔ Centraliza regra de negócio

🛡️ Segurança com Triggers
🔒 Validação de dados
Impede salários acima de limite definido
📋 Auditoria de acesso
Registro automático de logins no banco
🔁 Backup automático
Cópia de dados antes de exclusões
👁️ Views (Relatórios)
Criação de relatórios com JOIN
Abstração de consultas complexas
Pronto para BI
🔗 Constraints Avançadas
Uso de DEFERRABLE
Controle flexível de integridade referencial
📊 Resultados do Projeto
🗄️ Estrutura de Tablespaces

📋 Consulta de Dados

🔐 Auditoria de Logins

📈 Relatórios com JOIN

🧠 Diferenciais Técnicos

✔ Estrutura separada por tablespaces
✔ Automação com PL/SQL
✔ Triggers de segurança e auditoria
✔ Modelagem orientada a ambiente corporativo
✔ Preparado para escalabilidade

🏁 Conclusão

Este projeto demonstra domínio em:

Administração Oracle
SQL avançado
Segurança de banco de dados
Automação com PL/SQL
Boas práticas corporativas
👨‍💻 Autor

Hudney Gomes Nunes
💼 Desenvolvedor Back-End | SQL | .NET | Infraestrutura
