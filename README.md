# 🧩 Loja de Autopeças – Banco de Dados

Projeto acadêmico desenvolvido para a disciplina **Banco de Dados**, ministrada pelo professor **Heleno Cardoso da Silva Filho**, na **UniRuy Wyden**.  
O objetivo deste trabalho é apresentar a modelagem completa de um banco de dados para uma **Loja de Peças e Acessórios Automobilísticos**, incluindo os modelos conceitual, lógico e físico, além da normalização.

---

## 👥 Equipe

- **Victor Fernandes** – 202308426044  
- **Sinézio da Silva** – 202302375081  
- **Rui Romer** – 202302846157  
- **Karine Costa** – 202308426079  
- **Rafaela Soares** – 202403610876  

---

## 🧠 Objetivo

O projeto visa armazenar e organizar informações essenciais para o funcionamento de uma loja de autopeças, facilitando a gestão de **clientes, funcionários, fornecedores, produtos e pedidos**.  
A estrutura foi desenhada para garantir **integridade, consistência e eficiência** nas operações de leitura e escrita.

---

## 🗂️ Estrutura do Projeto

O banco de dados foi desenvolvido em **MySQL**, dividido nas seguintes etapas:

1. **Modelo Conceitual**  
   - Representa as principais entidades e relacionamentos do domínio da loja.
   - Inclui especializações (Pessoa Física e Jurídica) e entidades associativas (como `ITEM_PEDIDO` e `FORNECEDOR_PRODUTO`).

2. **Diagrama Entidade-Relacionamento (DER)**  
   - Demonstra graficamente as cardinalidades e dependências entre as entidades.

3. **Modelo Lógico**  
   - Apresenta as tabelas e seus relacionamentos com base nas regras de negócio do modelo conceitual.

4. **Modelo Físico (SQL Script)**  
   - Implementação completa do banco em MySQL, com `CREATE SCHEMA`, `FOREIGN KEY`, `PRIMARY KEY` e restrições de integridade.

---

## 🧾 Principais Tabelas

| Tabela | Descrição |
|--------|------------|
| `tb_contato` | Armazena telefones e e-mails de pessoas e empresas. |
| `tb_cargo` | Define cargos, salários e hierarquia dos funcionários. |
| `tb_funcionarios` | Contém dados dos colaboradores da loja. |
| `tb_produto` | Lista os produtos disponíveis, com custo, fabricante e categoria. |
| `tb_fornecedores` | Registra informações sobre fornecedores e representantes. |
| `tb_pessoafisica` / `tb_pessoajuridica` | Representam clientes em diferentes naturezas. |
| `tb_pedido` | Controla pedidos, status e valores. |
| `tb_item-pedido` | Relaciona pedidos com produtos vendidos. |
| `tb_fornecedor-produto` | Indica produtos fornecidos por cada fornecedor. |

---

## 💾 Requisitos de Execução

- **Banco de Dados:** MySQL 8.0+  
- **Ferramentas sugeridas:**  
  - MySQL Workbench  
  - DBeaver  
  - phpMyAdmin  

### 🔧 Passos para execução

1. Clone o repositório:
   ```bash
   git clone https://github.com/SEU-USUARIO/loja-autopecas-bd.git



Video de apresentação disponível no Youtube: https://youtu.be/0A6TCOzcwbA.

