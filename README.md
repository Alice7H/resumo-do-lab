# Resumo do lab

Repositório com o resumo das lições sobre computação em nuvem do lab na DIO

## O que é computação em nuvem?

É o fornecimento de serviços de computação pela internet, habilitando inovações mais rápidas, recursos flexíveis e economias de escala.
Exemplo: uso de data centers (servidor de bd, servidor de intranet, servidor de aplicação, servidor firewall).

## Modelos de nuvem

Falamos sobre 3 modelos, mas também temos o modelo multi-cloud (AWS + Azure), que é o uso de diferentes serviços de computação em nuvem trabalhando em paralelo.

### Nuvem privada

Resumo: São as próprias infraestruturas montadas e configuradas nas organizações.

As organizações criam um ambiente em nuvem em seu data center.
Elas são responsáveis por operar os serviços que fornecem.
Não fornece acesso aos usuário fora da organização.

### Nuvem pública

Resumo: São diversos data centers espalhados pelo mundo que provisionam serviços por determinado preço.

Nuvem pública pertence a serviços de nuvem ou provedor de hosting.
Fornece recursos e serviços a várias organizações e usuários.
Acessada via conexão de rede segura (geralmente pela internet);

### Nuvem híbrida

Combina nuvens públicas e privadas para permitir que os aplicativos sejam executados no local mais adequado. Podem trabalhar em conjunto e até fazendo a comunicação entre esses serviços.

## Comparação de Modelos de nuvem

### Em nuvem pública

- Não possui despesa de capital para escalar verticalmente (ampliação)
- Os aplicativos podem ser provisionados e desprovisionados rapidamente
- As organizações pagam pelo que usam

### Em nuvem privada

- As organizações têm controle total sobre os recursos e a segurança;
- As organizações são responsáveis pela manutenção e atualizações de hardware e software.

### Em nuvem híbrida

- As organizações determinam onde executar seus aplicativos
- As organizações controlam a segurança, a conformidade e os requisitos legais.
- Fornece maior flexibilidade.

## Comparação entre CapEx e OpEx

### CapEX - capital expenditure

Despesas de capital ou investimento a longo prazo (despesa com aquisição de ativos).

- Trata-se do gasto inicial de dinheiro em infraestrutura física.
- As despesas do CapEx têm um valor que se reduz com o tempo.
Exemplo: Cabeamento, máquinas, ar-condicionado, licença de softwares.

### OpEx - operational expenditure ou despesas operacionais diárias

Envolvem pagamentos relativos à atividade de gestão empresarial e venda de produtos e serviços.

- Gastar com produtos e serviços conforme necessário, pagamento conforme o uso.
- Seja cobrado imediatamente.
Exemplo: Energia elétrica, serviços, taxas de licença.

## Modelo baseado em consumo

Os provedores de serviços em nuvem operam em um modelo baseado no consumo, o que significa que os usuários finais pagam somente pelos recursos que usam.

- Possui melhor previsão de custos
- São fornecidos preços para recursos e serviços individuais
- A cobrança é feita com base no seu uso real.

## Serviços do Microsoft Azure

- A conta gratuita pode ter limitações de disponibilidade de serviços/recursos.
- Nas configurações, podemos trocar idiomas, aparência e exibições de inicialização do Portal do Microsoft Azure.
- No painel, podemos visualizar serviços por categoria, tais como: IA + Machine Learning, análises, computação, contêineres, banco de dados, DevOps, geral, híbrido + multinuvem, identidade, integração, IOT (internet das coisas), gerenciamento e governança.
- Na categoria Computação temos várias opções de serviços de IaaS, PaaS, serviços sem servidor e microsserviços, computação de alto desempenho e nuvem híbrida.
- Em Redes, temos os Bastions, endereços de IP, gateway NAT, link privado, zonas DNS, ExpressRoute, peerings (emparelhamento de redes), firewalls, balanceadores de carga.
- Bastions fornece uma maneira segura para acessar máquinas virtuais, semelhante a um jump server.
- Jump server: é um computador em uma rede tipicamente utilizado para gerenciar dispositivos em uma zona de segurança separada, responsável por canalizar tráfego através de firewalls usando um canal seguro supervisionado.
- A parte de Armazenamento possui recursos de servidores, discos, migrações.
- A versão prévia não possui garantias, pode-se dizer que está em modo de teste, ou seja, deve ser usado com cautela.
- Service Level Agreement ou Acordo de Nível de Serviço ou Garantia de Nível de Serviço é um termo que diz respeito aos serviços utilizados. Um compromisso por um prestador de serviço que estabelece os direitos e obrigações entre o contratado e o contratante.

