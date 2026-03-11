# Datathon-Fase-5-
Análise de dados e avaliação preditiva da Associação Passos Mágicos nos anos de 2022, 2023 e 2024.

Introdução

A Associação Passos Mágicos tem uma trajetória de 32 anos de atuação,
trabalhando na transformação da vida de crianças e jovens de baixa renda, os
levando a melhores oportunidades de vida.

Este trabalho propõe:

1 - Limpeza e análise de dados dos anos de 2022 a 2024;

2 - Responder dores do negócio relatadas no documento de apoio;

3 - modelo preditivo que mostre uma probabilidade do aluno ou aluna entrar em risco de defasagem;

4 - aplicação no Streamlit com o modelo preditivo gerado.


Limpeza do dataset

Para fins de melhor organização do trabalho,  a base de dados PEDE foi desmembrada em 3 planilhas, uma de 2022 (2022.xlsx), uma de 2023 (2023.xlsx) e outra de 2024 (2024.xlsx), após esse processo, aplicamos uma limpeza para padronização, conforme abaixo.


Limpezas aplicadas:

Gênero padronizado: Menina/Menino → Feminino/Masculino em todos os anos


Fase unificada: números (2022), textos variados (2023) e turmas como "3B" (2024) → formato único ALFA / FASE 1 ... FASE 8

Pedra corrigida: Agata → Ágata e INCLUIR → nulo

Colunas renomeadas: Matem → Mat, Portug → Por, Inglês → Ing, Defas → Defasagem, etc.

Instituição simplificada em categorias consistentes: Pública, Privada, Privada (Bolsa), Privada (Empresa), Concluído

INDE 2024 convertido de texto para numérico

