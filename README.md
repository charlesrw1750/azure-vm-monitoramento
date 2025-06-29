# 🚀 Projeto: Monitoramento de Máquinas Virtuais no Azure

## 🧠 Descrição do Projeto

Este repositório documenta um desafio prático da DIO, focando no monitoramento de VMs no Azure utilizando exclusivamente o Azure Monitor. O projeto demonstra como configurar alertas para eventos críticos e a importância da documentação técnica clara.

## 🎯 Objetivo

- Configurar monitoramento básico de VMs usando Azure Monitor
- Criar alertas para eventos de exclusão de recursos
- Validar o fluxo de monitoramento através de testes práticos
- Documentar o processo para referência futura

## 🛠️ Tecnologias Utilizadas

- **Azure Monitor** (serviço principal)
- Máquinas Virtuais Azure
- Alertas por email
- GitHub (documentação)

## 📚 Estrutura do Repositório

| Arquivo/Pasta | Descrição |
|--------------|-----------|
| `/images` | Contém os comprovantes de cada etapa: <br><br> **Tarefa 1** - Habilitar Monitoramento: <br> • `vm-monitor-ativo.png` <br><br> **Tarefa 2** - Configuração de Alerta: <br> • `regra-alerta-exclusao.png` <br><br> **Tarefa 3** - Testes: <br> • `alerta-portal-apos-exclusao.png` (resultado no Azure) <br> • `email-alerta-recebido.jpg` (comprovação de notificação) |
| `README.md` | Documentação principal do projeto |

## 📸 Evidências

Confira na pasta `/images`:
1. `alerta-portal.png` - Alerta disparado no Azure Portal
2. `alerta-email.png` - Notificação recebida por email

## 🔧 Passo a Passo Executado

### Tarefa 1: Configurar Monitoramento Básico
- Habilitado o Azure Monitor para a VM
- Verificado métricas básicas (CPU, memória, disco)

### Tarefa 2: Criar Regra de Alerta
- Criada regra para monitorar eventos de exclusão:
  - Tipo: "Activity Log - Delete Virtual Machine"
  - Ação: Notificação por email

### Tarefa 3: Teste Prático
1. Excluído a VM propositalmente
2. Verificado:
   - Alerta no Azure Portal (15-30 min após exclusão)
   - Recebimento do email de notificação

## 💡 Principais Aprendizados
- Fluxo completo de criação e teste de alertas
- Tempo de propagação de alertas no Azure
- Diferença entre métricas em tempo real e logs de atividade
- Importância de testar regras de alerta

## ✅ Status
✔️ Concluído com sucesso

## 🤝 Contribuições
Sugestões são bem-vindas via Issues.

## 📌 Referências
- [Documentação do Azure Monitor](https://learn.microsoft.com/pt-br/azure/azure-monitor/)
- [Tipos de alertas suportados](https://learn.microsoft.com/pt-br/azure/azure-monitor/alerts/alerts-types)
