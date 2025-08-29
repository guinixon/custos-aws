# RELATORIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 29/08/2025
Empresa: Abstergo Industries
Responsável: Guilherme Nixon

# INTRODUÇÃO
Este relatório apresenta a implementação de soluções de computação em nuvem na Abstergo Industries, com foco em redução de custos, segurança e automação de processos.
As tecnologias escolhidas foram Amazon EC2, Amazon S3 e AWS Lambda, selecionadas por sua capacidade de oferecer infraestrutura escalável, armazenamento eficiente e automação sem servidor, atendendo às necessidades específicas da indústria farmacêutica.

Etapa 1:
- Amazon EC2 (Elastic Compute Cloud)
- O Amazon EC2 fornece servidores virtuais escaláveis, permitindo à Abstergo Industries ajustar recursos conforme a demanda.
- Amplia ou reduz recursos de CPU, memória e armazenamento conforme necessidade, útil para períodos de pico em pesquisas ou processamento de dados de produção, pagamento somente pelo uso efetivo, eliminando gastos com servidores físicos e manutenção.

Etapa 2:
- Amazon S3 (Simple Storage Service)
- O Amazon S3 é um serviço de armazenamento escalável e seguro, ideal para dados laboratoriais, relatórios de produção e backups.
- Pagamento por armazenamento utilizado; políticas de ciclo de vida permitem transferir dados antigos para camadas mais econômicas. Suporta desde pequenos arquivos de relatórios até grandes volumes de dados científicos e funciona junto ao EC2 e Lambda para processamento e análise de dados automatizado

Etapa 3:
- AWS Lambda
- O AWS Lambda permite executar código sem precisar gerenciar servidores, reduzindo custos e automatizando tarefas repetitivas.
- Pagamento apenas pelo tempo de execução do código, sem necessidade de manter servidores 24/7 e ajusta automaticamente a execução conforme a demanda, garantindo performance mesmo em picos.
