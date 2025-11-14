# Avaliação de Riscos – Botium Toys

Este documento apresenta a avaliação de riscos identificada durante a auditoria interna de TI da Botium Toys, com base nas diretrizes do NIST Cybersecurity Framework (NIST CSF).

---

## 📌 Visão Geral do Risco

A Botium Toys apresenta lacunas significativas em seus controles de segurança, especialmente na gestão de ativos, proteção de dados sensíveis e conformidade regulatória.

**Pontuação de risco atribuída: 8/10 (alto)**  
Essa pontuação reflete a probabilidade elevada de incidentes e o impacto potencial nas operações da empresa.

---

## 🎯 Principais Riscos Identificados

### 🔴 **1. Gestão inadequada de ativos**
- Ativos não inventariados corretamente.
- Falta de classificação dos ativos por criticidade.
- Departamento de TI não tem clareza sobre quais ativos estão em risco.

### 🔴 **2. Excesso de privilégios e acesso irrestrito**
- Todos os funcionários têm acesso a dados sensíveis.
- Falta de controle baseado no princípio do **menor privilégio**.
- Risco alto de exposição de dados e uso indevido.

### 🔴 **3. Dados de cartão de crédito sem proteção**
- Informações de cartão não são criptografadas.
- Dados armazenados localmente sem controles seguros.
- Vulnerabilidade direta à não conformidade com **PCI DSS**.

### 🔴 **4. Ausência de controles técnicos essenciais**
- Não existe sistema de detecção de intrusão (**IDS**).
- Não há backups de dados críticos.
- Políticas de senha fracas e sem gerenciador centralizado.

### 🔴 **5. Fragilidades nos processos de manutenção**
- Sistemas legados sem cronograma de manutenção.
- Métodos de intervenção não padronizados.

### 🔴 **6. Exposição regulatória**
Risco de multas por:
- Armazenar dados sensíveis sem criptografia.
- Não limitar acesso a PII/SPII.
- Não cumprir requisitos obrigatórios de conformidade internacional.

---

## 🟢 Controles existentes que reduzem parcialmente o risco

Mesmo com diversas lacunas, alguns controles estão presentes:

- Firewall com regras definidas.  
- Antivírus instalado e monitorado.  
- Controles físicos robustos:  
  - fechaduras,  
  - sistema CFTV,  
  - detecção e prevenção de incêndios.  
- Processo de notificação de incidentes para clientes da UE (72h).

Esses controles reduzem apenas parte do risco, mas não compensam a falta de defesas técnicas fundamentais.

---

## 📌 Impacto Potencial

Caso um incidente ocorra, possíveis impactos incluem:

- Perda ou exposição de dados sensíveis de clientes.
- Multas por violação de PCI DSS, GDPR e SOC.
- Interrupção de operações e perda de confiança.
- Riscos financeiros e reputacionais significativos.

Impacto avaliado como: **médio**, mas com **risco geral alto** devido à falta de controles preventivos.

---

## 🧩 Conclusão da Avaliação

A Botium Toys deve priorizar:

1. Gestão de ativos e classificação de dados.  
2. Implementação de criptografia e backups.  
3. Controle de acesso baseado no menor privilégio.  
4. Implantação de IDS/IPS.  
5. Reforço das políticas de senha e uso de gerenciador.  

A maturidade atual é considerada **baixa**, exigindo medidas imediatas para alinhar a empresa às melhores práticas de segurança.

