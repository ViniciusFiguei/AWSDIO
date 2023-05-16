# RELATÓRIO DE IMPLEMENTAÇÃO DE MEDIDAS DE SEGURANÇA

Data: 16/05/2023
Empresa: Abstergo Industries 
Responsável: Vinícius Figueiredo Carneiro

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Vinícius Figueiredo Carneiro. O objetivo do projeto foi elencar 3 medidas de segurança em conjunto dos serviços da AWS, com a finalidade de realizar aumentar a segurança na empresa.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 medidas de segurança. A seguir, serão descritas as etapas da implementação:

Medida 1: Utilização do AWS Identity and Access Management (IAM)
- A medida 1 consiste em implementar o AWS Identity and Access Management (IAM) para gerenciar as identidades e permissões de acesso dos usuários da empresa aos recursos da AWS. Serão criados usuários individuais para cada funcionário, atribuindo permissões específicas baseadas no princípio de menor privilégio. Além disso, serão configurados grupos para facilitar o gerenciamento de permissões em larga escala. Com o IAM, será possível controlar e auditar de forma mais granular o acesso aos serviços e recursos da AWS, aumentando a segurança da empresa.

Medida 2: Implementação do AWS GuardDuty
- A medida 2 focará na configuração de grupos de segurança na Amazon Elastic Compute Cloud (EC2) para reforçar a segurança das instâncias EC2 da empresa. Serão definidas regras de entrada e saída nos grupos de segurança para permitir apenas o tráfego necessário e bloquear acessos indesejados. Serão aplicadas práticas recomendadas, como permitir apenas as portas e protocolos necessários, restringir o acesso por endereços IP específicos e implementar listas de controle de acesso (ACLs). Essas medidas ajudarão a proteger as instâncias EC2 contra ataques e acessos não autorizados.

Medida 3: Configuração do AWS CloudTrail
- A medida 3 envolverá a implementação do AWS GuardDuty para detecção de ameaças e atividades maliciosas na infraestrutura da empresa. O GuardDuty utilizará análise de comportamento e aprendizado de máquina para identificar padrões suspeitos de atividades, como tentativas de acesso não autorizado, comunicações de comando e controle e explorações de vulnerabilidades. O serviço emitirá alertas para eventos de ameaças detectados, permitindo uma resposta rápida e eficaz a possíveis ataques.

## Conclusão
A implementação de ferramentas na empresa *[nome da empresa] tem como esperado proporcionar aumento significativo na segurança dos serviços da AWS utilizados pela Abstergo Industries, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

Assinatura do Responsável pelo Projeto:

Vinícius Figueiredo Carneiro