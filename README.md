# RELATÓRIO DE IMPLEMENTAÇÃO DE MEDIDAS DE SEGURANÇA
Data: 24/02/2024 Empresa: Abstergo Industries. Responsável: Sthefani Francisca

Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Sthefani Francisca. O objetivo do projeto foi elencar 3 medidas de segurança em conjunto dos serviços da AWS, com a finalidade de realizar aumentar a segurança na empresa.

Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 medidas de segurança. A seguir, serão descritas as etapas da implementação:

1- AWS Identity and Access Management (IAM):

Descrição: IAM foi implementado para gerenciar identidades e controlar o acesso aos recursos da AWS.
Processo de Implementação: Foram configuradas políticas de acesso granulares para garantir que apenas usuários autorizados tenham acesso aos recursos relevantes da empresa. Além disso, o princípio do menor privilégio foi aplicado, limitando as permissões dos usuários às ações necessárias para suas funções. O uso de Autenticação Multifatorial (MFA) também foi habilitado para contas de alto privilégio.
Benefícios Esperados: Espera-se que a implementação do IAM melhore significativamente o controle de acesso aos recursos da AWS, reduzindo o risco de acessos não autorizados e vazamentos de dados.

2- AWS CloudTrail:

Descrição: CloudTrail foi configurado para fornecer trilhas de auditoria das atividades realizadas na conta da AWS.
Processo de Implementação: CloudTrail foi ativado para registrar todas as atividades, incluindo ações de usuários, serviços e recursos. Os logs são armazenados em um bucket do Amazon S3 com acesso restrito, e foram configurados alertas para atividades suspeitas ou incomuns.
Benefícios Esperados: A implementação do CloudTrail permitirá à Abstergo Industries monitorar e auditar todas as atividades realizadas em sua conta da AWS, facilitando a detecção de comportamentos maliciosos ou não autorizados.

3- Amazon GuardDuty:

Descrição: GuardDuty foi configurado para fornecer detecção de ameaças em tempo real na conta da AWS.
Processo de Implementação: GuardDuty foi configurado para monitorar atividades suspeitas, como tentativas de acesso não autorizadas, comunicações com endereços IP maliciosos conhecidos e atividades de mineração de criptomoedas. Integrações com outros serviços, como CloudWatch e Lambda, foram realizadas para automatizar respostas a eventos de segurança detectados.
Benefícios Esperados: Espera-se que o GuardDuty aumente significativamente a capacidade da Abstergo Industries de detectar e responder a ameaças em tempo real, protegendo os ativos e dados da empresa contra ataques cibernéticos.

Conclusão
A implementação de ferramentas na empresa Abstergo Industries. tem como esperado. Medidas de Segurança Implementadas, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.


Lista de Anexos:

Manual de Configuração do AWS Identity and Access Management (IAM)
Documento de Políticas de Acesso do IAM da Abstergo Industries
Planilha de Mapeamento de Permissões de Usuários no IAM
Documento de Configuração do AWS CloudTrail
Exemplo de Configuração de Alertas do CloudTrail
Guia de Integração do Amazon GuardDuty com AWS CloudWatch e AWS Lambda
Documento de Política de Resposta a Incidentes de Segurança na AWS
Plano de Treinamento em Segurança da AWS para Funcionários da Abstergo Industries
Documento de Procedimentos de Auditoria e Revisão de Segurança na AWS
Checklist de Segurança na AWS para Verificação Regular

Assinatura do Responsável pelo Projeto:

Sthefani Francisca
