<h1 align="center">⚡ ERP Pricing Intelligence ⚡</h1>

<p align="center">
<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=22&pause=1000&color=8A2BE2&center=true&vCenter=true&width=700&lines=Pricing+Analysis+%2B+Automation;Margin+Intelligence+System;Retail+Data+Audit;Built+with+n8n+%2B+LLMs" />
</p>

<p align="center">
<img src="https://img.shields.io/badge/n8n-Automation-111111?style=for-the-badge"/>
<img src="https://img.shields.io/badge/OpenAI-LLM-8A2BE2?style=for-the-badge"/>
<img src="https://img.shields.io/badge/ERP-Data-111111?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Retail-Analytics-8A2BE2?style=for-the-badge"/>
</p>

---

## Overview

Sistema de auditoria comercial automatizada focado em identificar falhas de precificação, prejuízo real e oportunidades de ajuste no ERP.

O objetivo é transformar relatórios brutos em decisões acionáveis.

<img width="977" height="250" alt="exmp1" src="https://github.com/user-attachments/assets/aed3ed14-9f87-4d07-9fe4-a222b2913d4c" />

---

## Capabilities

- leitura automática de relatórios do ERP  
- tratamento de dados inconsistentes  
- cálculo de margem real e variação de custo  
- detecção de prejuízo  
- identificação de furos de repasse  
- análise de margem baixa  
- geração de relatório estruturado (HTML)  
- geração de insights com IA  

---

## Stack

- n8n  
- OpenAI  
- Google Drive  
- ERP (dados estruturados)  

---

## Core Features

- auditoria automática de preços  
- detecção de produtos com prejuízo  
- identificação de repasse incorreto de custo  
- análise de margem operacional  
- organização visual dos dados (HTML report)  
- geração de insights estratégicos  

---

## Flow

Google Drive → Extract Data → Processing → Analysis → AI Insights → Email Report

---

## Business Logic

O sistema classifica produtos em três categorias principais:

- prejuízo real (margem negativa)  
- furos de repasse (custo subiu sem ajuste de preço)  
- margem baixa (abaixo do ideal operacional)  

---

## Security

- dados sensíveis removidos  
- credenciais substituídas  
- estrutura preparada para ambiente seguro  

---

## Setup

1. Importar JSON no n8n  
2. Configurar credenciais:
   - Google Drive  
   - OpenAI  
   - Gmail  
3. Ajustar fonte de dados  
4. Ativar workflow  

---

## Notes

A análise não depende apenas de IA.  
A lógica principal é baseada em regras de negócio reais.

IA é utilizada apenas para geração de insights estratégicos.

---

## Author

Igor Henrique  
Automation • Data • Systems
