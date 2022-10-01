
# ArenaDATAB - Desafio Copa do Mundo

## 🔥 EM ATUALIZACAO 🔥
Dados de todos os resultados da Copa do Mundo entre 1930-2014, com detalhes de cada partida (data, fase, cidade, árbitro, time da casa, time visitante, gols) e detalhes de eventos por atleta.

<center><img src="https://user-images.githubusercontent.com/25754870/192645692-bfbe4f32-0a85-4af3-9dc1-c1706801c738.png" alt="drawing" width="200"/></center>

    ⏱️ PRAZO FINAL PARA SUBMETER A SUA PARTICIPAÇÃO:  30/09/2022

## Objetivos-chave & Análises Recomendadas

- [ ] Como o comparecimento do público evoluiu ao longo do tempo?
- [ ] Qual foi o público record (maior audiência registrada)?
- [ ] Ranking dos países campeões
- [ ] Quais times mais ganharam e perderam partidas? 
- [ ] Quais jogadores participaram de mais copas? Quais fizeram mais gols?
- [ ] Existe uma relação entre o número da camisa e a quantidade de gols?
- [ ] Quais estádios são "pé quente" e registraram mais gols do Brasil?
- [ ] Quais partidas entre os mesmos países mais se repetiram? 
- [ ] Existe alguma tendência de aumento ou diminuição da quantidade de times participantes?

## Quais são os critérios de avaliação?
Os finalistas serão escolhidos pela equipe interna DATAB com base em insights, criatividade, design, visualizações e capacidade geral de storytelling (contar histórias com dados).

---

## Regras de negócio

**- Como o comparecimento do público evoluiu ao longo do tempo**
- Tabela WorldCupMatches
- Datetime = Data e hora da partida
- Attendance = Quantidade de torcedores no estádio
 
**-  Qual foi o público record (maior audiência registrada)?**
- Tabela WorldCupMatches
- Datetime = Data e hora da partida
- Attendance = Quantidade de torcedores no estádio

**- Ranking dos países campeões**
- Tabela WorldCups
- Year = Ano
- Winner = Campeão
- Mais dados complementares...

**- Quais times mais ganharam e perderam partidas?** 
- Tabela WorldCupMatches
- Home Team Name = Nome do time 1
- Home Team Goals = Quantidade de gols do time 1
- Away Team Goals = Nome do time 2
- Away Team Name = Quantidade de gols do time 2
- Calcular time vencedor e perdedor de acordo com o placar e contabilizar.

**- Quais jogadores participaram de mais copas? Quais fizeram mais gols?**
- Tabela WorldCupPlayers
- Player Name = Nome do jogador
- Event = Participação de evento na partida
- Tratar coluna Event que registra um Evento+TempoOcorrido, exemplo G23' = Gol aos 23 minutos de partida.

**- Existe uma relação entre o número da camisa e a quantidade de gols?**
- Tabela WorldCupPlayers
- Shirt Number = Número da camisa
- Event = Participação de evento na partida

**- Quais estádios são "pé quente" e registraram mais gols do Brasil?**
- Tabela WorldCupMatches
- Stadium = Estádio
- Home Team Name = Nome do time 1
- Home Team Goals = Quantidade de gols do time 1
- Away Team Goals = Nome do time 2
- Away Team Name = Quantidade de gols do time 2
- Contabilizar gols do Brasil por estádio e rankear

**- Quais partidas entre os mesmos países mais se repetiram?** 
**- Existe alguma tendência de aumento ou diminuição da quantidade de times participantes?**
- Criar gráfico de tendência do total de times participantes por ano.
- Tabela WorldCups
	- Year = Ano realizado
	- QualifiedTeams = Total de times participantes
