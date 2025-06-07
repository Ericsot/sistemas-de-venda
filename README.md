# 📦 Modelo de Banco de Dados - Sistema de Vendas

Este repositório contém um modelo de banco de dados para um sistema simples de vendas, com estrutura de clientes, colaboradores, produtos, vendas e itens vendidos.

---

## 📐 Estrutura das Tabelas

- **Clientes**: Informações dos clientes (nome, CPF, telefone, e-mail, endereço).
- **Colaboradores**: Funcionários que realizam as vendas (nome, CPF, cargo).
- **Produtos**: Cadastro de produtos com estoque e preço.
- **Vendas**: Registro de cada venda, com cliente, colaborador, data, total e forma de pagamento.
- **ItensVenda**: Detalhes dos produtos vendidos em cada venda (quantidade, preço unitário, desconto).

---

## 🗃️ Arquivos

- `modelo.sql`: Script SQL com a criação de todas as tabelas e relacionamentos.
- `modelo.dbml`: Versão compatível com [dbdiagram.io](https://dbdiagram.io/d/dbml-684492415a9a94714e5b56ba) para visualização gráfica do modelo.

