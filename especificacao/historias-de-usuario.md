## Histórias de usuário

### HU-001 – Consultar eventos

**Como** participante
**Quero** visualizar os eventos disponíveis
**Para** identificar aqueles nos quais tenho interesse em participar.

**Critérios de aceitação**

**CA-001**

Dado que existam eventos disponíveis
Quando o participante consultar os eventos
Então o sistema deve apresentar os eventos disponíveis.

---

### HU-002 – Realizar inscrição

**Como** participante
**Quero** realizar minha inscrição em um evento
**Para** garantir minha participação.

**Critérios de aceitação**

**CA-002**

Dado que o evento possua vaga disponível
Quando o participante realizar uma inscrição válida
Então o sistema deve registrar a inscrição.

**CA-003**

Dado que a inscrição dependa de pagamento confirmado
Quando o pagamento ainda não estiver confirmado
Então a inscrição não deve ser considerada liberada.

**Observação:** o momento exato em que a vaga será reservada continua pendente de validação.

---

### HU-003 – Acompanhar inscrições

**Como** participante
**Quero** consultar minhas inscrições
**Para** acompanhar os eventos nos quais estou inscrito.

**Critério de aceitação**

Dado que o participante possua inscrições
Quando consultar suas inscrições
Então o sistema deve apresentar as inscrições associadas a ele.

---

### HU-004 – Receber comprovante

**Como** participante
**Quero** receber um comprovante da minha inscrição
**Para** ter uma confirmação do registro realizado.

**Critério de aceitação**

Dado que a inscrição tenha sido registrada
Quando o processo de inscrição for concluído
Então o sistema deve disponibilizar um comprovante da inscrição.

**Ponto pendente:** não está definido se o comprovante será apresentado na plataforma, enviado por e-mail ou por outro canal.

---

### HU-005 – Cancelar inscrição

**Como** participante
**Quero** cancelar uma inscrição quando não puder participar
**Para** não precisar entrar em contato diretamente com a organização.

**Critério de aceitação**

Dado que o evento permita cancelamento
Quando o participante solicitar o cancelamento dentro das condições permitidas
Então o sistema deve processar o cancelamento.

**Ponto pendente:** prazo e demais condições de cancelamento precisam ser definidos.

---

### HU-006 – Emitir certificado

**Como** participante
**Quero** emitir meu certificado depois do evento
**Para** comprovar minha participação.

**Critério de aceitação**

Dado que o evento tenha ocorrido
Quando o participante estiver apto a receber o certificado
Então o sistema deve permitir sua emissão.

**Ponto pendente:** ainda é necessário definir o significado de “apto”, principalmente se será exigida confirmação de presença.

---

### HU-007 – Criar evento

**Como** organizador
**Quero** criar eventos
**Para** disponibilizá-los aos participantes.

**Critério de aceitação**

Dado que o usuário possua perfil de organizador
Quando cadastrar um evento com os dados obrigatórios
Então o sistema deve registrar o evento.

**Ponto pendente:** os campos obrigatórios ainda precisam ser definidos.

---

### HU-008 – Controlar vagas

**Como** organizador
**Quero** que as vagas sejam controladas automaticamente
**Para** evitar inscrições acima da capacidade do evento.

**Critério de aceitação**

Dado que um evento possua capacidade definida
Quando ocorrer uma alteração válida nas inscrições
Então o sistema deve atualizar a disponibilidade de vagas.

---

### HU-009 – Acompanhar inscritos

**Como** organizador
**Quero** acompanhar a quantidade de inscritos em tempo real
**Para** monitorar a ocupação dos eventos.

**Critério de aceitação**

Dado que existam inscrições registradas
Quando o organizador consultar o evento
Então o sistema deve apresentar a quantidade atual de inscritos.

---

### HU-010 – Gerenciar lista de espera

**Como** organizador
**Quero** utilizar uma lista de espera quando um evento atingir sua capacidade
**Para** possibilitar o preenchimento de vagas que venham a ser liberadas.

**Ponto pendente:** os critérios de entrada, ordenação e promoção da lista de espera ainda precisam ser definidos.

Não é adequado criar critérios de aceitação mais específicos antes dessa definição.

---

### HU-011 – Confirmar pagamento

**Como** integrante da equipe financeira
**Quero** confirmar pagamentos
**Para** permitir a liberação das inscrições que dependem dessa confirmação.

**Critério de aceitação**

Dado que uma inscrição dependa de confirmação de pagamento
Quando o pagamento for confirmado
Então o sistema deve permitir a liberação da inscrição.

---

### HU-012 – Processar reembolso

**Como** integrante da equipe financeira
**Quero** tratar os reembolsos aplicáveis
**Para** devolver os valores quando o participante tiver esse direito.

**Ponto pendente:** as condições e valores de reembolso precisam ser definidos.

---

### HU-013 – Consultar participantes

**Como** palestrante
**Quero** consultar os participantes inscritos em minhas atividades
**Para** ter acesso às informações necessárias à realização da atividade.

**Critério de aceitação**

Dado que o palestrante esteja associado a uma atividade
Quando consultar seus inscritos
Então o sistema deve apresentar os participantes da atividade.

**Ponto pendente:** quais informações pessoais serão apresentadas ainda precisa ser definido.
