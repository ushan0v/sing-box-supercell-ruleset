# sing-box Supercell rule-set

Binary `.srs` rule-set for Supercell domains.

## Included domain suffixes

- `supercell.com`
- `clashroyaleapp.com`
- `clashroyale.com`
- `clashofclans.com`
- `brawlstarsgame.com`
- `brawlstars.com`
- `haydaygame.com`
- `hayday.com`
- `boombeachgame.com`
- `boombeach.com`
- `squadbusters.com`
- `mo.co`

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
Binary sing-box rule-set (.srs) for Supercell domains
