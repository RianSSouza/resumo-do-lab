# resumo-do-lab
"Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO".

## Benefícios da nuvem
Neste lab consegui aprender quais são os benefícios da nuvem e o que são:
  - Alta disponibilidade;
  - Escalabilidade;
  - Elasticidade;
  - Confiabilidade;
  - Previsibilidade;
  - Segurança;
  - Governança;
  - Gerenciabilidade.

Também aprendi o que é SLA(Service Level Agreement) e como isso é importante para a empresa.

## Tipos de Nuvem

"Neste lab pude aprender a diferença de **IaaS**, **PaaS**, **SaaS** entendo o nível de gerenciamento e flexibilidade de cada um."
  - Infraestrutura como serviço: fornece a infraestrutura básica.
  - Plataforma como serviço: focado no desenvolvimento.
  - Software como serviço: utilização do software.

## Regiões e Grupos de Recursos

"Neste lab foi visto o que são recursos, como fazer um grupo de recursos"
  - Regiões:
    * Abrangem o mundo e têm datacenters próximos.
    * Reduzem a latência e garantem conformidade de dados.
  - Zonas de disponibilidade:
    * Protegem contra falhas em datacenters.
    * Datacenters separados na mesma região com sistemas independentes.
  - Pares de Regiões:
    * Regiões separadas por pelo menos 300 milhas.
    * Replicação automática e recuperação rápida em emergências.
  - Regiões soberanas do Azure:
    * EUA Governamental: Focado em segurança para agências dos EUA.
    * Azure China: Serviços separados do Azure global, com dados mantidos na China.


  - Recursos do Azure:
    *São componentes como armazenamento, máquinas virtuais e redes usados para criar soluções na nuvem.
  - Grupos de recursos:
    * Contêiner para gerenciar recursos como uma unidade.
    * Os recursos só podem estar em um grupo, mas podem ser movidos e existir em diferentes regiões.
  - Assinaturas do Azure:
    * Fornecem acesso autenticado ao Azure.
    * Controle de cobrança e relatórios separados para cada assinatura.
    * Gerenciam o acesso aos recursos baseados em assinaturas.
  - Grupos de gerenciamento:
    * Incluem várias assinaturas do Azure.
    * Assinaturas herdam as regras aplicadas ao grupo de gerenciamento.

## Computação e Rede
  "Neste pude entender melhor alguns serviços de computação e rede do Azure"
  - Serviços de computação do Azure:
    * Fornece recursos de computação sob demanda (discos, processadores, memória, rede).
    * **Máquinas Virtuais (VMs):** Emulam computadores físicos, oferecem personalização e controle total (IaaS), útil para migrações "lift-and-shift".
  - Conjunto de dimensionamento de VMs:
    * Balanceamento de carga e dimensionamento automático de recursos.
  - Conjunto de disponibilidade de VMs:
    * Alta disponibilidade e redundância, distribuindo VMs em diferentes servidores físicos para minimizar falhas.
  - Área de trabalho virtual do Azure:
    * Virtualização de área de trabalho e aplicativos na nuvem, com várias sessões e menos necessidade de servidores de gateway.
  - Serviços de contêineres do Azure:
    * Ambientes leves e virtualizados para executar contêineres sem gerenciar o sistema operacional.
    * **Instâncias de contêiner do Azure:** PaaS para executar um contêiner ou pod de contêineres.
    * **Aplicativos de contêiner do Azure:** PaaS com balanceamento de carga e escalabilidade.
    * **Serviço de Kubernetes do Azure:** Orquestração de contêineres para grandes arquiteturas distribuídas.
  - Azure Functions:
    * Computação sem servidor (PaaS) que executa código baseado em eventos, sem necessidade de servidores durante períodos ociosos.
  - Serviços de Aplicativo do Azure:
    * Plataforma gerenciada para criar, implantar e dimensionar rapidamente aplicativos web e APIs, compatível com várias linguagens (PaaS).
  - Serviço de rede do Azure:
    * **VNet:** Conecta recursos do Azure, a internet e redes locais.
    * **Gateway de VPN:** Envia tráfego criptografado entre a rede virtual do Azure e a local.
    * **ExpressRoute:** Conexão privada entre redes locais e Azure via provedor de conectividade.
    * **DNS do Azure:** Segurança baseada em controle de acesso e monitoramento detalhado.

   ## Armazenamento 
   "Neste lab aprendi sobre como funciona o armazenamento e as possiveis migrações pro Azure"
 - Blob do Azure:
   * Armazenamento otimizado para grandes quantidades de dados não estruturados (texto, dados binários).
