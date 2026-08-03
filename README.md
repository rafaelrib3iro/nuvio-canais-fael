# Addon de canais personalizados

Este diretório contém um protótipo de addon Stremio/Nuvio com catálogos
curados. Os itens usam os IDs `cs:channel:*` originais do FrostView, portanto
o addon serve apenas para organizar e exibir os canais; a reprodução continua
dependendo do addon que fornece o stream.

Catálogos incluídos:

- TV Aberta — seleção inicial sem duplicar variações;
- Discovery — categoria original do FrostView;
- Telecine — categoria original do FrostView;
- Desenho Animado — categoria infantil do FrostView.

Para aparecer no Nuvio, o diretório precisa ser publicado em uma URL HTTPS
pública que sirva `manifest.json` e os caminhos `catalog/channel/*.json`.
