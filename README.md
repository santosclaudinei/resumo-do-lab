# Resumo do Lab

## O que vimos até aqui?

### O que é Computação em Nuvem
Trata-se do fornecimento de recursos e serviços de TI, como servidores, armazenamento e aplicativos, pela internet ("nuvem"). Isso elimina a necessidade de infraestrutura física local, permitindo acesso sob demanda, escalabilidade e custos otimizados.

---

### Tipos de Nuvem:
- **Nuvem Privada**: Infraestrutura dedicada a uma única organização, proporcionando maior controle e segurança.
- **Nuvem Pública**: Recursos compartilhados entre várias organizações, oferecidos por provedores como Azure, com menor custo inicial.
- **Nuvem Híbrida**: Combinação de nuvens públicas e privadas, permitindo maior flexibilidade e opções de integração.

---

### CapEx vs. OpEx:
- **CapEx (Capital Expenditure)**: Investimentos em infraestrutura física (ex.: data centers).
- **OpEx (Operational Expenditure)**: Gastos operacionais recorrentes, como serviços em nuvem, permitindo maior agilidade e previsibilidade de custos.

---

### Exploração do Portal Azure:
- **Configurações**: Personalização da interface (idioma, tema, layout do menu).
- **Computação**: Criação e gerenciamento de máquinas virtuais, configuração de chaves SSH e discos.
- **Redes**: Configuração de endereços IP, Gateways, Bastions e Firewalls para segurança e conectividade.
- **Armazenamento**: Gerenciamento de servidores, discos e migração de dados para a nuvem.

---

## Seção 1: Conceitos Fundamentais de Nuvem

### SLA (Service Level Agreement)
- Discutimos sobre **SLA** e as diferenças nos tempos de **inatividade mensal e anual** ao optar por diferentes níveis de disponibilidade:
  - **99%**: Até 7,31 horas de inatividade por mês.
  - **99,9%**: Até 43,8 minutos de inatividade por mês.
  - **99,95%**: Até 21,9 minutos de inatividade por mês.
  - **99,99%**: Até 4,38 minutos de inatividade por mês.
  - **99,999%**: Até 26,3 segundos de inatividade por mês.
- A escolha de um SLA adequado é crucial para garantir o nível de **disponibilidade** que seu serviço ou aplicação necessita.

---

### Contas de Armazenamento e Redundância
- Criamos uma **conta de armazenamento** no Azure e exploramos diferentes configurações de **redundância**:
  - **LRS (Locally Redundant Storage)**: Armazena três cópias no mesmo datacenter.
  - **ZRS (Zone-Redundant Storage)**: Distribui cópias entre zonas para alta disponibilidade.
  - **GRS (Geo-Redundant Storage)**: Replica dados em outra região para recuperação de desastres.
  - **GZRS (Geo-Zone-Redundant Storage)**: Combina redundância de zona e replicação geográfica.

---

## Seção 2: Criação de Máquinas Virtuais no Azure

### O que são Máquinas Virtuais?
Máquinas Virtuais (VMs) são instâncias de servidores virtuais que permitem executar sistemas operacionais e aplicativos na nuvem como se fossem máquinas físicas dedicadas.

---

### Exploração do Portal Azure: Criação de VMs
- Utilizamos o **Portal Azure** para criar e gerenciar máquinas virtuais. No processo, exploramos:
  - **Configuração Básica**:
    - Escolha do **sistema operacional** (Windows ou Linux).
    - Definição do **tamanho da VM** (CPU, memória).
    - Criação de **nomes** e **grupos de recursos**.
  - **Zonas de Disponibilidade**:
    - Seleção de **zonas de disponibilidade** para garantir maior **resiliência** e **tolerância a falhas** ao distribuir VMs em diferentes datacenters.
  - **Discos e Armazenamento**:
    - Configuração de discos gerenciados (SSD/HDD) para melhorar o desempenho e a durabilidade.
  - **Opções de Acesso**:
    - Configuração de **chaves SSH** para VMs Linux e **RDP** (Remote Desktop Protocol) para VMs Windows, garantindo um acesso seguro e eficiente.

---

### Passo a Passo para Criação de uma VM:
1. Acessar o **Portal Azure** e selecionar a opção **Criar um recurso**.
2. Escolher **Máquina Virtual** e preencher as informações básicas:
   - Nome da VM, região, sistema operacional, etc.
3. Configurar a **rede virtual (VNet)** e endereços IP.
4. Definir **discos adicionais** se necessário para armazenamento.
5. Configurar **chaves de acesso** (SSH para Linux ou senha para Windows).
6. Revisar todas as configurações e clicar em **Criar**.

---

## Conclusão
Com este laboratório, vimos desde conceitos fundamentais da computação em nuvem até a criação prática de máquinas virtuais no Azure, entendendo como gerenciar recursos e otimizar o ambiente para atender às necessidades do seu negócio.

---
