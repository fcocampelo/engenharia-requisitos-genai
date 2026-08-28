# Regras de negócio

| ID     | Regra de negócio                                                                           | Origem            | Status                                 | Necessita validação? |
| ------ | ------------------------------------------------------------------------------------------ | ----------------- | -------------------------------------- | -------------------- |
| RN-001 | Um evento ou atividade possui quantidade limitada de vagas.                                | Organizadores     | Definida                               | Não                  |
| RN-002 | O sistema deve atualizar automaticamente a quantidade de vagas conforme as inscrições.     | Organizadores     | Definida                               | Não                  |
| RN-003 | Eventos podem ser gratuitos ou pagos.                                                      | Equipe Financeira | Definida                               | Não                  |
| RN-004 | Algumas inscrições somente poderão ser liberadas após a confirmação do pagamento.          | Equipe Financeira | Parcialmente definida                  | Sim                  |
| RN-005 | Alguns eventos permitem cancelamento e outros não.                                         | Organizadores     | Parcialmente definida                  | Sim                  |
| RN-006 | Em determinadas situações haverá direito a reembolso.                                      | Equipe Financeira | Parcialmente definida                  | Sim                  |
| RN-007 | Eventos ou atividades lotados poderão utilizar lista de espera.                            | Organizadores     | Parcialmente definida                  | Sim                  |
| RN-008 | O certificado somente estará disponível após a realização do evento.                       | Participantes     | Parcialmente definida                  | Sim                  |
| RN-009 | Um participante pode se inscrever em vários workshops realizados no mesmo dia.             | Participantes     | Definida parcialmente                  | Sim                  |
| RN-010 | Workshops programados para o mesmo horário podem ocorrer simultaneamente.                  | Organizadores     | Definida                               | Não                  |
| RN-011 | Palestrantes somente devem consultar participantes associados às suas próprias atividades. | Palestrantes      | Inferência necessária à funcionalidade | Sim                  |

A RN-011 não está explicitamente escrita dessa forma.

**Hipótese para validação com os stakeholders:** o palestrante deverá visualizar somente os participantes das atividades pelas quais é responsável.

---

#
