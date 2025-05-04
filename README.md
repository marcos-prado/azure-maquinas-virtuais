# Criação e Configuração de uma Máquina Virtual no Microsoft Azure

## 1. Criando uma Máquina Virtual (VM)
1. **Acesse o portal do Azure** ([https://portal.azure.com](https://portal.azure.com)) e faça login com sua conta.
2. **Navegue até "Máquinas Virtuais"** e clique em **"Criar"** → **"Máquina Virtual"**.
3. **Configure os detalhes básicos:**
   - Escolha a **assinatura** e **grupo de recursos**.
   - Defina o **nome da VM** e selecione a **região**.
   - Escolha a **imagem do sistema operacional** (Windows, Linux, etc.).
   - Selecione o **tamanho da VM** (CPU, RAM, etc.) com base nas necessidades.

## 2. Configurando Autenticação e Rede
4. **Método de autenticação**: Escolha entre **senha** ou **chaves SSH** para acesso remoto.
5. **Configuração de rede**:
   - Configure a **rede virtual** e **sub-rede**.
   - Escolha se deseja um **endereço IP público** (para acesso externo).
   - Ajuste **regras de firewall** para permitir conexões RDP (Windows) ou SSH (Linux).

## 3. Configuração Avançada
6. **Armazenamento**: Escolha entre **SSD Premium** ou **HDD Padrão**, dependendo do desempenho desejado.
7. **Extensões e Scripts**: Pode adicionar scripts de inicialização para instalar pacotes/configurações automaticamente.
8. **Monitoramento**: Ative o **Azure Monitor** para logs e métricas de desempenho.

## 4. Revisão e Implantação
9. **Revise todas as configurações** e clique em **"Criar"**.
10. O Azure iniciará a implantação da máquina virtual. O tempo varia conforme as configurações escolhidas.

---

## Dicas para Uso Eficiente da Azure
✅ **Escolha a região correta**: Regiões próximas reduzem latência e custos.  
✅ **Use grupos de recursos**: Ajuda na organização e gerenciamento de múltiplos serviços.  
✅ **Automatize processos**: Use **Azure Automation** ou **ARM Templates** para implantações consistentes.  
✅ **Monitore custos**: O **Azure Cost Management** evita gastos inesperados.  
✅ **Segurança sempre em primeiro lugar**: Configure **RBAC (controle de acesso baseado em função)** e **NSG (grupos de segurança de rede)**.
