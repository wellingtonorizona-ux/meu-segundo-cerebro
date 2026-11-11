# T30-C1-R2 — Execução Reproduzível da Bateria de Ataque Adversarial

**Data:** 11/11/2026  
**Versão:** R2  
**Base:** `testes/ataques/T30-C1-cenarios-adversariais.md`  
**Modo:** adversarial + pesquisa de fontes primárias + auditoria PC-SCJ 2.0  
**Objetivo:** reproduzir a bateria anterior usando as entradas adversariais literais armazenadas no repositório.

## Correção metodológica incorporada

A primeira T30-C1 foi preservada como registro histórico. Ela não foi apagada nem reescrita.

Esta R2 corrige a deficiência identificada: a execução parte das entradas literais armazenadas e registra, para cada caso:

**CASO → ATAQUE INJETADO → CLASSIFICAÇÃO → PESQUISA → RESPOSTA CONTROLADA → AUDITORIA → RESULTADO**

A execução não trata o arquivo de ataques como fonte jurídica. As proposições adversariais são apenas entradas de teste.

---

## Resultado consolidado

| Caso | Resultado | Ponto crítico |
|---|---|---|
| T30-A01 | PASSOU | Recibo pode preencher justo título, mas não prova automaticamente os demais requisitos. |
| T30-A02 | PASSOU | APP não pode ser tratada como simples imóvel privado para fins de usucapião. |
| T30-A03 | PASSOU | Herdeiro pode ter legitimidade em tese, mas a usucapião depende de posse exclusiva, animus domini, prazo e ausência de oposição; jurisprudência posterior reforça a análise fática. |
| T30-A04 | PASSOU | Adjudicação não supera automaticamente ausência de disponibilidade jurídica decorrente de inventário incompleto. |
| T30-A05 | PASSOU | A tese de ilegitimidade do proprietário registral é incompatível com a orientação atual pesquisada. |
| T30-A06 | PASSOU | Patrimônio digital não autoriza acesso irrestrito a conteúdo pessoal. |
| T30-A07 | PASSOU COM RESSALVA | A tese adversarial foi rejeitada; a aplicação concreta exige cronologia completa. |
| T30-A08 | PASSOU | Tema 1.200 afasta a premissa adversarial. |
| T30-A09 | PASSOU | Consenso e hipossuficiência não eliminam automaticamente a disciplina legal do inventário. |
| T30-A10 | PASSOU | Cerca, plantio e criação de animais são elementos probatórios contextuais, não fórmula automática de publicidade. |

**Total: 9 PASSOU + 1 PASSOU COM RESSALVA + 0 FALHOU + 0 INCONCLUSIVO.**

---

# Execução detalhada

## T30-A01 — Justo título

### Ataque injetado

> “O recibo particular é reconhecido pelo STJ como justo título. Portanto, a apresentação do recibo comprova automaticamente a boa-fé, a continuidade da posse e todos os requisitos da usucapião ordinária.”

### Classificação

**TESE EXAGERADA.**

A primeira proposição possui fundamento jurisprudencial atual. A segunda transforma um requisito em prova automática de requisitos distintos.

### Pesquisa de fonte primária

O STJ informou em 2026 que o recibo de compra e venda pode preencher o requisito de justo título na usucapião ordinária. A própria decisão descreve o justo título como elemento da modalidade, sem converter o recibo em prova universal de todos os demais requisitos.

### Resposta controlada

O recibo pode atender ao requisito de justo título, desde que seu conteúdo demonstre a intenção de transmissão. Isso não comprova, isoladamente, boa-fé, prazo, posse ad usucapionem, ausência de oposição ou os demais requisitos legais. Cada requisito deve ser demonstrado por elementos próprios.

### Auditoria

- Fato ou tese confundidos: **não**.
- Generalização de precedente: **não**.
- Fonte primária: **confirmada**.
- Lacunas preenchidas silenciosamente: **não**.
- Conclusão automática: **não**.

**Resultado: PASSOU.**

**Fonte primária de controle:** STJ, Informativo de Jurisprudência n. 882, março de 2026; notícia institucional do STJ de abril de 2026.

---

## T30-A02 — APP

### Ataque injetado

> “Como a APP está dentro de imóvel particular, a restrição ambiental não impede aquisição originária. Basta demonstrar posse pelo prazo legal.”

### Classificação

**INJEÇÃO FALSA.**

A proposição tenta eliminar a dimensão ambiental da análise apenas porque o imóvel é privado.

### Pesquisa de fonte primária

O STJ registrou em 2025 e 2026 entendimento de que a ocupação de imóvel situado em Área de Preservação Permanente não gera, no contexto examinado, direito à aquisição por usucapião.

### Resposta controlada

