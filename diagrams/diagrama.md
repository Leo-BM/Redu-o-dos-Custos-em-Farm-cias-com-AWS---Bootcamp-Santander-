Arquitetura Serverless - Farmácia Virtual Abstergo Industries

Este diagrama representa o fluxo de dados e a integração entre os serviços AWS selecionados para a otimização de custos e escalabilidade da plataforma.

Descrição do Fluxo

Acesso: O cliente acessa a interface da farmácia.

Arquivos Estáticos (S3): As fotos dos medicamentos e os PDFs das bulas são carregados diretamente do Amazon S3, reduzindo a carga nos servidores.

Processamento (Lambda): Quando o cliente finaliza uma compra ou anexa uma receita, o API Gateway aciona uma função AWS Lambda.

Banco de Dados (DynamoDB): A função Lambda valida o estoque e registra a transação no Amazon DynamoDB.

Segurança: Toda a comunicação entre esses serviços é controlada por regras do IAM (Identity and Access Management).

Relatório de Arquitetura criado por Leonardo Bento Maria.
