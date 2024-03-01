# school-reference-buildings
Reference models in EnergyPlus format for School Buildings

Objetivo:
O objetivo deste repositório é disponibilizar os modelos de referência de edificações educacionais desenvolvidos na tese de Matheus Geraldi entitulada: Building stock modelling for energy benchmarking of schools in Brazil

A geometria dos modelos de referência foram desenvolvidos no artigo: 
https://doi.org/10.1016/j.jobe.2021.103142

Demais características foram obtidas por meio de pesquisa ampla aplicada em todo o território nacional, e explicada no seguinte artigo: https://doi.org/10.1016/j.enbuild.2020.110209

E as demais características foram combinadas para formar uma base de dados que representa o estoque de edificações escolares. Este trabalho foi publciado no artigo: https://doi.org/10.1016/j.apenergy.2021.11796

Existem sete modelos de referência que representam as principais tipologias de edifícios educacionais no Brasil:

1) Rectangular
2) Shape U
3) Shape H
4) SHape L
5) Shape O
6) Shape E
7) Multiple Buildings

A partir destes modelos base, foram criados cenários de avaliação, e utilizada uma codificação para facilitar a análise:

A - Operation time (A1 = 8h/dia, A2=14h/dia).
B - Density of students in classrooms (B1 = 0.66 m²/pessoa, B2 = 1.25 m²/pessoa).
C - Total conditioned area (C1 = Only the administrative rooms (17% of the total area), C2 = Administrative rooms and classrooms (72% of the total area)).
D - Equipment Density Power (D1 = 7.15 W/m², D2 = 9.87 W/m²).
E - Lighting Density Power (E1 = 11.09 W/m², E = 2 - 3.37 W/m²).

Os valores adotados nos cenários foram obtidos por meio de análise de Entropia, a partir dos valores encontrados no estoque de edificações (descrito no artigo https://doi.org/10.1016/j.apenergy.2021.11796).

O modelo de simulação utiliza EMS (Energy Management System) no EnergyPlus para combinar o uso de ventilação natural e condicionamento de ar.

O uso destes modelos é permitido desde que citada a fonte:
GERALDI, M.S. Building stock modelling for energy benchmarking of schools in Brazil. Tese de Doutorado. Programa de Pós-Graduação em Engenharia Civil. Florianópolis. 2021.
