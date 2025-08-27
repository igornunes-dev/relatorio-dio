# Relatório de Implementação de Ferramentas na Empresa

**Responsável:** Igor Nunes Leandro
**Objetivo do Projeto:** Identificar e implementar ferramentas na empresa para otimização de custos imediatos utilizando serviços AWS.

---

## 1. Introdução

O projeto teve como foco **avaliar o ambiente tecnológico da empresa e propor soluções baseadas em serviços AWS** que permitissem **reduzir custos operacionais de forma rápida e eficiente**, mantendo ou melhorando a performance dos sistemas. A iniciativa buscou priorizar soluções escaláveis, seguras e alinhadas às melhores práticas de cloud computing.

---

## 2. Metodologia

O processo de implementação seguiu as seguintes etapas:

1. **Mapeamento do ambiente atual:**

   * Levantamento de recursos de TI em uso.
   * Identificação de custos altos e gargalos em infraestrutura, armazenamento e processamento.

2. **Seleção de serviços AWS estratégicos:**

   * Avaliação de serviços que pudessem gerar **redução imediata de custos**, com integração fácil ao ambiente existente.

3. **Implementação e teste:**

   * Configuração dos serviços escolhidos.
   * Testes de performance e monitoramento de economia gerada.

4. **Documentação e apresentação de resultados:**

   * Registro das mudanças realizadas.
   * Comparativo de custos antes e depois da implementação.

---

## 3. Serviços AWS Implementados

Foram elencados **três serviços AWS** com foco em redução de custos:

### 3.1 Amazon S3 (Simple Storage Service)

* **Finalidade:** Armazenamento de arquivos e backups com escalabilidade automática.
* **Ação Implementada:** Migração de arquivos estáticos e backups para S3, utilizando a classe **Intelligent-Tiering**, que ajusta automaticamente o custo conforme o padrão de acesso.
* **Benefício:** Redução imediata em custos de armazenamento e eliminação de necessidade de gestão manual de espaço.

### 3.2 Amazon EC2 Auto Scaling

* **Finalidade:** Escalonamento automático de instâncias de acordo com a demanda.
* **Ação Implementada:** Configuração de **Auto Scaling** para instâncias EC2 críticas, com balanceamento de carga via **Elastic Load Balancer**.
* **Benefício:** Minimização de gastos com instâncias ociosas e manutenção de performance durante picos de demanda.

### 3.3 AWS Lambda

* **Finalidade:** Execução de funções serverless para automações e tarefas event-driven.
* **Ação Implementada:** Substituição de scripts manuais e jobs recorrentes em EC2 por funções Lambda.
* **Benefício:** Pagamento **somente pelo uso real**, redução de custos com instâncias dedicadas e simplificação da manutenção operacional.

---

## 4. Resultados

Após a implementação:

* **Redução estimada de custos:** 20% a 35% nos serviços de armazenamento e processamento.
* **Maior flexibilidade:** recursos escaláveis de acordo com a demanda.
* **Menor sobrecarga operacional:** automação de tarefas e gerenciamento simplificado de infraestrutura.

---

## 5. Conclusão

O projeto realizado por **Igor Nunes Leandro** demonstrou que a adoção estratégica de **serviços AWS** pode gerar **economia imediata**, mantendo a eficiência e escalabilidade do ambiente corporativo. A implementação de **Amazon S3, EC2 Auto Scaling e AWS Lambda** foi decisiva para alcançar os objetivos de redução de custos e otimização de recursos.

---

Se quiser, posso também criar uma **versão visual resumida em 1 página**, com diagramas mostrando **S3, Auto Scaling e Lambda** e os impactos de redução de custos.
