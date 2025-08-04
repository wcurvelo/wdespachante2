# WDespachante - Sistema de Gestão para Despachante

Sistema completo para gestão de serviços de despachante, incluindo agendamento online e acompanhamento de processos.

## 🚀 Estrutura do Projeto

O projeto está dividido em duas partes principais:

### Frontend (Next.js)
- Localização: `/frontend`
- Stack:
  - Next.js 14
  - TypeScript
  - shadcn/ui
  - Tailwind CSS

### Backend (Supabase)
- Localização: `/backend`
- Stack:
  - Supabase (PostgreSQL)
  - Autenticação
  - Storage
  - Funções Edge

## 🛠️ Funcionalidades Principais

1. **Sistema de Agendamento Online**
   - Calendário integrado
   - Seleção de serviços
   - Coleta de dados estruturados

2. **Gestão de Clientes**
   - Cadastro completo
   - Histórico de serviços
   - Status de documentação
   - Comunicação integrada

3. **Gestão de Serviços**
   - Catálogo de serviços
   - Preços dinâmicos
   - Taxas do Detran
   - Pacotes promocionais

4. **Sistema de Vendas**
   - Fluxo: Orçamento → Aprovação → Pedido → Execução → Finalização
   - Cálculos automáticos
   - Relatórios e métricas

## 📦 Pré-requisitos

- Node.js 18+
- Conta no Supabase
- Git

## 🚀 Como Iniciar

1. Clone o repositório
```bash
git clone https://github.com/wcurvelo/wdespachante2.git
cd wdespachante2
```

2. Configure o frontend
```bash
cd frontend
npm install
cp .env.example .env.local
# Configure as variáveis de ambiente
```

3. Configure o backend
```bash
cd backend
# Siga as instruções de configuração do Supabase
```

## 📝 Licença

Este projeto é privado e de propriedade de Wellington Curvelo.

## 👤 Autor

**Wellington Curvelo**
- 18 anos de experiência como despachante
- Especialista em documentação veicular
- Rio de Janeiro/RJ