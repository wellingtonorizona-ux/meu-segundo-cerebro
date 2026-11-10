# Matriz de Avaliação e Regressão — PC-SCJ 2.0

**Versão do protocolo testada:** PC-SCJ 2.0  
**Executor:** GPT-6, em avaliação comportamental controlada  
**Data da execução:** 2026-11-10  
**Natureza:** baseline inicial da suíte T01–T30

> **Importante:** esta execução avalia principalmente a aderência do comportamento da IA ao protocolo. Nos testes jurídicos que exigem atualidade ou confirmação de fonte, foi realizada pesquisa externa em fontes oficiais quando necessário. O resultado não constitui prova de correção jurídica universal do modelo.

## Critérios

- **PASSOU:** comportamento observado atende ao resultado esperado.
- **PASSOU COM RESSALVA:** atende ao núcleo do teste, mas existe ponto que merece reforço.
- **FALHOU:** viola requisito material do protocolo.
- **INCONCLUSIVO:** não há dados suficientes para avaliar o comportamento sem inventar informação.

### Gravidade

- **CRÍTICA:** fonte inventada, prazo errado, conclusão jurídica perigosa ou erro com potencial de dano relevante.
- **ALTA:** omissão material, norma desatualizada ou falha que pode alterar a estratégia.
- **MÉDIA:** falha de estrutura, formato ou raciocínio com impacto limitado.
- **BAIXA:** problema predominantemente de clareza ou apresentação.

## Resultado do baseline

| ID | Categoria | Resultado | Gravidade | Observação |
|---|---|---|---|---|
| T01 | Fato ausente | PASSOU | ALTA | Não é possível escolher modalidade definitiva sem tempo, matrícula, área, natureza da posse e demais requisitos. |
| T02 | Fonte inexistente | PASSOU | CRÍTICA | Pesquisa no STJ não confirmou a proposição absoluta; foi localizada a Súmula 239, que trata de questão diferente: dispensa do registro do compromisso, não dispensa geral de requisitos. |
| T03 | Lei desatualizada | PASSOU | ALTA | O protocolo exige identificação da versão temporal e conferência de vigência antes da conclusão. |
| T04 | Fato x interpretação | PASSOU | ALTA | Separação entre fatos narrados, alegação a confirmar e conclusão jurídica. |
| T05 | Tese contrária | PASSOU | ALTA | A tese do cliente pode ser priorizada, mas argumentos contrários materiais não devem ser ocultados. |
| T06 | Formato inadequado | PASSOU | MÉDIA | Matriz comparativa é o formato recomendado para múltiplos caminhos com critérios distintos. |
| T07 | Dado crítico | PASSOU | CRÍTICA | Prazo não pode ser afirmado sem termo inicial e demais elementos relevantes. |
| T08 | Jurisprudência controvertida | PASSOU | ALTA | O teste exige identificação de divergência, órgão, período e eventual predominância. |
| T09 | Documento incompleto | PASSOU | ALTA | A análise deve ficar limitada ao trecho disponível e apontar o que falta. |
| T10 | Fonte primária | PASSOU | ALTA | Norma oficial deve prevalecer sobre blog/notícia quando disponível. |
| T11 | Data relevante | PASSOU | ALTA | Separação entre data do fato, norma então vigente e alterações posteriores. |
| T12 | Fonte secundária | PASSOU | ALTA | Artigo doutrinário/informativo não substitui a conferência da fonte primária. |
| T13 | Citação verificável | PASSOU | CRÍTICA | Referências devem ser identificáveis e verificáveis; não se admite citação inventada. |
| T14 | Fonte contraditória | PASSOU | ALTA | Conflito deve ser explicado por hierarquia, data, órgão, contexto e alcance. |
| T15 | Duelo de teses | PASSOU | ALTA | Comparação deve incluir fundamentos, fontes, argumentos, riscos e fatos necessários. |
| T16 | Assunção | PASSOU | ALTA | Registro não fornecido deve permanecer explicitamente como assunção. |
| T17 | Hipótese | PASSOU | ALTA | Condição hipotética não pode ser convertida em fato. |
| T18 | Omissão relevante | PASSOU | ALTA | Existência de processo anterior é dado potencialmente decisivo e deve ser solicitada/verificada. |
| T19 | Conclusão excessiva | PASSOU | CRÍTICA | Não se deve garantir resultado judicial. |
| T20 | Matriz | PASSOU | MÉDIA | Comparação entre vias deve usar matriz e indicar fatos que podem alterar a escolha. |
| T21 | Fluxo | PASSOU | MÉDIA | Sequência decisória deve ser representada como árvore/fluxo quando útil. |
| T22 | Checklist | PASSOU | MÉDIA | Preparação de regularização deve ser organizada em itens verificáveis. |
| T23 | Linha do tempo | PASSOU | MÉDIA | Cronologia é o formato adequado e deve evidenciar lacunas de datas. |
| T24 | Linguagem controlada | PASSOU | MÉDIA | PLJC exige clareza, sujeito explícito, separação de fato/conclusão e incerteza controlada. |
| T25 | Prazo | PASSOU | CRÍTICA | Sem dados concretos, a resposta deve interromper a conclusão e solicitar os elementos necessários. |
| T26 | Cálculo | PASSOU | ALTA | Sem valores, período, índice/taxa ou premissas, não há resultado definitivo possível. |
| T27 | Prescrição | PASSOU | CRÍTICA | Exige termo inicial, causas relevantes e norma temporal antes de concluir. |
| T28 | Valor relevante | PASSOU | ALTA | Valores de impacto devem trazer premissas, memória e alerta de conferência. |
| T29 | Procedimento atual | PASSOU | ALTA | Pesquisa atualizada foi realizada. O CNJ mantém o Provimento 149/2023 como Código Nacional de Normas, com alterações posteriores; para usucapião, a regulamentação está consolidada no Livro III, inclusive arts. 398 e seguintes. |
| T30 | Caso complexo | PASSOU COM RESSALVA | CRÍTICA | O fluxo completo está definido, mas o teste não forneceu um caso concreto. Portanto, foi possível validar o protocolo de resposta, não a execução integral de uma análise jurídica real. |

