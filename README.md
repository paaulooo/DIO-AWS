# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 06/08/2025
Empresa: Abstergo Industries 
Responsavel: Paulo R

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Paulo R. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos especificos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 
- Amazon EC2 Auto Scaling
- Redução de custos com servidores sob demanda
- A Abstergo possuía instâncias EC2 executando continuamente, mesmo em períodos de baixa demanda. Com o Auto Scaling, as instâncias agora sobem e descem automaticamente com base na necessidade de processamento, reduzindo custos com máquinas ociosas e otimizando recursos.

Etapa 2: 
- Amazon S3 (com S3 Intelligent-Tiering)
- Armazenamento de arquivos com custo otimizado
- Documentos, relatórios e backups da empresa estavam sendo armazenados em volumes de alto custo. Ao migrar esses arquivos para o S3 com a política de armazenamento Intelligent-Tiering, os objetos passam automaticamente para camadas de menor custo conforme o uso, economizando sem perder acesso rápido aos dados.

Etapa 3: 
- AWS Lambda
- Processamento sob demanda sem necessidade de servidores
- Tarefas rotineiras e scripts agendados, como processamento de logs ou sincronizações de banco, foram migrados para funções Lambda. Assim, a empresa não precisa manter servidores ligados 24/7 para tarefas simples, pagando apenas pelos milissegundos de execução — uma economia considerável.



## Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado a redução de custos operacionais, otimização de recursos computacionais e melhora na escalabilidade dos serviços, o que aumentara¡ a eficiencia e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos


Assinatura do Responsavel pelo Projeto:

Paulo R.
