---
id: u0gjxa4kc6ncba1i8jude62
title: Dendron
desc: ''
updated: 1650642633885
created: 1650121578805
---

## Note References

With Dendron you can reference and embed content from other notes in the current note

### Reference Types

* Note Reference
  * `![[name.of.note]]`
* Header Reference
  * `![[name.of.note#header-name]]`
* Block (anchor) Reference
  * `![[name.of.note#^important-paragraph]]`
* Range Reference
  * `![[name.of.note#starting-header:#ending-header]]`

For references with spaces in the name use `-` instead

## Cross Vault Links

Prefix link with: `dendron://$vaultName/`

* Regular link: `[[dendron://vault/foo]]`
* Wiki link with alias: `[[Foo Note|dendron://vault/foo]]`
* Relative link: `[[Foo Note|dendron://vault/foo#header]]`
* Note reference: `![[dendron://vault/foo]]`
