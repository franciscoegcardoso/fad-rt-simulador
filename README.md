# Simulador de Decisões FAD-RT

Simulador parametrizado de decisões sobre a reforma tributária para estabelecimentos de alimentação fora do lar (restaurantes, padarias).

**Página publicada:** https://franciscoegcardoso.github.io/fad-rt-simulador/

## O que é

Protótipo funcional em arquivo único (HTML + JavaScript, sem servidor, sem banco de dados, sem serviço externo e sem IA generativa). Todos os cálculos rodam no navegador; nada é enviado para fora da máquina de quem abre a página.

Responde, para uma janela histórica de 12 meses:

- qual é a exposição do estabelecimento à reforma (impacto no resultado e no caixa);
- quanto disso depende de hipótese não verificada, e o que inverte a conclusão;
- quais alternativas atuam sobre as causas identificadas, com custos, datas e restrições;
- o que é executável, o que exige piloto, o que exige informação e o que não é conclusivo.

## Dados

A base que abre por padrão é **sintética e fictícia** ("Restaurante Vila Nova (demonstrativo)"), identificada como tal na própria interface. Não há dados de nenhum estabelecimento real neste repositório.

Quem quiser usar com dados próprios pode iniciar uma base vazia ou importar um pacote JSON dentro da própria página; esses dados ficam apenas no navegador (localStorage) e nunca são enviados a lugar nenhum.

## Validade fiscal

Motor 3.0.0 · regras 2026.09.2 · verificação normativa em 09/09/2026.

As regras marcadas como **verificadas** foram lidas na fonte primária (LC 214/2025, LC 227/2026, LC 123/2006, ADCT, Regulamento do IBS e anexos do Simples). As marcadas como **parciais**, **demonstrativas** ou **pendentes** não têm validade fiscal alegada. Alíquotas de referência de 2027 em diante são hipóteses até a resolução do Senado.

Este material não é consultoria tributária e não substitui a análise de um contador.