- Disco do Azure:
  * Fornece discos para máquinas virtuais e outros serviços.
- Fila do Azure:
  * Armazenamento de mensagens com suporte para até 64 KB por mensagem.
- Arquivos do Azure:
    * Compartilhamento de arquivos de rede altamente disponível via protocolo SMB.
- Tabelas do Azure:
    * Armazenamento de dados estruturados não relacionais, sem esquema.
- Migrações para o Azure:
  * Plataforma unificada com ferramentas para avaliação e migração.
- Azure Data Box:
  * Armazena até 80TB de dados e facilita a migração segura para o Azure.
- AzCopy:
  * Utilitário de linha de comando para copiar e sincronizar arquivos/blobs no armazenamento.
- Gerenciador de Armazenamento do Azure:
  * Interface gráfica compatível com Windows, MacOS e Linux para gerenciar o armazenamento.
- Sincronização de Arquivos do Azure:
  * Sincroniza arquivos locais e do Azure de forma bidirecional, liberando espaço com acesso a arquivos frequentes. 

 ## Identidade, Acesso e Segurança
   "Neste lab aprendi sobre como funciona as ferramentas para autenticação e autorização"
- Microsoft Entra ID:
  * Serviço de gerenciamento de identidades e acesso na nuvem.
- Autenticação:
  * Verifica a identidade de pessoas ou serviços com credenciais.
  * Base para criar identidades e controle de acesso seguros.
- Autorização:
  * Determina o nível de acesso após a autenticação.
  * Define quais dados podem ser acessados e as ações permitidas.
- Autenticação multifator:
  * Adiciona uma camada extra de segurança exigindo dois ou mais fatores de autenticação.
- Acesso condicional:
  * Controla o acesso com base em grupo, IP, dispositivo, aplicativo e detecção de risco.
- Controle de acesso baseado em função:
  * Gerencia permissões finamente, concedendo apenas o acesso necessário para a equipe.
- Proteção Completa:
  * Abordagem em camadas para proteger sistemas, isolando ataques entre camadas.
- Microsoft Defender para Nuvem:
  * Serviço de monitoramento que protege contra ameaças nos datacenters do Azure e locais.

 ## Gerenciamneto de custos
 "Neste lab aprendi sobre gerenciamneto de custos do Azure e a calculadora"
 - Gerenciamento de custos na Azure:
  * Fatores que afetam os custos: incluem tipo de recurso, consumo, manutenção, área geográfica, tráfego de rede e  assinatura.
  * Azure Marketplace: permite que os clientes encontrem, experimentem, comprem e provisionem aplicativos e serviços de provedores certificados.
  * Marcas (tags): fornecem metadados aos recursos, organizam de forma lógica e consistem em pares nome-valor, sendo úteis para informações de cobrança.

 ## Governança e Conformidade
  "Neste lab aprendi sobre paddrões e organização"
  -Governança e Conformidade:
 * Azure Policy: impõe padrões organizacionais, avalia a conformidade e oferece governança em áreas como segurança, custo e gerenciamento, identificando recursos que não      seguem as políticas.
 * Bloqueios de recursos: protegem recursos contra exclusão ou modificação acidental, podendo ser gerenciados em diferentes níveis (assinatura, grupo de recursos, etc.).
 * Microsoft Purview: solução para governança de dados que unifica a visualização de dados locais, multinuvem e SaaS.

## Ferramentas de gerenciamento e implantação
"Neste lab aprendi sobre paddrões e organização"
- Azure Arc: permite a criação de aplicativos e serviços em ambientes multinuvem.
- ARM (Azure Resource Manager): fornece uma camada de gerenciamento para criar, atualizar e excluir recursos na assinatura do Azure.
- Infraestrutura como código: garante consistência na implantação e gerencia a configuração em escala.
- Modelos ARM: arquivos JSON que permitem criar e implantar infraestrutura no Azure de forma declarativa, com resultados repetíveis, orquestração, validação integrada e   
 código exportável.
 
