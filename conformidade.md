# Auditoria de Conformidade – Botium Toys

Este documento apresenta a avaliação das práticas de conformidade da Botium Toys em relação às principais normas e regulamentações: **PCI DSS**, **GDPR** e **SOC 1/2**.

A análise foi baseada nos dados fornecidos no relatório oficial de escopo, objetivos e avaliação de riscos.

---

# 📌 PCI DSS – Segurança de Dados de Cartão de Pagamento

| Melhores Práticas | Em Conformidade? | Observação |
|-------------------|------------------|------------|
| Somente usuários autorizados têm acesso às informações de cartão | ❌ Não | Todos os funcionários têm acesso a dados sensíveis. |
| Armazenamento, processamento e transmissão de cartão em ambiente seguro | ❌ Não | Dados são armazenados localmente sem controles fortes. |
| Uso de criptografia para dados de cartão | ❌ Não | Nenhuma criptografia implementada. |
| Políticas seguras de gerenciamento de senhas | ❌ Não | Política existente, porém fraca e não conforme. |

**Conclusão PCI DSS:**  
❌ **Não conforme.**  
A empresa corre risco de violação regulatória e multas.

---

# 📌 GDPR – Regulamento Geral de Proteção de Dados

| Melhores Práticas | Em Conformidade? | Observação |
|-------------------|------------------|------------|
| Dados de clientes da UE mantidos em segurança | ❌ Não | Falta de controles fundamentais; risco significativo. |
| Plano de notificação em 72h para incidentes | ✔️ Sim | Plano estruturado existe. |
| Classificação e inventário de dados | ❌ Não | Ativos não são classificados adequadamente. |
| Políticas e processos de privacidade implementados | ✔️ Sim | Políticas de privacidade estão documentadas e aplicadas. |

**Conclusão GDPR:**  
⚠️ **Parcial**, mas formalmente tratado como **Não Conforme**,  
pois falta classificação de dados e controles essenciais.

---

# 📌 SOC 1 / SOC 2 – Controles de Segurança, Disponibilidade e Confidencialidade

| Melhores Práticas | Em Conformidade? | Observação |
|-------------------|------------------|------------|
| Políticas de acesso do usuário estabelecidas | ❌ Não | Não há controle baseado em privilégios mínimos. |
| Dados sensíveis mantidos confidenciais | ❌ Não | Acesso irrestrito e ausência de criptografia. |
| Integridade dos dados garantida | ✔️ Sim | Controles mantêm consistência e integridade. |
| Disponibilidade dos dados para indivíduos autorizados | ❌ Não | Acesso não é limitado apenas a usuários autorizados. |

**Conclusão SOC:**  
❌ **Não Conforme.**  
A empresa carece de controles de acesso e confidencialidade essenciais.

---

# 📌 Resumo Geral da Conformidade

| Norma | Situação |
|-------|----------|
| **PCI DSS** | ❌ Não Conforme |
| **GDPR** | ⚠️ Parcial, porém considerada Não Conforme |
| **SOC 1 / SOC 2** | ❌ Não Conforme |

---

# 📝 Conclusão

A Botium Toys apresenta lacunas importantes em todas as regulamentações avaliadas.  
Os principais problemas estão relacionados a:

- ausência de controles de acesso adequados  
- falta de criptografia  
- gestão de ativos limitada  
- ausência de backups  
- políticas de senha inadequadas  

Recomenda-se a implementação imediata de medidas corretivas, descritas no arquivo **`recomendacoes.md`**.

