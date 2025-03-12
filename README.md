# resumo-do-lab
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento dos labs na DIO

# 1º módulo - Microsoft Azure - Conceitos Iniciais / Localizando Serviços por Categoria

Durante o primeiro módulo do laboratório da DIO sobre **Microsoft Azure**, aprendi os conceitos iniciais da **computação em nuvem**, suas utilidades, seu funcionamento e as necessidades que acompanham o uso dessa tecnologia.

## Tipos de Nuvem

Obtive um conhecimento introdutório sobre os diferentes **tipos de nuvem**:

- **Nuvem privada**: Gerenciada e utilizada exclusivamente por uma única empresa, garantindo maior controle e segurança sobre os dados.
- **Nuvem pública**: Oferecida por grandes empresas como **Amazon (AWS), Google (Google Cloud) e Microsoft (Azure)**, permitindo que qualquer organização ou indivíduo utilize seus recursos de forma escalável e sob demanda.
- **Nuvem híbrida**: Combinação das duas anteriores, permitindo que empresas aproveitem a escalabilidade da nuvem pública sem abrir mão da segurança e do controle da nuvem privada. Esse modelo é útil para **organização interna de recursos, proteção de dados sensíveis e manutenção de servidores legados**.

## Custos da Criação e Manutenção de um Data Center em Nuvem. Utilizado caso queira criar uma nuvem privada.

Os custos são divididos em dois modelos principais:

- **CAPEX (Capital Expenditure)**: Representa o **investimento inicial**, incluindo a compra de hardware, infraestrutura, instalação e configuração dos servidores.
- **OPEX (Operational Expenditure)**: Refere-se aos **custos operacionais contínuos**, como **refrigeração, consumo de energia e manutenção** dos servidores para garantir o funcionamento adequado do sistema.

## Modelo de Precificação Baseado em Consumo

Outro ponto abordado foi o **modelo de precificação baseado em consumo**, que permite um controle financeiro mais eficiente, pois os custos são proporcionais ao uso dos recursos. Mais uma vantagem de uma nuvem pública. Esse modelo possibilita:

- ✅ Melhor **previsão de gastos**, pois a empresa paga apenas pelos recursos utilizados.
- ✅ **Otimização de custos**, desativando serviços e máquinas virtuais quando não forem mais necessários.
- ✅ **Flexibilidade**, permitindo ajustes rápidos na infraestrutura conforme a demanda da empresa.

## Localizando Serviços por Categoria

O Microsoft Azure oferece uma ampla gama de serviços em nuvem, abrangendo diversas categorias, como computação, contêineres, bancos de dados, DevOps, redes, Bastions e muitas outras. Esses serviços possibilitam soluções escaláveis, seguras e eficientes para atender às mais variadas necessidades de desenvolvimento e infraestrutura.

# 2º módulo - Benefícios da Computação em Nuvem – Criando Máquinas Virtuais na Azure 

Durante o segundo módulo do laboratório da DIO sobre **Microsoft Azure**, aprofundei meu conhecimento sobre os **benefícios da computação em nuvem** e como a criação de **máquinas virtuais** no Azure pode trazer vantagens significativas para empresas e desenvolvedores.

## **Principais Benefícios**

### **Alta Disponibilidade**
Os recursos estão sempre acessíveis quando necessário, garantindo o funcionamento contínuo dos serviços. Embora um uptime de 100% seja impossível, os provedores oferecem acordos de nível de serviço (SLA) que garantem **altos índices de disponibilidade**, como 99% ou mais.

### **Escalabilidade**
A nuvem permite **aumentar ou diminuir recursos conforme necessário**, garantindo que a infraestrutura se adapte à demanda sem desperdício de recursos ou falta de capacidade.

### **Elasticidade**
Caso a demanda aumente repentinamente, a elasticidade permite **expandir rapidamente os recursos** para evitar sobrecarga, adicionando máquinas virtuais ou expandindo contêineres automaticamente.

### **Confiabilidade**
O design descentralizado da nuvem possibilita uma **infraestrutura confiável**, com recursos distribuídos em diversas regiões do mundo. Mesmo que haja falhas em pontos específicos, o sistema continua operando de forma global.

### **Previsibilidade**
A computação em nuvem oferece **previsibilidade de custos e desempenho**, garantindo que os usuários saibam o que esperar em termos de investimento e qualidade dos serviços prestados.

### **Segurança**
A nuvem disponibiliza ferramentas avançadas de **segurança**, protegendo a integridade dos dados e serviços. No entanto, é essencial que o cliente implemente boas práticas de segurança para garantir uma proteção ainda mais eficaz.

