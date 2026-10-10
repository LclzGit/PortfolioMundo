# WorkingAgents: ecossistema de agentes

Capa animada para portfólio. Um time de 8 agentes de IA fictícios aparece trabalhando ao vivo nos seus projetos.

- **ATLAS** é o orquestrador e delega as tarefas.
- **NOVA** cuida do frontend, **FORGE** do backend/API, **PIXEL** da UI/design, **ORACLE** de dados/analytics, **SENTINEL** de QA/segurança, **ORBIT** de DevOps/cloud e **ECHO** de conteúdo/SEO.

Os pacotes de dados circulam entre os agentes, cada um tem uma barra de progresso, os logs rolam em tempo real e os contadores sobem sozinhos.

## Usar

É um único arquivo, `index.html`, sem build e sem dependências. Basta abrir no navegador ou publicar no GitHub Pages, Vercel ou Netlify.

## Personalizar

No topo do `<script>` em `index.html`:

```js
const CONFIG = {
  name: "Seu Nome",
  projects: ["Portfólio v3", "App Fintech “Cofre”", "Dashboard E-commerce", "API de Agendamentos"],
};
```

No array `AGENTS` você troca nomes, cores, especialidades e a lista de tarefas de cada agente. A página respeita `prefers-reduced-motion` e se adapta ao celular.
