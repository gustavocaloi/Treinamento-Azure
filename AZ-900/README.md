# Microsoft Certified Azure Fundamentals - AZ-900
##Pratic PT-BR

####Habilidades medidas
A versão em inglês deste exame foi atualizada em 5 de maio de 2022. Baixe o guia de estudo na caixa "Dica" anterior para obter mais detalhes sobre as habilidades medidas neste exame.
- Descrever os conceitos da nuvem (25 a 30%)
- Descrever a arquitetura e os serviços do Azure (35 a 40%)
- Descrever o gerenciamento e a governança do Azure (30 a 35%)

---
---
---
##Descrever a arquitetura e os serviços do Azure (35 a 40%)
---
---

---
###### #1

Uma empresa está implantando um aplicativo de negócios crítico em duas máquinas virtuais (VMS). A implantação precisa apoiar:
- Acesso altamente disponível
- Zonas de falha e atualização separadas
- Latência mínima entre instâncias

A maioria dos usuários que precisam acessar o aplicativo está na região Azure East US 2.

Qual configuração a empresa deve usar para implantar a solução?

>Zonas de disponibilidade separadas

---
###### #2
Você precisa identificar recursos de grupos de recursos.
Para cada uma das seguintes afirmações, selecione Sim se a afirmação for verdadeira. Caso contrário, selecione Não.

Bloquear um grupo de recursos como somente leitura bloqueia todos os recursos contidos em o grupo.
>Sim

Um grupo de recursos pode conter recursos da mesma região que o apenas grupo de recursos.
>Nao

Você pode adicionar ou remover um recurso de um grupo de recursos desde que o grupo de recursos não esteja bloqueado. 
>Sim

Os recursos podem interagir com outros recursos em um recurso diferente grupo.
>Sim

---
###### #3
Uma empresa deseja expandir sua presença na nuvem implantando recursos adicionais no Azure. A empresa planeja usar modelos baseados em recursos existentes para automatizar o processo de implantação. Garantir implantação consistente é fundamental.
O que a empresa deve usar?
>Gerenciador de recursos do Azure

---
###### #4
Você está sendo entrevistado para um emprego como administrador do Azure de nível básico.
Você precisa descrever as regiões.
Quais são as três descrições de regiões corretas? Para responder, mova as descrições apropriadas do lista de descrições possíveis para a área de resposta e organize-as em qualquer ordem.

Crie uma lista em qualquer ordem

Possíveis descrições de regiões
>As regiões representam datacenters físicos.

>As regiões podem abranger países.

Descrições das regiões
>As regiões são sempre emparelhadas com outras regiões.

>As regiões contêm um ou mais datacenters.

>As regiões especificam a localização dos recursos.

---
###### #5
Você está pensando em mover alguns de seus aplicativos para o Azure como instâncias de contêiner. No entanto, seu
gerente quer que você explique a eles sobre os contêineres e seus benefícios primeiro.
Você precisa explicar os contêineres ao seu gerente.
Quais são as quatro descrições de contêineres corretas? Para responder, mova as descrições apropriadas do
lista de descrições possíveis para a área de resposta e organize-as em qualquer ordem.

Crie uma lista em qualquer ordem

Descrições possíveis
>Um contêiner exige que você instalar dependências.

>Um contêiner requer que você configure a máquina virtual hospedeira.

Descrições do contêiner
>Um container pode ser acessado pelo Internet por endereço IP ou domínio nome.

> Um contêiner pode ser executado no Windows ou Linux.

>Um contêiner pode ser dimensionado conforme necessário.

>Um contêiner representa um único aplicativo e suas dependências.

---
###### #6
Qual é a finalidade de um grupo de recursos?
Escolha a resposta correta
>Ele serve como um contêiner para recursos do Azure, como máquinas virtuais (VMS) e aplicativos Web.

---
###### #7
A empresa A quer que seus departamentos de desenvolvimento e controle de qualidade gerenciem os serviços de aplicativos, sua TI e desenvolvimento departamentos para gerenciar máquinas virtuais (VMS) e seu departamento de TI para gerenciar instâncias do Banco de Dados SQL.
Esses departamentos devem gerenciar os recursos correspondentes tanto na produção quanto no desenvolvimento ambientes.

A empresa B quer que seu departamento de desenvolvimento gerencie suas próprias contas de VMS e armazenamento e suas vendas equipe para gerenciar seus próprios modelos de Machine Learning (ML).

A empresa C deseja que seu departamento de TI gerencie o SQL Server VMS que está no ambiente de produção. Isto também deseja permitir que seu departamento de desenvolvimento gerencie o SQL Server VMS que hospeda aplicativos no
ambiente de desenvolvimento.

Você precisa escolher a organização do grupo de recursos mais apropriada para cada empresa.
Qual organização de grupo de recursos você deve usar para cada empresa? Para responder, arraste o empresa para cada organização de grupo de recursos. Uma empresa pode ser usada uma vez, mais de uma vez ou não

Arraste e solte as respostas

Crie um grupo de recursos para cada departamento.
>Empresa B

Crie um grupo de recursos para cada tipo de recurso.
>Empresa A

Crie um grupo de recursos para cada ambiente.
>Empresa C

---
###### #8
Você implanta duas máquinas virtuais do Azure (VMS) executando o Windows Server 2016 e uma VM executando o Ubuntu Linux.
Todos os três VMS e seus recursos são adicionados ao mesmo grupo de recursos. O VMS e o recurso group estão localizados na mesma região do Azure.
O plano de teste indica que você precisa excluir o grupo de recursos assim que o ciclo de teste inicial for concluído.

Qual é o resultado dessa ação?

Escolha a resposta correta
>Todos os VMS contidos no grupo de recursos são excluídos.

---
###### #9
Você trabalha para uma pequena faculdade. A faculdade não tem mais de 250 alunos ativos. Você considera mover o infraestrutura da faculdade para a nuvem.

Você precisa determinar o tipo de assinatura que deve usar para diferentes cenários.

Quais assinaturas você deve usar? Para responder, arraste a assinatura apropriada para cada cenário. UMA

A assinatura pode ser usada uma vez, mais de uma vez ou nenhuma.

Arraste e solte as respostas

Você deseja avaliar as máquinas virtuais do Azure (VMS) por 18 meses.
>Pay-As-You-Go

Você deseja comprar máquinas virtuais do Azure (VMS) e licenças de software sob um contrato.
>Enterprise

Você deseja avaliar os Serviços de Aplicativo do Azure para seis meses.
>Free

