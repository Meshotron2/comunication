## Contexto

Este projeto enquadra-se no projeto Meshotron, que pretende criar um ASH para análise acústica paralela de salas.

<!--
## Equipa

Deste projeto irão fazer parte os alunos do grupo 8 da unidade curricular PECI de LECI sendo eles:
- Bruno Silva
- João Felisberto
- Jodionísio Muachifi
- Marta Oliveira
- Ruben Castelhano
- Vasco Santos

Contando com a orientação do professor Guilherme Campos e coorientação do professor Arnaldo Oliveira.
-->

## Problema

Análise da propagação de som numa sala demora demasiado tempo e consome demasiados recursos.

Temos provas de que este modelo resolve estes problemas, mas fazer ASHs é muito caro.

O problema físico que queremos solucionar é a modelação acústica.

## Objetivos

- Tornar a análise sonora de uma sala mais financeiramente acessível.
- Implementar o Meshotron em unidades computacionais de baixo custo.
- Idealmente atingir velocidades perto de análise em tempo real para salas não muito grandes.
- Ter unidades que comunicam por links independentes.

## Tarefas

- Selecionar a placa
	+ Ter em conta os requisitos de comunicação
- Escolha dos switches
- Portar DWM para correr nas placas
- Fazer o programa que distribui os dados pelo cluster
- Website

## Resultados esperados

Para um cluster de N nós obter um processamento N vezes mais rápido.

Idealmente este projeto comprovará a viabilidade de se converter este cluster num ASH.

## Trabalho relacionado

- Sara Barros e Guilherme Campos (2010) ‘Unidades ASH para paralelização de modelos acústicos DWM tridimensionais’. 6as Jornadas Portuguesas de Arquitecturas Reconfiguráveis (REC’2010), Aveiro, Fevereiro 2010.
- Carlos Romeiro, Guilherme Campos e Arnaldo Oliveira (2011) ‘Design and Simulation of a Rectangular Meshotron Unit Prototype’. Symposium on Application Accelerators in High Performance Computing (SAAHPC’11), Knoxville, Tennessee, 19-21 Julho.
- Kris Wouk (2020) ‘Eight Awesome Raspberry Pi Clusters’. IoT Tech Trends.

## Calendário

![Calendário](./plano.PNG)

## Plano de comunicação

- Site \small https://meshotron2.github.io/comunication/meshotron/
- Github
- Jira
- Discord

## Distribuição de tarefas

Pela metodologia Agile será feita dinamicamente a cada sprint.

Todos os elementos do grupo irão trabalhar nas diferentes frentes de trabalho, num sistema de rotatividade.

No final de cada sprint cada um dos elementos poderá integrar uma frente diferente.
