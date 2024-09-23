## Resumo-do-lab-VM<br/>

### Laboratório GIO 

## SLA
### O que é SLA
SLA é um sigla cujo significado, em inglês, é Service Level Agreement. Em português, a sigla correspondente é ANS, que quer dizer Acordo de Nível de Serviço.
Basicamente, o SLA é um documento que formaliza os termos referente ao serviço realizado entre as duas partes envolvidas, a empresa contratada e o contratante,
ou seja, define as normas a respeito de prazos, direitos e deveres, além de outros aspectos importantes relativos ao serviço.<br/>
Através do SLA definimos métricas como tempo de atividade, tempo de entrega, tempo de resposta e tempo de resolução, tempo de inatividade.<br/><br/>
Segue exemplo abaixo, tabela contendo os valores de SLA por tempo de inatividade aceitável conforme a Azure:<br/>


<img src="https://unascimento.wordpress.com/wp-content/uploads/2020/01/azureresilienceservices4.png" alt="Valores de SLA azure"><br/><br/>

## Tipos de armazenamento com redundância 

### LRS
LRS, ou Locally Redundant Storage, é um tipo de replicação de dados do Azure que copia os dados três vezes em um mesmo datacenter. É a opção de replicação padrão e está disponível para todos os tipos de conta de armazenamento.

### GRS
GRS é a sigla para Geo redundant storage ou armazenamento com redundância geográfica, que é um recurso do Azure Storage. O GRS é um método de armazenamento de dados que oferece uma durabilidade de pelo menos 99,99999999999999% (dezesseis noves) ao ano.

### ZRS
ZRS (Zone Redundant Storage) é uma opção do Azure que permite aumentar a disponibilidade de cargas de trabalho críticas, permitindo que os discos tolerem falhas zonais. 
O ZRS replica os dados em três zonas de disponibilidade (AZ) dentro da mesma região, de forma síncrona, o que significa que a gravação e a replicação são feitas imediatamente. Isso garante que os dados estejam disponíveis mesmo que um ou dois datacenters falhem.

### GZRS
A redundância de zona geográfica (GZRS) é uma opção de armazenamento de dados no Azure que combina a proteção contra interrupções regionais com a alta disponibilidade.<br/><br/>

Segue links de referência para uma explicação mais detalhada:

[Regiões, zonas de disponibilidade e redundâncias de armazenamento no Microsoft Azure](https://azuretar.com/portuguese-regioes-zonas-de-disponibilidade-e-redundancias-de-armazenamento-no-microsoft-azure/)<br/>
[Redundância de Armazenamento no Azure](https://www.linkedin.com/pulse/redund%C3%A2ncia-de-armazenamento-azure-dreher-bonfim/)






