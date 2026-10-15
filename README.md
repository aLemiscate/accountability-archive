# Said / Did: saved copies

Raw copies of the sources cited by [Said / Did](https://alemiscate.github.io/accountability/), a sourced record of what OpenAI and Anthropic said and what they did next. The record itself lives in [aLemiscate/accountability](https://github.com/aLemiscate/accountability).

Each folder under `snapshots/` is one capture of one source, at the same path as in the main repository:

- `page.html`: the page as the server sent it
- `screenshot.jpg`: a full-page screenshot as a browser rendered it
- `document.pdf`: the file, for sources that are PDFs
- `media-*.jpg`, `quoted-media-*.jpg`: images attached to a post
- `page.txt`, `rendered.txt`, `post.txt`, `document.txt`: the readable text, which the main repository also keeps for its quote check
- `meta.json`: capture time, HTTP status and the SHA-256 hash of every file

These files moved here on 2026-10-15 because they made the main repository too large to clone quickly. Copies from before that date are also in the main repository's git history. New captures are added by the main repository's Capture and Watch workflows.
