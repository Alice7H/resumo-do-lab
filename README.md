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

## Responsabilidade compartilhada

Na nuvem privada tudo é de responsabilidade das organizações.
Na nuvem pública em geral, o fornecedor de nuvem é responsável pela segurança da infraestrutura, enquanto o cliente é responsável pela segurança das áreas da infraestrutura de nuvem sobre as quais tem controle. As responsabilidades da carga de trabalho variam dependendo se a carga de trabalho está hospedada no SaaS (software como serviço), na PaaS (plataforma como serviço), na IaaS (infraestrutura como serviço) ou em um data center local.

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
