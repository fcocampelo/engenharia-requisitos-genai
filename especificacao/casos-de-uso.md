# Casos de uso

## UC-001 – Realizar inscrição em evento

**Objetivo:** permitir que um participante se inscreva em um evento.

**Ator principal:** Participante

**Pré-condições:**

- evento disponível para inscrição;
- existência de vaga, considerando as regras ainda a serem definidas.

**Gatilho:** participante seleciona a opção de inscrição.

### Fluxo principal

1. O participante seleciona um evento.
2. O sistema apresenta a possibilidade de inscrição.
3. O participante solicita a inscrição.
4. O sistema verifica a disponibilidade de vagas.
5. O sistema registra a solicitação de inscrição.
6. Caso não exista exigência de confirmação financeira, a inscrição é liberada.
7. O sistema disponibiliza o comprovante correspondente.

### Fluxo alternativo – evento pago

1. O sistema identifica que a inscrição exige pagamento.
2. O pagamento é posteriormente confirmado pela equipe financeira.
3. O sistema libera a inscrição conforme a regra aplicável.

### Fluxo alternativo – evento lotado

1. O sistema identifica que não existem vagas disponíveis.
2. Caso exista lista de espera para o evento, o sistema oferece o tratamento previsto para a lista.

**Ponto pendente:** fluxo detalhado da lista de espera ainda depende de validação.

### Pós-condição

A inscrição fica registrada no sistema conforme as regras do evento.

**Regras relacionadas:** RN-001, RN-002, RN-003, RN-004 e RN-007.

**Requisitos relacionados:** RF-002, RF-009, RF-013, RF-014, RF-015 e RF-016.

---

## UC-002 – Cancelar inscrição

**Objetivo:** permitir ao participante cancelar uma inscrição quando permitido.

**Ator principal:** Participante

**Pré-condição:** existir uma inscrição associada ao participante.

**Gatilho:** participante solicita cancelamento.

### Fluxo principal

1. O participante consulta suas inscrições.
2. O participante seleciona uma inscrição.
3. O sistema verifica se o evento permite cancelamento.
4. O sistema verifica as condições aplicáveis ao cancelamento.
5. Caso sejam atendidas, o sistema cancela a inscrição.
6. O sistema atualiza o controle de vagas.

### Fluxo alternativo

Se o evento não permitir cancelamento, a operação não será executada.

### Pós-condição

A inscrição é cancelada e a disponibilidade de vagas é atualizada.

**Ponto pendente:** definir prazo limite e relação entre cancelamento e reembolso.

**Regras relacionadas:** RN-002, RN-005 e RN-006.

**Requisitos relacionados:** RF-005, RF-009 e RF-017.

---

## UC-003 – Emitir certificado

**Objetivo:** permitir ao participante emitir seu certificado após o evento.

**Ator principal:** Participante

**Pré-condição:** o evento já deve ter ocorrido.

**Gatilho:** participante solicita emissão do certificado.

### Fluxo principal

1. O participante acessa suas inscrições.
2. Seleciona o evento realizado.
3. Solicita o certificado.
4. O sistema verifica se o participante atende às condições de emissão.
5. O sistema disponibiliza o certificado.

### Exceção

Caso o participante não atenda às condições definidas, o certificado não será liberado.

**Ponto pendente:** condições de emissão ainda precisam ser definidas.

**Regra relacionada:** RN-008.

**Requisito relacionado:** RF-006.