## Benefícios da Nuvem Azure

A computação em nuvem oferece diversas vantagens como a diminuição da necessidade de investimento em infraestrutura física, como servidores e equipamentos de armazenamento, mas isso não é tudo, exitem outros ganhos:

### Alta disponibilidade

Se concentra em garantir a disponibilidade máxima, independentemente de interrupções ou eventos que possam ocorrer. Se um serviço extrapolar o tempo de indisponibilidade, por exemplo, o SLA garante créditos.

### Escalabilidade

- A escalabilidade refere-se à capacidade de **ajustar recursos para atender à demanda**.
- A capacidade de escalar significa que você poderá adicionar mais recursos para lidar melhor com o aumento da demanda.
- Com a escalabilidade você não paga além do necessário pelos serviços. Paga pelo que usa.
- Se a demanda cair, você poderá reduzir seus recursos, reduzindo custo consequentemente.
- Com a escala vertical, se você tivesse desenvolvendo um aplicativo e precisasse de mais capacidade de processamento, poderia escalar verticalmente para adicionar mais CPUs ou RAM à máquina virtual.

### Elasticidade

- Elasticidade é a capacidade de expandir ou diminuir **rapidamente** os recursos de armazenamento, memória, processamento do computador.
- Com a elasticidade, se você experimentasse um salto repentino acentuado na demanda, seus recursos implantados poderiam ser expandidos (automaticamente ou manualmente).
- Exemplo: adicionar máquinas virtuais ou contêineres por meio da expansão.
- Se houver queda significativa na demanda, os recursos implantados poderão ser reduzidos horizontalmente (de maneira automática ou manual).

A escalabilidade trata de aumentar o uso de recursos com o tempo, o crescimento e demanda do negócio. Ela trata de altos e baixos na demanda

### Confiabilidade

- Confiabilidade: ser **resiliente**, devido a design descentralizado, a nuvem dá suporte a uma infraestrutura confiável, com recursos implantados em várias regiões do mundo.
- Se recupera de falhas e ter redundâncias de informações criam ambientes confiáveis.
- Com essa escala global, mesmo que ocorra um evento catastrófico em uma região, as outras regiões ainda estarão em funcionamento.

### Previsibilidade

- Previsibilidade: permite que você avance com **confiança**, seja no desempenho ou no custo.
A **previsibilidade de desempenho** se concentra em prever os recursos necessários para oferecer uma experiência positiva aos clientes.
A **previsibilidade de custos** se concentra em prever o custo dos gastos com a nuvem. Com a nuvem, você pode acompanhar o uso de recursos em tempo real, monitorar os recursos para garantir a maior eficiência de uso possível e aplicar a análise de dados para encontrar padrões e tendências que ajudam a planejar melhor as implantações de recursos. Operando na nuvem e usando a análise e as informações da nuvem, você pode prever custos futuros e ajustar os recursos conforme o necessário. Você pode até mesmo usar ferramentas como TCO (custo total de propriedade) ou a Calculadora de Preços para obter uma estimativa de possíveis gastos com a nuvem.

O Microsoft Azure Well-Architected Framework é um conjunto de princípios orientados à qualidade, pontos de decisão de arquitetura e ferramentas de revisão destinados a ajudar arquitetos de soluções a construir uma base técnica para suas cargas de trabalho que pode influenciar essa previsibilidade de desempenho e custo.

### Segurança

- Segurança: **a nuvem oferece ferramentas de segurança** que atendem às necessidades dos clientes mas, é importante lembrar que a **implementação** de muitas delas devem ser realizadas pelo **cliente**.
Exemplo: setor de infraestrutura de uma empresa criar apólices para painel de controle e prompt de comando.
- Se você quiser o controle máximo da segurança, a infraestrutura como serviço fornecerá recursos físicos, mas permitirá que você gerencie os sistemas operacionais e o software instalado, incluindo aplicação de patches e manutenção.

### Governança

- Governança: são padrões adotados pela empresa, ato de verificar se as atividades estão de acordo com o planejado.
- A **auditoria** baseada em nuvem ajuda a sinalizar qualquer recurso que esteja fora de conformidade com seus padrões corporativos e fornece estratégias de mitigação (resolução de problema).
- Dependendo do modelo operacional, patches de software e atualizações também podem ser aplicados automaticamente, o que ajuda na governança e na segurança.
- Ao estabelecer uma presença de governança o mais cedo possível, você poderá manter sua presença de nuvem atualizada, protegida e bem gerenciada.

