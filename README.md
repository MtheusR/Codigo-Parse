# Projeto AIS - Parse

## Descrição do Projeto

Este projeto acadêmico tem como objetivo extrair informações de arquivos em PDFs que foram convertidos em Planilhas, realizar análises e armazenar os resultados em arquivos CSV. Atualmente, o projeto abrange a extração de dados referentes a alunos, grades curriculares, históricos e status acadêmico.

## Funcionalidades Principais

### 1. Extração de Dados dos Alunos

- Busca por informações específicas na planilha de alunos, como nomes e formas de ingresso.
- Salva os dados encontrados em um arquivo CSV.

### 2. Extração de Dados da Grade Curricular

- Identifica códigos e informações sobre disciplinas na grade curricular.
- Salva os dados encontrados em um arquivo CSV.

### 3. Extração de Dados do Histórico Acadêmico

- Analisa o histórico acadêmico dos alunos, extraindo informações como códigos de disciplinas, notas e situações.
- Salva os dados encontrados em um arquivo CSV.

### 4. Status do Aluno

- Identifica o status atual dos alunos, como "Cursando", "Desligamento", "Desvinculado" ou "Formado".
- Salva os dados encontrados em um arquivo CSV.

### 5. Identificação de Docentes

- Analisa a grade curricular para identificar os nomes únicos dos docentes.
- Salva os dados encontrados em um arquivo CSV.

## Pré-requisitos

Antes de começar, certifique-se de ter instaladas as bibliotecas necessárias:

```bash
pip install tabula-py pandas openpyxl
