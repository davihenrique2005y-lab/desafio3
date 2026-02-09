Azure-Monitoramento-VMs/
│
├─ README.md
├─ /docs
│   ├─ resumos.md
│   ├─ dicas.md
│   └─ logs-exemplos.md
│
├─ /images
│   ├─ alerta-vm.png
│   ├─ dashboard-vm.png
│   └─ metrics-vm.png
│
└─ /scripts
    └─ queries-kusto.txt
# Projeto: Monitoramento de Máquinas Virtuais no Microsoft Azure

## Descrição
Este projeto ensina a **configurar e gerenciar o monitoramento de recursos no Microsoft Azure**, com foco em **máquinas virtuais (VMs)**. O objetivo é manter **visibilidade, controle e resposta proativa** a eventos críticos, como a exclusão de uma VM, utilizando **Azure Monitor** e **Log Analytics**.

---

## Objetivos
- Configurar alertas e métricas para monitoramento de VMs.  
- Criar dashboards para acompanhamento de desempenho.  
- Utilizar consultas no Log Analytics para análise de logs.  
- Documentar boas práticas e aprendizados obtidos durante o laboratório.

---

## Estrutura do Projeto

---

## Como Usar
1. Clone o repositório:
```bash
git clone https://github.com/davihenrique2005y-lab/desafio3

---

### 2️⃣ /docs/resumos.md
```markdown
# Resumos - Monitoramento no Azure

## Azure Monitor
- Serviço que fornece **visibilidade total** sobre recursos do Azure.  
- Coleta métricas e logs de VMs, redes e aplicativos.

## Log Analytics
- Ferramenta para **consultas avançadas** usando linguagem Kusto (KQL).  
- Permite criar dashboards, alertas e relatórios detalhados.

## Métricas de VMs
- CPU, memória, disco e rede.  
- Alertas podem ser configurados quando limites críticos são atingidos.

## Boas Práticas
- Separar workspaces por ambiente (produção/teste).  
- Utilizar alertas para eventos críticos como exclusão de VM ou falhas de disco.
# Dicas e Boas Práticas

- Configure alertas para **eventos críticos** como exclusão de VMs.  
- Use dashboards para **monitoramento centralizado**.  
- Documente consultas úteis e métricas monitoradas.  
- Organize imagens e logs para referência futura.  
- Sempre teste alertas em **ambiente não produtivo** antes de aplicar na produção.