### Gerenciabilidade

Há dois tipos de capacidade de gerenciamento para computação em nuvem, o gerenciamento **da nuvem** diz respeito a gerenciar seus recursos de nuvem e o gerenciamento **na nuvem** diz respeito à maneira de gerenciar seu ambiente de nuvem e seus recursos.

Gerenciamento da nuvem:

- Escalar automaticamente a implantação de recursos com base na necessidade.
- Implantar recursos com base em um modelo pré-configurado, removendo a necessidade de configuração manual.
- Diz respeito à capacidade de gerenciar eficazmente os recursos de TI, monitorar o desempenho, aplicar políticas de segurança e realizar manutenção.

Gerenciamento na nuvem:

- Pode ser feito por meio de um portal da Web.
- Usando uma interface de linha de comando.
- Usando APIs.
- Usando o PowerShell

## Disponibilidade em máquinas virtuais e armazenamento

  Ao criar uma máquina virtual, temos algumas opções para manter a disponibilidade desse serviço, isso envolve algumas estratégias e o SLA.

### SLA e o tempo de inatividade

Informações obtidas através do Bootcamp XP Fullstack na DIO:

- 99% => 1.68h de inatividade por semana , 7.2h por mês e 3.65dias por ano.
- 99.95% => 10.1 minutos por semana, 43.2min por mês e 8.76h por ano;
- 99.95% => 5 minutos por semana, 21.6min por mês e 4.38h por ano;
- 99.99% => 1.01 minutos por semana, 4.32min por mês e 52.56min por ano;
- 99.999% => 6 segundos por semana, 25.9segundos por mês e 5.26min por ano;

A porcentagem depende do SLA, por isso é importante saber o tempo de inatividade aceitável para o serviço desejado e futuros planejamentos na área de arquitetura de sistemas.

### Opções de disponibilidade

As zonas de disponibilidade expandem o nível de controle necessário para manter a disponibilidade dos aplicativos e dados em suas VMs. Pode proteger os aplicativos e dados de interrupções de data centers e eventos de manutenção.

- Nenhuma redundância infraestrutura necessária
- Zona de disponibilidade - separa fisicamente seus recursos em uma região
- Conjunto de dimensionamento de máquinas virtuais - distribui Vms entre zonas e domínios de falha em escala
- Conjunto de disponibilidade - distribui Vms automaticamente entre vários domínios de falha

### Zona de disponibilidades

Uma Zona de Disponibilidade é uma zona fisicamente separada, dentro de uma região do Azure. Há três zonas de disponibilidade por região do Azure com suporte.
Ao escolher fazer isso, o disco gerenciado e o IP público (caso tenha um) serão criados na mesma zona de disponibilidade da máquina virtual.

Cada Zona de Disponibilidade tem uma fonte de energia, uma rede e um sistema de refrigeração distintos. Ao projetar suas soluções para usar VMs replicadas em zonas, você pode proteger seus aplicativos e dados contra a perda de um data center. Se uma zona estiver comprometida, os aplicativos e dados replicados estarão instantaneamente disponíveis em outra zona.

### Redundância de armazenamento

Criar contas de armazenamento também afeta na disponibilidade de dados e temos opções de redundância que são: LRS, GRS, ZRS e GZRS.

#### Armazenamento com redundância local (LRS)

Esta opção tem custo mais baixo, com proteção básica contra falhas de drive e de rack do servidor, mas não é recomendada para aplicativos que exigem alta disponibilidade ou durabilidade.
O LRS copia dados de forma síncrona três vezes em um único local físico na região primária. Recomendada para cenários não críticos.

#### Armazenamento com redundância geográfica (GRS)

Opção intermediária com funcionalidades de failover em uma região secundária. Recomendada para cenários de backup. GRS copia seus dados de forma síncrona três vezes em um único local físico na região primária usando o LRS, e depois copia seus dados de forma assíncrona para um único local físico em uma região secundária.

Failover é uma técnica de recuperação de desastres que permite que sistemas e redes continuem a funcionar mesmo quando há falhas ou interrupções. Ela funciona de forma automática, transferindo a operação de um sistema ou componente para um  backup ou standby.

#### Armazenamento com redundância de zona (ZRS)

O ZRS é recomendado para aplicativos que exigem alta disponibilidade, como clustering para cargas de trabalho SAP e SQL Server, aplicativos de contêiner e aplicativos herdados. É uma opção intermediária com proteção contra falhas no nível do data center.
Ele replica a conta de armazenamento de modo síncrono em três zonas de disponibilidade do Azure na região primária. Cada zona é um local físico separado.

