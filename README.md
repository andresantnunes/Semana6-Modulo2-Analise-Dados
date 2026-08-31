## Dadas as Colunas:

Descrição das Colunas (Dicionário de Dados)
- ID_Consulta: Identificador único numérico para cada consulta realizada ou agendada no sistema.
- Data_Hora_Consulta: A data e o horário programados para a consulta do paciente, no formato AAAA-MM-DD HH:MM.
- Nome_Paciente: O nome completo (fictício) do paciente que agendou a consulta.
- Idade_Paciente: A idade do paciente no momento da consulta, variando de 16 a 75 anos.
- Sexo: O sexo biológico do paciente (Feminino ou Masculino).
- Tipo_Consulta: A categoria do agendamento, que pode ser:
  - Primeira Consulta: Avaliação inicial do paciente.
  - Retorno: Consulta de acompanhamento de curto prazo (geralmente sem custo).
  - Acompanhamento Mensal: Consultas subsequentes para avaliação contínua.
- Motivo_Consulta: O objetivo principal do paciente ao buscar atendimento nutricional (ex: Emagrecimento, Hipertrofia, Reeducação Alimentar, Nutrição Esportiva, Doenças Crônicas, Gestação).
- Nutricionista_Responsavel: O nome do(a) profissional da clínica responsável por conduzir o atendimento.
- Status_Comparecimento: A situação atual do agendamento, sendo:
- Realizada: O paciente compareceu.
- Cancelada: O paciente cancelou antes do horário.
- Faltou: O paciente não compareceu e não avisou.
- Peso_kg: O peso do paciente registrado em quilogramas (kg). (Valores variam de acordo com o motivo da consulta para maior realismo nos dados).
- Altura_m: A altura do paciente registrada em metros (m).
- IMC: O Índice de Massa Corporal do paciente, calculado automaticamente com base no peso e na altura fornecidos (Peso / Altura²).
- Valor_Cobrado_R$: O valor financeiro cobrado pela consulta em Reais. (Ex: R$ 250 para primeira consulta, R$ 150 para acompanhamento, e isento para retorno).

## Crie uma modelagem dimensional estrela para essa base de dados
- Não precisa me enviar
- Apenas crie os SQL de CREATE Table para cada tabela dimensão e fato