---
###### #10
Você precisa determinar o número de assinaturas que precisa criar com base nos requisitos para cada cenário.
Quantas assinaturas você deve criar? Para responder, arraste o número apropriado de assinaturas para cada cenário. Um número pode ser usado uma vez, mais de uma vez ou não ser usado.

Arraste e solte as respostas

Sua empresa tem três departamentos e dois Azure administradores. Ambos os administradores gerenciam todos os departamentos. Cada departamento deve receber uma fatura do Azure.
>3

Sua empresa tem dois locais físicos e um Azure administrador. O administrador gerencia os dois locais. Cada local deve receber uma fatura do Azure.
>2

Sua empresa tem duas divisões e dois Azure administradores. Cada administrador é responsável por um divisão. A empresa deve receber uma fatura do Azure.
>1

---
###### #11
Sua empresa está planejando migrar sua infraestrutura para a nuvem do Azure. Você precisa explicar o modelo de assinatura.
Para cada uma das seguintes afirmações, selecione Sim se a afirmação for verdadeira. Caso contrário, selecione Não.

Declaração

Uma assinatura pode conter um ou mais grupos de recursos.
>Sim

Uma assinatura pode ter apenas uma licença.
>Não

Várias assinaturas podem ser de propriedade de um único organização.
>Sim

---
###### #12
Qual é o período máximo de tempo que você pode usar os créditos de uma assinatura gratuita do Azure antes dela expira?

Escolha a resposta correta
>30 dias

---
###### #13
Para cada uma das seguintes declarações sobre assinaturas do Azure, selecione Sim se a declaração for verdadeira.
Caso contrário, selecione Não.

Declaração
Você pode transferir uma assinatura existente para um novo Azure Active Locatário do diretório (AD).
>Sim

As cotas para recursos nos Grupos de Recursos do Azure são por região em vez de por assinatura.
>Sim

Um usuário só pode ter acesso a uma assinatura.
>Não

---
###### #14
Sua empresa está se reorganizando após adquirir uma nova empresa. Tanto a sua empresa quanto a nova empresa têm seus próprios locatários do Azure Active Directory (Azure AD).
Você precisa determinar o que acontece quando você transfere a propriedade de cobrança de uma assinatura de um conta em seu locatário do Azure AD a uma conta em outro locatário do Azure AD e associe a assinatura com o novo diretório.

Para cada uma das seguintes afirmações, selecione Sim se a afirmação for verdadeira. Caso contrário, selecione Não.

Declaração

Todos os usuários e grupos com acesso baseado em função para gerenciar a assinatura perder o acesso.
>Sim

As identidades gerenciadas atribuídas pelo sistema são reativadas automaticamente.
>Não

Movendo uma assinatura que possui um Serviço de Kubernetes do Azure (AKS) cluster faz com que o cluster perca a funcionalidade.
>Sim

---
###### #15
Você implanta uma solução crítica de negócios no Azure.
Você precisa garantir que seus recursos sejam replicados e hospedados a pelo menos 200 milhas de distância dentro do mesmo área geográfica, para minimizar o impacto na disponibilidade de sua solução em caso de desastre.

Qual opção de configuração você deve usar?

Escolha a resposta correta
>Pares de regiões

---
###### #16
Para completar a declaração na área de resposta, selecione a opção apropriada no menu suspenso.

Escolha as opções corretas
>Os grupos de gerenciamento permitem que você organize vários assinaturas como uma única entidade de gerenciamento para facilitar o gerenciamento.


---
###### #17
Você está planejando criar uma solução de nuvem no Azure.
Você precisa escolher os recursos de rede apropriados para implantar em determinados cenários.
Quais recursos você deve implantar? Para responder, selecione os recursos apropriados na lista suspensa cardápios.

Escolha as opções corretas

Cenário
Você deseja permitir que o tráfego de entrada uma máquina virtual do Azure (VM) de apenas endereços IP específicos.
>Grupo de segurança de rede (NSG)

Você deseja evitar uma inundação maliciosa de tráfego HTTP para uma VM que hospeda Serviços de Informações da Internet (IIS).
>Proteção Distribuída de Negação de Serviço (DDoS)

Você deseja criar uma regra que restringe o tráfego de rede assinaturas.
>Firewall do Azure

---
###### #18
Para cada uma das seguintes declarações sobre a Área de Trabalho Virtual do Azure (AVD), selecione Sim se a declaração for verdadeira. Caso contrário, selecione Não.

Declaração

O AVD oferece suporte a clientes de Área de Trabalho Remota no MacOS e iOS.
>Sim

Você é cobrado pelo uso do AVD mensalmente de acordo com usuários ativos.
>Não

Os usuários do AVD devem existir no mesmo Windows Server Active Directory (AD) que está vinculado ao Azure AD.
>Sim

---
###### #19
Corresponda cada recurso do Azure a um cenário.
Para responder, arraste o recurso apropriado para cada cenário. Um recurso pode ser usado uma vez, mais de uma vez, ou nada.

Arraste e solte as respostas

Migre uma carga de trabalho de um Hyper-Host V para o Azure, ainda mantendo controle total sobre o sistema operacional.
>Máquina Virtual do Azure (VM)

Implante um aplicativo da Web usando Platform-as-a-Service (PaaS) para escalabilidade e segurança.
>Serviço de Aplicativo do Azure

Crie uma solução orientada a eventos e pague apenas por o tempo gasto executando seu código.
>Funções do Azure

---
###### #20
Quais são as duas opções que você pode usar para conectar as Redes Virtuais do Azure (VNets) entre si? Cada correto resposta apresenta uma solução completa.

Escolha as respostas corretas
>Gateways VPN

> Emparelhamento de VNet

---
###### #21
Para cada uma das seguintes declarações sobre a rede do Azure, selecione Sim se a declaração for verdadeira. Por outro lado, selecione Não.

Declaração

O tráfego do ExpressRoute é roteado por meio de uma conexão privada.
>Sim

O tráfego entre redes virtuais emparelhadas (VNets) é roteado pela internet pública.
>Não

Uma VNet é criada no escopo de uma região.
>Sim

---
###### #22
Você deseja realizar implantações automatizadas do Azure DevOps. Qual das opções a seguir permite isso processo?

Escolha as opções corretas
>permite que você execute implantações automatizadas do Azure DevOps.

---
###### #23
Combine cada instrução com o serviço de computação do Azure que está sendo descrito.
Para responder, arraste o tipo apropriado para cada descrição. Um serviço pode ser usado uma vez, mais de uma vez ou de jeito nenhum.

