# zed-biome-2

demo repo that seems to break with biome 2 and zed.

Zed still seems to do rudimentary formatting so if you move the console log to the same line as the constructor, it will put it on a new line, and do indentation, which was confusing me.

However it wont fix the array being on multiple lines, quotes, etc.

If you run `npx @biomejs/check . --write` it will fix all the problems fine.

Zed config is in `.zed/settings.json`

In addition, I get this error when loading the workspace:

```
Language server error: biome

oneshot canceled
-- stderr--
Error: `--config-path` is not expected in this context
```
