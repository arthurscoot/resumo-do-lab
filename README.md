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