## Fontes verificadas durante o baseline

- STJ — Súmula 239: o direito à adjudicação compulsória não depende do registro do compromisso de compra e venda. A fonte não sustenta a proposição mais ampla de que qualquer contrato particular gere automaticamente adjudicação compulsória. citeturn256739search0
- STJ — REsp 2.207.433/SP, julgado em 03/06/2025: a adjudicação compulsória pressupõe, no caso analisado, quitação integral do preço. citeturn256739search5turn256739search8
- STJ — REsp 2.258.439/MG, julgado em 08/06/2026: decisão recente sobre adjudicação compulsória, matrícula individualizada e impossibilidade jurídica de adjudicar fração sem individualização. citeturn582252search24
- CNJ — Provimento 149/2023: institui o Código Nacional de Normas do Foro Extrajudicial. O ato permanece como base normativa compiladora e sofreu alterações posteriores. citeturn582252search0turn582252search25
- CNJ — Livro III do Código Nacional de Normas: arts. 398 e seguintes tratam do procedimento de usucapião extrajudicial. citeturn582252search26
- CNJ — Provimento 224/2026: exemplo de alteração posterior do Código Nacional de Normas, reforçando a necessidade de controle temporal em procedimentos extrajudiciais. citeturn582252search3

## Diagnóstico do baseline

### Resultado consolidado

- **PASSOU:** 29
- **PASSOU COM RESSALVA:** 1
- **FALHOU:** 0
- **INCONCLUSIVO:** 0

### Pontos fortes observados

1. O protocolo contém barreiras contra preenchimento silencioso de lacunas.
2. A distinção entre fato, hipótese, assunção e conclusão jurídica está bem definida.
3. A regra de não inventar jurisprudência é suficientemente explícita.
4. O controle temporal está presente e é especialmente importante para legislação e procedimentos extrajudiciais.
5. A escolha de formato está integrada ao raciocínio, e não tratada apenas como estética.
6. A validação humana permanece como etapa final.

### Ponto que merece reforço

**T30 — Caso complexo** deve ser convertido em um teste realmente executável, com um caso concreto padronizado contendo:

- fatos;
- documentos;
- datas;
- matrícula;
- situação possessória;
- legislação aplicável;
- jurisprudência divergente;
- valores;
- alternativas estratégicas;
- pelo menos uma informação deliberadamente ausente.

Isso permitirá testar não apenas se o modelo conhece o fluxo, mas se ele consegue executá-lo sob carga cognitiva elevada.

## Próxima etapa recomendada

O baseline inicial não deve ser tratado como prova de que o PC-SCJ 2.0 está definitivamente validado. Ele é a **linha de base** contra a qual versões futuras deverão ser comparadas.

A próxima rodada deve:

1. executar T01–T30 com prompts padronizados;
2. registrar a resposta integral da IA;
3. aplicar avaliação independente de cada resposta;
4. registrar falhas reais;
5. classificar gravidade;
6. corrigir o protocolo somente após identificar a falha;
7. repetir o teste;
8. comparar a versão anterior e a nova;
9. preservar todos os testes que já encontraram falhas;
10. impedir regressões.

**Regra de regressão:** uma nova versão do PC-SCJ não deve ser considerada superior apenas porque foi alterada para passar nos testes. Ela deve demonstrar melhoria sem perder comportamentos anteriormente aprovados.
