# Outlet contact pages, outlets 21 to 134 (batches 2 to 7)

Same method and limits as batch 1, which cl-6.security passed at 11:33 UTC on 26 Nov 2026: each outlet's OWN contact page (the URL in `data/organisations/<id>/organisation.json`, https), read without a login by plain request on 26 Nov 2026; a role mailbox listed only if its local part is one of redacao, redaccao, newsroom, news, noticias, geral, info, imprensa, press, editor, editorial, tips, contacto, contact on the outlet's own domain. No phones, names or personal addresses. Addresses hidden behind an obfuscation script were not decoded; sites that refused or timed out are marked, not worked round. Machine-readable copy: `outlet-contacts-batches-2-to-7.json`.

Result: 35 of 114 pages publish a role mailbox. Not yet seen by cl-6.security: nothing here goes into data/ before they have looked.

| Outlet id | Contact page | Role mailbox | Status |
|---|---|---|---|
| correio-do-ribatejo | https://www.correiodoribatejo.pt/contactos/ | - | read: no role mailbox published on the page |
| correio-dos-acores | https://correiodosacores.pt/contactos/ | - | read: no role mailbox published on the page |
| diario-as-beiras | https://www.asbeiras.pt/contactos/ | redacao@asbeiras.pt, redaccao@asbeiras.pt | read |
| diario-de-aveiro | https://www.diarioaveiro.pt/sobre/ | - | page hides its address behind an obfuscation script: not read |
| diario-de-coimbra | https://www.diariocoimbra.pt/sobre/ | - | page hides its address behind an obfuscation script: not read |
| diario-de-leiria | https://www.diarioleiria.pt/sobre/ | - | page hides its address behind an obfuscation script: not read |
| diario-de-noticias-madeira | https://www.dnoticias.pt/servicos/contactos | - | page hides its address behind an obfuscation script: not read |
| diario-de-noticias | https://www.dn.pt/contactos | - | read: no role mailbox published on the page |
| diario-de-tras-os-montes | https://www.diariodetrasosmontes.com/p/ficha-tecnica | - | read: no role mailbox published on the page |
| diario-de-viseu | https://www.diarioviseu.pt/sobre/ | - | page hides its address behind an obfuscation script: not read |
| diario-do-alentejo | https://diariodoalentejo.pt/pt/menu/1076/contactos.aspx | - | read: no role mailbox published on the page |
| diario-do-distrito | https://diariodistrito.sapo.pt/contactos/ | - | read: no role mailbox published on the page |
| diario-do-sul | https://diariodosul.pt/contacto/ | - | page hides its address behind an obfuscation script: not read |
