# davbaga gaps

| # | Дупка | Статус |
|---|-------|--------|
| D1 | споделено заключване не се издаваше в XML | **Closed 2026-10-31** — `dav_lockdiscovery_scoped` / `dav_lock_xml_scoped` с `"shared"`; default остава exclusive |
| D2 | `If` с `Not` и или-списъци не се оценяваше | **Closed 2026-10-31** — `dav_if_eval(header, held_tokens)` парсира RFC 4918 §10.4: `Not`, OR-списъци, AND между скоби, `[etag]` се пропуска |
| D3 | lock-null ресурс (RFC 4918 §7.3) | **Closed 2026-10-31** — `dav_locknull_add/remove/is_lock_null` + `dav_locknull_response` (празен resourcetype + lockdiscovery + size 0) |
