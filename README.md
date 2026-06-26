# organizador-de-rotas-fluviais
Organizador de rotas de entrega para barcos regionais do tipo ferry boat, utilizando listas, dicionários, funções e algoritmos de ordenação em Python.
#  Organizador de Rotas de Entrega para Barcos Regionais
## Descrição

Este projeto foi desenvolvido para auxiliar no planejamento logístico de entregas e viagens fluviais na região amazônica, utilizando como estudo de caso uma rota ao longo do Rio Madeira. O sistema considera um modelo de navegação realizado por ferry boat, permitindo a organização das rotas de forma eficiente por meio de recursos da linguagem Python.

O sistema permite gerenciar comunidades e cidades, calcular distâncias e tempos de viagem, organizar destinos e simular atrasos causados por condições climáticas adversas.

O projeto foi implementado em Python utilizando estruturas básicas da linguagem, como listas, dicionários, funções, laços de repetição e condicionais.

##  Objetivo

Desenvolver uma aplicação capaz de:

Cadastrar novos destinos fluviais;
Exibir a rota completa de navegação;
Calcular a distância total percorrida;
Calcular o tempo total da viagem;
Identificar o destino mais distante;
Ordenar destinos por distância;
Simular atrasos provocados por chuva.

##  Contexto

Na Amazônia, muitas comunidades dependem exclusivamente do transporte fluvial para deslocamento de pessoas e mercadorias.

Um planejamento eficiente das rotas contribui para:

Redução de custos operacionais;
Melhor aproveitamento do tempo de viagem;
Maior eficiência logística;
Melhor atendimento às comunidades ribeirinhas.

## Tecnologias Utilizadas

Python 3
GitHub
Inteligência Artificial Generativa (ChatGPT) para apoio no desenvolvimento
Perplexity ai

##  Estruturas de Dados Utilizadas
Lista

A rota é armazenada em uma lista chamada rota.

rota = [
    {
        "cidade": "Borba",
        "distancia": 40,
        "tempo": "3:00"
    }
]

Dicionário

Cada destino é representado por um dicionário contendo:

Cidade
Distância
Tempo de viagem

Funcionalidades
1. Listar Rota

Exibe toda a sequência de cidades da rota fluvial.

2. Listar Destinos

Mostra todos os destinos cadastrados.

3. Cadastrar Destino

Permite adicionar novas comunidades à rota.

4. Ordenar por Distância

Utiliza o algoritmo Bubble Sort para ordenar os destinos.

5. Calcular Distância Total

Soma todas as distâncias cadastradas.

6. Calcular Tempo Total

Converte horários no formato hh para minutos e calcula o tempo total da viagem.

7. Destino Mais Distante

Identifica o destino com maior distância registrada.

8. Simulação de Chuva

Aplica um acréscimo de 20% no tempo total da viagem para simular atrasos climáticos.

## Rota Utilizada

O sistema utiliza como exemplo uma rota do Rio Madeira:

Manaus → Nova Olinda do Norte → Axinim → Borba → Novo Aripuanã → Manicoré

##  Metodologia de IA

Foi utilizada Inteligência Artificial Generativa (ChatGPT) como ferramenta de apoio durante o desenvolvimento do projeto.

A IA auxiliou em:

Interpretação dos requisitos;
Estruturação da lógica computacional;
Sugestões de algoritmos;
Revisão do código;
Produção da documentação.

## Exemplo de Saída

DESTINOS CADASTRADOS 

Nova Olinda do Norte - 120 km - 12:00

Axinim - 30 km - 2:30

Borba - 40 km - 3:00

Novo Aripuanã - 120 km - 9:00

Manicoré - 60 km - 3:30

## Integrantes

Elizabeth Freitas

Matheus Anverez
