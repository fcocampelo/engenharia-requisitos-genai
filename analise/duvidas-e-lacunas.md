# Ambiguidades e pontos a esclarecer

| ID     | Tipo                        | Problema identificado                                                                           | Impacto                                                     | Pergunta ao stakeholder                                                                                                            |
| ------ | --------------------------- | ----------------------------------------------------------------------------------------------- | ----------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- |
| PE-001 | Requisito incompleto        | Não foi definido o prazo limite para cancelamento.                                              | Impede definir corretamente a regra de cancelamento.        | Até quanto tempo antes do evento o participante poderá cancelar sua inscrição?                                                     |
| PE-002 | Regra de negócio incompleta | Alguns eventos não permitem cancelamento, mas não foi definido como isso será configurado.      | Pode gerar cancelamentos indevidos.                         | O organizador poderá definir individualmente se cada evento aceita cancelamento?                                                   |
| PE-003 | Ambiguidade                 | Não foram definidas as situações que permitem reembolso.                                        | Afeta pagamentos, cancelamentos e financeiro.               | Em quais situações o cancelamento gera direito ao reembolso?                                                                       |
| PE-004 | Informação ausente          | Não foi definido se o reembolso será integral ou parcial.                                       | Impede definir valores a devolver.                          | O reembolso será integral ou poderá haver retenções?                                                                               |
| PE-005 | Informação ausente          | Não foi definido como funcionará a lista de espera.                                             | Não é possível determinar promoção automática ou manual.    | Quando surgir uma vaga, como o participante da lista de espera será selecionado?                                                   |
| PE-006 | Informação ausente          | Não foi definido se a entrada na lista de espera será automática.                               | Afeta experiência do participante.                          | Quando o evento estiver lotado, o participante será inserido automaticamente na lista de espera ou deverá confirmar seu interesse? |
| PE-007 | Ambiguidade                 | Não foi definido como será liberada uma vaga da lista de espera.                                | Pode ocorrer disputa por uma mesma vaga.                    | A vaga ficará reservada para o primeiro participante da lista? Por quanto tempo?                                                   |
| PE-008 | Requisito incompleto        | Certificados são mencionados, mas não há critério de emissão.                                   | Pode ocorrer emissão para participantes ausentes.           | O certificado dependerá da confirmação de presença?                                                                                |
| PE-009 | Informação ausente          | Não foi definido quem registra a presença.                                                      | Afeta emissão dos certificados.                             | Como e por quem será confirmada a presença do participante?                                                                        |
| PE-010 | Informação ausente          | Não foi definido o canal de envio do comprovante de inscrição.                                  | Afeta requisitos de comunicação.                            | O comprovante será exibido no sistema, enviado por e-mail ou por outro canal?                                                      |
| PE-011 | Informação ausente          | Não foram definidas outras notificações.                                                        | Pode haver expectativas diferentes entre stakeholders.      | Quais eventos devem gerar notificações para o participante?                                                                        |
| PE-012 | Regra incompleta            | Não foi definido quando uma vaga de evento pago passa a ser considerada ocupada.                | Pode causar overbooking ou bloqueio desnecessário de vagas. | A vaga será reservada no início do pagamento ou somente após sua confirmação?                                                      |
| PE-013 | Informação ausente          | Se existir reserva temporária, não foi definido seu tempo de validade.                          | Pode bloquear vagas indefinidamente.                        | Caso a vaga seja reservada durante o pagamento, por quanto tempo a reserva será mantida?                                           |
| PE-014 | Ambiguidade                 | Participante deseja vários workshops no mesmo dia, mas não há regra para horários conflitantes. | Pode permitir inscrições impossíveis de serem frequentadas. | O sistema deve impedir, alertar ou permitir inscrições em workshops com horários conflitantes?                                     |
| PE-015 | Informação ausente          | Não estão definidos os dados que palestrantes poderão visualizar.                               | Risco de exposição indevida de dados pessoais.              | Quais informações dos participantes poderão ser acessadas pelos palestrantes?                                                      |
| PE-016 | RNF ausente                 | Segurança não foi discutida.                                                                    | Risco de acesso indevido.                                   | Quais mecanismos de autenticação e níveis de acesso são necessários?                                                               |
| PE-017 | RNF ausente                 | Privacidade/LGPD não foi discutida.                                                             | Risco legal e de exposição de dados.                        | Quais dados pessoais são necessários e quais regras de retenção e consentimento devem ser aplicadas?                               |
| PE-018 | RNF ausente                 | Desempenho não foi definido.                                                                    | Não existem critérios objetivos de qualidade.               | Qual quantidade de usuários simultâneos e qual tempo de resposta esperado?                                                         |
| PE-019 | RNF ausente                 | Disponibilidade não foi definida.                                                               | Não é possível estabelecer níveis de serviço.               | Em quais períodos o sistema precisa estar disponível?                                                                              |
| PE-020 | RNF ausente                 | Acessibilidade não foi definida.                                                                | Pessoas com deficiência podem encontrar barreiras.          | Existe algum padrão de acessibilidade que deverá ser seguido?                                                                      |
| PE-021 | Inconsistência documental   | A descrição da equipe financeira na seção de stakeholders parece corresponder aos palestrantes. | Pode gerar atribuição incorreta de requisitos.              | Confirmar quais responsabilidades pertencem à equipe financeira e quais pertencem aos palestrantes.                                |
| PE-022 | Informação ausente          | Não está definido como pagamentos serão realizados.                                             | Impede especificação completa do fluxo financeiro.          | O sistema realizará o pagamento diretamente ou apenas registrará/confirma pagamentos externos?                                     |
| PE-023 | Informação ausente          | “Gerenciar participantes” é uma expressão genérica.                                             | Pode provocar interpretações diferentes.                    | Quais operações os organizadores poderão executar sobre os participantes?                                                          |

---

# Perguntas para os stakeholders

Uma nova rodada de elicitação deveria priorizar as seguintes perguntas:

1. Cada evento poderá configurar individualmente se aceita ou não cancelamento?

2. Qual será o prazo máximo para cancelar uma inscrição?

3. Quais cancelamentos dão direito a reembolso?

4. O reembolso poderá ser parcial?

5. Como será determinada a ordem da lista de espera?

6. A entrada na lista de espera será automática ou solicitada pelo participante?

7. Quando surgir uma vaga, a promoção será automática ou dependerá do organizador?

8. Existe prazo para o participante da lista de espera confirmar a vaga?

9. A emissão do certificado dependerá da presença no evento?

10. Como será registrada a presença?

11. Como os comprovantes de inscrição serão entregues?

12. Quais notificações deverão ser enviadas?

13. Em eventos pagos, quando a vaga passa a ficar reservada?

14. Caso exista reserva durante o pagamento, qual será o tempo de expiração?

15. O sistema deverá impedir inscrições em atividades simultâneas ou apenas alertar o participante?

16. Quais informações dos participantes os palestrantes poderão consultar?

17. O sistema processará pagamentos diretamente?

18. Quais tipos de pagamento serão aceitos?

19. Como os usuários serão autenticados?

20. Quais perfis e permissões existirão?

21. Quais dados pessoais precisarão ser armazenados?

22. Há requisitos específicos relacionados à LGPD?

23. Quantos participantes simultâneos o sistema deve suportar?

24. Existe meta de disponibilidade?

25. Existem requisitos específicos de acessibilidade?
