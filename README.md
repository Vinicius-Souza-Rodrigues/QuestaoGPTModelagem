# QuestaoGPTModelagem

##Regra de Negocio

Uma plataforma de gestão de eventos corporativos é utilizada por empresas para organizar treinamentos, workshops e palestras internas.

Cada evento é um conceito genérico e pode ser realizado várias vezes ao longo do tempo, em edições diferentes, com datas, horários, local (presencial ou online) e capacidade máxima de participantes, que pode variar entre edições do mesmo evento.

Os participantes realizam um cadastro único na plataforma utilizando e-mail exclusivo, podendo participar de eventos organizados por empresas diferentes. Um participante pode se inscrever em várias edições, mas não pode se inscrever duas vezes na mesma edição.

Cada edição de evento pode possuir um ou mais palestrantes, e um palestrante pode atuar em várias edições, inclusive de eventos distintos. Para cada palestrante, devem ser armazenadas informações profissionais e um identificador interno exclusivo.

Durante uma edição, os participantes podem responder a avaliações de satisfação, que possuem nota e comentário opcional. Uma edição pode ter mais de uma avaliação, e um participante pode responder ou não às avaliações disponíveis.

Após o término da edição, a empresa pode emitir certificados de participação, que só podem existir para participantes que efetivamente compareceram ao evento. Cada certificado deve possuir um código único de validação e data de emissão.

A inscrição em uma edição pode gerar cobranças. Uma cobrança pode ser gratuita ou paga.
Quando paga, a cobrança pode ser quitada em uma ou mais parcelas, cada uma com valor, data de vencimento e status.

Uma empresa pode subsidiar parcialmente o valor de uma inscrição, arcando com parte do custo, ficando o restante sob responsabilidade do participante.
