<!-- golf-picks-record readme v1 -->
# Golf picks record

A public, timestamped record of a golf model's weekly betting card (paper trading).

**How to verify.** Each card in `cards/` is posted before the event's first tee time and
has a matching GitHub *Release* (see Releases). A release's time is set by GitHub's
server, so it can't be backdated. Card files are never edited after posting; if picks
ever change before the event, the new version is posted as a separate `_v2` file and
release, the original stays, and the record counts the latest version.

**What's here**
- `cards/*_card.md`: the picks, odds taken (FanDuel), model and market probabilities.
- `cards/*_results.md`: results and closing line value (CLV), added after the event.
- `RESULTS.md`: running totals by market. `record.csv`: every pick in one table.

Weeks with no qualifying picks are posted too, so the record can't skip bad weeks.

Paper trading: these are model picks tracked for a public record, not real bets and not advice. 21+. Gambling problem? Call 1-800-GAMBLER.
