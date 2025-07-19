# Auditoria Interna de Segurança – Botium Toys

## 1. Escopo da Auditoria

- O escorpo da auditoria tem como objetivo realizar a validação de segurança, física e tecnológica da impresa fictícia Botium Toys.
- Realizar avalialção empresarial dos ativos de rede e vunerabilidades possível
- Documentar formalmente as possíveis ameaças e irregularidades de forma objetiva
- Fornecer soluções praticas e ajustes no instuito de evitar danos por ataques cyberneticos

## 2. Metas da Auditoria

- Mapeamento de ativos e identificação de risco
- Analise do impacto potencial, probabilidade de ataques e a conparação entre eles.
- Avaliação e aplicação das melhores praticas perante a postura de seguraça da Botium Toys.

## 3. Avaliação de Riscos

| Ativo                      | Risco Identificado                           | Impacto Potencial          | Probabilidade | Nível de Risco (Impacto x Probabilidade) |
|----------------------------|----------------------------------------------|----------------------------|---------------|------------------------------------------|
| Computadores               | Senhas de acesso fracas                      | Médio                      | Média         |   Médio                                  |
| Gerenciamento de serviços/Sistemas| Fatlta de criptografia                | Alto                       | Alta          | Alta                                     |
| Acesso a internet          | Senhas de acesso fracas                      | Alto                       | Média         | Alta                                     |
| Rede interna               | Não há separação restrições de acessos rígidas| Medio                     | Alto          | Alta                                     |
| Sistemas legado            | Não há rotinas para manutenção para regulação| Baixo                      | Baixo         | Baixo                                    |
| Estoque de produtos        | Nenhum risco encontrado                      | Baixo      | Baixo         |    Baixo      | Baixo                                    |

## 4. Lista de Verificação de Controles

Ao estar analisando as políticas de segurança da empresa Botium Toys, foi analisado os itens abaixo e destacado como "yes" (SIM) para os controles/praticas que estão completamente implementados e operantes e "no" para os controles/praticas que fogem das boas práticas de postura de segurança, classificando como um possível alvo de ataques devido a vunerabilidade e falta de conformidade com as leis internas ou externas. 
 
| Yes | No | Controle                                        |
|------|----|------------------------------------------------|
|      |  ✅  | Least Privilege (Privilégio Mínimo)           |
|      |  ✅  | Disaster recovery plans (Planos de recuperação de desastres)|
|   ✅   |    | Password policies (Políticas de senha)        |
|      |  ✅  | Separation of duties (Separação de funções)   |
|   ✅   |    | Firewall                                      |
|      |  ✅  | Intrusion detection system (IDS)              |
|      |    | Backups (Backups regulares)                    |
|   ✅   |    | Antivirus software (Software antivírus)       |
|   ✅   |    | Manual monitoring, maintenance, and intervention for legacy systems (Monitoramento e manutenção manual para sistemas legados) |
|      |  ✅  | Encryption (Criptografia)                     |
|      |  ✅  | Password management system (Sistema de gerenciamento de senhas) |
|   ✅   |    | Locks (oficinas, loja, depósito)              |
|   ✅   |    | Closed-circuit television (CCTV) surveillance (Câmeras de segurança) |
|   ✅   |     | Fire detection/prevention (alarme de incêndio, sprinklers)|

## 5. Lista de Verificação de Conformidade

Ao estar analisando as políticas de melhores práticas da empresa Botium Toys, foi analisado os itens abaixo e destacado como "yes" (SIM) para os controles/praticas que estão completamente implementados e operantes e "no" para os controles/praticas que fogem das boas práticas de postura de segurança, classificando como um possível alvo de ataques devido a vunerabilidade e falta de conformidade com as leis internas ou externas. 

### Payment Card Industry Data Security Standard (PCI DSS)

| Yes | No | Melhores práticas                                                                                   |
|------|----|----------------------------------------------------------------------------------------------------|
|      |  ✅  | Apenas usuários autorizados têm acesso às informações dos cartões de crédito dos clientes.        |
|   ✅   |    | Informações dos cartões são armazenadas, processadas e transmitidas em ambiente seguro.           |
|      |  ✅  | Procedimentos de criptografia para proteger dados de transações com cartão.                       |
|      |  ✅  | Políticas seguras para gerenciamento de senhas.                                                   |

### General Data Protection Regulation (GDPR)

| Yes | No | Melhores práticas                                                                                  |
|------|----|---------------------------------------------------------------------------------------------------|
|   ✅   |    | Dados dos clientes da UE são mantidos privados e seguros.                                        |
|   ✅   |    | Plano para notificar clientes da UE em até 72 horas em caso de violação de dados.                |
|   ✅   |    | Dados são devidamente classificados e inventariados.                                             |
|   ✅   |    | Políticas, procedimentos e processos de privacidade são aplicados e documentados.                |

### System and Organization Controls (SOC type 1, SOC type 2)

| Yes | No | Melhores práticas                                                                                 |
|------|----|--------------------------------------------------------------------------------------------------|
|      |  ✅  | Políticas de acesso de usuários estão estabelecidas.                                            |
|      |  ✅  | Dados sensíveis (PII/SPII) são mantidos confidenciais/privados.                                 |
|   ✅   |    | Integridade dos dados é garantida (dados completos, precisos e validados).                      |
|      |  ✅  |Dados estão disponíveis para indivíduos autorizados.                                             |

## 6. Recomendações

- Realizar melhorias na segurança de sistemas de gerenciamento de rede interna e sistemas legado. 
- Apesar de haver um firewall para estar lidando com eventuais ameaças, as senhas dos usuários não são criptográfadas, causando assim uma falha de segurança que pode ser explorada por harckers
- Classificação, catalogar e validação de acessos para todos os colaboradores, permitindo a eles o acesso mínimo para que possam executar suas atividades. 
- Realização de backups dos dados de PII e SPII assim como uma implementação de criptografia para eles
---
## Contato

- **Email:** ediwillson.alencar@gmail.com
- **LinkedIn:** (https://www.linkedin.com/in/ediwillson-pereira)