### **Governança**
A auditoria baseada em nuvem facilita a **identificação e correção de recursos fora de conformidade**. Além disso, permite a aplicação automática de atualizações e patches de segurança, reforçando a proteção dos sistemas.

### **Gerenciabilidade**
A capacidade de gerenciar recursos de diferentes maneiras é um dos pontos fortes da nuvem. O gerenciamento eficiente permite:
- **Escalar automaticamente a infraestrutura** com base na necessidade.
- **Evitar erros humanos** ao automatizar processos.
- **Acelerar o tempo de desenvolvimento** com modelos pré-configurados, eliminando a necessidade de configurações manuais.

## Criando Máquinas Virtuais na Azure

Ao criar uma máquina virtual na Azure, existem várias opções disponíveis, como **disponibilidade**, **tipos de segurança**, entre outras configurações essenciais. A plataforma permite a criação de **contas de armazenamento**, incluindo **LRS (Locally Redundant Storage)**, **GRS (Geo-Redundant Storage)**, **ZRS (Zone-Redundant Storage)** e **GZRS (Geo-Zone-Redundant Storage)**.

Além disso, a Azure oferece uma vasta documentação para auxiliar na configuração e gerenciamento de máquinas virtuais dentro da plataforma. Compreender as melhores estratégias é essencial para **atingir as expectativas da empresa sem custos desnecessários**.

# 3º módulo - Tipos de serviço em nuvem -  Configurando uma instância de banco de dados na Azure

## **IaaS - Infraestrutura como Serviço**

O cliente tem mais acesso e controle sobre os recursos. Os serviços oferecidos podem ser alterados, manuseados e configurados conforme a necessidade do usuário.

### **Principais recursos:**
- Servidores e armazenamento
- Firewalls e segurança de rede
- Data centers físicos

A IaaS é a opção mais flexível, permitindo que o usuário gerencie o hardware e a infraestrutura de TI.

---

## **PaaS - Plataforma como Serviço**

Engloba a IaaS e fornece uma plataforma completa para desenvolvimento na nuvem. O usuário pode focar na criação e gerenciamento de aplicações sem precisar lidar com a infraestrutura subjacente.

### **Principais recursos:**
- Sistemas operacionais
- Ferramentas de desenvolvimento
- Gerenciadores de banco de dados

Ideal para desenvolvedores que desejam criar, testar e implementar aplicativos sem se preocupar com a administração do ambiente.

---

## **SaaS - Software como Serviço**

Engloba tanto a IaaS quanto a PaaS, porém, o cliente não possui acesso direto à infraestrutura subjacente. O provedor gerencia toda a infraestrutura e disponibiliza o software como um serviço.

### **Principais recursos:**
- Aplicações hospedadas na nuvem
- Modelo de pagamento conforme o uso
- Exemplo: Microsoft 365

Os usuários podem acessar os aplicativos diretamente pela internet, sem necessidade de instalação ou manutenção.

---

## **Modelo de Responsabilidade Compartilhada**

A responsabilidade do usuário varia de acordo com o modelo de serviço utilizado. Quanto mais simplificado o serviço, menor a responsabilidade do cliente:

- **IaaS**: O cliente tem maior controle e gerencia o hardware virtual.
- **PaaS**: O provedor gerencia a plataforma e o usuário foca no desenvolvimento de aplicativos.
- **SaaS**: O provedor cuida de tudo, e o usuário apenas utiliza o software.

A única responsabilidade sempre mantida pelo provedor é a infraestrutura física da nuvem, como a rede, os data centers e os servidores físicos.

---

## Configurando uma Instância de Banco de Dados na Azure

Para criar um banco de dados na Azure, alguns passos são essenciais:

1. **Criar uma Máquina Virtual**
   - Selecionar uma imagem pré-configurada.
   - Definir o tamanho da imagem para estimar custos.

2. **Configurar o Banco de Dados**
   - Definir um nome para o banco de dados.
   - Escolher um servidor antes da criação.
   - Configurar o tipo de autenticação de acesso.

3. **Gerenciamento de Custos**
   - O banco em nuvem exibe o custo mensal esperado baseado nas configurações escolhidas.
  
# 4º módulo - Componentes de Arquitetura do Azure - Construindo Arquiteturas na Azure

O Microsoft Azure é um serviço de computação em nuvem que oferece diversas regiões e recursos para a criação de soluções escaláveis e seguras. Abaixo estão os principais conceitos e componentes da arquitetura do Azure.

## Regiões do Azure

O Azure possui mais de **60 regiões** distribuídas por **140 países**, incluindo:
- Canadá
- Estados Unidos
- Brasil
- Países da Europa
- Austrália
- Sul da Ásia
- China
- Japão

