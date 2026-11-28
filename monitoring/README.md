<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Monitoring: what is read and what came of it

How global-law monitors every country: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). This page is the same for Vologda Oblast only: every time an official source is read, when, and what came of it (acts added, changed and removed). The machine-readable form is [data/checks/](../data/checks/) (JSON Lines, schema `lexifina-check/1`), in `git log` as `Kind: check` commits, and month by month in [checks/](checks/).

**Last check:** 2026-11-28 06:18 UTC, Vologda Oblast: Official Internet Portal of Legal Information (region35): 17 addresses read; 1 added, 0 changed, 0 removed; changes found; 0 not published, 0 of them with no reason.

## Sources

| Source | Folders | How often | Last successful check | Last result | State |
| --- | --- | --- | --- | --- | --- |
| [Vologda Oblast: Official Internet Portal of Legal Information (region35)](http://publication.pravo.gov.ru/documents/block/region35) | `zakony-<year>/` | daily | 2026-11-28 06:18 UTC | changes found | watched |

## The last 30 days

| Started (UTC) | Source | Read | Added | Changed | Removed | Not published (no reason) | Result | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-28 06:16](checks/2026-11.md#ru-pravo-vologda-20261128t061644z) | pravo-vologda | 17 | 1 | 0 | 0 | 0 (0) | changes found | [2](https://github.com/lexifina/russia-vologda-law/compare/c7441d81a4cc...2230d7f33471) |
| [2026-11-27 06:02](checks/2026-11.md#ru-pravo-vologda-20261127t060238z) | pravo-vologda | 17 | 1 | 0 | 0 | 0 (0) | changes found | [2](https://github.com/lexifina/russia-vologda-law/compare/8df70c08616d...d570d417d80a) |
| [2026-11-26 06:10](checks/2026-11.md#ru-pravo-vologda-20261126t061003z) | pravo-vologda | 17 | 2 | 0 | 0 | 0 (0) | changes found | [2](https://github.com/lexifina/russia-vologda-law/compare/83a9cc46e7e8...001becccd282) |
| [2026-11-25 06:51](checks/2026-11.md#ru-pravo-vologda-20261125t065137z) | pravo-vologda | 17 | 0 | 0 | 0 | 0 (0) | no change | — |
| [2026-11-24 15:02](checks/2026-11.md#ru-pravo-vologda-20261124t150218z) | pravo-vologda | 17 | 32 | 0 | 0 | 0 (0) | changes found | [4](https://github.com/lexifina/russia-vologda-law/compare/1e902e4bc181...04fba886fb61) |

## Check it yourself

```
python tools/checktrail.py                      # the latest check of every source
python tools/checktrail.py --day 2026-11-23     # every check of a day
python tools/checktrail.py --act <id>           # when an act was seen and published
git log --grep='^Kind: check' --format='%ci %s'  # the checks in the history
```

Only the official publication has legal force; the texts here are copies for reading and searching.