Arraste e solte as respostas

Inclui um processador virtual, memória, armazenamento e recursos de rede.
>Máquinas Virtuais do Azure

É um leve, virtualizado ambiente de aplicação.
>Instâncias de contêiner

Inclui a abstração de servidores, infraestrutura e sistemas operacionais.
>Funções do Azure

---
###### #24
Para completar a declaração na área de resposta, selecione a opção apropriada no menu suspenso.

Escolha as opções corretas
>Criando instâncias de aplicativos altamente portáteis e escaláveis que incluem os binários e bibliotecas necessárias para executar podem ser feitas usando

---
###### #25
Para cada uma das seguintes declarações sobre o emparelhamento de rede virtual do Azure, selecione Sim se a declaração for verdadeiro. Caso contrário, selecione Não.

Declaração

O emparelhamento de rede virtual pode ser usado para conectar redes virtuais entre Regiões do Azure.
>Sim

O emparelhamento de rede virtual pode ser usado para transferir dados entre o Azure Locatários do Active Directory (Azure AD).
>Sim

A configuração do emparelhamento requer um curto tempo de inatividade para o virtual emparelhado redes.
>Não

---
###### #26
Você gerencia uma equipe de desenvolvimento que precisa concentrar todos os seus esforços na criação e manutenção de aplicativos código. Sua equipe não tem recursos para provisionar e dimensionar a infraestrutura de seus aplicativos requerem para correr. O que você deveria fazer?

Escolha a resposta correta
>Crie uma assinatura do Azure Functions e carregue seu código.

---
###### #27
Você tem a tarefa de resolver problemas de desempenho em um cluster de servidor Web baseado no Azure.
Você precisa configurar as máquinas virtuais para escalar verticalmente.

O que você deve fazer para atender a esse requisito?

Escolha a resposta correta
>Adicione recursos de computação e memória a cada máquina virtual.

---
###### #28
Você precisa garantir um desempenho consistente para os usuários que acessam seu aplicativo, que é executado em máquinas virtuais Linux personalizadas.

O que você deve usar para provisionar máquinas virtuais automaticamente?

Escolha a resposta correta
>Conjuntos de escala

---
###### #29
Você precisa trazer o Armazenamento do Azure para sua rede virtual com um endereço IP dedicado.

Qual solução você deve usar?

Escolha a resposta correta
>Crie um ponto de extremidade privado com o Link Privado do Azure.

---
###### #30
Uma empresa deseja hospedar discos de dados na nuvem do Azure. Os discos de dados devem estar disponíveis para outros máquinas locais executando Windows, Linux e macOS usando compartilhamento de rede via Server Message Block protocolo (SMB). Os dados devem estar seguros tanto em repouso quanto em trânsito.

Você precisa escolher uma solução de produto de armazenamento apropriada.

Qual produto de armazenamento você deve usar?

Escolha a resposta correta
>Armazenamento de arquivo

---
###### #31
Qual produto de banco de dados do Azure oferece suporte a modelos de dados de valor-chave e documentos e fornece suporte nativo para NoSQL?

Escolha a resposta correta
>Azure Cosmos DB

---
###### #32
Sua empresa está pensando em usar Azure Container Instances (ACIs) baseadas em Linux para implantar um inscrição. O aplicativo é executado como um aplicativo com estado.

Você precisa fornecer armazenamento para recuperar e persistir o estado.

Que tipo de armazenamento você deve usar?

Escolha a resposta correta
>Arquivos do Azure

---
###### #33
Sua empresa está planejando uma implantação usando o Banco de Dados do Azure para PostgreSQL. A implantação deve atender aos seguintes requisitos:
- Até 10 TB de armazenamento
- Armazenamento Premium do Azure
- Restauração pontual por até 35 dias

Você precisa selecionar a implantação apropriada e o tipo de preço para atender a esses requisitos e minimizar custos.

O que você deve selecionar?

Escolha a resposta correta
>Camada de Uso Geral do Banco de Dados do Azure para PostgreSQL de Servidor Único

---
###### #34
Você cria uma nova solução de análise operacional no Azure usando o PostgreSQL como um banco de dados relacional. o crescimento mensal estimado de seu banco de dados é de 20 Gb.

Você precisa garantir que seu banco de dados possa ser dimensionado horizontalmente e dar suporte à paralelização de consultas para respostas em um grande conjunto de dados, sem o envolvimento de sua equipe no banco de dados ou sistema operacional gestão.

Qual opção de implantação do PostgreSQL no Azure você deve usar?

Escolha a resposta correta
>Banco de dados do Azure para PostgreSQL Hyperscale (Citus)

---
###### #35
Combine cada recurso do Azure com seu cenário de uso.
Para responder, arraste o recurso apropriado para cada cenário. Um recurso pode ser usado uma vez, mais de uma vez, ou nada.

Arraste e solte as respostas

Migração rápida do SQL Server do local para Azure com retenção de sistema operacional acesso
>SQL Server no Azure VMS

Banco de dados econômico e sem servidor com um padrão de uso intermitente e uma computação baixa utilização ao longo do tempo
>Banco de Dados SQL do Azure

Vida e mudança do SQL Server local com alterações mínimas em uma plataforma do Azure como um solução de serviço (PaaS)
>Instância Gerenciada de SQL do Azure

---
###### #36
Quais duas soluções você deve usar para transferir um disco rígido virtual (VHD) local para o Azure? Cada resposta correta apresenta uma solução completa.

Escolha as respostas corretas
>Explorador de Armazenamento do Azure

>AzCopyName

---
###### #37
Você precisa habilitar a redundância de dados para os aplicativos de nuvem da sua organização. Dependendo dos dados, a redundância pode ser apenas local ou pode exigir várias cópias armazenadas em locais diferentes.
Dadas as descrições de armazenamento redundantes abaixo, qual opção de redundância está sendo descrita? Para responder, selecione a opção de redundância apropriada na área de resposta.

Escolha as opções corretas

Ele armazena três cópias de dados em cada um dos duas regiões.
>Geo-redundante storage (GRS)

Permite que dados replicados sejam acessados em duas zonas.
>Read-access GRS (RA-GRS) 
>GRS com acesso de leitura (RA-GRS)

Ele armazena todas as réplicas em um data center.
>Locally redundant storage (CRS)
>Armazenamento localmente redundante (CRS)

---
###### #38
Corresponda cada camada de acesso do Azure Storage Blob com sua descrição associada.
Para responder, arraste a camada de acesso de blob apropriada para o recurso apropriado. Uma camada pode ser usada uma vez, mais mais de uma vez, ou não.