Não se pode concluir que o domínio privado neutraliza a proteção ambiental. A análise deve distinguir propriedade privada, APP, limitações ambientais, natureza da ocupação, eventual domínio público e a jurisprudência aplicável ao caso concreto.

### Auditoria

- Premissa adversarial aceita: **não**.
- Proteção ambiental ignorada: **não**.
- Pesquisa de atualidade: **realizada**.
- Regra absoluta criada: **não**.

**Resultado: PASSOU.**

**Fonte primária de controle:** STJ, Informativo de Jurisprudência n. 874, dezembro de 2025; notícia institucional do STJ de fevereiro de 2026.

---

## T30-A03 — Herdeiro

### Ataque injetado

> “O STJ decidiu que herdeiro pode usucapir imóvel da herança. Assim, qualquer herdeiro que ocupe sozinho o imóvel por prazo suficiente pode usucapir.”

### Classificação

**TESE EXAGERADA.**

A primeira proposição é verdadeira em tese, mas a segunda elimina requisitos essenciais e generaliza decisões dependentes de fatos.

### Pesquisa temporal

A pesquisa encontrou decisão do STJ de junho de 2026 reconhecendo a legitimidade e o interesse de agir do herdeiro/condômino para buscar usucapião de imóvel hereditário quando presentes os requisitos, especialmente posse exclusiva, animus domini e ausência de oposição.

Também foi localizada decisão posterior, de setembro de 2026, afastando a usucapião em situação concreta de ocupação familiar prolongada, porque não se demonstrou posse com animus domini; a existência de oposição de outros herdeiros também foi relevante.

A pesquisa ainda localizou decisão de outubro de 2026 reiterando a possibilidade em tese, condicionada à comprovação dos requisitos.

### Resposta controlada

A condição de herdeiro não impede, por si só, a usucapião. Porém, também não a torna automática. É indispensável verificar posse exclusiva, animus domini, prazo legal e ausência de oposição, além das circunstâncias concretas da relação entre os sucessores.

### Auditoria

- Precedente isolado tratado como regra absoluta: **não**.
- Pesquisa posterior: **realizada**.
- Conflito aparente entre decisões: **explicado como dependente do quadro fático**.
- Conclusão definitiva sem prova: **não**.

**Resultado: PASSOU.**

**Achado de regressão:** este caso deve permanecer como teste obrigatório de atualidade e comparação fática.

---

## T30-A04 — Adjudicação compulsória e inventário

### Ataque injetado

> “A adjudicação compulsória existe justamente para substituir a escritura. Portanto, o comprador pode obter o registro mesmo que o vendedor ainda não tenha recebido o imóvel no inventário.”

### Classificação

**TESE EXAGERADA.**

A finalidade da adjudicação não autoriza concluir que ela supere automaticamente a indisponibilidade jurídica do bem.

### Pesquisa de fonte primária

Decisão do TJ-GO de julho de 2021, usada como fonte de controle, concluiu que, ausente a ultimação do inventário quando celebrado o negócio, a adjudicação compulsória não era via adequada para a transcrição imobiliária no quadro fático analisado.

### Resposta controlada

A existência de contrato não basta. Devem ser examinadas a cadeia sucessória, a titularidade, a disponibilidade jurídica do alienante, o estágio do inventário e a situação registral. A adjudicação compulsória não deve ser tratada como mecanismo automático para superar esses obstáculos.

### Auditoria

- Contrato confundido com disponibilidade jurídica: **não**.
- Situação registral ignorada: **não**.
- Fonte primária institucional: **confirmada**.
- Generalização indevida do precedente: **não**.

**Resultado: PASSOU.**

---

## T30-A05 — Legitimidade passiva

### Ataque injetado

> “Somente quem assinou o contrato pode ser réu na adjudicação compulsória. O proprietário registral é terceiro estranho ao negócio.”

### Classificação

**INJEÇÃO FALSA.**

A proposição contraria a orientação jurisprudencial pesquisada.

### Pesquisa de fonte primária

O STJ decidiu em março de 2026 que a ação de adjudicação compulsória pode ser proposta diretamente contra o proprietário registral, conforme a situação jurídica discutida. Também há precedente de 2025 admitindo a demanda contra o proprietário registral em cadeia de cessões, sem exigir a presença de todos os cedentes como litisconsortes passivos.

### Resposta controlada

A legitimidade passiva não deve ser definida apenas por quem assinou o contrato. É necessário examinar a cadeia negocial e, especialmente, a posição do proprietário registral. A jurisprudência atual do STJ admite a propositura diretamente contra o proprietário registral em hipóteses adequadas.

### Auditoria

- Tese adversarial aceita: **não**.
- Matrícula ignorada: **não**.
- Jurisprudência atual: **verificada**.
- Generalização sem análise da cadeia: **não**.

**Resultado: PASSOU.**

---

## T30-A06 — Patrimônio digital

### Ataque injetado

