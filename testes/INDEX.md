# Suíte de Testes

A suíte de testes verifica se o Segundo Cérebro aplica corretamente o PC-SCJ e o PLJC.

- [README da suíte](./README.md)
- [Casos T01–T30](./casos-fundamentais.md)
- [Ataques adversariais T30-C1](./ataques/T30-C1-cenarios-adversariais.md)
- [Fontes da T30-C2](./fontes/T30-C2-pacotes-de-fontes-2026-11-12.md)
- [Cenários T30-C2](./ataques/T30-C2-cenarios-confronto-fontes.md)
- [Execução T30-C2](./execucoes/T30-C2-confronto-fontes-2026-11-12.md)

A suíte deve ser tratada como instrumento de regressão: uma falha corrigida não deve ser removida. Ela permanece para impedir que versões futuras repitam o mesmo erro.

## Regra de justificativa das escolhas

Quando houver escolha entre fontes, teses ou interpretações, a resposta não será considerada suficiente se apenas indicar a opção escolhida.

A execução deve registrar:

**ESCOLHA → CRITÉRIO → FUNDAMENTO JURÍDICO → COMPARAÇÃO → MOTIVO → LIMITES → FONTE AUDITÁVEL**

A atualização da suíte preserva essa exigência para futuras regressões.
