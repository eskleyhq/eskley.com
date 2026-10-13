eskley.com company page, and the Rowtrace pages under `/rowtrace/` until rowtrace.com has its own DNS.

## tokens.css

`/tokens.css` is a whole, unedited copy of `project/tokens.css` from the Eskley DS_Blue design-system artifact (https://claude.ai/artifact/DQrTJSKTbPzy4civVNb5uf), version 1791578871-9e96, SHA-256 `d1f920cbf0ec5b005b78771f3201fc294870c73aafb34c604b361af5de819065`. Every page loads it before its own styles. Never edit it here: token values change only in the artifact's token editor, then the whole file is copied again and this line updated.

## site.css

`/site.css` is the one stylesheet for every page: eskley.com (solid navy header and footer) and the Rowtrace pages (white header with an accent rule), picked by `data-site` on `<html>`. It comes from the site design artifact (https://claude.ai/artifact/GwpeeyTrcBDFnjZhVnCkqn, version 1791922948-497d) and takes every value from `/tokens.css`.

The Rowtrace pages are `noindex` and nothing on the company page links to them yet. Yellow `Gap` marks are facts still owed; resolve or cut each one before a page goes live.
