# Exercícios de Banco de Dados II

Este repositório contém uma coleção de exercícios e projetos práticos desenvolvidos para a disciplina de Banco de Dados II. Os projetos exploram conceitos de Orientação a Objetos e bancos de dados NoSQL, especificamente **MongoDB** (Documentos) e **Neo4j** (Grafos), utilizando a linguagem **Python**.

## Estrutura do Projeto

Abaixo está a descrição de cada diretório e seu propósito:

### 1. `Exercicio1`
*   **Foco:** Programação Orientada a Objetos (POO).
*   **Descrição:** Implementação básica de classes em Python (`Aluno`, `Professor`, `Aula`) para simular um sistema acadêmico simples.
*   **Tecnologias:** Python (Puro).

### 2. `Exercicio2`
*   **Foco:** Introdução ao MongoDB.
*   **Descrição:** Scripts para conexão e manipulação de dados no MongoDB. Inclui funcionalidades para resetar o banco de dados com um dataset inicial (`aula_dataset`, `pokemon_dataset`).
*   **Tecnologias:** Python, MongoDB, `pymongo`.

### 3. `Exercicio4`
*   **Foco:** Análise de Dados com MongoDB.
*   **Descrição:** Aplicação focada em análise de produtos de mercado (`datasetMercado`). Possui uma classe `ProductAnalyzer` para realizar consultas e agregações sobre os dados de compras.
*   **Tecnologias:** Python, MongoDB, `pymongo`.

### 4. `Exercicio6`
*   **Foco:** Consultas Cypher (Neo4j).
*   **Descrição:** Contém um arquivo `relatorio.cypher` com scripts para criar e consultar um grafo de "Games" e "Jurados" (quem jogou o quê, notas, horas de jogo).
*   **Tecnologias:** Neo4j (Cypher Query Language).

### 5. `Exercicio_Avaliativo1`
*   **Foco:** Aplicação Completa com MongoDB.
*   **Descrição:** Um sistema CLI (Command Line Interface) para gerenciar Corridas, Passageiros e Motoristas.
    *   **Funcionalidades:** CRUD de Motoristas, adição de corridas.
    *   **Arquitetura:** DAO (Data Access Object) para isolar a lógica do banco.
*   **Tecnologias:** Python, MongoDB, `pymongo`.

### 6. `Exercicio_Avaliativo2`
*   **Foco:** CRUD com Neo4j.
*   **Descrição:** Aplicação CLI para gerenciamento de Professores (`TeacherCRUD`). Permite criar, ler, atualizar e deletar nós de professores em um banco de dados orientado a grafos.
*   **Tecnologias:** Python, Neo4j, `neo4j` driver.

### 7. `ExecicioTeoria2_Avaliativo`
*   **Foco:** Manipulação de Grafos Familiares (Neo4j).
*   **Descrição:** Script `Client.py` que interage com o Neo4j para mapear e consultar relações familiares (Neto, Irmão, Casado com, etc.) e propriedades específicas (Profissão, Raça de pets).
*   **Tecnologias:** Python, Neo4j, `neo4j` driver.

## Pré-requisitos

Para executar os projetos, você precisará de:

*   **Python 3.x**
*   **MongoDB** (Rodando localmente na porta padrão 27017 ou configurado nas strings de conexão).
*   **Neo4j** (Rodando localmente na porta 7687 ou configurado nas URIs).

### Instalação das Dependências

Instale os drivers necessários via pip:

```bash
pip install pymongo neo4j
```

## Como Executar

Cada pasta possui geralmente um arquivo `main.py` ou scripts específicos. Navegue até a pasta do exercício desejado e execute o arquivo principal.

Exemplo para o Exercicio_Avaliativo1:

```bash
cd Exercicio_Avaliativo1
python main.py
```