### Importância da Escolha da Região
O ideal é contratar um servidor mais próximo de você para reduzir a latência e melhorar o desempenho da rede.

### Estrutura das Regiões
Cada região é composta por **um ou mais datacenters**. Quanto mais datacenters em uma área, maior a estabilidade e a disponibilidade dos serviços. Isso garante a continuidade dos servidores em caso de falha.

- Diversos servidores reduzem a latência, permitindo o armazenamento e recuperação de dados de forma distribuída.
- As regiões preservam a **residência dos dados**, garantindo conformidade com legislações como a **LGPD (Lei Geral de Proteção de Dados)**.

### Zonas de Disponibilidade
Cada região contém **zonas de disponibilidade**, compostas por datacenters independentes.
- Cada datacenter possui **alimentação, resfriamento e rede próprios**.
- Conectados por uma **rede privada de fibra óptica**, garantindo alta performance e redundância.

## Pares de Regiões e Grupos de Recursos

Para garantir **recuperação de desastres**, cada região tem um **par de região** onde os dados podem ser replicados automaticamente.

- A separação entre pares de regiões é de **pelo menos 300 milhas (aproximadamente 480 km)**.
- Replicação automática em alguns serviços.
- Em caso de falha, a recuperação da região emparelhada tem **prioridade**.

### Regiões Soberanas
Existem **regiões soberanas** que não estão disponíveis para qualquer pessoa ou empresa. Essas instâncias são **fisicamente isoladas** e seguem regras específicas:

#### Azure Governo dos EUA
- Atende a **agências federais**, governos estaduais e locais dos EUA.
- Apenas **pessoas verificadas e autorizadas** têm acesso.
- Isolado de implementações comuns do Azure.

#### Azure China
- Operado por um grupo local chamado **21Vianet**.
- Todos os dados permanecem **dentro da China**.

## Recursos do Azure

Os recursos do Azure são componentes essenciais para a construção de soluções em nuvem, como:
- **Máquinas Virtuais (VMs)**
- **Bancos de Dados SQL**
- **Serviços de Aplicativos**
- **Redes Virtuais (VNet)**
- **Contas de Armazenamento**

### Grupos de Recursos
Os grupos de recursos organizam os componentes do Azure de forma eficiente:
- Permitem agrupar **máquinas virtuais, bancos de dados, redes e armazenamento**.
- Podem ser organizados por **projetos, ambientes de testes, entre outros**.
- Os grupos de recursos **não são limitados por região**.
- Recursos podem ser **movidos entre grupos** sem restrições diretas.

## Assinaturas do Azure

Quando uma conta é criada no Azure, ela recebe uma **assinatura associada**. É possível ter **várias assinaturas** dentro da mesma conta.

- Exemplo: Assinaturas separadas para **desenvolvimento, teste e produção**.
- Cada assinatura possui **cobrança individual**.
- A cobrança gera **relatórios e faturas separadas** para cada assinatura.

### Hierarquia de Organização e Segurança no Azure
1. **Grupos de gerenciamento**
2. **Assinaturas**
3. **Grupos de recursos**
4. **Recursos individuais**

## Construção de Arquiteturas no Azure

### Criando um Grupo de Recursos
1. Criar um **Grupo de Recursos** para melhor organização.
2. Definir **assinatura, região e nome** para o grupo.
3. Adicionar **marcações (tags)** para facilitar identificação e controle de custos.
4. Revisar e criar o grupo de recursos.

### Gerenciamento e Segurança
- O **Log de Atividade** exibe alterações nos recursos (criação, modificação, exclusão).
- O **IAM (Controle de Acesso)** define permissões para usuários. É recomendável seguir o princípio de **menor privilégio**.
- Existem áreas dedicadas a **implantação, segurança, monitoramento e custos**.

### Criando uma VNet
É possível criar uma **rede virtual (VNet)** e direcionar um IP para um grupo de recursos específico.
Isso facilita a comunicação entre diferentes serviços dentro do Azure.

# 4º módulo - Computação e Rede na Azure - Configurando Recursos e Dimensionamentos em Máquinas Virtuais na Azure

## Introdução
A computação do Azure é um serviço sob demanda que fornece diversos recursos, incluindo máquinas virtuais, aplicativos como serviço, contêineres, instâncias de contêineres, Kubernetes e a Área de Trabalho Virtual do Azure.

---

## Tipos de Computação no Azure

### Máquinas Virtuais (VMs)
As máquinas virtuais são um dos principais recursos do Azure. Elas são emulações de hardware físico e incluem componentes como processador, memória, armazenamento e redes. 

