angou\_bitmex 2 (May 24, 2018)
===
- `angou_bitmex.rest` now exposes a module-scoped `LOGGER` variable, instead of
  per-class `angou_bitmex.rest.RestSession.logger`s.
- If a response has a “success” HTTP status code but its body cannot be parsed
  as JSON, `angou_bitmex.rest.InvalidJSON` is raised.
- `angou_bitmex.rest.RestSession` constructor now takes an optional `timeout`
  argument.

angou\_bitmex 1 (May 19, 2018)
===
The first release of angou\_bitmex!
