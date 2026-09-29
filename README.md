# plugin-locale-it

Lingua italiana per [Cuelith](https://github.com/Cuelith/cuelith-core). In Cuelith anche le lingue sono moduli: questo è un modulo di soli dati (`runtime: none`, nessun processo), preinstallato con il nucleo e non disattivabile finché è l'unica lingua installata.

- `cuelith-plugin.json` — manifest (famiglia `locale`).
- `locales/it.json` — catalogo piatto `chiave → testo`. Segnaposto `{nome}`; plurali con i suffissi `#one` / `#other`.

Ogni chiave usata dal nucleo (`core.*`) e dal protocollo (`protocol.*`) deve avere qui la sua traduzione: il test delle lingue in `cuelith-core` fallisce se ne manca una.

Licenza Apache 2.0.
