# Miniguia de Estudos GA4

## Entendendo o Desafio

Este projeto foi desenvolvido como parte de um desafio da **DIO**, utilizando Inteligência Artificial como ferramenta de aprendizagem ativa.

O tema escolhido foi o **Google Analytics 4 (GA4)**, com o objetivo de organizar conhecimentos fundamentais sobre Web Analytics utilizando o **Google NotebookLM** para consulta e análise das fontes selecionadas.

## Objetivos

* Compreender os principais conceitos do GA4;
* Entender eventos, parâmetros, dimensões e métricas;
* Conhecer relatórios, explorações e conversões;
* Aprender boas práticas de análise e implementação;
* Utilizar IA para apoiar o processo de estudo e revisão.

---

# Curadoria de Fontes

Foram priorizadas fontes oficiais do Google:

* [Google Analytics Developers — Coleta de dados no GA4](https://developers.google.com/analytics/devguides/collection/ga4?hl=pt-br)
* [Google Analytics Help — Visão geral](https://support.google.com/analytics/answer/9164320?hl=en)
* [Google Analytics Help — Google Analytics 4](https://support.google.com/analytics/answer/10089681?hl=pt-br)

As fontes foram utilizadas como base para as consultas realizadas no NotebookLM.

---

# Engenharia de Prompts e Cicatrizes

## Prompt 1

> Quais as diferenças entre relatórios padrão e explorações personalizadas?

**Resultado:**
A resposta apresentou uma comparação clara entre os dois recursos, abordando características, possibilidades de personalização e objetivos de utilização.

**Aprendizado:**
Perguntas comparativas e objetivas facilitaram a compreensão das diferenças entre os recursos.

## Prompt 2

> O que muda no GA4 em 2026?

**Resultado:**
A resposta apresentou as principais novidades em tópicos.

**Cicatriz:**
Foi possível perceber que perguntas muito amplas podem gerar respostas genéricas. Para melhorar o resultado, é importante especificar o assunto, período e formato desejado.

Exemplo de melhoria:

> Quais foram as principais mudanças do GA4 em 2026 relacionadas a eventos, relatórios e coleta de dados? Organize por tópicos e utilize somente as fontes fornecidas.

---

# Miniguia de Estudo

## GA4

O **Google Analytics 4** é uma plataforma de análise de dados digitais baseada principalmente em eventos, permitindo acompanhar interações dos usuários em sites e aplicativos.

### Eventos

Representam ações realizadas pelos usuários.

Exemplos:

`page_view` · `click` · `view_item` · `add_to_cart` · `purchase`

### Parâmetros

São informações adicionais associadas aos eventos.

Exemplo:

`transaction_id` · `value` · `currency` · `item_id`

### Dimensões

Representam características dos dados.

Exemplos:

`País` · `Dispositivo` · `Origem` · `Campanha`

### Métricas

Representam valores quantitativos.

Exemplos:

`Usuários` · `Sessões` · `Eventos` · `Receita`

### Relatórios x Explorações

**Relatórios:** apresentam informações estruturadas para análises recorrentes.

**Explorações:** permitem análises mais personalizadas, utilizando diferentes dimensões, métricas e segmentos.

### Conversões

São ações importantes para os objetivos do negócio, como:

* Compra;
* Cadastro;
* Geração de lead;
* Envio de formulário.

---

# Glossário

| Termo          | Definição                                                              |
| -------------- | ---------------------------------------------------------------------- |
| **GA4**        | Plataforma de análise de dados do Google.                              |
| **Evento**     | Registro de uma interação do usuário.                                  |
| **Parâmetro**  | Informação adicional associada a um evento.                            |
| **Dimensão**   | Característica utilizada para analisar os dados.                       |
| **Métrica**    | Valor quantitativo utilizado na análise.                               |
| **Conversão**  | Ação importante para determinado objetivo.                             |
| **Exploração** | Recurso para análises personalizadas.                                  |
| **UTM**        | Parâmetros utilizados para identificar campanhas e origens de tráfego. |

---

# Prompts Reutilizáveis

### Revisão de conceito

> Explique o conceito de **[TEMA]** no GA4 utilizando linguagem simples e exemplos práticos.

### Comparação

> Compare **[CONCEITO A]** e **[CONCEITO B]** no GA4. Apresente as principais diferenças e exemplos de utilização.

### Troubleshooting

> Estou enfrentando o seguinte problema no GA4: **[PROBLEMA]**. Liste possíveis causas e apresente um passo a passo para diagnosticar o problema.

### Preparação para entrevista

> Crie 10 perguntas de entrevista sobre **Google Analytics 4**, separadas por nível iniciante, intermediário e avançado, apresentando também as respostas esperadas.

---

# Conclusão

A utilização do NotebookLM permitiu transformar fontes oficiais em um material de estudo mais organizado e facilitar a revisão dos principais conceitos do GA4.

O projeto também demonstrou a importância de elaborar prompts claros, analisar criticamente as respostas da IA e validar informações utilizando fontes confiáveis.

**Tema:** Google Analytics 4
**Ferramenta:** Google NotebookLM
**Plataforma:** DIO
