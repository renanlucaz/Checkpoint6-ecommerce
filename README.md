# Relatório de Vendas - Projeto de Análise

Este repositório contém um conjunto de scripts Python e PL/SQL para processar e analisar dados de vendas em um banco de dados Oracle. Os scripts executam operações como o cálculo de tempo médio entre compras, geração de relatórios mensais e atualização do estoque com base nas vendas realizadas.

## Sumário

- [Configuração do Ambiente](#configuração-do-ambiente)
- [Passo a Passo para Executar os Scripts](#passo-a-passo-para-executar-os-scripts)
- [Descrição das Análises e Decisões Tomadas](#descrição-das-análises-e-decisões-tomadas)

---

## Configuração do Ambiente

Para configurar o ambiente e começar a executar os scripts, siga as instruções abaixo:

### 1. **Pré-requisitos**

Antes de começar, você precisará de:

- **Python 3.x**: O Python é necessário para rodar os scripts de análise.
- **Oracle Database**: Você precisará de uma instância do Oracle Database com acesso configurado.
- **Pacotes Python**:
  - `oracledb` para interagir com o banco de dados Oracle.
  - `pandas` para manipulação de dados (caso haja necessidade de manipulação de arquivos CSV ou outros dados).

### 2. **Instalação do Python e Pacotes Necessários**

Certifique-se de que o **Python 3.x** esteja instalado em seu sistema. Caso não tenha o Python instalado, você pode baixá-lo [aqui](https://www.python.org/downloads/).

Depois de instalar o Python, crie um ambiente virtual para o seu projeto (opcional, mas recomendado):

```bash
python3 -m venv venv
source venv/bin/activate  # No Windows use: venv\Scripts\activate
