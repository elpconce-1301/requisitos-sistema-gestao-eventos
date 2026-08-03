# Casos de Uso

## 1. Inscrever em Evento
- Ator: Participante
- Descrição: Participante seleciona um evento e realiza a inscrição.
- Fluxo principal:
  1. Participante visualiza a lista de eventos.
  2. Seleciona o evento desejado.
  3. Informa dados pessoais e confirma a inscrição.
  4. Se o evento for pago, o sistema envia para confirmação de pagamento.
  5. O sistema reserva a vaga se houver disponibilidade.
  6. O sistema envia comprovante de inscrição.
- Fluxos alternativos:
  - Se o evento estiver lotado, o participante é incluído na lista de espera.
  - Se o evento não permitir cancelamento, o sistema informa a política.

## 2. Cancelar Inscrição
- Ator: Participante
- Descrição: Participante cancela sua inscrição em um evento.
- Fluxo principal:
  1. Participante acessa suas inscrições.
  2. Seleciona a inscrição a ser cancelada.
  3. Confirma o cancelamento.
  4. O sistema atualiza a disponibilidade de vagas.
- Fluxos alternativos:
  - Se o evento não permitir cancelamento, o sistema informa que a ação não é permitida.

## 3. Confirmar Pagamento
- Ator: Equipe Financeira
- Descrição: Equipe financeira confirma o pagamento de uma inscrição paga.
- Fluxo principal:
  1. Financeiro visualiza inscrições pendentes de pagamento.
  2. Confirma o pagamento.
  3. O sistema libera a inscrição e reserva a vaga.

## 4. Emitir Certificado
- Ator: Participante
- Descrição: Participante emite certificado após a realização do evento.
- Fluxo principal:
  1. Participante acessa eventos concluídos.
  2. Seleciona a opção de emitir certificado.
  3. O sistema gera o certificado disponível para download.

## 5. Consultar Programação e Participantes
- Ator: Palestrante
- Descrição: Palestrante consulta a programação de suas atividades e a lista de participantes.
- Fluxo principal:
  1. Palestrante acessa sua agenda.
  2. Visualiza as atividades atribuídas.
  3. Consulta a lista de participantes inscritos em cada atividade.
