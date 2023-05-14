# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 14/05/2023
Empresa: Abstergo Industries 
Responsável: Vinícius Figueiredo Carneiro

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Vinicius Figueiredo Carneiro. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 
- AWS Auto Scaling
- Dimensionamento automático da capacidade de recursos.
-  O AWS Auto Scaling permite ajustar automaticamente a capacidade dos recursos de computação com base na demanda em tempo real. No contexto da empresa farmacêutica, podemos aplicar o Auto Scaling aos servidores de aplicativos, bancos de dados e outros recursos. Com essa ferramenta, podemos otimizar o uso de recursos e evitar gastos excessivos com infraestrutura ociosa. Por exemplo, durante períodos de alta demanda, o Auto Scaling pode aumentar a capacidade de servidores para atender ao aumento de tráfego, garantindo desempenho adequado, e durante períodos de baixa demanda, reduzir a capacidade para economizar recursos e custos operacionais.

Etapa 2: 
- Amazon S3 Intelligent-Tiering
- Otimização de custos de armazenamento.
- Essa ferramenta é uma classe de armazenamento que move automaticamente os dados entre as camadas de armazenamento com base no padrão de acesso dos objetos. Isso permite reduzir os custos de armazenamento, pois os dados menos acessados são movidos para camadas de menor custo. Na indústria farmacêutica, que geralmente possui grandes quantidades de dados, o uso do S3 Intelligent-Tiering pode ajudar a economizar custos significativos de armazenamento, mantendo a acessibilidade aos dados quando necessário.

Etapa 3: 
- Amazon Aurora
- Otimização de custos em bancos de dados.
- É um serviço de banco de dados relacional que se ajusta automaticamente com base na demanda. Ao contrário dos bancos de dados tradicionais, o Aurora Serverless não requer a configuração ou a manutenção de servidores de banco de dados. Ele dimensiona automaticamente a capacidade com base no tráfego de aplicativos em tempo real, o que significa que pagamos apenas pelos recursos utilizados durante a execução de consultas. Isso ajuda a reduzir significativamente os custos operacionais, pois não precisamos provisionar capacidade ociosa e pagamos apenas pelo que realmente usamos. Além disso, permite pausar a execução do banco de dados quando não está em uso, proporcionando ainda mais economia de custos.


## Conclusão
A implementação de ferramentas na empresa Abstergo tem como esperado uma significativa diminuição de custos imediatos, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.


Assinatura do Responsável pelo Projeto:

Vinícius Figueiredo Carneiro