# Maestria — releases

Este repositório é público só para hospedar o feed de atualização
automática (Sparkle) e os binários (`.dmg`) de cada versão do
[Maestria](https://github.com/themaestria/app) — que continua privado.

- `appcast.xml`: feed consultado pelo app (Sparkle). Assinado com a
  chave EdDSA do projeto.
- Cada release traz o `.dmg` daquela versão como asset.

Não contém código-fonte. Gerado/atualizado por
`tools/publish_update.sh` no repo principal.
