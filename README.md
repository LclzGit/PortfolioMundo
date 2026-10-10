# Lucas Calaza: escritório de agentes

Capa interativa do portfólio. É um escritório em pixel art: cada mesa é um **projeto real** e tem um agente trabalhando nele, digitando no monitor.

Ao **clicar numa mesa**, a câmera dá zoom no monitor e ele vira a página do projeto, com captura de tela, descrição, stack, links e o log ao vivo do agente. Dá para voltar pelo botão **← Voltar ao escritório**, pela tecla **Esc** ou pelo **voltar do navegador**. Com **◀ ▶** (ou as setas do teclado) você passa de um projeto para o outro.

| Mesa | Agente | Projeto |
|---|---|---|
| 01 | LEX | ReformaPro |
| 02 | IRIS | IRCSPro |
| 03 | PRISMA | Calculadora da Reforma Tributária |
| 04 | DELTA | Calculadora & Apuração DIFAL |
| 05 | SINAL | SNNFSe Python |
| 06 | ROTA | Painel de NFs × Qive |
| 07 | FIREWALL | Daemon Bar |
| 08 | LUCAS | Sobre mim |

Cada projeto também tem um link direto, por exemplo `index.html#/reformapro`.

## Usar

O site é o `index.html` com a pasta `assets/` (capturas de tela) e a pasta `demos/` (o protótipo jogável do Daemon Bar). Não tem build: basta abrir no navegador ou publicar no GitHub Pages.

## Editar

Os projetos ficam no array `PROJECTS`, no início do `<script>`. Cada item tem o texto do projeto (`title`, `lede`, `points`, `stack`, `links`, `img`), o agente (`agent`, `job`), as cores do personagem (`look`) e as linhas que aparecem no monitor (`log`). Os textos vieram do repositório [Portf-lio](https://github.com/LclzGit/Portf-lio).
