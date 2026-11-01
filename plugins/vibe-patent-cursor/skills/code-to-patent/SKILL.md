---
name: code-to-patent
description: Turns the current repository into a Vibe Patent software specification disclosure. Use when the user asks to patent, protect or disclose their code or invention.
---

# Code to patent disclosure

Use this workflow to prepare a Vibe Patent disclosure from the repository open in Cursor.

1. Call `vibe_patent_prepare_repo_disclosure` and follow the returned `drafting_brief` exactly. The brief is the authority on content, structure and rules.
2. Read the repository locally and assemble the software specification as the brief describes. The repository itself is never sent to Vibe Patent.
3. Submit the specification the way the brief says: save it to a file and upload it with `vibe_patent_get_signed_upload_url` and `vibe_patent_attach_file`, or, when a file upload is not possible, call `vibe_patent_new_disclosure` with the text.
4. Show the user the `disclosure_id`. Offer `vibe_patent_get_web_signin_link` to open the disclosure in the browser, and offer the next steps given by `next_action`.
