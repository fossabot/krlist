# krlist

`krlist.yaml` is a ruleset of [Clash](https://github.com/Dreamacro/clash), contains domains that may trigger redirection to http://warning.or.kr/.

# Howtouse
Below is an example for your `config.yaml`
```
rule-providers:
  krlist:
    type:         http
    behavior:     domain
    path:         ./Rules/krlist
    url:          https://raw.githubusercontent.com/ygsk10/krlist/master/krlist.yaml
    interval:     86400

rules:
- RULE-SET,krlist,nokr
```
