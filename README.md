# Desafio: Microsoft Azure - Localizando Serviços por Categoria
No laboratório, descobri como ajustar as configurações do portal Azure, incluindo a mudança de idioma e a personalização da interface por meio das exibições de inicialização no menu. Além disso, explorei a seção "Todos os serviços", que agrupa as categorias de funcionalidades fornecidas pela plataforma. Familiarizei-me com os serviços principais nas áreas de Computação, Redes e Armazenamento. Também foi abordada a questão das versões em prévia e sua influência no SLA (Acordo de Nível de Serviço).

# Benefícios da Nuvem - Criando máquinas Virtuais na Azure

O resumo da aula abordou o conceito de SLA (Service Level Agreement) e o impacto do tempo de inatividade, que pode ser medido semanalmente, mensalmente e anualmente. Quanto mais “nove” houver na métrica do SLA, menor será o tempo de inatividade; por outro lado, menos “nove” significa maior tempo de inatividade.

Ao criar uma arquitetura no Azure, é essencial entender qual SLA se aplica, dependendo do tipo de requisição que será feita. Por exemplo, ao configurar uma máquina virtual, a opção de disponibilidade escolhida afetará diretamente o SLA e o tempo de inatividade.

Em relação ao armazenamento, a escolha de redundância (LRS, GRS, ZRS, GZRS) implica que os dados serão replicados entre datacenters ou regiões. Essa replicação influencia o SLA: quanto mais replicações houver, maior será o tempo de disponibilidade, pois os mesmos dados estarão acessíveis em vários locais ao mesmo tempo. É importante notar que isso também impactará nos custos associados ao serviço.

# Configurando uma instância de Banco de Dados na Azure

Durante o desenvolvimento do laboratório, adquiri conhecimento sobre a criação e configuração de uma máquina virtual (VM). Realizei etapas como a adição de um grupo de recursos, definição do nome da VM, seleção da região, configuração das opções de disponibilidade e escolha do tamanho ideal para a máquina. Também ajustei a rede, especificando a rede virtual (VNet) e definindo as opções para remover automaticamente a VM, IP público e NIC quando a máquina for excluída, mantendo essa configuração habilitada.

No ambiente de trabalho do Azure, aprendi a criar e gerenciar um pool de hosts.

No módulo de aplicativos de funções, explorei a criação de um aplicativo de função, atribuindo um nome, selecionando entre código ou imagem de contêiner (mantendo a opção de código ativa), especificando a linguagem de programação na configuração de runtime e, por fim, configurando o plano de hospedagem para o aplicativo.
