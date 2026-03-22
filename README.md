# sing-box Supercell rule-set

Binary `.srs` rule-set for Supercell domains.

## Included domain suffixes

- `boombeachgame.com`
- `boombeach.com`
- `brawlstars.com`
- `brawlstarsgame.com`
- `clash.com`
- `clashmini.com`
- `clashofclans.com`
- `clashroyale.com`
- `clashroyaleapp.com`
- `gamesfirsthelsinki.com`
- `hayday.com`
- `haydaygame.com`
- `mo.co`
- `seeurlpcl.com`
- `squadbusters.com`
- `supercell.com`
- `supercell.helpshift.com`
- `supercell.net`
- `supercellcreators.com`
- `supercellgames.com`
- `supercellid.com`
- `supercellstore.com`

## Files

- `supercell.json` - source rule-set
- `supercell.srs` - compiled binary rule-set

## Example

```json
{
  "route": {
    "rule_set": [
      {
        "tag": "supercell",
        "type": "remote",
        "format": "binary",
        "url": "https://raw.githubusercontent.com/ushan0v/sing-box-supercell-ruleset/main/supercell.srs",
        "download_detour": "direct"
      }
    ],
    "rules": [
      {
        "rule_set": "supercell",
        "outbound": "proxy"
      }
    ]
  }
}
```
