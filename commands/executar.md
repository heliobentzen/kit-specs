---
description: Executa o plano aprovado de uma spec
argument-hint: [pasta da spec, ex.: 00-base]
---
Leia specs/$ARGUMENTS/plano.md. Se o cabeçalho não tiver "status: aprovado", pare e avise.
Execute o plano alterando apenas os arquivos listados nele.
Depois, no próprio plano.md: deixe "a conferir" na coluna Resultado de cada critério
e preencha "Desvios na execução" (nenhum, ou o que mudou e por quê).
Nunca escreva "passou" ou "falhou": quem testa é o grupo.
