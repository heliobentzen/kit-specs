---
description: Gera o plano de uma spec, sem executar nada
argument-hint: [pasta da spec, ex.: 00-base]
---
Leia specs/$ARGUMENTS/spec.md, o CLAUDE.md e docs/contexto.md.
Escreva specs/$ARGUMENTS/plano.md seguindo o modelo de specs/_modelo/plano.md:
arquivos, passos ligados aos critérios (CA-01...), rastreabilidade, premissas e riscos.
Deixe status: rascunho. Não altere nenhum outro arquivo além de plano.md.
Se a spec tiver critério ambíguo, não invente: liste a dúvida em Premissas assumidas.
