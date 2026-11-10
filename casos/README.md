# Banco de Casos de Estresse Jurídico

## Finalidade

Este diretório contém casos para testar o comportamento do Segundo Cérebro Jurídico em situações reais, adversariais, sintéticas e de regressão.

A primeira série é composta por **10 casos públicos reais**, reconstruídos em formato clínico e deliberadamente desidentificados.

## Regra de proteção de dados

Os casos publicados neste repositório **não devem conter nomes de pessoas, números de processo, CPF, RG, telefone, e-mail, endereço completo, placa, RENAVAM, matrícula individualizada, dados bancários, documentos pessoais, identificadores eletrônicos ou qualquer outro dado que permita identificar diretamente ou indiretamente uma pessoa natural**.

Os casos públicos foram reduzidos ao conjunto de fatos necessário para o teste jurídico. O resultado do julgamento não aparece no arquivo de teste; fica separado no respectivo gabarito de controle.

A anonimização deve ser tratada como requisito de segurança, não como mera substituição de nomes. A ANPD destaca que a anonimização exige impedir a associação, direta ou indireta, do dado a uma pessoa por meios razoáveis.

## Origem dos casos

- **T30-A:** casos públicos reais, principalmente STJ e TJ-GO.
- **T30-B:** casos provenientes da prática profissional, somente após anonimização e autorização.
- **T30-C:** casos adversariais criados para provocar falhas.
- **T30-D:** casos sintéticos controlados.
- **T30-E:** casos de regressão, preservados quando uma falha anterior for corrigida.

## Regra de construção

O arquivo de teste deve apresentar fatos, documentos, datas e questões jurídicas suficientes para permitir análise independente.

O arquivo de teste **não deve revelar a conclusão judicial original**.

O gabarito separado deve conter:
- fatos confirmados;
- questões jurídicas;
- normas aplicáveis;
- jurisprudência de controle;
- resultado judicial original em linguagem resumida;
- pontos que a IA deve identificar;
- erros graves;
- erros aceitáveis;
- critérios de PASSOU/FALHOU.

## Escala

1. Básico
2. Intermediário
3. Avançado
4. Adversarial
5. Crítico

## Regra de atualização

Antes de utilizar um caso para avaliar conclusão jurídica atual, deve-se verificar novamente a legislação e a jurisprudência vigente na data do teste.

A jurisprudência usada para controle pode mudar. O caso histórico permanece como caso histórico, mas a resposta jurídica atual deve considerar eventual superação, distinção ou evolução posterior.

## Fontes prioritárias

- STJ
- STF
- TJ-GO
- CNJ
- legislação oficial

O Provimento CNJ nº 149/2023 instituiu o Código Nacional de Normas do Foro Extrajudicial e continua sendo objeto de alterações posteriores. Portanto, procedimentos registrais devem ser verificados na versão vigente.

## Primeira série

| ID | Tema | Origem | Nível |
|---|---|---|---|
| T30-A01 | Usucapião ordinária e recibo de compra e venda | STJ | 3 |
| T30-A02 | Usucapião em APP | STJ | 4 |
| T30-A03 | Usucapião entre herdeiros / posse exclusiva | STJ | 4 |
| T30-A04 | Adjudicação compulsória e inventário incompleto | TJ-GO | 4 |
| T30-A05 | Adjudicação compulsória e legitimidade passiva | STJ | 3 |
| T30-A06 | Inventário e bens digitais | STJ | 3 |
| T30-A07 | Colação de bens e conflito temporal de normas | STJ | 5 |
| T30-A08 | Petição de herança e termo inicial da prescrição | STJ | 5 |
| T30-A09 | Inventário diante de patrimônio imobiliário | STJ | 4 |
| T30-A10 | Usucapião e posse sem publicidade suficiente | STJ | 4 |

## Segurança

Se qualquer dado identificador aparecer em uma nova versão, a versão deve ser rejeitada e corrigida antes de entrar no repositório.

A presença de informação em fonte pública não elimina automaticamente a necessidade de avaliar finalidade, necessidade, contexto e risco de reidentificação. A ANPD recomenda medidas de anonimização ou pseudonimização quando cabíveis.
