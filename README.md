# Benefícios da computação em nuvem e criando máquinas virtuais no Azure
Resumo do módulo **"Benefícios da computação em nuvem"** e do laboratório **"Criando máquinas virtuais no Azure"** do curso **"Introdução a cloud com Azure"** da **DIO**.

## Benefícios da computação em nuvem
Existem 5 benefícios principais relacionados à computação em nuvem:

* Alta disponibilidade;
* Escalabilidade e elasticidade;
* Confiabilidade, previsibilidade e segurança;
* Governança; e
* Gerenciabilidade.

### Alta disponibilidade
Garantia da máxima disponbilidade, independentemente de interrupções ou eventos críticos que possam ocorrer.

Essa disponibilidade é garantida, no Azure, pelos *SLAs (Service Level Agreements)*, que são acordos entre as organizações e a Microsoft referentes ao tempo de indisponibilidade tolerado dentro daquele contrato de prestação de serviços de cloud. Caso o tempo de indisponibilidade supere a faixa acordada, as organizações lesadas são ressarcidas em créditos dentro do próprio Azure pela Microsoft.

### Escalabilidade e elasticidade
Referem-se à capacidade do servidor em cloud utilizado aumentar a sua oferta de armazenamento de acordo com aquilo que é demandado pelas organizações. 

Enquanto a escalabilidade se refere a um aumento pré-definido da capacidade de armazenamento de acordo com um crescimento previsível do serviço demandado, a elasticidade se refere a um aumento - ou até mesmo diminuição - flexível da capacidade de armazenamento ofertada de acordo com a demanda em tempo real (por exemplo em um evento de grandes variações no fluxo de usuários como na *Black Friday*).

### Confiabilidade, previsibilidade e segurança
Referem-se à resiliência dos serviços de nuvem. Como a nuvem é um serviço altamente descentralizado, isso oferece uma grande redundância, sendo possível de alocar recursos em diversas partes do mundo e se prevenir de eventos críticos locais.

A confiabilidade também é afetada pela previsibilidade na nuvem, tanto no desempenho quanto no custo. No Azure, essa previsibilidade é influenciada pelo Microsoft Azure Well-Architected Framework.

Finalmente, um grande fator de impacto na confiabilidade é a segurança que é ofertada por meio de diversos serviços na nuvem, mas de cuja a implantação é de responsabilidade do usuário. Portanto, a garantia da segurança na nuvem é um compartilhamento de responsabilidades entre o provedor e o usuário.

### Governança
A nuvem auxilia a sinalizar quaisquer recursos alocados fora dos padrões de conformidade das organizações e ainda fornece também estratégias de mitigação dos riscos.

Com a nuvem, também existe a possibilidade da aplicação de patches e atualizações de software automáticas, o que auxilia na governança e na segurança.

### Gerenciabilidade
A nuvem oferece diversos tipos de gerenciabilidade, desde opções mais low code na prórpia plataforma web do serviço, até opções mais complexas utilizado linhas de comando ou chamadas em *APIs*. Com isso, é possível ter flexibilidade no gerenciamento dos recursos.

Pode-se, por exemplo, optar por implantar recursos com base em um modelo pré-configurado, escalar automaticamente a partir da demanda etc.

## Primeiros passos na criação de máquinas virtuais no Azure
No laboratório foram exploradas as escolhas de opções de disponibilidade na criação de uma máquina virtual no Azure. Existem três opções disponíveis:
* **Por Zona de Disponibilidade:** Separa fisicamente os recursos em uma região do Azure;
* **Por conjunto de dimensionamento de máquinas virtuais:** Distribui as máquinas virtuais entre zonas e domínios de falha em escala; e
* **Por conjunto de máquinas virtuais:** Distribui as máquinas virtuais automaticamente entre vários domínios de falha.

Dentro de cada uma dessas opções existem configurações a serem escolhidas de modo a determinar qual será o *SLA*.
