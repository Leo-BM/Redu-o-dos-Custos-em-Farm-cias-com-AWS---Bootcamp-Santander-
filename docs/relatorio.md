RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS
Data: 29 de dezembro de 2025 Empresa: Abstergo Industries Responsável: Leonardo Bento Maria

Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Leonardo Bento Maria. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos e modernizar a plataforma da farmácia virtual.

Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas. A estratégia foca no modelo Pay-as-you-go (pagamento por uso), eliminando gastos com servidores ociosos durante a madrugada.

Etapa 1:

Nome da ferramenta: AWS Lambda

Foco da ferramenta: Computação Serverless (Sem servidor).

Descrição de caso de uso: Migração das APIs de processamento de pedidos para funções Lambda. Em vez de manter um servidor EC2 ligado 24h para processar vendas, a farmácia só pagará pelos milissegundos em que um cliente estiver finalizando uma compra. Isso reduz o custo operacional em horários de baixo movimento.

Etapa 2:

Nome da ferramenta: Amazon S3 (Simple Storage Service)

Foco da ferramenta: Armazenamento de Objetos escalável e de baixo custo.

Descrição de caso de uso: Armazenamento de imagens dos produtos, bulas em PDF e fotos de receitas médicas enviadas pelos clientes. O S3 substitui o uso de discos rígidos caros (EBS), permitindo pagar apenas pelos GBs armazenados e oferecendo alta durabilidade.

Etapa 3:

Nome da ferramenta: Amazon DynamoDB

Foco da ferramenta: Banco de dados NoSQL totalmente gerenciado.

Descrição de caso de uso: Armazenamento do catálogo de produtos e carrinhos de compras. Por ser serverless, o DynamoDB escala automaticamente durante promoções da farmácia e reduz custos em períodos de inatividade, além de não exigir manutenção de infraestrutura de banco de dados.

Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado a redução de até 60% nos custos fixos de infraestrutura, além de aumentar a eficiência e a produtividade da equipe de TI, que não precisará mais gerenciar servidores manuais. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias, como o AWS CloudFront, para melhorar ainda mais os processos e a velocidade de entrega do site.

Responsável pelo Projeto: Leonardo Bento Maria