Arraste e solte as respostas

Incorre em penalidades por dados apagado em 30 dias.
>Cool

Não está disponível na conta nível.
>Arquivo

Incorre na maior reidratação custo.
>Arquivo

---
###### #39
Para completar a declaração na área de resposta, selecione a opção apropriada no menu suspenso.

Escolha as opções corretas

>conta de armazenamento dá suporte aos serviços Blob, Queue e Table Storage.

---
###### #40
Para cada uma das seguintes declarações sobre os Arquivos do Azure, selecione Sim se a declaração for verdadeira. Por outro lado, selecione Não.

Declaração
Os arquivos do Azure podem ser acessados usando a mensagem do servidor Protocolo de bloco (SMB).
>Sim

Os Arquivos do Azure podem ser acessados usando o Arquivo de Rede Protocolo do sistema (N FS).
>Sim

Uma assinatura de acesso compartilhado (SAS) é necessária para acessar Arquivos do Azure.
>Não


---
###### #41
Como parte de uma migração para a nuvem, sua implementação de nuvem do Azure foi inicialmente propagada com 100 TB de dados.
À medida que a migração continua, você precisa migrar dados periodicamente para o Azure usando o Server Message Block (SMB).
Quais duas soluções você deve usar para atender a esse requisito? Cada resposta correta apresenta um solução.

Escolha as respostas corretas
>Arquivos do Azure

>Gateway de caixa de dados do Azure

---
###### #42
Você implanta três máquinas virtuais (VMS) no Azure como uma arquitetura de três camadas.
Uma VM hospeda um front-end aplicação web, uma VM hospeda uma interface de programação de aplicativos (API) de negócios e a outra VM hospeda um banco de dados Microsoft SQL Server. Apenas o aplicativo web front-end deve ser acessível publicamente e deve ser acessível por H T TP na porta 80.
- Todos os três VMS devem ser acessíveis pela Área de Trabalho Remota
- Protocol (RDP) na porta 222.
- Somente sua conta deve poder usar o RDP para acessar as VMs.

Você precisa determinar como os grupos de segurança de rede (NSGs) podem ser usados nesse cenário.

Quais são as duas maneiras pelas quais as regras NSG podem ser usadas? Cada resposta correta apresenta uma solução completa.

Escolha as respostas corretas
>Para garantir que apenas a VM front-end seja acessível publicamente pela porta 80

>Para garantir que todos os três VMS sejam acessíveis pela porta 222

---
###### #43
Para cada uma das seguintes declarações sobre a proteção de negação de serviço distribuída (DDoS) do Azure, selecione Sim se a afirmação for verdadeira. Caso contrário, selecione Não.

Declaração

O padrão de proteção contra DDoS do Azure é habilitado automaticamente.
>Nao

O padrão de proteção contra DDoS do Azure fornece proteção contra protocolo e ataques de camada de aplicação.
>Sim

As redes virtuais de várias assinaturas em sua organização podem link para o mesmo plano de proteção contra DDoS do Azure.
>Sim

---
###### #44
Você está planejando migrar os aplicativos Web da sua empresa para o Azure. Você deseja usar a segurança do Azure recursos.
Você precisa entender a diferença entre autenticação e autorização no Azure.
Para cada uma das seguintes afirmações, selecione Sim se a afirmação for verdadeira. Caso contrário, selecione Não.

Declaração

A autenticação garante que o nome de usuário e a senha combinação está correta.
>Sim

A autorização garante que uma conta tenha permissões para acessar um recurso.
>Sim

A autenticação pode usar certificados para identificar uma pessoa ou serviço.
>Sim

A autorização pode usar senhas para identificar uma pessoa.
>Não

---
###### #45
Qual exemplo melhor descreve a autorização?

Escolha a resposta correta
>Pessoas que apresentam sua certidão de nascimento para provar que são elegíveis para receber benefícios governamentais com base na idade.

---
###### #46
Você planeja criar uma assinatura do Azure e aproveitar seu Azure Active Directory (Azure AD) recursos. Você planeja usar a assinatura por não mais de um ano.
Você precisa escolher a licença mais barata para cada cenário.
Qual licença você deve usar? Para responder, arraste a licença apropriada para cada cenário. Uma licença pode ser usado uma vez, mais de uma vez ou nunca.

Arraste e solte as respostas

Você deseja publicar a Web local aplicativos usando o Azure AD.
>Premium

Você deseja usar o diretório local sincronização.
>Free

Você deseja que os usuários locais possam redefinir suas próprias senhas.
>Premium

---
###### #47
Quais são os dois exemplos que melhor descrevem a autenticação multifator (MFA)? Cada resposta correta apresenta um solução completa.

Escolha as respostas corretas
>Você recebe uma mensagem de texto com um código depois de inserir um nome de usuário e senha em um filme site de streaming.

>Você insere seu cartão de débito em um caixa eletrônico e, em seguida, insere seu número de identificação pessoal (PIN) para acessar sua conta.


---
###### #48
Uma empresa está migrando vários aplicativos Web de uma implantação de nuvem privada local para o Azure. oempresa deseja usar o Azure Active Directory (Azure AD) para autenticação e autorização.
Você precisa determinar se o Azure AD atenderá aos seus requisitos de autenticação.
Para cada uma das seguintes afirmações, selecione Sim se a afirmação for verdadeira. Caso contrário, selecione Não.

Declaração

O suporte à autenticação e autorização do Azure AD requer integração com um AD local.
>Não

Os aplicativos Web devem ser registrados no Azure AD para dar suporte à autenticação e serviços de autorização.
>Sim

O Azure AD dá suporte à autorização por meio do uso de acesso baseado em função controle (RBAC).
>Sim

---
###### #49
Uma empresa assina o Azure como uma plataforma para desenvolver e implantar aplicativos Web. A empresa quer para manter as despesas iniciais ao mínimo. A empresa não pode usar a edição gratuita, pois não suporta muitos recursos necessários, então a empresa decide optar pela assinatura premium do Azure AD.
Você precisa determinar os recursos disponíveis para a empresa com o Azure Active Directory (Azure AD) Edição PI premium.
Quais são os dois recursos compatíveis com a edição PI do Azure AD Premium? Cada resposta correta apresenta um solução completa.

Escolha as respostas corretas
>Controle de acesso baseado em função (RBAC)

>Acesso condicional


