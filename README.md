# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS - ABSTERGO INDUSTRIES

**Data:** 16 de Janeiro de 2026  
**Empresa:** Abstergo Industries  
**Responsável:** Edson

## 1. Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa **Abstergo Industries**, realizado por **Edson**. O objetivo do projeto foi elencar 3 serviços AWS estratégicos com a finalidade de realizar a transição da infraestrutura local para a nuvem, visando a **diminuição de custos operacionais imediatos**, aumento da segurança de dados sensíveis e escalabilidade tecnológica.

## 2. Descrição do Projeto
A estratégia de migração foi dividida em três pilares fundamentais para o setor farmacêutico: armazenamento seguro de dados regulatórios, capacidade computacional sob demanda e gestão eficiente de bancos de dados de inventário.

---

### Etapa 1: Armazenamento e Backup
* **Nome da ferramenta:** Amazon S3 (Simple Storage Service)
* **Foco da ferramenta:** Armazenamento de objetos com alta durabilidade.
* **Descrição de caso de uso:** A Abstergo Industries lida com grandes volumes de dados de pesquisas clínicas e documentações regulatórias (como as da ANVISA/FDA) que exigem retenção por décadas. O S3 substitui os caros servidores de arquivos locais, utilizando políticas de **Lifecycle** para mover dados antigos para o *S3 Glacier*, reduzindo o custo de armazenamento em até 80%.

### Etapa 2: Computação Flexível
* **Nome da ferramenta:** Amazon EC2 (Elastic Compute Cloud)
* **Foco da ferramenta:** Servidores virtuais escaláveis.
* **Descrição de caso de uso:** Hospedagem do sistema de gestão (ERP) e softwares de controle laboratorial. Ao invés de investir em hardware físico que fica ocioso, a empresa passa a utilizar instâncias ajustadas à carga de trabalho atual. A implementação de **Instâncias Reservadas** permite uma economia significativa de custos fixos em relação à manutenção de um Data Center próprio.

### Etapa 3: Banco de Dados Gerenciado
* **Nome da ferramenta:** Amazon RDS (Relational Database Service)
* **Foco da ferramenta:** Banco de dados relacional (SQL).
* **Descrição de caso de uso:** Migração dos bancos de dados de estoque e fórmulas químicas. O RDS automatiza tarefas complexas como backup, aplicação de patches de segurança e alta disponibilidade (Multi-AZ). Isso reduz a necessidade de intervenção humana e evita interrupções na linha de produção por falhas de banco de dados.

---

## 3. Conclusão
A implementação das ferramentas AWS na **Abstergo Industries** tem como benefícios esperados a **redução drástica em despesas de capital (CapEx)** e a modernização da infraestrutura. A centralização na nuvem aumentará a eficiência operacional e a produtividade, garantindo que a empresa esteja em conformidade com as normas de segurança de dados. Recomenda-se a continuidade da jornada para a nuvem com foco em automação e análise de dados (Big Data) para acelerar a descoberta de novos medicamentos.

---
**Assinatura do Responsável pelo Projeto:**

*[Edson]*
