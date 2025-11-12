# 📚 Databricks Certified Associate Data Engineer - Guia de Estudo

Este repositório contém os materiais de estudo, notebooks e anotações para a preparação da certificação **Databricks Certified Associate Data Engineer**. O objetivo é seguir um guia de estudo estruturado, cobrindo todos os tópicos do exame com foco em prática e compreensão conceitual.

---

## 🎯 Objetivo da Certificação

A certificação Databricks Certified Associate Data Engineer valida a proficiência em usar a plataforma Databricks para tarefas de engenharia de dados, incluindo:

*   **Plataforma de Inteligência Databricks:** Entendimento da arquitetura Lakehouse, Delta Lake e Unity Catalog.
*   **Desenvolvimento e Ingestão:** Leitura, escrita e transformações de dados usando PySpark e Spark SQL.
*   **Processamento de Dados & Transformações:** Funções avançadas do Spark e recursos do Delta Lake.
*   **Produzindo Pipelines de Dados:** Criação e orquestração de Jobs, e compreensão do Delta Live Tables (DLT).
*   **Governança e Qualidade de Dados:** Aplicação de conceitos de governança e garantia de qualidade.

---

## 🛠️ Ferramentas e Ambientes Utilizados

Para maximizar o aprendizado e contornar as limitações de acesso a certos recursos, o estudo será conduzido principalmente na **Databricks Community Edition** e complementado por compreensão conceitual.

1.  **Databricks Community Edition (CE):**
*   **Uso:** Prática intensiva de **PySpark** e **Spark SQL**.
*   **Foco:** Criação de DataFrames em memória, transformações de dados, simulação de funcionalidades do Delta Lake (Time Travel, MERGE INTO, Schema Evolution) usando tabelas temporárias.
*   **Limitações:** Não permite acesso ao DBFS para persistência de arquivos, nem criação de clusters All-Purpose, nem o uso do Autoloader para ingestão de arquivos. A criação de Jobs e pipelines DLT também não é possível.

2.  **GitHub:**
*   **Uso:** Versionamento de todos os notebooks e materiais de estudo.
*   **Foco:** Prática de boas práticas de Git (branches, commits, push).

3.  **Documentação Oficial do Databricks & Databricks Academy:**
*   **Uso:** Aprofundamento conceitual para tópicos que não podem ser praticados diretamente (ex: Autoloader, DLT, Unity Catalog avançado, DBFS, criação de Jobs e Clusters All-Purpose).
*   **Foco:** Entender o "como" e o "porquê" dessas funcionalidades, seus benefícios e casos de uso, através de exemplos de código e explicações teóricas.

---

## 🗺️ Estrutura do Repositório

O repositório está organizado em módulos, seguindo a estrutura do exame de certificação. Cada módulo conterá notebooks com atividades práticas e anotações conceituais.

*   **`00_M0_Setup_e_Testes_Basicos/`**: Configuração inicial dos ambientes e testes de funcionalidade.
*   **`01_M1_Plataforma_Databricks/`**: Conceitos da plataforma, Lakehouse, Delta Lake, Unity Catalog, tipos de compute.
*   **`02_M2_Desenvolvimento_e_Ingestao/`**: Leitura, escrita e transformações básicas de dados com PySpark e Spark SQL.
*   **`03_M3_Processamento_e_Transformacoes/`**: Funções avançadas do Spark, Delta Lake (Time Travel, MERGE INTO, Schema Evolution).
*   **`04_M4_Pipelines_de_Dados/`**: Criação de Jobs (prática conceitual ou em ambiente compatível) e conceitos de Delta Live Tables (DLT).
*   **`05_M5_Governanca_e_Qualidade/`**: Governança de dados com Unity Catalog e qualidade de dados.
*   **`Recursos_Adicionais/`**: Links úteis, simulados, e outras anotações.

---

## 🚀 Progresso e Status

*   **Módulo 0: Revisão e Setup Básico** - ✅ Concluído
*   **Módulo 1: Plataforma de Inteligência Databricks** - ⏳ Em Andamento
*   **Módulo 2: Desenvolvimento e Ingestão** - ⏳ Em Andamento
*   PySpark e SQL (leitura/transformações básicas) - ✅ Concluído
*   Autoloader - 💡 Conceitual
*   **Módulo 3: Processamento de Dados & Transformações** - ✅ Concluído
*   **Módulo 4: Produzindo Pipelines de Dados** - 🔜
*   **Módulo 5: Governança e Qualidade de Dados** - 🔜

---

## 🤝 Contribuições

Este é um repositório de estudo pessoal. No entanto, sugestões, correções ou recursos adicionais são sempre bem-vindos! Sinta-se à vontade para abrir uma issue ou Pull Request.

---

**Autor:** mcunhash
**Data de Início:** [30/10/2025]