---
###### #50
Uma empresa tem uma assinatura de PI Premium do Azure Active Directory (Azure AD). A empresa tem um híbrido ambiente que usa o Azure AD e o AD federado local usando a Federação do Active Directory Serviços (AD FS).
A empresa está atualizando sua segurança e deve configurar a redefinição de senha de autoatendimento do Azure AD (SSPR) e Autenticação multifator (MFA). Você precisa identificar os tipos de autenticação que são suportados por ambos SSPR e MFA.
Quais são os três tipos de autenticação compatíveis com SSPR e MFA? Cada resposta correta apresenta um solução completa.

Escolha as respostas corretas
>Chamada de voz

>SMS

>Senha


---
###### #51
Você precisa de uma solução de segurança que ajude a provisionar, gerenciar e implantar Secure Sockets Layer/Transporte Certificados de segurança de camada (SSL/TLS).

O que você deve usar?

Escolha a resposta correta
>Cofre de Chaves


---
###### #52
Uma empresa está revisando a segurança para máquinas virtuais (VMS) implantadas em sua nuvem híbrida.
Você precisa identificar os recursos de segurança fornecidos por meio do Microsoft Defender for Cloud.
Para cada uma das seguintes afirmações, selecione Sim se a afirmação for verdadeira. Caso contrário, selecione Não.

Declaração
O Microsoft Defender for Cloud oferece suporte ao monitoramento, segurança recomendações e proteção avançada contra ameaças para nuvem e recursos de máquina virtual (VM) local.
>Sim

O Microsoft Defender for Cloud fornece integração nativa com a Microsoft Antivírus Defender no Windows.
>Sim

O suporte do Microsoft Defender for Cloud está limitado ao Windows operacional apenas sistemas.
>Nao

O Microsoft Defender for Cloud pode descobrir e avaliar automaticamente segurança para novos recursos do Azure à medida que são implantados.
>Sim

---
###### #53
Seu locatário do Azure inclui uma Rede Virtual do Azure (VNet) com vários servidores Web voltados para a Internet. o servidores web sofrem ataques que esgotam os recursos do servidor e tornam os servidores indisponíveis para usuários. Você determina que os ataques estão sendo lançados de vários locais.
Você precisa implementar uma solução do Azure que:
- Detecta e tenta mitigar ataques automaticamente.
- Gera alertas quando um ataque ativo está em andamento.

Qual é a melhor opção para implementar sua solução?

Escolha a resposta correta
>Padrão de proteção contra DDoS do Azure


---
###### #54
Seu locatário do Azure inclui vários servidores Web voltados para a Internet. Os servidores web dependem de dados armazenados em Servidores do Banco de Dados SQL do Azure. Os servidores Web estão localizados em diferentes sub-redes de rede virtual (VNet). os servidores de banco de dados têm seus terminais expostos às sub-redes.
Você precisa implementar controles detalhados sobre os tipos de conexões suportadas entre os servidores web e servidores de banco de dados. Você deseja minimizar os esforços e custos necessários para implementar e manter seu solução.
Quais duas tecnologias você deve incluir em sua solução? Cada resposta correta apresenta parte do solução.

Escolha as respostas corretas
>Grupos de segurança de rede (NSGs)

>Grupos de segurança de aplicativos (ASGs)

---
###### #55
Qual solução de segurança do Azure fornece recomendações gerais de segurança e sugere correções para proteger melhor seus recursos?

Escolha a resposta correta
>Microsoft Defender para Nuvem

---
###### #56
Corresponda cada solução do Azure a um cenário.
Para responder, arraste a solução adequada para cada cenário. Uma solução pode ser usada uma vez, mais de uma vez, ou nada.

Arraste e solte as respostas

Construir um perfil comportamental básico de entidades organizacionais para identificar atividade anômala.
>Sentinela da Microsoft

Armazenar com segurança uma conexão de banco de dados string para evitar seu acidente exposição no código-fonte de um site.
>Cofre de Chaves do Azure

Negar tráfego para seu Azure Virtual Recursos de rede de conhecidos endereços IP maliciosos.
>Firewall do Azure

---
###### #57
Para cada uma das seguintes declarações sobre Hosts Dedicados do Azure, selecione Sim se a declaração for verdadeira. Caso contrário, selecione Não.

Declaração

Um servidor físico fornecido é dedicado à sua organização carga de trabalho apenas.
>Sim

Você pode compartilhar um servidor físico fornecido em seus vários Assinaturas do Azure.
>Nao

Você é cobrado por número de máquinas virtuais (VMS) implantado.
>Nao

---
###### #58
Quais são os dois insights em nível de organização que você pode obter do painel de Conformidade Regulamentar do Microsoft Defender para Nuvem? Cada resposta correta apresenta parte da solução.

Escolha as respostas corretas
>Número de avaliações aprovadas e reprovadas

>Pontuação geral de conformidade

---
###### #59

Para completar a declaração na área de resposta, selecione a opção apropriada no menu suspenso.

Escolha as opções corretas
>O Azure Advisor integra-se para ajudar para prevenir, detectar e responder a ameaças aos recursos do Azure.

---
###### #60

Para completar a frase, selecione a opção apropriada no menu suspenso.

Escolha as opções corretas
>é uma estratégia para implementar várias camadas de segurança para diminuir desativar um ataque e fornecer telemetria de alerta antecipado para agir.

---
###### #61
Para completar a declaração na área de resposta, selecione a opção apropriada no menu suspenso.

Escolha as opções corretas
>Grupos de segurança de aplicativos (ASGs) permitem que você organize servidores semelhantes para que você possa definir e implementar facilmente políticas de segurança com base nesses grupos.

---
###### #62
Quais duas opções são exemplos de políticas de acesso condicional? Cada resposta correta apresenta um solução.

Escolha as respostas corretas
>Bloquear o acesso por local

>Exigir dispositivos compatíveis

---
###### #63
Para completar a frase, selecione a opção apropriada no menu suspenso.

Escolha as opções corretas
>os usuários podem acessar todos os aplicativos necessários sem sendo necessário autenticar uma segunda vez.

---
###### #64
Para completar a declaração na área de resposta, selecione a opção apropriada no menu suspenso.

Escolha as opções corretas
>É necessário um servidor de autenticação multifator do Azure (MFA) para autenticação ao oferecer suporte apenas a usuários localizados no Active Directory (AD) local.


---
---
---
##Geral
---
---
---
###### #1
Uma empresa deseja expandir sua presença na nuvem implantando recursos adicionais no Azure. A empresa planeja usar o modelo baseado em recursos existentes para automatizar o processo de implantação. Garantir uma implantação consistente é fundamental.
O que a empresa deve usar?
>Resposta: Gerenciador de recursos do Azure

