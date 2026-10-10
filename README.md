# Lucas Calaza: o planeta dos robôs

Capa interativa do portfólio. É um pequeno planeta 3D em low-poly onde robôs trabalham nos **meus projetos reais**.

- **Arraste** o globo para girar (com inércia). Use a **roda do mouse** ou **pinça** para dar zoom.
- Cada projeto é uma área com o seu prédio e os seus robôs trabalhando. Por exemplo, a biblioteca do ReformaPro tem um livro girando, a fábrica da Calculadora da Reforma solta fumaça e moedas, e a torre do SNNFSe emite sinais.
- Na **sala de descanso** os robôs recarregam a bateria nos pads ou sentam nos bancos (com "zzz"). De tempos em tempos, um robô larga o trabalho e atravessa o planeta a pé até lá. Quando passa por cima da água, ele flutua.
- Pacotes de dados viajam em arcos entre os projetos que se conversam.
- **Clique numa área, num robô ou no nome dela**: a câmera voa até lá e abre o painel do projeto, com captura de tela, descrição, stack, links, quem está trabalhando e o log ao vivo. Para voltar, use **← Voltar ao planeta**, a tecla **Esc**, um clique fora ou o **voltar do navegador**. **‹ ›** (ou as setas do teclado) passam de uma área para outra.
- A barra de baixo lista todas as áreas e funciona como atalho.

| Área | Projeto | Robôs |
|---|---|---|
| Biblioteca das Leis | ReformaPro | LEX, NORMA |
| Arquivo do IR | IRCSPro | IRIS |
| Fábrica de Preços | Calculadora da Reforma Tributária | PRISMA, CBS-9 |
| Balança do ICMS | Calculadora & Apuração DIFAL | DELTA |
| Torre de Recepção | SNNFSe Python | SINAL, NSU |
| Correio das Notas | Painel de NFs × Qive | ROTA |
| Fortaleza Firewall | Daemon Bar | FIREWALL, SCANNER, PATCHER |
| QG do Lucas | Sobre mim | (o humano) |
| Sala de descanso | Área comum | quem estiver na pausa |

Cada área tem um link direto, por exemplo `index.html#/reformapro`.

## Usar

O site é o `index.html` com as pastas `assets/` (capturas de tela) e `demos/` (o protótipo jogável do Daemon Bar). O 3D usa [three.js](https://threejs.org/) 0.128 carregado de um CDN. Não tem build: basta publicar no GitHub Pages ou abrir no navegador. Se o navegador não tiver WebGL, a barra de áreas e os painéis continuam funcionando.

## Editar

Tudo fica no array `AREAS`, no início do `<script>`. Cada item tem:

- os textos do projeto: `title`, `lede`, `points`, `stack`, `links` e `img`;
- a posição no planeta: `lat` e `lon`;
- o tipo de prédio: `build`;
- os robôs da área: `robots`;
- as linhas do log: `log`.

Os textos vieram do repositório [Portf-lio](https://github.com/LclzGit/Portf-lio).
