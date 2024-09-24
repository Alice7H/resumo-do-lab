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
