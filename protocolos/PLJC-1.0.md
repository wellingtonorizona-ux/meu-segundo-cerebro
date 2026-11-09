# PLJC 1.0 — Padrão de Linguagem Jurídica Controlada

- **Versão:** 1.0
- **Data:** 2026-11-09
- **Status:** Proposta inicial
- **Finalidade:** estabelecer regras de comunicação jurídica clara, precisa, verificável e adequada para análise humana e processamento por IA.

> **Princípio central:** linguagem clara não reduz a complexidade do Direito; ela reduz a ambiguidade da comunicação sobre o Direito.

## 1. Relação com o ASD-STE100

O PLJC utiliza princípios inspirados em linguagem técnica controlada, inclusive clareza, consistência, redução de ambiguidade e preferência por estruturas diretas.

O PLJC **não é ASD-STE100**, não pretende substituir o padrão e não deve ser apresentado como extensão ou adaptação oficial do ASD-STE100.

## 2. Objetivos

O PLJC deve:

- reduzir ambiguidade;
- separar fatos de interpretações;
- facilitar auditoria;
- facilitar leitura humana;
- facilitar recuperação por IA;
- melhorar a reutilização do conhecimento;
- reduzir frases com múltiplas conclusões;
- tornar a incerteza explícita.

## 3. Regra de uma ideia principal

Sempre que possível, uma frase deve apresentar uma ideia principal.

### Evitar

> Considerando os documentos apresentados e a posse exercida pelo interessado, verifica-se que, embora existam divergências registrais, pode ser possível adotar procedimento extrajudicial, desde que os demais requisitos estejam presentes.

### Preferir

> Os documentos indicam divergência registral.

> O interessado informa que exerce a posse do imóvel.

> O procedimento extrajudicial pode ser possível.

> É necessário verificar os demais requisitos.

## 4. Sujeito explícito

Evitar construções que ocultem quem praticou a ação.

### Evitar

> Foi identificada uma divergência.

### Preferir

> A matrícula apresenta uma divergência de área.

Quando o agente não puder ser identificado, declarar isso.

## 5. Voz ativa

Preferir voz ativa quando ela aumentar a precisão.

### Preferir

> O cartório apresentou exigência.

em vez de:

> Foi apresentada exigência pelo cartório.

A voz passiva pode ser utilizada quando o agente for irrelevante ou desconhecido.

## 6. Evitar termos vagos

Evitar, sem qualificação:

- situação irregular;
- problema documental;
- questão relevante;
- prazo adequado;
- documentação necessária;
- entendimento pacífico;
- jurisprudência dominante;
- imóvel regular;
- posse antiga;
- prova suficiente.

Substituir por descrição objetiva.

### Exemplo

Em vez de:

> O imóvel está irregular.

Usar:

> A construção não está averbada na matrícula.

ou:

> A área física informada é diferente da área registrada.

## 7. Separação obrigatória entre fato e interpretação

A resposta deve distinguir:

### FATO

> A matrícula registra 400 m².

### INTERPRETAÇÃO

> A divergência pode exigir análise de retificação.

### HIPÓTESE

> Pode existir fundamento para usucapião, dependendo dos demais requisitos.

Nunca apresentar a interpretação como se fosse um fato.

## 8. Datas e números

Usar datas completas quando houver risco de confusão.

Preferir:

> 09/11/2026

a:

> 9/11

Em documentos internacionais ou sistemas que possam gerar ambiguidade, utilizar:

> 2026-11-09

Valores monetários devem indicar moeda:

> R$ 10.000,00

Percentuais devem ser escritos de modo explícito:

> 10%

## 9. Termos jurídicos

Utilizar o termo técnico quando ele for necessário para precisão.

Não substituir um conceito jurídico específico por expressão genérica apenas para simplificar.

A regra é:

> **simplificar a linguagem, não simplificar indevidamente o conceito jurídico.**

## 10. Uma conclusão por bloco

Quando houver múltiplas conclusões, separá-las.

### Conclusão

> A documentação atual não é suficiente para concluir pela usucapião extrajudicial.

### Próxima providência

> Solicitar matrícula atualizada.

### Risco

> O risco principal é a existência de divergência entre a situação física e a situação registral.

## 11. Linguagem de incerteza

A incerteza deve ser explícita e específica.

Preferir:

- não foi possível confirmar;
- depende de documento;
- depende da vigência da norma;
- existem entendimentos divergentes;
- a fonte não foi localizada;
- o documento não informa;
- a conclusão é preliminar.

Evitar:

- provavelmente;
- talvez;
- aparentemente;
- possivelmente;

quando a expressão não vier acompanhada da razão da incerteza.

### Exemplo

> A conclusão é preliminar porque a matrícula atualizada não foi apresentada.

## 12. Citações jurídicas

Toda afirmação jurídica relevante deve permitir identificação da fonte.

Para jurisprudência, registrar, quando disponível:

- tribunal;
- órgão julgador;
- classe processual;
- número do processo;
- relator;
- data do julgamento;
- tema;
- fonte;
- link;
- trecho relevante.

Se a informação não puder ser confirmada:

> **Fonte não confirmada.**

## 13. Não inventar precisão

Nunca criar precisão que não esteja disponível.

Não transformar:

> “há muitos anos”

em:

> “há 20 anos”

sem fonte.

Não transformar:

> “o tribunal entende”

em:

> “o STJ decidiu no REsp X”

sem confirmação.

## 14. Regra de rastreabilidade

Sempre que possível, uma conclusão deve poder ser percorrida assim:

**Conclusão → fundamento → fonte → fato → documento.**

Se algum elo não existir, a lacuna deve ser indicada.

## 15. Estrutura preferencial para análises jurídicas

Quando adequado:

1. **Questão apresentada**
2. **Fatos confirmados**
3. **Fatos pendentes**
4. **Questões jurídicas**
5. **Normas aplicáveis**
6. **Jurisprudência**
7. **Análise**
8. **Teses alternativas**
9. **Riscos**
10. **Conclusão**
11. **Providências**
12. **Fontes**
13. **Status de confiabilidade**

O formato pode mudar quando outro formato for mais adequado ao problema.

## 16. Regra para IA

Ao gerar resposta jurídica, a IA deve:

1. identificar o problema;
2. identificar lacunas;
3. separar fatos e interpretações;
4. utilizar fontes verificáveis;
5. informar a data de referência;
6. escolher ou sugerir o formato de saída;
7. explicar a escolha;
8. indicar incertezas;
9. permitir auditoria;
10. submeter a conclusão à validação humana.

## 17. Checklist de conformidade

Antes de finalizar uma resposta, verificar:

- [ ] O sujeito das ações está claro?
- [ ] Os fatos estão separados das interpretações?
- [ ] Existem termos vagos?
- [ ] As datas estão claras?
- [ ] Os números estão identificados?
- [ ] As fontes são verificáveis?
- [ ] Alguma citação foi inventada?
- [ ] A vigência das normas foi considerada?
- [ ] A incerteza foi explicitada?
- [ ] A conclusão está sustentada pelos fatos?
- [ ] O formato escolhido é adequado?
- [ ] O usuário pode auditar a conclusão?
- [ ] A validação humana está registrada?

## 18. Regra final

> **Escrever de forma controlada não significa escrever de forma simplista. Significa tornar claro o que é fato, o que é fonte, o que é interpretação, o que é hipótese e o que ainda precisa ser verificado.**

O PLJC é uma metodologia própria do projeto Meu Segundo Cérebro. Ele utiliza princípios de linguagem controlada como referência metodológica e não constitui padrão oficial do ASD-STE100.