#### Armazenamento com redundância de zona geográfica (GZRS)

Solução de proteção de dados ideal que inclui as redundância entre zonas e proteção contra interrupções regionais fornecidas pela replicação geográfica. Recomendada para cenários de dados críticos.

## Tipos de Serviços de Nuvem na Azure

Não apenas na Azure, como em todos os outros serviços em nuvem, existem três modelos:

### IaaS

Infraestrutura como serviço - dispõe sob demanda de recursos de computação altamente escalonáveis como serviços pela internet. Ela elimina a necessidade de as empresas adquirirem, configurarem ou gerenciarem infraestrutura. É o mais utilizado e o que mais precisa ser configurado em questões de servidores, armazenamento, segurança, monitoramento, backup.

### PaaS

Plataforma como serviços - fornece um ambiente para a criação, o teste e a implantação de aplicativos de software, com recursos que permitem oferecer desde aplicativos simples baseados em nuvem até sofisticados aplicativos empresariais sem focar no gerenciamento da infraestrutura subjacente.

### SaaS

Software como serviço permite se conectar e usar aplicativos baseados em nuvem pela internet; são os apps hospedados.Exemplos comuns são email, calendário e ferramentas do office. Possui configurações mais básicas e está baseado em recursos determinados na licença de serviço.

## Modelo de responsabilidade compartilhada

Na nuvem privada ou modelo on-premise, o servidor é físico, ou seja toda a responsabilidade torna-se do cliente ou empresa que a detém.

Na nuvem pública em geral, o fornecedor de nuvem é responsável pela segurança da infraestrutura, enquanto o cliente é responsável pela segurança das áreas da infraestrutura de nuvem sobre as quais tem controle. As responsabilidades da carga de trabalho variam dependendo se a carga de trabalho está hospedada no SaaS (software como serviço), na PaaS (plataforma como serviço), na IaaS (infraestrutura como serviço) ou em um data center local.

No modelo IaaS, os provedores são responsáveis pelo data center físico, a rede física e os hosts físicos. O resto é de responsabilidade do cliente.

No modelo PaaS, responsabilidades como cuidados com controle de rede, aplicativos e infraestrutura de identidade e diretório são do provedor e do cliente.

No modelo SaaS, as responsabilidades do cliente são sobre as informações e dados, dispositivos, contas e identidades, e em partes da infraestrutura de identidade e diretório.

[Modelo de Responsabilidade Compartilhada](./responsabilidade_compartilhada.png)

## Comparação do serviço de nuvem

IaaS é mais flexível, você configura e gerencia o hardware para seu aplicativo. Citando Stan Lee, Com grandes poderes vêm grandes responsabilidades.

PaaS focado no desenvolvimento de aplicativos e banco de dados, o gerenciamento de plataforma é realizado pelo provedor de nuvem.

SaaS ressalta o modelo de preço de pagamento conforme uso, os usuários pagam pelo software que utilizam em um modelo de assinatura.

## Máquina virtual

Na categoria máquina virtual, é possível visualizar a grande quantidade de detalhes de configurações na criação e ao selecionar uma imagem, a opção de tamanho já fornece uma previsão de custo. Além da estrutura básicas da VM, ainda há a aba para configurações de discos, rede, gerenciamento, monitoramento, configurações avançadas, marcas, revisão e por fim, criação da VM.

## Configurando uma Instância de Banco de Dados

Usando o portal da Microsoft Azure, nas categorias, selecionamos Banco de Dados SQL.

- Selecionar a assinatura para gerenciar custos e os recursos implantados
- Selecionar grupo de recursos (pastas para organizar e gerenciar recursos)
- Informamos o nome do banco de dados
- Selecionamos o servidor ou criamos um novo caso não tenhamos nenhum

- Configuramos o servidor (mesmo sendo simbólico, pois não teremos acesso a ele pelo BD)
  - Informamos o nome do servidor
  - Selecionamos a localização do servidor
  - Selecionamos o método de autenticação do servidor
  - Definimos administrador do Microsoft Entra

- Selecione se deseja usar pool elástico SQL
- Selecione o ambiente de carga de trabalho
- Configura parte de computação + armazenamento (ex: 32gb de armazenamento, uso geral sem servidor)
- Seleciona a redundância do armazenamento de backup.

Por fim, uma previsão de custo estimado de armazenamento mensal será exibida.
