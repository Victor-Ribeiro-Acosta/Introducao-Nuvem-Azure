# Introdução a Nuvem

### O que é Nuvem

A nuvem, como conhecemos, é definida cientificamente com "Nuvem é um conjunto visível de partículas diminutas de gelo ou água em seu estado líquido ou ainda de ambos ao mesmo tempo, que se encontram em suspensão na atmosfera, após terem se condensado ou liquefeito em virtude de fenómenos atmosféricos".
Em tecnologia, a nuvem refere-se ao comjunto de recursos computacionais asseciveis via internt, como hardwares, plataformas, softwares, entre outros. Os serviços de nuvem e seus recursos ficam armazenados em locais planejados para sua plena funcionalidade, chamados Datacenters.
Os serviços de nuvem tem, como carecterística, serem escaláveis e flexíveis, podendo atender a diversas necessidades, além disso, muitas nuvens permitem o pagamento via recurso utilizado, ou seja, você paga apenas pelo recurso que vai usar e pelo tempo que necessitar.

### Tipos de Nuvem

**Nuvem Privada:** É aquela cujo Datanceter é criado e e mantido por uma empresa ou organização, onde apenas os usuarios da organização tem acesso aos seus recursos (salvo exceções), ou seja, seus recursos são usados apenas para as necessidades da empresa ou organização que a mantém.
**Nuvem Pública:** É aquela criada por uma empresa, cujos recursos e serviços são disponibilizados para usuarios de outras empresas, onde essas pagam pelos serviços utilizados.
**Nuvem Híbrida:** É quando uma organização dispõe dos dois tipos de nuvem, a pública e a privada, para o desenvolvimento de suas aplicações.

#### Vantagens da Nuvem Pública
- Pagamento conforme o uso.
- Acesso a diversos recursos, pagando apenas aqueles que utilizar.
- Acesso a diversas ferramentas de segurança.
- Garantia de recursos e funcionamento da aplicação via contratos SLA.
- Garantia de recursos escaláveis e flexíveis de maneira facilitada.

#### Desvantagens da Nuvem Pública
- Falta de controle sobre a criação, inflantação e planejamento dos recursos (ex. um recurso não lhe atende da forma como queria, não é possível altera-lo).

#### Vantagens da Nuvem Privada
- Maior controle da organização sobre os recursos e serviços da nuvem.
- Garantia de disponibilidade do serviço a organização.
- Sem necessidade dos usuarios pagarem pelos recursos.
- Maior segurança pelos servidores estarem "dentro" da organização.

#### Desvantagens da Nuvem Privada
- A organização é responsável pela implantação e manutenção do datacenter.
- A organização é responsável pela aquisiçao de mais recursos computacionais quando necessário, além de arcar com os custos gerados.
- A organização é responsável pela segurança, governaça e garantida dos recursos da nuvem.


## CapEx X OpEx

### Despesas de Capital - CapEx
É o capital de uma empresa ou organização, usado para adquirir, manter ou aprimorar seus espólios fixos.

### Despesas Operacionais - OpEx
É o capital de uma empresa ou organização utilizado para despesas fixas, como manutenção, aluguel, etc.

## Vantagens em Relação a Nuvem

 CapEx é indicado para empresas que tem uma exigencia orçamentária, ou seja, aquelas que possuem uma demanda que os recursos de uma nuvem pública não podem atender e possuem recursos para implementar seus próprios serviços
 OpEx está relacionada aos custos operacionais do uso das nuvens públicas, indicado para empresas que possuem alta demanda e não possuem capital para implementação de uma nuvem privada.

# Benefícios da Nuvem

## Alta Disponibilidade
Os recursos em nuvem são flexíveis e escaláveis, sendo garantido sua disponibilidade mesmo em casos de interrupção da funcionalidade por qualquer motivo.
Essa disponibilidade é garantida por meio de um contrato de SLA, onde é previsto o tempo mínimo de interrupção que o sistema pode apresentar. Caso o sistema ou recurso fique indisponível por um período maior que o previsto pelo contrato, o proprietario da nuvem oferece créditos para compensar o usuario lesado.

## Escalabilidade
A nuvem permite a adição de recursos adicionais para aumentar o desempenho da aplicação em momentos de grande acesso, sendo pagos apenas pelo período em que forem usados. O usuario pode remover esses recursos quando não forem mais necessários sem nenhum onus adicional.

## Elasticidade
É a capacidade dos recursos serem aumentados ou diminuidos diante da demanda, sendo feita de maneira manual ou automática.

## Confiabilidade
Os recursos de grandes nuvens, com a Azure, são internacionalmente descentralizados, isso significa que os recursos de uma determinada região ficam concentrados nos datacenters localizados na mesma região.
Isso permite a resiliencia de sistemas, que nada mais é do que acionar os recursos de outro datacenter mais próximo quando os recursos do datacenter atual forem comprometidos (com uma inundação ou terremoto, por exemplo). Isso garante que os recursos estejam sempre disponíveis para o usuario, mesmo em momentos adversos.

## Previsibilidade
Permite o avanço nos processos e no sistema com segurança no desempenho e no custo. A Azure fornece uma calculadora que permite analisar o custo gerado quando um recursos for usado ou ampliado.

## Segurança
A nuvem oferece diversas ferramentas de segurança contra ações mal intensionadas e as disponibiliza aos usuarios, contudo, as empresas gerenciadoras da nuvem não se comprometem com a aplicação dessas ferramentas, sendo de responsabilidade do usuario contratar e gerenciar o uso dos recursos de segurnaça.

## Governança
São padrões e normas usados para gerenciar os recursos da nuvem, garantindo a confiabilidade e a segurança do uso desses recursos.

## Gerenciabilidade
São as formas de gerenciar os recursos e suas implantações. No Azure, isso pode ser feito via protal do Azure, onde é possível criar, implantar e gerenciar recursos de maneira fácil e intuitiva. Contudo, também é possivel criar e gerenciar recursos via linha de comando.
