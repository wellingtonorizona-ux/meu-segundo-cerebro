# Pesquisa e análise de jurisprudência e doutrina

**Versão 1.1 · 26/11/2026**  
Complemento ao [PC-SCJ 2.0](./PC-SCJ-2.0-Prompt-Mestre.md). Acione com `/JURISPRUDÊNCIA-E-DOUTRINA` ou peça apenas uma das duas pesquisas.

## 1. Delimite a questão

Identifique pedido, fatos e datas decisivos, ramo do direito, fase processual, legislação aplicável e tribunal competente. Formule a pergunta de pesquisa e registre data, bases, termos e filtros que permitam reproduzi-la. Busque argumentos favoráveis, contrários e distinções. Use descrições impessoais nas buscas e exemplos do repositório.

## 2. Jurisprudência

1. Pesquise e apresente os resultados em bases oficiais nesta ordem: **TJGO → STJ → STF → demais tribunais**. Entre os demais, consulte os pertinentes à matéria, como TST, TRT da 18ª Região, TRF da 1ª Região ou TNU. Indique quando uma base foi consultada sem resultado pertinente ou ficou indisponível. A ordem de busca e apresentação convive com o peso jurídico de cada precedente. Destaque o entendimento aplicável e eventual divergência local.
2. Abra o inteiro teor oficial e a página do tema, quando houver. Confira fatos julgados, questão decidida, fundamento determinante, dispositivo e natureza da decisão. Informe o peso do precedente conforme o regime aplicável. Dê tratamento próprio a precedentes qualificados, súmulas, decisões colegiadas persuasivas e decisões monocráticas.
3. Use uma janela móvel de **dez anos anteriores à data da pesquisa**, pela data do julgamento. Registre as datas inicial e final e apresente primeiro os julgados mais recentes e pertinentes em cada tribunal. Se for indispensável citar precedente qualificado ou enunciado anterior ainda aplicável, identifique-o à parte como referência anterior ao recorte, justifique sua inclusão e confirme sua atualidade. Confira afetação ou julgamento do tema, publicação, suspensão, modulação, alterações posteriores, superação, distinção e situação processual quando relevante e verificável. Se houver divergência, explicite seu alcance e evite afirmar pacificação com base em julgados isolados.
4. Compare o caso julgado e o caso concreto. Indique fatos em comum, diferenças, objeção previsível e efeito sobre a recomendação.

**Ficha por julgado.** Tribunal e órgão julgador · classe e número oficial ou identificador público · relator e, se relevante, redator · datas do julgamento e publicação · tema ou súmula, se houver · link oficial do inteiro teor e da tese · página do acórdão/PDF, item ou seção do voto · fundamento conferido · aderência e distinções · status e data da verificação. Registre expressamente o alcance de uma consulta limitada à ementa.

## 3. Doutrina

**Ordem de busca e apresentação**, conforme pertinência e acesso ao texto:

1. **Livros, tratados, manuais e capítulos de coletâneas.** Consulte edição identificada, original disponível em editora, biblioteca ou repositório autorizado, ou exemplar fornecido pelo usuário.
2. **Artigos.** Priorize periódicos especializados, publicações acadêmicas e repositórios institucionais com autoria e texto verificáveis.
3. **Informativos, comentários, citações indiretas e demais escritos jurídicos relevantes.** Identifique a natureza e o peso do material. Para informativo de tribunal, procure o julgado correspondente. Distinga resumo institucional de comentário doutrinário assinado.

**Ficha de livro ou capítulo.** Autor da passagem e organizador, se houver · título e subtítulo · edição · volume · cidade, editora e ano · capítulo, seção ou item · página impressa ou folha exata; indique frente/verso quando aplicável · página do visualizador/PDF quando diferente · ISBN ou identificador quando disponível · fonte efetivamente consultada e link, ou identificação do exemplar e das páginas fornecidas · data de consulta.

**Obra digital sem paginação fixa.** Registre a versão, capítulo, seção e posição ou outro localizador estável disponível. Informe que a obra é sem paginação. Se houver paginação, mas ela estiver indisponível, marque “página não confirmada”.

**Ficha de artigo ou outro escrito.** Autor, título, veículo, data, volume/número quando houver, página ou seção exata, DOI ou URL e origem efetivamente consultada.

Para cada referência doutrinária usada na análise, escreva **pelo menos um parágrafo analítico em palavras próprias**. Explique a posição do autor sobre o tema pesquisado, o fundamento ou a distinção relevante, como ela se aplica aos fatos do caso e o que reforça, limita ou muda na tese. Se houver posição contrária pertinente, confronte os argumentos. Referências acessíveis apenas em catálogo ou sumário ficam como pistas de pesquisa, conforme o alcance verificável. Identifique expressamente **trecho literal**, **paráfrase** ou **citação indireta**. Use citações literais curtas, dentro dos limites aplicáveis. Na indireta, identifique a fonte efetivamente lida e sua localização, atribua o texto com *apud* quando couber e indique que a obra original está pendente de conferência.

## 4. Resultado auditável

| Status | Tratamento |
|---|---|
| Confirmado na fonte consultada | Texto, autoria, localização e aderência conferidos. Informe o que foi verificado. |
| Verificação parcial | Indique o que foi acessível, como ementa, sumário ou catálogo, e o que falta abrir. |
| Não confirmado | Registre como pista para diligência. Solicite a página, o trecho ou o inteiro teor necessário. |

**Regra de auditoria.** Atribua a referência somente até o limite que a fonte consultada demonstra. Busca por fragmentos, catálogo ou sumário serve à localização. Ementa permite reportar o que ela contém. Tese, página, folha, edição e citação literal exigem conferência no material correspondente. Se houver conflito entre referências, explique a divergência e o impacto.

**Entrega.** Abra com a resposta à questão e o grau de confirmação. Use tabela com questão, referência, localizador, aderência, objeção e efeito prático. Após a tabela, desenvolva os parágrafos de análise doutrinária com seus localizadores. Inclua as fontes pendentes e como obtê-las. Aplique `/VERIFIQUE-ME` aos fundamentos decisivos e mantenha a validação pelo advogado. Registre no GitHub o método e exemplos anonimizados.

## Fontes para iniciar

- [CPC, arts. 489, § 1º, V e VI, e 926 a 927](https://www.planalto.gov.br/ccivil_03/_ato2015-2018/2015/lei/l13105.htm).
- [STF, teses de repercussão geral](https://portal.stf.jus.br/repercussaogeral/teses.asp) e [STJ, pesquisa de jurisprudência](https://cartadeservicos.stj.jus.br/jurisprudencia/pesquisa-de-jurisprudencia-do-stj/).
- [STJ, Biblioteca Digital Jurídica — BDJur](https://cartadeservicos.stj.jus.br/biblioteca/biblioteca-digital-juridica-do-stj-bdjur/).

## Histórico

- **1.1** — Ordem de consulta e apresentação por tribunal, recorte jurisprudencial de dez anos e análise doutrinária em parágrafos.
- [Versão 1.0](https://github.com/wellingtonorizona-ux/meu-segundo-cerebro/blob/391167960ed76fdab1ab311dc5b6a95a07bb95e9/protocolos/pesquisa-jurisprudencia-e-doutrina.md).
