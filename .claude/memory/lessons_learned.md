# Lessons learned

Pitfalls met in earlier sessions. Check here before repeating an approach.

- **Wikipedia, Math is Fun, the Stanford Encyclopedia, YouTube and github.io are blocked** by the cloud session's network policy. Describe such a page from memory and say so; check a deploy through the Actions API, not by fetching the site.
- **The owner's external drive is unreachable** from cloud sessions. Search Google Drive first; otherwise ask the owner to upload the file.
- **A new example has no answer key**: run `python3 tools/run_examples.py --only <stem> --update` once, then the plain check.
- **After a pull request is merged**, restart the working branch from `origin/main` before new work. Force pushes are not an option.
- **Studies cited from memory** (author, year, journal) should be said to be from memory in the reply, so the owner knows they were not looked up. On an evidence-graded page, a source cited from memory gets at most "good evidence".
- **The Polish summaries use „ and a plain " as closing quote.** When editing one with a Python script, wrap the match strings in triple quotes.
- **Write edit scripts to a file in the scratchpad and run them**, rather than inline heredocs: one syntax error costs the whole batch.
- **A move between repositories goes stale fast.** Sibling sessions keep adding lessons; before merging a move, diff the source folder against the snapshot that was copied, and port what arrived.
- **Chapter `README.md` files have paragraphs of many kilobytes on one line.** Slice them with a short Python script, not long shell pipelines.
