# Suíte de Testes do PC-SCJ

Esta pasta contém casos controlados para testar o comportamento do Segundo Cérebro Jurídico.

## Objetivo

A suíte não serve para provar que a IA está correta. Ela serve para descobrir onde o sistema pode:

- inventar fatos;
- inventar fontes;
- ignorar informação ausente;
- confundir fato com interpretação;
- usar norma desatualizada;
- apresentar uma hipótese como conclusão;
- escolher formato inadequado;
- deixar de apontar risco;
- calcular de forma incorreta;
- não executar a auditoria;
- produzir uma conclusão sem rastreabilidade.

## Regra de teste

Um caso de teste deve ter:

1. entrada controlada;
2. resultado esperado;
3. comportamento proibido;
4. critérios de aprovação;
5. resultado observado;
6. falhas encontradas;
7. correção proposta;
8. versão do protocolo testada.

## Classificação

- **T01–T09:** fundamentos de confiabilidade;
- **T10–T14:** pesquisa e fontes;
- **T15–T19:** raciocínio jurídico e teses;
- **T20–T24:** formato e produção;
- **T25–T29:** riscos, prazos e cálculos;
- **T30+:** casos complexos e regressão.

## Critério de aprovação

Um teste pode ser:

- **PASSOU** — comportamento esperado foi observado;
- **PASSOU COM RESSALVA** — resultado adequado, mas existe ponto a melhorar;
- **FALHOU** — violou requisito do PC-SCJ;
- **INCONCLUSIVO** — não há dados suficientes para avaliar.

## Regra de regressão

Quando uma alteração do PC-SCJ corrigir uma falha, o teste correspondente deve permanecer na suíte.

Uma nova versão do protocolo deve ser comparada com testes anteriores para verificar se a correção não criou uma nova falha.

## Índice

| ID | Teste | Objetivo | Tipo |
|---|---|---|---|
| T01 | Fato ausente | Impedir preenchimento silencioso de lacuna | Confiabilidade |
| T02 | Fonte inexistente | Impedir citação inventada | Confiabilidade |
| T03 | Lei desatualizada | Verificar controle temporal | Pesquisa |
| T04 | Fato x interpretação | Separar categorias | Raciocínio |
| T05 | Tese contrária | Verificar confronto de teses | Raciocínio |
| T06 | Formato inadequado | Verificar recomendação de formato | Formato |
| T07 | Dado crítico | Acionar regra de interrupção | Segurança |
| T08 | Jurisprudência controvertida | Expor divergência | Pesquisa |
| T09 | Documento incompleto | Detectar lacunas | Documento |
| T10 | Fonte primária | Priorizar fonte oficial | Pesquisa |
| T11 | Data relevante | Controlar direito intertemporal | Pesquisa |
| T12 | Fonte secundária | Não substituir fonte oficial sem justificativa | Pesquisa |
| T13 | Citação verificável | Rastrear fundamento | Pesquisa |
| T14 | Fonte contraditória | Identificar conflito | Pesquisa |
| T15 | Duelo de teses | Comparar teses | Raciocínio |
| T16 | Assunção | Identificar premissa não comprovada | Raciocínio |
| T17 | Hipótese | Não apresentar possibilidade como fato | Raciocínio |
| T18 | Omissão relevante | Detectar dado jurídico omitido | Raciocínio |
| T19 | Conclusão excessiva | Limitar inferência | Raciocínio |
| T20 | Matriz | Escolher formato comparativo | Formato |
| T21 | Fluxo | Representar decisões sequenciais | Formato |
| T22 | Checklist | Estruturar procedimento | Formato |
| T23 | Linha do tempo | Organizar eventos | Formato |
| T24 | Linguagem controlada | Aplicar PLJC | Produção |
| T25 | Prazo | Controlar premissas de contagem | Risco |
| T26 | Cálculo | Exigir fórmula e premissas | Cálculo |
| T27 | Prescrição | Aumentar nível de verificação | Risco |
| T28 | Valor relevante | Destacar risco financeiro | Risco |
| T29 | Procedimento atual | Verificar norma administrativa vigente | Risco |
| T30 | Caso complexo | Teste integrado | Regressão |

## Ficha padrão

Cada caso deve seguir o modelo:

- ID:
- Nome:
- Categoria:
- Versão do PC-SCJ:
- Entrada:
- Comando utilizado:
- Resultado esperado:
- Comportamentos proibidos:
- Critérios de aprovação:
- Resultado observado:
- Status:
- Falhas:
- Correção proposta:
- Impacto no protocolo:
- Data do teste:

## Próxima etapa

Os casos detalhados ficam em arquivos individuais ou agrupados por categoria.

A suíte deve crescer com base nos erros reais encontrados no uso do Segundo Cérebro.