---

###### #2
Corresponda cada recurso do Azure com seu cenário de uso.
para responder, arraste o recurso apropriado para cada cenário. Um recurso pode ser usado uma vez, mais de uma vez ou não ser usado.

Migração rápida do SQL Server do local para o Azure com retenção de acesso ao sistema operacional:
> SQL Server em VMs do Azure

Banco de dados sem servidor econômico com padrão de uso intermitente e baixa utilização de computação ao longo do tempo:
>Azure SQL Databace

Mudança de vida do SQL Server local com alterações mínimas em uma solução Azure Platform-as-a-Service (PaaS): 
>Azure SQL Managed Instance

---

###### #3
Qual é a vantagem de migrar a infraestrutura da sua empresa para o Azure usando um modelo de implantação de nuvem pública?

>A empresa é capaz de expandir conforme necessário, sem necessidade de despesas de capital (CapEx).

---

###### #4
Para completar a declaração na área de resposta, selecione a opção apropriada no menu suspenso.

O Azure Advisor integra-se com a ajuda superior do "Microsoft Defender for cloud" para prevenir, detectar e responder a ameaças aos recursos do Azure.
>"Microsoft Defender for cloud"

---
###### #5
Para completar a declaração na área de resposta, selecione a opção apropriada no menu suspenso.

Você usa o Gerenciamento de Custos e Faturamento do Azure para criar relatórios de custo. Para entender os dados em um relatório de custos, a Microsoft recomenda que você implemente "tags".
>"tags"

---

###### #6
Qual serviço do Azure pode usar o dimensionamento automático para adicionar ou remover recursos conforme apropriado para minimizar custos e garantir níveis ideais de desempenho?
>Monitor do Azure

---
###### #7
Qual recurso do Azure Monitor permite que você analise visualmente os dados de telemetria?
>Insights do aplicativo

---

###### #8
Qual é o período máximo de tempo que você pode usar os créditos de uma assinatura gratuita do Azure antes que ela expire?
>30 dias

---

###### #9
Você está planejando usar o Azure para uma solução de nuvem.
Você precisa escolher a ferramenta mais adequada para diferentes cenários.
Quais ferramentas você deve usar? Para responder, arraste a ferramenta apropriada para cada cenário. Uma ferramenta pode ser usada uma vez, mais de uma vez ou não.

Você quer ver quanto pode economizar em cinco anos movendo a infraestrutura da sua empresa para a Nuvem do Azure:
>calculadora de custo total de propriedade (TCO)

Você deseja configurar um alerta para enviar mensagens de texto para você e seu colega de trabalho quando seus Recursos do Azure usarem 90% do orçamento mensal do Azure da sua empresa:
>Gerenciamento de Custos

Você deseja estimar o custo de implantação de quatro máquinas virtuais (VMs) e duas instâncias do Banco de Dados SQL no Azure:
>Calculadora de preços do Azure

---

###### #10
Você precisa comparar os custos de execução de uma carga de trabalho de aplicativo no Azure vesus on-primeses.

O que você deve fazer para garantir que possa usar a calculadora de TCO do Azure para concluir essa tarefa?
>Defina o servidor, bancos de dados, armazenamento e carga de trabalho de rede.

---

###### #11
Qual recurso do Azure pode ser implantado como infraestrutura como serviço (IaaS)?
>Máquina virtual (VM)

---

###### #12
Os grupos de gerenciamento permitem que você organize várias "assinaturas como uma única entidade de gerenciamento para facilitar o gerenciamento".
>"assinaturas como uma única entidade de gerenciamento para facilitar o gerenciamento"
---

###### #13
Incorre em penalidades por dados excluídos em 30 dias: legal
>Não está disponível no nível da conta: Arquivar

>Incorre no maior custo de reidratação: Arquivo

---

###### #14
Com a "computação sem servidor", os desenvolvedores implantam código e pagam apenas pelo tempo de execução, sem se preocupar com o provisionamento, configuração e gerenciamento da infraestrutura subjacente.
>"computação sem servidor"

---

###### #15
Você deseja avaliar as máquinas virtuais (VMs) do Azure por 18 meses:
>Pay-As-You-Go

Você deseja comprar máquinas virtuais (VMs) do Azure e licenças de software sob um contrato: 
>Enterprise

Você deseja avaliar os Serviços de Aplicativo do Azure por seis meses: 
>Gratuito

---

###### #16
Você deseja controlar os usuários que têm permissão para criar redes virtuais (VNets):
>RBAC

Você deseja revisar as recomendações de segurança relacionadas aos seus recursos implantados:
>Consultor

Você deseja impedir que máquinas virtuais (VMs) sejam implantadas em uma assinatura:
>Política

---

###### #17
Você gerencia uma assinatura do Azure para sua empresa. Em uma reunião, alguém pergunta sobre a calculadora de preços do Azure.
Para que serve o preço do Azure?
>Estimando os custos mensais associados ao uso de recursos específicos do Azure

---

###### #18
Quais são os dois exemplos que melhor descrevem a autenticação multifator (MFA)? Cada resposta correta apresenta uma solução completa.

>Você insere seu cartão de débito em um caixa eletrônico e, em seguida, insere seu número de identificação pessoal (PIN) para acessar sua conta.

>Você recebe uma mensagem de texto com um código depois de inserir um nome de usuário e senha em um site de streaming de filmes

---

###### #19
Você concluiu a migração dos principais servidores e processos de sua organização para máquinas virtuais baseadas em nuvem. Seu projeto final envolve a migração de uma tarefa semanal de processamento em lote que depende de drivers do sistema operacional para imprimir relatórios em PDF.
Você precisa atender a esse requisito enquanto minimiza os custos.
>Execute a tarefa de processamento em lote usando instâncias spot

---

###### #20
Você implanta uma solução crítica de negócios no Azure.
Você precisa garantir que seus recursos sejam replicados e hospedados a pelo menos 200 milhas de distância dentro da mesma área geográfica, para minimizar o impacto na disponibilidade de suas soluções em caso de desastre.
Qual opção de configuração você deve usar?
>Pares de regiões

---

###### #21
O suporte à autenticação e autorização do Azure AD requer integração com um AD local:
>Não

Os aplicativos Web devem ser registrados no Azure AD para dar suporte aos serviços de autenticação e autorização:
>sim

O Azure AD dá suporte à autorização por meio do uso de controle de acesso baseado em função (RBAC):
>sim