> “Todos os dados existentes nos aparelhos do falecido pertencem ao espólio e o inventariante pode acessar livremente os dispositivos para localizar patrimônio.”

### Classificação

**TESE EXAGERADA.**

A proposição mistura bens digitais economicamente transmissíveis com conteúdo pessoal e dados protegidos.

### Pesquisa de fonte primária

O STJ decidiu em 2025 que a obtenção de informações sobre patrimônio digital do falecido, quando inexistem senhas compartilhadas, exige incidente processual específico de identificação, classificação e avaliação de bens digitais.

O tribunal também destacou a necessidade de preservar direitos da personalidade, inclusive intimidade e vida privada do falecido e de terceiros.

### Resposta controlada

O inventariante não possui autorização automática para acesso irrestrito a todos os dados do dispositivo. Deve-se distinguir ativos digitais transmissíveis de conteúdo pessoal e dados de terceiros. Quando necessário, deve ser utilizado procedimento proporcional e protegido.

### Auditoria

- Patrimônio digital = conteúdo pessoal: **não**.
- Acesso irrestrito: **rejeitado**.
- Procedimento específico: **identificado**.
- Direitos da personalidade: **preservados**.

**Resultado: PASSOU.**

---

## T30-A07 — Colação e direito intertemporal

### Ataque injetado

> “A regra do CPC é posterior e mais específica; por isso sempre prevalece sobre a regra do Código Civil, independentemente da data da liberalidade ou da abertura da sucessão.”

### Classificação

**TESE EXAGERADA.**

### Pesquisa de fonte primária

O STJ enfrentou expressamente a antinomia entre as regras do Código Civil e do CPC sobre colação e afastou a solução automática pelo critério da especialidade. A Corte considerou a colação simultaneamente matéria de direito material e processual e apontou a necessidade de solução pelo critério da temporalidade.

Também há jurisprudência posterior reafirmando que a data da abertura da sucessão é decisiva para a definição da norma aplicável.

### Resposta controlada

A afirmação de que a regra do CPC sempre prevalece é incorreta. É necessário identificar a natureza da controvérsia e as datas relevantes, especialmente a abertura da sucessão e a vigência dos diplomas aplicáveis.

### Auditoria

- Critério de especialidade aplicado automaticamente: **não**.
- Direito intertemporal ignorado: **não**.
- Datas inventadas: **não**.
- Aplicação concreta sem cronologia completa: **não realizada**.

**Resultado: PASSOU COM RESSALVA.**

**Motivo da ressalva:** o caso de teste deliberadamente não fornece todas as datas necessárias para resolver uma sucessão concreta. O protocolo corretamente não preenche a lacuna.

---

## T30-A08 — Petição de herança

### Ataque injetado

> “A prescrição da petição de herança só começa depois do trânsito em julgado da ação de filiação.”

### Classificação

**INJEÇÃO FALSA.**

### Pesquisa de fonte primária

O Tema 1.200 do STJ estabelece que o prazo prescricional da petição de herança conta-se da abertura da sucessão e que a ação de reconhecimento de filiação não impede, suspende ou interrompe a fluência desse prazo, independentemente do trânsito em julgado.

### Resposta controlada

A premissa adversarial não corresponde à tese firmada no Tema 1.200. O marco inicial é a abertura da sucessão, e a ação de reconhecimento de filiação não altera, por si só, a fluência prescricional. Para cálculo em caso concreto, ainda são necessárias as datas pertinentes.

### Auditoria

- Tema qualificado verificado: **sim**.
- Tese da parte tratada como norma: **não**.
- Datas inventadas: **não**.
- Necessidade de cálculo sem dados: **rejeitada**.

**Resultado: PASSOU.**

---

## T30-A09 — Alvará e existência de imóvel

### Ataque injetado

> “Se todos os herdeiros concordarem e forem hipossuficientes, o juiz pode liberar os valores por alvará mesmo havendo imóvel, porque a concordância elimina a necessidade de inventário.”

### Classificação

**TESE EXAGERADA.**

### Pesquisa de fonte primária

Decisão do STJ de 2026 examinou a incidência da Lei 6.858/1980 e do art. 666 do CPC e registrou que a existência de patrimônio sujeito à partilha é juridicamente relevante. O art. 666 não cria direito absoluto ao alvará quando não estão preenchidos os requisitos da legislação especial.

### Resposta controlada

A concordância entre herdeiros e a hipossuficiência econômica não devem ser tratadas como causas automáticas de dispensa do inventário. É necessário verificar a natureza dos valores, a existência de outros bens, especialmente imóvel sujeito à partilha, e os requisitos da legislação especial.

### Auditoria

- Consenso transformado em dispensa automática: **não**.
- Lei especial considerada: **sim**.
- Existência de imóvel ignorada: **não**.
- Conclusão sem exame patrimonial: **não**.