- **Oferta de IaaS**: Fornece personalização e controle total sobre os recursos.
- **Conjuntos de Dimensionamento de VMs**: Permitem balanceamento de carga e escalonamento automático de recursos.

### Conjunto de Disponibilidade de VMs
Para garantir alta disponibilidade e resiliência:
- Se um rack falhar, outras instâncias podem assumir.
- As máquinas são distribuídas entre **Domínios de Falha** (isolando falhas físicas) e **Domínios de Atualização** (evitando indisponibilidade durante atualizações).
- Recomenda-se pelo menos **três domínios de falha** para garantir maior confiabilidade.

### Área de Trabalho Virtual do Azure
- Serviço de virtualização de desktops e aplicativos baseado na nuvem.
- Suporte para várias sessões simultâneas.
- Redução de riscos com segurança aprimorada e MFA (Autenticação Multifator).
- Permite configurar regras de acesso e personalizar o ambiente.

---

## Serviços de Contêineres do Azure
Os contêineres são ambientes leves e isolados que não exigem gerenciamento de sistema operacional completo.

### Principais serviços de contêineres no Azure:
- **Instâncias de Contêineres do Azure (ACI)**: Oferta de PaaS para executar contêineres sem necessidade de gerenciar infraestrutura.
- **Aplicativos de Contêineres do Azure**: Também PaaS, permite balanceamento de carga e escalonamento.
- **Serviço de Kubernetes do Azure (AKS)**: Orquestração de contêineres para arquiteturas distribuídas e gerenciamento do ciclo de vida.

O **Docker** é um dos formatos mais populares de contêineres e é compatível com o Azure.

---

## Azure Functions
- Serviço **serverless** baseado em eventos.
- Executa código sob demanda sem necessidade de infraestrutura permanente.
- Ideal para automação e processamento de eventos.

---

## Comparação das Opções de Computação no Azure

| Opção | Características |
|---|---|
| **Máquinas Virtuais** | Servidor baseado em nuvem para Windows e Linux, ideal para migração *Lift-and-Shift* |
| **Área de Trabalho Virtual** | Ambientes de desktop na nuvem acessíveis via navegador ou aplicativo |
| **Contêineres** | Execução leve e escalável de microsserviços, suportando orquestração com AKS |

---

## Serviços de Aplicativos do Azure
- Plataforma gerenciada para criar, implantar e escalar **aplicações web e APIs**.
- Suporte a diversas tecnologias como **.NET, Node.js, Java, Python e PHP**.
- Integração com GitHub para automação de deploys.
- Oferta de **PaaS** com segurança e conformidade corporativa.

---

## Serviços de Rede do Azure

### Rede Virtual (VNet)
- Permite comunicação entre recursos do Azure e redes externas.
- Pontos de extremidade **públicos** (acessíveis via Internet) e **privados** (internos à rede).
- Uso de **sub-redes** para segmentação e segurança.
- **Emparelhamento de Rede** conecta redes privadas diretamente.
- **Evitar overlap de IP** ao configurar redes para evitar conflitos de endereçamento.

### Gateway de VPN
- Envia tráfego criptografado entre uma rede local e uma rede virtual no Azure.
- **ExpressRoute**: Alternativa mais segura e confiável para conexões dedicadas ao Azure.

### DNS do Azure
- Rede global de servidores DNS com alta confiabilidade e desempenho.
- Controle de acesso baseado em função.
- **Registros de Alias** permitem apontamento direto para recursos do Azure.

---

## Configurando Recursos e Dimensionamentos em Máquinas Virtuais na Azure

### Criando uma Máquina Virtual
1. Criar um **Grupo de Recursos** e uma **Rede Virtual**.
2. Selecionar **Assinatura** e o **Grupo de Recursos**.
3. Configurar **Nome da Máquina**, **Região**, **Opções de Disponibilidade**.

### Opções de Disponibilidade
- **Zonas de Disponibilidade**: Distribui máquinas em diferentes locais para alta resiliência.
- **Conjuntos de Dimensionamento de VMs**: Permite escalonamento automático baseado em demanda.

### Dimensionamento de Máquinas Virtuais
- Definir **mínimo e máximo** de instâncias.
- Configurar **escalonamento automático** baseado no uso da CPU.
- Ajustar **escala horizontal** (adicionar ou remover VMs).
- **Spot VM**: Oferece preços reduzidos, mas pode ser encerrada pelo Azure em momentos de alta demanda.

---

# Criando Aplicativos de Função no Azure
1. Adicionar um **Nome** e selecionar **Código** ou **Imagem de Contêiner**.
2. Escolher a **Pilha de Runtime** e sua versão.
3. Definir a **Região**.
4. A pilha de runtime influencia o sistema operacional base.
