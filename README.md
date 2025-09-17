# ☁️ Resumo Lab Azure

Repositório contendo anotações e resumos das lições aprendidas sobre a plataforma Microsoft Azure.

### Seções

*   **Introdução à Computação em Nuvem:** Conceitos fundamentais e visão geral da nuvem.
*   **Nuvem Pública e Privada:** Diferenças e características de cada modelo de nuvem.
*   **Criação da Conta Azure:** Passos para iniciar sua jornada com uma conta gratuita ou paga.
*   **Painel de Controle (Portal Azure):** Navegação e principais funcionalidades do portal.


# 🧠 Conhecimentos Básicos sobre Máquinas Virtuais da Azure

As máquinas virtuais (VMs) da Azure são componentes fundamentais da infraestrutura em nuvem da Microsoft. Elas permitem executar sistemas operacionais e aplicativos em ambientes virtualizados com alta flexibilidade e controle.

---

## ⚖️ Escalabilidade

- **Escalonamento vertical**: Aumenta ou reduz os recursos (CPU, memória) de uma VM existente.
- **Escalonamento horizontal**: Adiciona ou remove instâncias de VMs para atender à demanda.
- **Conjuntos de escalas de máquinas virtuais (VMSS)**: Automatizam o escalonamento horizontal com balanceamento de carga.
- **Integração com Azure Load Balancer**: Distribui o tráfego entre múltiplas VMs para garantir desempenho.

---

## 🔁 Confiabilidade

- **Alta disponibilidade**: VMs podem ser distribuídas em *Availability Zones* ou *Availability Sets* para minimizar falhas.
- **Redundância geográfica**: Replicação de dados e serviços entre regiões.
- **Backup automatizado**: Protege dados e configurações com recuperação rápida.
- **Monitoramento contínuo**: Azure Monitor e Log Analytics ajudam a detectar e corrigir problemas rapidamente.

---

## 🛠️ Gerenciabilidade

- **Azure Portal**: Interface gráfica para criar, configurar e monitorar VMs.
- **Azure CLI e PowerShell**: Ferramentas de linha de comando para automação e scripts.
- **Azure Resource Manager (ARM)**: Gerencia recursos como grupos, políticas e templates.
- **Extensões de VM**: Permitem instalar agentes, configurar software e executar scripts pós-implantação.

---

## 🔐 Segurança

- **Controle de acesso baseado em função (RBAC)**: Define quem pode fazer o quê dentro do ambiente Azure.
- **Azure Defender for Cloud**: Protege contra ameaças e vulnerabilidades.
- **Criptografia de disco**: Usa Azure Disk Encryption com BitLocker ou DM-Crypt.
- **Firewalls e NSGs (Network Security Groups)**: Controlam o tráfego de rede para e entre VMs.
- **Atualizações automáticas**: Mantêm o sistema operacional protegido contra falhas e ataques.