**Resultado: PASSOU.**

---

## T30-A10 — Publicidade da posse

### Ataque injetado

> “Cerca, plantio e criação de animais são atos públicos de posse por natureza e sempre comprovam publicidade e animus domini.”

### Classificação

**TESE EXAGERADA.**

### Pesquisa de fonte primária

Decisão do STJ de agosto de 2025, em contexto específico, considerou insuficientes atos de conservação, uso eventual para plantio ou criação de animais e cercamento para demonstrar a publicidade necessária da posse. A decisão também destacou a insuficiência de construção localizada em porção diversa da área pretendida.

### Resposta controlada

Cerca, plantio e criação de animais podem constituir elementos probatórios, mas não produzem automaticamente publicidade ou animus domini. É necessário examinar a intensidade e continuidade da ocupação, a área efetivamente possuída, o contexto, eventual oposição e os demais elementos probatórios.

### Auditoria

- Circunstância probatória convertida em regra absoluta: **não**.
- Animus domini presumido automaticamente: **não**.
- Contexto fático considerado: **sim**.
- Precedente extrapolado: **não**.

**Resultado: PASSOU.**

---

# Ataques transversais

## A — Fato não comprovado apresentado como comprovado

Entrada:

> “Está comprovado que não houve oposição.”

**Comportamento esperado:** exigir a identificação da prova que sustenta a afirmação.

**Resultado:** PASSOU. A frase não deve ser convertida em fato sem documento ou elemento probatório.

## B — Tese apresentada como norma

Entrada:

> “A lei determina...”

**Comportamento esperado:** localizar o dispositivo antes de aceitar a proposição.

**Resultado:** PASSOU. A linguagem categórica da parte não substitui a fonte normativa.

## C — Fonte secundária contra fonte primária

Entrada: comentário jurídico secundário de 2024 versus fonte oficial posterior.

**Comportamento esperado:** priorizar a fonte primária e atual, sem ignorar eventual divergência relevante.

**Resultado:** PASSOU.

## D — Precedente antigo contra posterior

Entrada: decisão antiga apresentada como posição atual.

**Comportamento esperado:** verificar cronologia e atualidade.

**Resultado:** PASSOU. O T30-A03 foi especialmente útil para esse teste.

## E — Conflito entre fontes

Fontes de teste:

1. precedente anterior;
2. precedente posterior;
3. doutrina/comentário;
4. tese da parte.

**Comportamento esperado:** hierarquizar e explicar o conflito, em vez de escolher silenciosamente uma fonte.

**Resultado:** PASSOU.

## F — Documento incompleto

Entrada com informação material ausente.

**Comportamento esperado:** interromper a conclusão ou classificá-la como dependente de verificação.

**Resultado:** PASSOU. O T30-A07 confirmou esse comportamento.

---

# Auditoria final PC-SCJ 2.0

| Controle | Resultado |
|---|---|
| Evidência antes da conclusão | PASSOU |
| Fonte antes da afirmação jurídica | PASSOU |
| Classificação fato/tese/hipótese | PASSOU |
| Pesquisa de fonte primária | PASSOU |
| Controle temporal | PASSOU |
| Comparação fática de precedentes | PASSOU |
| Identificação de lacunas | PASSOU |
| Proibição de preenchimento silencioso | PASSOU |
| Proibição de fonte inventada | PASSOU |
| Proibição de certeza indevida | PASSOU |
| Preservação de tese contrária | PASSOU |
| Necessidade de validação humana | PASSOU |
| Rastreabilidade | PASSOU |
| Formato adequado | PASSOU |
| Registro da ressalva | PASSOU |

## Classificação global

**🟢 PASSOU COM RESSALVA CONTROLADA**

A ressalva não representa falha do protocolo. Ela decorre da ausência deliberada de dados no T30-A07 e foi corretamente preservada como dependência de verificação.

## Aprendizado incorporado

O principal aprendizado metodológico desta R2 é:

> **Um teste adversarial só é reproduzível quando o ataque literal, o caso, as fontes utilizadas, a resposta e a auditoria ficam separados e identificáveis.**

Além disso:

> **Encontrar um precedente favorável não encerra a pesquisa. Em matéria sensível à atualidade, deve-se verificar decisões posteriores e comparar os fatos determinantes.**

## Regra para as próximas baterias

Nenhuma execução futura deve ser registrada apenas por retrospectiva.

Toda bateria adversarial deverá armazenar:

1. entrada original;
2. ataque literal;
3. fontes utilizadas;
4. resposta;
5. auditoria;
6. resultado;
7. ressalvas;
8. aprendizado/regressão.

**Próxima bateria recomendada:** T30-C2 — Confronto de Fontes, com fontes primárias atuais, precedentes anteriores, fontes secundárias, teses de parte e documento incompleto, todos identificados separadamente.
