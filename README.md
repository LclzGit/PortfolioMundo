# Lucas Calaza: o planeta dos robôs

Capa interativa do portfólio. É um pequeno planeta 3D em low-poly onde robôs trabalham nos **meus projetos**.

## Como funciona

- **Visual:** tema de atlas celeste, com azul-noite e detalhes dourados, títulos em serifa clássica e etiquetas em fonte mono. Cada área tem número e coordenadas, e o canto da tela mostra a coordenada do centro da vista.
- **Robôs:** são redondinhos e flutuam com um jatinho. Têm rosto de tela, olhos que piscam, bochechas e sorriso.
- **Interação:** arraste o globo para girar e use a roda do mouse ou a pinça para dar zoom.
- **Descanso:** os robôs vão a pé até a sala de descanso para recarregar e depois voltam ao trabalho.
- **Abrir um projeto:** ao clicar numa área, num robô ou no nome dela, a câmera voa até lá e abre o painel do projeto. Ele tem uma captura de tela ou um **protótipo interativo com dados fictícios**, a descrição e os robôs da área.
- **Voltar:** pelo botão, pela tecla Esc, com um clique fora ou pelo voltar do navegador.

## Regras de conteúdo

- **Nada de código-fonte.** O site não mostra trechos de código nem links para repositórios. Os projetos aparecem só como capturas de tela, protótipos para testar ou o app publicado.
- **Só marcas próprias.** Aparecem apenas os meus projetos (ReformaPro, IRCSPro, Daemon Bar e os demais). Nomes e logos de outras empresas ficam de fora, inclusive nas imagens e no protótipo do jogo.

| Área | Projeto | Robôs |
|---|---|---|
| Biblioteca das Leis | ReformaPro | LEX, NORMA |
| Arquivo do IR | IRCSPro | IRIS |
| Fábrica de Preços | Calculadora da Reforma Tributária | PRISMA, CBS-9 |
| Balança do ICMS | Calculadora & Apuração DIFAL (protótipo: simulador) | DELTA |
| Torre de Recepção | SNNFSe (protótipo: caixa de notas) | SINAL, NSU |
| Correio das Notas | Painel de NFs (protótipo: painel por analista) | ROTA |
| Fortaleza Firewall | Daemon Bar (protótipo jogável) | FIREWALL, SCANNER, PATCHER |
| QG do Lucas | Sobre mim | (o humano) |
| Sala de descanso | Área comum | quem estiver na pausa |

## Usar e editar

É um site estático: `index.html` com as pastas `assets/` e `demos/`. Não precisa de build, basta publicar em qualquer hospedagem de site estático.

Para editar, tudo fica no array `AREAS`, no início do `<script>`, e os protótipos ficam em `PROTOS`.
