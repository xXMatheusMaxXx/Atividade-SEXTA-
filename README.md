# ATIVIDADE AVALIATIVA (TÓPICOS ESPECIAIS)

Nesta tarefa, você implementará um Agente Racional que limpa um quarto com o mínimo
possível de ações, e o objetivo é que todo o ambiente esteja limpo e o agente retorne ao lar
(localização de início A). 

# Parte A

Na Parte A, você precisa identificar o PEAS (Medida de Desempenho, Ambiente, Atuadores e
Sensores).

**PEAS (Performance measure, Environment, Actuators, Sensors)** é um acrônimo usado na inteligência artificial para descrever um sistema de agentes. Aqui está uma descrição do PEAS para o projeto do Agente Aspirador:

**Performance Measure:**
- **Energia do Agente:** A quantidade de energia que o agente tem. O agente perde energia ao executar ações e ganha energia ao voltar para a base.
- **Itens na Sacola:** O número de sujeiras que o agente coletou e colocou na sacola.
- **Limpeza do Ambiente:** O objetivo é maximizar a limpeza do ambiente, ou seja, minimizar o número de sujeiras no chão.
- **Eficiência Energética:** O objetivo é maximizar a limpeza do ambiente com o uso eficiente de energia.

**Environment:**
- O ambiente é uma grade 4x4 onde cada célula pode estar suja (1) ou limpa (0).
- O agente pode estar em uma das células da grade.
- O ambiente pode ser percebido pelo agente, permitindo que ele saiba se a célula em que ele está está suja ou limpa.

**Actuators:**
- **Movimento:** O agente pode mover-se para cima, para baixo, para a esquerda ou para a direita na grade.
- **Limpar:** O agente pode limpar a sujeira da célula em que está.
- **Retornar para Casa:** O agente pode retornar para a posição inicial (0, 0) para esvaziar a sacola.

**Sensors:**
- **Percepção de Sujeira:** O agente pode perceber se a célula em que está está suja ou limpa.
- **Percepção de Energia:** O agente pode perceber sua energia atual.
- **Percepção de Sacola:** O agente pode perceber quantos itens ele tem na sacola.
- **Percepção de Posição:** O agente sabe em qual célula da grade ele está localizado.

### Participantes
1. Matheus Max 1900989
2. Alexsander Rocha 1902161
3. Laís Pantoja 0560981
4. Samuel Sales 0199636
