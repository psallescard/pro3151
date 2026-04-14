# 💈 BarbearIA: Inteligência Baseada em Dados para Barbearias Modernas

![Versão do Python](https://img.shields.io/badge/python-3.12%2B-blue?logo=python)
![Arquitetura](https://img.shields.io/badge/arquitetura-Backend%2FFrontend-success)
![Status](https://img.shields.io/badge/status-Prot%C3%B3tipo%20v1.0.0-gold)

O **BarbearIA** é um sistema de gestão orientado a dados projetado para eliminar a "névoa gerencial" no setor de estética masculina. Atuando como um assistente silencioso, a plataforma preenche a lacuna entre o serviço técnico de alta qualidade e o crescimento empresarial estratégico, focando em baixa carga cognitiva para barbeiros e análises de alta fidelidade para proprietários.

---

## 🚀 Visão Geral da Aplicação
O BarbearIA transforma as operações tradicionais de barbearias em centros de lucro otimizados por meio de:
- **Eficiência Operacional:** Agendamento e checkout projetados para levar menos de 10 segundos.
- **Governança Estratégica:** Rateio automatizado de comissões e rastreamento de lucro líquido.
- **Retenção de Clientes:** Gatilhos inteligentes para reengajamento via WhatsApp.
- **Frontend:** Dashboards interativos construídos com **Streamlit** para visualização tática e estratégica.
- **Backend:** Uma arquitetura robusta em **Python** lidando com pipelines ETL, lógica de inventário e auditoria financeira.

---

## 📋 Requisitos Funcionais

O sistema foi estruturado para atender três fluxos de informação distintos (Administrador, Operacional e Cliente), com foco na automação e redução de atrito.

### 1. Sincronização e Ingestão de Dados
- **Agendamento Online 24/7:** Interface web para agendamento autônomo pelo cliente, com visualização de serviços, preços e disponibilidade sem necessidade de login.
- **Sincronização de Agendas:** Consolidação automática de todas as reservas realizadas via link em uma grade centralizada para os profissionais.

### 2. Visões de Dashboard e Análise
- **Performance de Vendas:** Monitoramento em tempo real do número de atendimentos e taxa de ocupação das cadeiras.
- **Análise de Rentabilidade:** Relatórios de Lucro Bruto Real, realizando o abate automático de custos fixos, variáveis e comissões.
- **Analytics de Produto:** Identificação de itens mais vendidos e padrões de consumo de insumos premium.
- **Gestão de No-Show:** Métricas específicas sobre evasão de receita por não comparecimento para mitigação estratégica.

### 3. Operações e Controle
- **Check-out de Atendimento:** Finalização rápida de serviços com registro de pagamento e vínculo ao perfil do cliente.
- **Controle de Inventário Digital:** Gestão automática de estoque a cada venda realizada no PDV, com alertas de nível mínimo de segurança.
- **Cálculo de Comissões:** Processamento automatizado do rateio por profissional, eliminando erros manuais.
- **Exportação de Dados:** Capacidade de gerar relatórios para suporte à tomada de decisão estratégica.

---

## ⚙️ Requisitos Não Funcionais

- **Performance:** Resposta às requisições em até **2 segundos** em todas as interfaces para evitar o abandono do fluxo pelo cliente.
- **Disponibilidade:** Garantia de **99,5%** de uptime mensal, assegurando que a barbearia nunca perca agendamentos por indisponibilidade técnica.
- **Segurança:** Proteção de dados via protocolo **HTTPS**, armazenamento de senhas com hash criptográfico e expiração de sessões inativas após 30 minutos.
- **Usabilidade:** Design simplificado para o nível operacional (botões grandes, checkout em <10s) e fluxo de agendamento do cliente concluído em no máximo 4 etapas.
- **Compatibilidade:** Suporte pleno aos navegadores Chrome, Firefox e Edge em resoluções a partir de 1280x720 pixels.
- **Manutenibilidade:** Arquitetura modular que permite a adição de novas funcionalidades sem impactar componentes já implantados.

## Colaboradores do Projeto

- Pedro Salles
- Pedro Leme
- Francisco Behr
- Rafael Arraes
- Felipe Isamu
