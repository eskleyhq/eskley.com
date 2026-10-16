eskley.com company page. The Rowtrace pages live at https://rowtrace.com/ (repo eskleyhq/rowtrace.com); each old `/rowtrace/` address here is a noindex page that forwards to its rowtrace.com counterpart.

## tokens.css

`/tokens.css` is a whole, unedited copy of `project/tokens.css` from the Eskley DS_Blue design-system artifact (https://claude.ai/artifact/DQrTJSKTbPzy4civVNb5uf), version 1791578871-9e96, SHA-256 `d1f920cbf0ec5b005b78771f3201fc294870c73aafb34c604b361af5de819065`. Every page loads it before its own styles. Never edit it here: token values change only in the artifact's token editor, then the whole file is copied again and this line updated.

## site.css

`/site.css` is the one stylesheet for every page: eskley.com (solid navy header and footer) and the Rowtrace pages (white header with an accent rule), picked by `data-site` on `<html>`. It comes from the site design artifact (https://claude.ai/artifact/GwpeeyTrcBDFnjZhVnCkqn, version 1791922948-497d) and takes every value from `/tokens.css`.

The company page links to the Rowtrace home, the download page and the comparisons on rowtrace.com. `/site.css` is shared with rowtrace.com, which holds a byte-for-byte copy; a change to it lands in both repos.
