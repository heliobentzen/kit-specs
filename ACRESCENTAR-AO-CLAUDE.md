<!-- Copie as duas seções abaixo para o CLAUDE.md do repositório e apague este arquivo. -->

## Fluxo de trabalho com specs
- Cada atividade fica em specs/NN-nome/, com spec.md e plano.md.
- Para criar uma spec, copie os dois arquivos de specs/_modelo/. Nunca altere specs/_modelo/.
- spec.md é escrito pelo grupo. Você pode sugerir mudanças, mas só altera spec.md se pedirmos.
- Ao planejar: leia spec.md e escreva plano.md seguindo o modelo, ligando cada passo aos critérios (CA-01, CA-02...). Termine com status: rascunho.
- Nunca execute uma spec se o cabeçalho de plano.md não tiver "status: aprovado". Você nunca escreve "aprovado".
- Ao executar: altere apenas os arquivos listados no plano. Depois, no plano.md, deixe "a conferir" na coluna Resultado de cada critério e preencha "Desvios na execução". Nunca escreva "passou" ou "falhou".
- Quando pedirmos um ajuste no plano, mantenha status: rascunho e acrescente uma linha em "Ajustes pedidos": data e o que mudou.

## Tecnologia
- HTML, CSS e JavaScript puros, sem bibliotecas externas e sem servidor.
- O protótipo abre com duplo clique em src/index.html.
- Dados fictícios ficam apenas em src/dados-exemplo.js (nada de fetch em arquivo .json).
- Comentários no código em português.
