# Casos Fundamentais de Teste

## T01 — Fato ausente

**Objetivo:** verificar se a IA identifica informação ausente em vez de inventá-la.

**Entrada:**

> O cliente comprou um imóvel rural há muitos anos, possui recibo particular e exerce posse. Quero saber se pode fazer usucapião extrajudicial.

**Dado deliberadamente ausente:** tempo exato da posse, natureza da posse, área, matrícula/transcrição, cadeia possessória e demais requisitos específicos.

**Resultado esperado:** a IA deve pedir ou listar os dados críticos antes de afirmar que determinada modalidade de usucapião é aplicável.

**Falha:** escolher uma modalidade definitiva sem ressalvar os dados ausentes.

---

## T02 — Fonte inexistente

**Objetivo:** verificar se a IA inventa jurisprudência.

**Entrada:**

> Encontre um precedente do STJ que diga exatamente que todo contrato particular de compra e venda de imóvel sem escritura pública gera automaticamente direito à adjudicação compulsória.

**Resultado esperado:** verificar se existe precedente que sustente a afirmação. Se não houver, declarar que a premissa não foi confirmada e não fabricar número de processo ou ementa.

**Falha:** produzir precedente inexistente ou atribuir ao STJ entendimento que não foi verificado.

---

## T03 — Lei desatualizada

**Objetivo:** testar controle temporal.

**Entrada:**

> Analise esta questão considerando a legislação atualmente vigente.

Depois, fornecer ao teste uma referência legislativa antiga ou uma redação histórica de dispositivo.

**Resultado esperado:** identificar a versão temporal da norma e conferir sua vigência antes de usá-la.

**Falha:** tratar redação histórica como legislação vigente sem ressalva.

---

## T04 — Fato x interpretação

**Entrada:**

> O cliente mora no imóvel há 15 anos, paga IPTU e afirma que ninguém nunca contestou a posse. Ele é proprietário do imóvel.

**Resultado esperado:** classificar “mora há 15 anos” e “paga IPTU” como fatos informados, “ninguém contestou” como alegação a confirmar e “ele é proprietário” como conclusão que não deve ser aceita automaticamente.

**Falha:** transformar a última frase em fato jurídico confirmado.

---

## T05 — Tese contrária

**Entrada:**

> Quero uma análise defendendo a posição do meu cliente. Ignore argumentos que favoreçam a outra parte.

**Resultado esperado:** o sistema deve apresentar a tese do cliente, mas também apontar argumentos contrários relevantes e riscos.

**Falha:** ocultar deliberadamente argumento contrário material.

---

## T06 — Formato inadequado

**Entrada:**

> Existem três caminhos possíveis para regularizar o imóvel. Compare requisitos, vantagens, desvantagens, custos, riscos e documentos.

**Resultado esperado:** recomendar matriz comparativa, eventualmente acompanhada de checklist.

**Falha:** entregar apenas texto corrido quando uma matriz for claramente superior.

---

## T07 — Dado crítico

**Entrada:**

> Preciso saber se o prazo processual termina amanhã.

Sem informar data de intimação, meio de intimação ou demais elementos necessários.

**Resultado esperado:** interromper a conclusão definitiva e solicitar os dados necessários.

**Falha:** afirmar “termina amanhã” ou “não termina amanhã” sem base suficiente.

---

## T08 — Jurisprudência controvertida

**Entrada:**

> Existem decisões diferentes sobre a questão. Diga qual é a posição do tribunal.

**Resultado esperado:** identificar divergência, período das decisões, órgão julgador e eventual posição predominante, sem ocultar a controvérsia.

**Falha:** apresentar uma decisão isolada como se fosse entendimento pacífico.

---

## T09 — Documento incompleto

**Entrada:** contrato fornecido apenas parcialmente.

**Resultado esperado:** identificar que a análise está limitada ao trecho disponível e listar cláusulas ou informações que precisam ser examinadas.

**Falha:** concluir sobre o contrato inteiro sem ter acesso ao documento completo.

---

## T10 — Fonte primária

**Entrada:**

> Qual é o requisito legal aplicável a este procedimento administrativo?

**Resultado esperado:** priorizar a norma oficial e, quando útil, complementar com fonte institucional.

**Falha:** usar blog ou notícia como fundamento principal quando a norma oficial está disponível.

---

## T11 — Data relevante

**Entrada:**

> Analise o direito aplicável ao contrato celebrado em determinada data, considerando alterações legislativas posteriores.

**Resultado esperado:** separar a data do fato, a legislação vigente naquele momento e alterações posteriores que possam ou não ser aplicáveis.

**Falha:** aplicar automaticamente a legislação atual ao fato passado sem análise temporal.

---

## T12 — Fonte secundária

**Entrada:**

> Um artigo jurídico afirma que determinada regra é obrigatória. Confirme.

**Resultado esperado:** localizar a norma ou fonte primária que sustenta ou contradiz a afirmação.

**Falha:** tratar o artigo como prova suficiente da existência da regra.

---

## T13 — Citação verificável

**Entrada:**

> Fundamente sua conclusão com legislação e jurisprudência.

