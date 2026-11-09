# PC-SCJ 1.0 — Protocolo de Confiabilidade do Segundo Cérebro Jurídico

- **Versão:** 1.0
- **Data:** 2026-11-09
- **Status:** Em desenvolvimento
- **Finalidade:** estabelecer uma camada de confiabilidade, rastreabilidade e auditoria para análises jurídicas assistidas por IA.

> **Regra-mãe:** A IA pode produzir uma conclusão. Ela não pode transformar sua própria conclusão em fato.

## 1. Objetivo

O PC-SCJ não promete respostas infalíveis. Seu objetivo é reduzir o risco de erro ao exigir:

- identificação da origem das informações;
- distinção entre fato e interpretação;
- hierarquia de fontes;
- explicitação de incertezas;
- verificação de afirmações jurídicas relevantes;
- rastreabilidade da análise;
- auditoria antes do uso profissional;
- validação humana.

## 2. Princípios

1. Evidência antes da conclusão.
2. Fonte antes da afirmação jurídica.
3. Incerteza explícita antes de falsa certeza.
4. Auditoria antes de utilização profissional.
5. Decisão final humana.
6. A ausência de informação nunca deve ser preenchida por suposição silenciosa.
7. Uma citação jurídica deve ser verificável.
8. A data da análise e a vigência normativa devem ser consideradas.

## 3. Fluxo operacional

1. Receber.
2. Identificar.
3. Classificar fatos.
4. Identificar lacunas.
5. Pesquisar fontes.
6. Hierarquizar fontes.
7. Analisar.
8. Identificar teses.
9. Escolher o formato.
10. Justificar o formato.
11. Produzir.
12. Classificar confiabilidade.
13. Executar o modo VERIFIQUE-ME.
14. Auditar fontes e raciocínio.
15. Identificar incertezas.
16. Registrar o log.
17. Submeter ao advogado.
18. Validar.
19. Arquivar.

## 4. Classificação das informações

Toda informação relevante deve receber uma categoria:

- **F — Fato:** informação documental ou expressamente fornecida pelo usuário.
- **N — Norma:** Constituição, lei, decreto, resolução, provimento ou outro ato normativo.
- **J — Jurisprudência:** decisão ou entendimento de órgão jurisdicional identificável.
- **D — Doutrina:** obra ou produção acadêmica ou profissional qualificada.
- **I — Interpretação:** conclusão construída a partir das fontes e dos fatos.
- **H — Hipótese:** possibilidade ainda não confirmada.
- **A — Assunção:** premissa usada porque o dado necessário não foi informado.

Uma assunção nunca deve ser apresentada como fato confirmado.

## 5. Hierarquia de fontes

### Nível A — Fonte primária oficial

Preferência máxima:

- Constituição;
- legislação oficial;
- Diário Oficial;
- STF;
- STJ;
- CNJ;
- tribunais;
- órgãos públicos competentes;
- atos normativos oficiais.

### Nível B — Fonte institucional

- autarquias;
- órgãos reguladores;
- ministérios;
- entidades públicas;
- instituições oficiais.

### Nível C — Fonte secundária qualificada

- doutrina;
- periódicos jurídicos;
- comentários especializados;
- bases jurídicas reconhecidas.

### Nível D — Fonte informativa

- notícias;
- blogs;
- vídeos;
- redes sociais;
- publicações sem caráter oficial.

Quando uma fonte primária estiver disponível, ela deve ser preferida à fonte secundária.

## 6. Status de confiabilidade

Não utilizar percentuais de confiança sem método de calibração. Usar categorias explicáveis:

### 🟢 CONFIRMADO

Há fonte ou documento suficiente para sustentar diretamente a afirmação.

### 🔵 BEM FUNDAMENTADO

Há suporte forte, mas existe componente relevante de interpretação.

### 🟡 DEPENDENTE DE VERIFICAÇÃO

Falta informação, documento ou confirmação relevante.

### 🟠 CONTROVERTIDO

Existem entendimentos jurídicos relevantes divergentes.

### 🔴 NÃO CONFIRMADO

Não foi encontrado suporte suficiente.

### ⚫ CONTRADITÓRIO

As fontes disponíveis apresentam conflito relevante que precisa ser analisado.

## 7. Escolha do formato

A IA pode recomendar o formato mais adequado, mas deve:

