# IF722 - Tópicos Avançados Em Engenharia de Software
Grupo:
1. Caio Roberto da Silva Verçosa (crsv)
2. José Basilio da Silva Neto (jbsn3)
3. Ricardo Bizerra de Lima Filho (rblf)
4. Pedro Henrique de Oliveira Silva (phos)

## Contexto
O projeto tem como base o artigo "Translation Titans, Reasoning Challenges: Satisfiability-Aided Language Models for Detecting Conflicting Requirements", que explora o uso de LLMs para auxiliar na melhoria da completude dos requisitos em engenharia de software através de métodos formais. Nosso objetivo é expandir essa abordagem, investigando novas técnicas de aprendizado profundo para aprimorar a avaliação e validação de requisitos conflitantes encontrados no dataset [2].

Por meio de estratégias de processamento de linguagem natural, o objetivo é avaliar algumas lacunas e inconsistências encontradas na parte de metodologia do artigo, no qual não ficou muito evidente como foi executado a tradução de requisitos para especificação formal, além de avaliar novos modelos de LLMs e comparar com resultados encontrados neste artigo.

## Projeto
### 1. Identificação Direta de Conflitos com LLMs

O objetivo desta abordagem é avaliar a capacidade de novas versões de modelos de linguagem (LLMs) na identificação direta de conflitos e inconsistências em requisitos, sem a necessidade de conversão prévia para uma especificação formal. Utilizando técnicas de aprendizado profundo, busca-se explorar a eficácia dessas redes neurais na análise automatizada de requisitos, tornando o processo mais ágil e acessível.

### 2. Tradução de Requisitos para Linguagem Formal e Validação com Z3 Solver

Esta abordagem tem como objetivo investigar o uso de LLMs na tradução automática de requisitos para uma linguagem formal, garantindo maior precisão e estruturação na especificação. Além disso, será avaliada a eficácia desses modelos ao serem combinados com o Z3 solver para verificar a validade das traduções e identificar possíveis inconsistências na lógica formal dos requisitos.

## Referências
[1] Artigo: https://dl.acm.org/doi/abs/10.1145/3691620.3695302

[2] Dataset: https://zenodo.org/records/11000349

[3] Z3 Solver: https://microsoft.github.io/z3guide/programming/Z3%20JavaScript%20Examples
