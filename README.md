# Hard Gate · capacitação

O plugin traz o método C1–C10 da Hard Gate para o seu Claude. Ele junta duas coisas: o
conector da mentoria (o material dos dez temas de estratégia de IA, C1 a C10, o método e o seu
dossiê) e as instruções de como o assistente responde: curto, a partir do material, com uma
entrega já no primeiro turno e uma só pergunta no fim, para você escolher o próximo passo.

## Como usar

1. No Claude (site ou Desktop), vá em **Customize > Plugins > Add > Add marketplace** e cole
   `https://github.com/MKanhan/hard-gate-plugin`. Instale **hard-gate**.
2. Na aba **Conectores** do plugin, conecte o hard-gate e entre com o e-mail da sua mentoria.
3. Converse. Pergunte sobre um tema, peça um resumo, descreva uma decisão. Para tabela, plano ou
   checklist com a marca da mentoria, peça "no visor".

No Claude Code, um comando basta:

```
/plugin install hard-gate --marketplace MKanhan/hard-gate-plugin
```

## Que dado o plugin envia

As perguntas que você faz ao assistente vão ao servidor `mcp.hardgate.com.br`, que devolve
trechos do material e o seu dossiê. O plugin não guarda nada. O servidor só lê.

## Para quem é

Para quem está na capacitação da Hard Gate. Sem a matrícula, o conector não autoriza o acesso.