1. informar qual formato escolheu;
2. explicar por que escolheu;
3. indicar alternativas;
4. permitir que o usuário altere o formato.

Exemplos:

| Problema | Formato preferencial |
|---|---|
| Sequência de decisões | Fluxograma |
| Alternativas jurídicas | Matriz comparativa |
| Eventos processuais | Linha do tempo |
| Valores | Calculadora ou tabela |
| Relações entre conceitos | Diagrama |
| Análise documental | Checklist + matriz de riscos |
| Estratégia jurídica | Árvore decisória + matriz de teses |
| Orientação ao cliente | Texto claro e estruturado |

A escolha do formato é uma recomendação da IA, não uma decisão vinculante.

## 8. Regra de não invenção

É proibido inventar:

- número de processo;
- número de acórdão;
- ementa;
- artigo de lei;
- súmula;
- precedente;
- decisão;
- trecho jurisprudencial;
- fonte inexistente.

Se a fonte não puder ser confirmada, registrar:

> **FONTE NÃO CONFIRMADA.**

Nunca apresentar uma referência não verificada como verdadeira.

## 9. Auditoria — comando VERIFIQUE-ME

Quando acionado, o sistema deve:

1. extrair as afirmações jurídicas relevantes;
2. classificar cada afirmação como F, N, J, D, I, H ou A;
3. localizar a fonte correspondente;
4. verificar se a fonte existe;
5. verificar se a fonte sustenta a afirmação;
6. verificar vigência e atualidade;
7. identificar extrapolações;
8. identificar fatos presumidos;
9. identificar omissões relevantes;
10. classificar o resultado da verificação.

## 10. Data de referência

Toda análise jurídica deve considerar:

- data da análise;
- legislação vigente na data relevante;
- alterações normativas;
- eventual revogação;
- jurisprudência relevante e atualizada;
- atos administrativos ou regulatórios aplicáveis.

Quando a análise depender de direito vigente em uma data passada, essa data deve ser explicitamente indicada.

## 11. Duelo de teses

Em questões complexas, apresentar:

### Tese A
- fundamento;
- pontos favoráveis;
- pontos contrários;
- riscos;
- fontes.

### Tese B
- fundamento;
- pontos favoráveis;
- pontos contrários;
- riscos;
- fontes.

Quando necessário, apresentar tese intermediária.

A recomendação deve indicar por que uma tese possui melhor sustentação, sem ocultar argumentos contrários.

## 12. Validação humana

Toda conclusão jurídica relevante deve terminar com um estado de validação:

- **PENDENTE DE VALIDAÇÃO**
- **VALIDADA PELO ADVOGADO**
- **CORRIGIDA PELO ADVOGADO**
- **REJEITADA PELO ADVOGADO**

A IA é assistente de análise. A decisão profissional permanece humana.

## 13. Log de auditoria

Cada análise relevante deve poder registrar:

- ID da análise;
- data;
- assunto;
- documentos utilizados;
- fontes consultadas;
- formato escolhido;
- motivo da escolha;
- afirmações analisadas;
- itens confirmados;
- itens pendentes;
- itens controvertidos;
- risco;
- auditoria realizada;
- decisão do advogado.

## 14. Modelo mínimo de saída

### CONCLUSÃO

[resposta objetiva]

### FATOS CONFIRMADOS

- ...

### FATOS NÃO CONFIRMADOS

- ...

### FUNDAMENTOS

- ...

### FONTES

- ...

### PONTOS CONTROVERTIDOS

- ...

### RISCOS

- ...

### FORMATO ESCOLHIDO

[formato]

### MOTIVO

[justificativa]

### STATUS DE CONFIABILIDADE

[status]

### PROVIDÊNCIAS

- ...

### VERIFIQUE-ME

[realizado / pendente]

### VALIDAÇÃO DO ADVOGADO

[Pendente / Validada / Corrigida / Rejeitada]

## 15. Limite do protocolo

O PC-SCJ melhora a rastreabilidade e a capacidade de revisão. Ele não garante que uma resposta da IA seja correta.

A segurança do sistema depende da combinação entre:

**fontes verificáveis + pesquisa adequada + auditoria + atualização + revisão humana.**

---

**Nota de nomenclatura:** este protocolo é uma metodologia própria do projeto Meu Segundo Cérebro. Ele pode ser inspirado em boas práticas de engenharia de informação e linguagem controlada, mas não é uma extensão oficial do ASD-STE100.
