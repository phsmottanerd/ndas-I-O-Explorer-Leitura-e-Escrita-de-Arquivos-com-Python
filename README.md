from pathlib import Path

readme_content = """
# 🐼 Pandas I/O Explorer — Manipulando Arquivos com Python

> 📘 Projeto prático desenvolvido durante o curso **"Pandas I/O: Trabalhando com diferentes formatos de arquivos"**.  
> Utilizando a poderosa biblioteca **Pandas**, este notebook demonstra como realizar **leitura e escrita** de dados em diversos formatos, essenciais para análise de dados no dia a dia.

---

## 📂 **Arquivos e Formatos Trabalhados**
Manipulação de dados com diferentes fontes e estruturas:

- 🗂️ **CSV** — Tabelas planas
- 📊 **Excel (.xlsx)** — Planilhas com múltiplas abas
- 🌐 **HTML** — Tabelas extraídas de páginas web
- 📄 **XML** — Arquivos estruturados com hierarquia de dados

---

## 🧠 **Funcionalidades Demonstradas**
Exploração prática com uso das principais funções da biblioteca **Pandas**:

- `read_csv()`
- `read_excel()`
- `read_html()`
- `read_xml()`
- `to_csv()` / `to_excel()` / `to_xml()`

---

## ✅ **Tecnologias Utilizadas**
| Ferramenta        | Descrição                                 |
|-------------------|---------------------------------------------|
| ![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)       | Linguagem principal do projeto |
| ![Pandas](https://img.shields.io/badge/Pandas-1.5-purple?logo=pandas)      | Biblioteca para análise e manipulação de dados |
| ![Jupyter](https://img.shields.io/badge/Jupyter_Notebook-orange?logo=jupyter) | Ambiente interativo para execução |
| ![Google Colab](https://img.shields.io/badge/Google_Colab-cloud-yellow?logo=googlecolab) | Plataforma utilizada para rodar o notebook |

---

## 🗃️ **Formato do Projeto**
- Arquivo: `Aula_5_atualizada.ipynb`  
- Tipo: **Jupyter Notebook**  
- Linguagem: **Python 3**  
- Biblioteca Principal: **Pandas**

---

## 🎯 **Objetivo do Projeto**
Capacitar o aluno a:

- Ler dados estruturados e semi-estruturados
- Trabalhar com diferentes fontes de dados
- Aplicar operações de transformação e exportação de dados
- Automatizar importações de fontes externas com Pandas

---

## 🚀 **Público-Alvo**
📌 Ideal para estudantes, iniciantes em Data Science ou profissionais que desejam aprender como **manipular dados com diferentes formatos de arquivos** usando **Python e Pandas**.

---

## 📎 **Como acessar**
1. Clone ou baixe o projeto
2. Abra o notebook no Jupyter ou no [Google Colab](https://colab.research.google.com/)
3. Execute célula por célula e explore os exemplos!
"""

# Salvar como arquivo README.md
readme_path = Path("/mnt/data/README.md")
readme_path.write_text(readme_content, encoding="utf-8")
readme_path
