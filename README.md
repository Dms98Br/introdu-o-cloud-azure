# Desafio: Microsoft Azure - Localizando Serviços por Categoria
No laboratório, aprendi que nas configurações do portal, é possível alterar o idioma no Azure. Além disso, ao acessar a opção de exibições de inicialização do menu, você pode modificar a aparência. Explorei o menu "Todos os serviços", que apresenta as categorias de funções dos serviços que o Azure oferece. Conheci os diversos serviços disponíveis nos menus de Computação, Redes e Armazenamento. Ela também comentou sobre a versão prévia em relação ao SLA.

# Benefícios da Nuvem - Criando máquinas Virtuais na Azure

O resumo da aula abordou o conceito de SLA (Service Level Agreement) e o impacto do tempo de inatividade, que pode ser medido semanalmente, mensalmente e anualmente. Quanto mais “nove” houver na métrica do SLA, menor será o tempo de inatividade; por outro lado, menos “nove” significa maior tempo de inatividade.

Ao criar uma arquitetura no Azure, é essencial entender qual SLA se aplica, dependendo do tipo de requisição que será feita. Por exemplo, ao configurar uma máquina virtual, a opção de disponibilidade escolhida afetará diretamente o SLA e o tempo de inatividade.

Em relação ao armazenamento, a escolha de redundância (LRS, GRS, ZRS, GZRS) implica que os dados serão replicados entre datacenters ou regiões. Essa replicação influencia o SLA: quanto mais replicações houver, maior será o tempo de disponibilidade, pois os mesmos dados estarão acessíveis em vários locais ao mesmo tempo. É importante notar que isso também impactará nos custos associados ao serviço.
