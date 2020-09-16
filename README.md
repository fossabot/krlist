![WARNING](https://archive.vn/KUwoL/d65a98301512ab5a40c7325a0eec12c6ac3663f8/scr.png)
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fygsk10%2Fkrlist.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Fygsk10%2Fkrlist?ref=badge_shield)

# krlist

`krlist.yaml` is a ruleset of [Clash](https://github.com/Dreamacro/clash), contains domains that may trigger redirection to http://warning.or.kr/, or other restrictions.

# Howtouse
Below is an example for your `config.yaml`
```
rule-providers:
  krlist:
    type: http
    behavior: classical
    path: ./Rules/krlist
    url: https://ygsk10.github.io/krlist/krlist.yaml
    interval: 86400

rules:
- RULE-SET,krlist,nokr
```
# See Also
[한국에서 인터넷 검열을 피하는 방법](https://github.com/preco21/bypass-censorship-korea)


## License
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fygsk10%2Fkrlist.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Fygsk10%2Fkrlist?ref=badge_large)