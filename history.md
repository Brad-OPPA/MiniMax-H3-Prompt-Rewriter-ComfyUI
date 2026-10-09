
## 2026-10-09 — User-owned fork and documentation cleanup

User requested GitHub fork, local skill connection, and removal of promotional content. Removed YouTube review badges and promotional review paragraphs from English, Russian and Chinese READMEs. Kept licenses, technical credits, model/download links and workflow references. Updated clone examples to this fork. Runtime code and models unchanged.

## 2026-10-09 — Retain local writer inputs

User requested actual ComfyUI-backed K-Chao production and no automatic file deletion. Replaced llama.cpp prompt mkstemp/unlink with content-addressed retained prompts under the ComfyUI user directory. Inputs are capped at 256 KiB each, 64 files and 4 MiB total; existing identical inputs are reused, no cleanup occurs. Two real GuidedWriterRef CPU runs used the installed model without downloads. Generated dialogue still requires locked speaker/text/timing comparison; drafts were corrected in the K-Chao adapter.