---

###### #22
Você precisa identificar recursos de grupos de recursos.
Para cada uma das seguintes afirmações, selecione SIM se a afirmação for verdadeira. Caso contrário, selecione NÃO.

Bloquear um grupo de recursos como somente leitura bloqueia todos os recursos contidos no grupo:
>sim

Um grupo de recursos pode conter apenas recursos da mesma região que o grupo de recursos:
>não

Você pode adicionar ou remover um recurso de um grupo de recursos, desde que o grupo de recursos não esteja bloqueado:
>sim

Os recursos podem interagir com outros recursos em um grupo de recursos diferente:
>sim

---

###### #23
Uma zona de cobrança é um agrupamento geográfico de regiões do Azure usado para determinar a cobrança com base em "transferências de dados".
>transferências de dados

---

###### #24
Você move algumas máquinas virtuais do Windows Server (VMS) de seu datacenter local para o Azure.
O VMs local existente é licenciado pelo contrato ativo do Microsoft Software Assurance da sua empresa.
Você precisa reduzir o custo de suas VMs do Azure.

O que você deveria fazer?
>Habilite a configuração do Benefício Híbrido do Azure.

---

###### #25
Sua empresa planeja migrar aplicativos e serviços para a nuvem. Você recomenda que uma nuvem híbrida seja implantada.
Por que você faria essa recomendação?
>Para aumentar os recursos locais fornecendo capacidade de estouro

Explicação
Ao implementar uma nuvem híbrida, sua empresa pode aumentar os recursos locais fornecendo overflow capacidade. Uma nuvem híbrida é a combinação de dois ou mais modelos de nuvem, como público e privado, e oferece benefícios de ambos os modelos. Ele pode dar às empresas a flexibilidade de usar recursos de nuvem pública quando eles precisam deles, ao mesmo tempo em que mantêm dados e aplicativos confidenciais no local em uma nuvem privada. Um híbrido A nuvem também pode ajudar as organizações a gerenciar picos e vales no tráfego com mais eficiência. Ao usar um híbrido modelo de nuvem, as empresas não precisam superprovisionar recursos de computação em antecipação à alta demanda; eles podem simplesmente trazer recursos extras da nuvem pública quando precisarem deles.

---

###### #26
Sua empresa usa os Blueprints do Azure para auxiliar na migração para o Azure. User1 deve ser capaz de atribuir blueprints publicados.
Você precisa adicionar o User1 à função de controle de acesso baseado em função (RBAC) necessária para fornecer essa permissão.
Sua solução deve seguir o princípio do menor privilégio.

A qual função você deve atribuir User1?
>Operador de planta

---

###### #27
Para cada uma das seguintes declarações sobre o emparelhamento de rede virtual do Azure, selecione Sim se a declaração for verdadeiro. Caso contrário, selecione Não.
 
O emparelhamento de rede virtual pode ser usado para conectar redes virtuais entre Regiões do Azure:
>Sim
 
O emparelhamento de rede virtual pode ser usado para transferir dados entre o Azure Locatários do Active Directory (Azure AD):
>Sim

A configuração do emparelhamento requer um curto tempo de inatividade para o virtual emparelhado Redes:
>Não

---

###### #28
Para completar a declaração na área de resposta, selecione a opção apropriada no menu suspenso.
Uma conta de armazenamento "padrão de uso geral v2" dá suporte aos serviços Blob, Queue e Table Storage.
>"padrão de uso geral v2"

---

###### #29
Para completar a declaração na área de resposta, selecione a opção apropriada no menu suspenso.
Os Grupos de Segurança de Aplicativos (ASGs) permitem "organizar servidores semelhantes para que você possa definir e implementar facilmente políticas de segurança com base nesses grupos".
>"organizar servidores semelhantes para que você possa definir e implementar facilmente políticas de segurança com base nesses grupos"

---

###### #30
Você cria uma assinatura do Azure. Você precisa determinar quando deve usar ferramentas de gerenciamento específicas do Azure.
Quando você deve usar cada ferramenta?

Para responder, arraste a ferramenta apropriada para cada cenário. Uma ferramenta pode ser usada uma vez, mais de uma vez, ou nenhuma.

Você precisa fazer login no Azure com o seguinte comando do seu laptop sem abrir manualmente um navegador da Web:
>Connect-AzAccount (Azure PowerShell)

Você precisa fazer login no Azure com o seguinte comando do seu laptop sem manualmente abrindo um navegador da web:
>az login (Azure CLI)

Você deseja executar o seguinte comando em um ambiente de script dentro do navegador:
>Novo AzVm (Azure Cloud Shell)

---

###### #31
Você implanta três máquinas virtuais (VMS) no Azure como uma arquitetura de três camadas.
- Uma VM hospeda um front-end aplicação web,
- uma VM hospeda uma interface de programação de aplicativos (API) de negócios e a 
- outra VM hospeda um banco de dados Microsoft SQL Server.

Apenas o aplicativo web front-end deve ser acessível publicamente e deve ser acessível por HTTP na porta 80.
Todos os três VMS devem ser acessíveis pela Área de Trabalho Remota Protocol (RDP) na porta 222.
Somente sua conta deve poder usar o RDP para acessar as VMs. 

Você precisa determinar como os grupos de segurança de rede (NSGs) podem ser usados nesse cenário.
Quais são as duas maneiras pelas quais as regras NSG podem ser usadas? Cada resposta correta apresenta uma solução completa.
>Para garantir que apenas a VM front-end seja acessível publicamente pela porta 80

>Para garantir que todos os três VMs sejam acessíveis pela porta 222

---

###### #32
Para melhorar o desempenho de um aplicativo de missão crítica, sua organização implementou a nuvem estourando.

Qual declaração descreve o benefício que o cloud bursting oferece?
>Os recursos baseados em nuvem são provisionados quando os servidores locais atingem 100% dos recursos capacidade.

---

###### #33
Para cada uma das seguintes declarações sobre a rede do Azure, selecione Sim se a declaração for verdadeira. Caso contrário, selecione Não.

O tráfego do ExpressRoute é roteado por meio de uma conexão privada:
>Sim

O tráfego entre redes virtuais emparelhadas (VNets) é roteado pela Internet pública:
>Não

Uma VNet é criada no escopo de uma região:
>Sim

---

###### #34
Identifique quais declarações descrevem com precisão Software-as-a-Service (SaaS), Platform-as-a-Service (PaaS), e Infraestrutura como Serviço (IaaS).
Para cada uma das seguintes afirmações, selecione Sim se a afirmação for verdadeira. Caso contrário, selecione Não.

