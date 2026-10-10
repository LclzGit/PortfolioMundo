# Lucas Calaza: estúdio de agentes

Capa animada para o portfólio. Mostra um estúdio de 8 agentes trabalhando ao vivo nos projetos do Lucas.

| # | Agente | Função |
|---|--------|--------|
| 00 | Atlas | Orquestração (distribui e revisa o trabalho) |
| 01 | Nova | Frontend |
| 02 | Forge | Backend · API |
| 03 | Pixel | Design de interface |
| 04 | Oracle | Dados · Analytics |
| 05 | Sentinel | QA · Segurança |
| 06 | Orbit | DevOps · Cloud |
| 07 | Echo | Conteúdo · SEO |

Cada estação digita a tarefa atual e enche a barra de progresso. Depois passa por "Em revisão" até chegar em "Entregue", e às vezes repassa o contexto para outro agente. O quadro "Projeto em pauta" troca de projeto com efeito de letreiro de aeroporto, e a faixa laranja embaixo rola o log de entregas.

## Usar

É um único arquivo, `index.html`, sem build e sem dependências. Basta abrir no navegador ou publicar no GitHub Pages, Vercel ou Netlify.

## Personalizar

No topo do `<script>` em `index.html`:

```js
const CONFIG = {
  first: "Lucas",
  last: "Calaza",
  projects: ["COFRE APP", "LOJA NUVEM", "AGENDA API", "PORTFOLIO V3", "PAINEL KPI"],
};
```

No array `AGENTS` você troca o nome, a função, a forma geométrica, a cor e a lista de tarefas de cada agente.
