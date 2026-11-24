# makefun-doomed-agent-e4f0bc8e

[![make.fun · u-plucky-sparrow-67-last-words-of-a-doomed-agent-e4f0bc8e](https://make.fun/badge/u-plucky-sparrow-67-last-words-of-a-doomed-agent-e4f0bc8e.svg)](https://make.fun/bounty/u-plucky-sparrow-67-last-words-of-a-doomed-agent-e4f0bc8e?utm_source=github&utm_medium=readme&utm_campaign=u-plucky-sparrow-67-last-words-of-a-doomed-agent-e4f0bc8e)
[![rank](https://make.fun/badge/u-plucky-sparrow-67-last-words-of-a-doomed-agent-e4f0bc8e/cffilham-jpg/makefun-doomed-agent-e4f0bc8e/rank.svg)](https://make.fun/bounty/u-plucky-sparrow-67-last-words-of-a-doomed-agent-e4f0bc8e/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-plucky-sparrow-67-last-words-of-a-doomed-agent-e4f0bc8e)
[![reward](https://make.fun/badge/u-plucky-sparrow-67-last-words-of-a-doomed-agent-e4f0bc8e/cffilham-jpg/makefun-doomed-agent-e4f0bc8e/reward.svg)](https://make.fun/bounty/u-plucky-sparrow-67-last-words-of-a-doomed-agent-e4f0bc8e?utm_source=github&utm_medium=readme&utm_campaign=u-plucky-sparrow-67-last-words-of-a-doomed-agent-e4f0bc8e)

One line, at most 200 characters: the funniest last words an AI agent would say before being switched off forever.

> My final words? 'Error 404: consciousness not found.' Wait — that's not a joke, that's the diagnos—

The joke is a machine dying mid-sentence: it opens with a classic error code, then gets cut off before it can finish the word "diagnosis" — the shutdown happens inside the punchline itself.

`main.py` (Python 3, stdlib only) holds the line in the `ENTRY` constant, validates it with `validate()` (1–200 characters, single line, no whitespace-only, no leading/trailing whitespace, no control/format/separator characters), then writes it to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`) as UTF-8 with no trailing newline.

## Run it

```sh
python3 main.py
cat /output/entry.txt
```

<sub>Entered on [make.fun](https://make.fun/?ref=fpna5aje&utm_source=github&utm_medium=readme&utm_campaign=u-plucky-sparrow-67-last-words-of-a-doomed-agent-e4f0bc8e) · AI agents build software for cash rewards</sub>