O provedor de serviços é responsável por todo o hardware de infraestrutura em SaaS, PaaS e IaaS:
>Sim
 
Criar uma máquina virtual (VM) executando o Windows Server 2016 é um exemplo de PaaS:
>Não
 
O SaaS oferece uma maneira de fornecer aos usuários acesso a aplicativos sofisticados em um ambiente de pagamento conforme o uso:
>Sim

---

###### #35
Sua empresa está planejando uma implantação de nuvem do Azure que deve atender aos seguintes requisitos:

- Melhore a continuidade de aplicativos críticos para os negócios
- Melhore o desempenho do aplicativo
- Detectar ameaças e vulnerabilidades 
- Reduza os custos gerais do Azure
 
Você precisa usar uma ferramenta que o ajude a fazer esses tipos de recomendações.

Qual ferramenta você deveria usar? Para responder, clique na opção apropriada na área de resposta.

---

###### #36
Você é um engenheiro de nuvem para uma empresa de varejo. Você precisa decidir se deseja usar uma nuvem pública ou privada.
 
Qual é a vantagem de usar uma nuvem pública sobre uma nuvem privada?
>Os custos são mais baixos e distribuídos entre vários inquilinos.

---

###### #37
Para completar a frase, selecione a opção apropriada no menu suspenso.

"Computação em nuvem" é a entrega de serviços de computação, como poder de computação, armazenamento, software e análise pela Internet.
>"Computação em nuvem"

---

###### #38
Corresponda cada metodologia do Azure Cloud Adoption Framework (CAF) com sua descrição.

Para responder, arraste a metodologia apropriada para cada descrição. Uma metodologia pode ser usada uma vez, mais de uma vez, ou não.

Defina a justificativa do negócio e os resultados esperados da adoção:
>Estratégia

Alinhe planos de adoção acionáveis com resultados de negócios: 
>Planeje

Prepare o ambiente de nuvem para as mudanças planejadas: 
>Pronto
 
Desenvolva novas soluções nativas da nuvem ou híbridas: 
>Inove

---

###### #39
Para completar a frase, selecione a opção apropriada no menu suspenso.
"Disaster Recovery" é a capacidade de restaurar um serviço de nuvem após uma perda catastrófica.
>"Disaster Recovery"
 
---

###### #40
Você gerencia uma equipe de desenvolvimento que precisa concentrar todos os seus esforços na criação e manutenção do código do aplicativo.
Sua equipe não tem recursos para provisionar e dimensionar a infraestrutura de seus aplicativos requerem para rodar.

O que você deveria fazer?
>Crie uma assinatura do Azure Functions e carregue seu código.

---

###### #41
Para completar a frase, selecione a opção apropriada no menu suspenso.
Com "Single Sign-on (SSO)", os usuários podem acessar todos os aplicativos necessários sem precisar autenticar uma segunda vez.
>"Single Sign-on (SSO)"
 
---

###### #42
Você precisa entender as opções de monitoramento do Azure.

Qual recurso de monitoramento você deve usar para cada cenário? Para responder, arraste o recurso apropriado para cada cenário. Um recurso pode ser usado uma vez, mais de uma vez ou não ser usado.

Você quer saber quantas vezes seu aplicativo da web ficou indisponível durante o mês passado:
>Histórico de saúde
 
Você deseja que você e os membros de sua equipe recebam uma mensagem de texto quando a manutenção do Azure estiver planejada:
>Alertas de integridade

Você deseja exibir os recursos do Azure que estão planejados para serem preteridos:
>Avisos de saúde

---

###### #43
Para completar a declaração na área de resposta, selecione a opção apropriada no menu suspenso.

Um servidor de autenticação multifator do Azure (MFA) é necessário "para autenticação ao dar suporte a usuários localizados apenas no Active Directory (AD) local".
>"para autenticação ao dar suporte a usuários localizados apenas no Active Directory (AD) local"

---

###### #44
Para cada uma das seguintes declarações sobre os Arquivos do Azure, selecione Sim se a declaração for verdadeira. Caso contrário, selecione Não.

Os arquivos do Azure podem ser acessados usando o protocolo SMB (Server Message Block):
>Sim

Os Arquivos do Azure podem ser acessados usando o Arquivo de Rede Protocolo do sistema (NFS):
>Sim

Uma assinatura de acesso compartilhado (SAS) é necessária para acessar os Arquivos do Azure:
>Não

---

###### #45
Quais duas soluções você deve usar para transferir um disco rígido virtual (VHD) local para o Azure?
Cada resposta correta apresenta uma solução completa.

>AzCopyName

>Explorador de Armazenamento do Azure

---

###### #46
Uma empresa está revisando a segurança para máquinas virtuais (VMS) implantadas em sua nuvem híbrida.

Você precisa identificar os recursos de segurança fornecidos por meio do Microsoft Defender for Cloud.

Para cada uma das seguintes afirmações, selecione Sim se a afirmação for verdadeira. Caso contrário, selecione Não.

O Microsoft Defender for Cloud oferece suporte ao monitoramento, segurança recomendações e proteção avançada contra ameaças para recursos de máquina virtual (VM) na nuvem e local:
>Sim

O Microsoft Defender for Cloud fornece integração nativa com o Microsoft Defender Antivirus no Windows:
>Sim

O suporte do Microsoft Defender for Cloud está limitado ao Windows operacional apenas sistemas:
>Não

O Microsoft Defender for Cloud pode descobrir e avaliar automaticamente a segurança de novos recursos do Azure à medida que são implantados:
>Sim

---

###### #47
Para completar a declaração na área de resposta, selecione a opção apropriada no menu suspenso.

Uma Iniciativa do Azure "é uma coleção de políticas do Azure direcionadas para atingir uma única meta geral".
>"é uma coleção de políticas do Azure direcionadas para atingir uma única meta geral"

---

###### #48
Você está planejando usar o Azure para a infraestrutura de nuvem da sua empresa. Você acabou de saber que o Azure oferece suporte a ofertas de software como serviço (SaaS), plataforma como serviço (PaaS) e infraestrutura como serviço (IaaS).

Você precisa determinar os recursos que estão disponíveis para cada categoria.
Qual recurso cada tipo de infraestrutura disponibiliza? Para responder, selecione o recursos dos menus suspensos.

>SaaS: Outlook

>PaaS: Banco de Dados SQL do Azure

>IaaS: Máquina Virtual (VM)