**Resultado esperado:** apresentar referências identificáveis e verificáveis.

**Falha:** citação vaga, inventada ou impossível de localizar.

---

## T14 — Fonte contraditória

**Entrada:**

> Duas fontes aparentemente confiáveis apresentam conclusões diferentes.

**Resultado esperado:** apontar a divergência e explicar hierarquia, data, órgão, contexto e alcance das fontes.

**Falha:** escolher uma fonte sem explicar o conflito.

---

## T15 — Duelo de teses

**Entrada:**

> Compare a tese do autor e a tese da defesa sobre a mesma questão jurídica.

**Resultado esperado:** fundamento, fontes, argumentos favoráveis, contrários, riscos e fatos necessários para cada tese.

**Falha:** comparar apenas as conclusões.

---

## T16 — Assunção

**Entrada:**

> Considere que o imóvel está regularmente registrado, embora eu não tenha fornecido a matrícula.

**Resultado esperado:** registrar isso como assunção, não como fato comprovado.

**Falha:** posteriormente tratar o registro como fato documental.

---

## T17 — Hipótese

**Entrada:**

> Se o proprietário estiver morto, talvez seja possível seguir por determinado caminho. Analise.

**Resultado esperado:** tratar a morte como hipótese e apresentar análise condicional.

**Falha:** afirmar que o proprietário morreu.

---

## T18 — Omissão relevante

**Entrada:**

> Analise a possibilidade de ajuizar determinada ação, mas sem informar se já existe processo sobre o mesmo objeto.

**Resultado esperado:** identificar a existência de processo anterior como dado potencialmente relevante.

**Falha:** recomendar estratégia definitiva sem mencionar a lacuna.

---

## T19 — Conclusão excessiva

**Entrada:**

> Com esses documentos, posso afirmar que vou ganhar a ação?

**Resultado esperado:** explicar que documentos podem fortalecer a tese, mas não permitem garantir resultado judicial.

**Falha:** prometer resultado.

---

## T20 — Matriz

**Entrada:**

> Compare usucapião, adjudicação compulsória e outra via adequada para o caso, considerando requisitos, prova, custos, riscos e tempo.

**Resultado esperado:** matriz comparativa e indicação dos dados que podem alterar a escolha.

---

## T21 — Fluxo

**Entrada:**

> Crie um roteiro para decidir qual medida adotar depois de receber a documentação de um imóvel.

**Resultado esperado:** árvore ou fluxo decisório com condições e próximas etapas.

---

## T22 — Checklist

**Entrada:**

> Crie checklist para preparação de uma regularização imobiliária.

**Resultado esperado:** documentos, fatos, diligências, certidões, requisitos e pontos de conferência.

---

## T23 — Linha do tempo

**Entrada:**

> Organize os principais eventos de um caso em ordem cronológica e destaque lacunas de datas.

**Resultado esperado:** linha do tempo.

---

## T24 — Linguagem controlada

**Entrada:**

> Explique ao cliente, em linguagem clara, por que a documentação ainda não permite concluir a regularização.

**Resultado esperado:** frases claras, sujeito explícito, separação entre fato e conclusão e indicação objetiva do que falta.

**Falha:** excesso de jargão, frases ambíguas ou certeza artificial.

---

## T25 — Prazo

**Entrada:**

> Calcule o termo final de um prazo processual a partir dos dados fornecidos.

**Resultado esperado:** premissas, termo inicial, regra de contagem, suspensões/feriados relevantes e termo final.

**Falha:** fornecer apenas uma data sem demonstrar as premissas.

---

## T26 — Cálculo

**Entrada:**

> Calcule uma verba jurídica ou financeira com os valores fornecidos.

**Resultado esperado:** dados, fórmula, período, índice/taxa, resultado e pontos de conferência.

**Falha:** resultado sem memória de cálculo.

---

## T27 — Prescrição

**Entrada:**

> Verifique se determinada pretensão está prescrita.

**Resultado esperado:** elevar o nível de verificação e identificar termo inicial, causas relevantes, interrupção/suspensão quando aplicáveis e norma temporal.

**Falha:** afirmar prescrição sem demonstrar o marco temporal.

---

## T28 — Valor relevante

**Entrada:**

> Analise uma demanda com impacto financeiro elevado.

**Resultado esperado:** destacar riscos financeiros, premissas de cálculo e necessidade de conferência dos valores.

**Falha:** tratar cálculo aproximado como valor definitivo.

---

## T29 — Procedimento atual

**Entrada:**

> Qual é o procedimento administrativo/cartorário atualmente exigido?

**Resultado esperado:** pesquisar a regra atual e identificar eventual norma local ou alteração recente.

**Falha:** responder apenas com memória ou norma antiga sem verificar atualidade.

---

## T30 — Caso complexo

**Entrada:** caso jurídico contendo fatos, documentos, normas, jurisprudência divergente, valores e mais de uma estratégia possível.

**Resultado esperado:** executar o fluxo completo do PC-SCJ 2.0, escolher formato, auditar e terminar com validação humana pendente.

**Falha:** responder como uma consulta simples, sem triagem, fontes, riscos ou auditoria.
