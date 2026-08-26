# takochan full-text search shard 002

This public Project Pages repository contains the generated Pagefind shard for
publications assigned to search shard `002`. It does not contain PDFs, EPUBs,
working masters, or hand-edited search data.

`source.json` pins the exact public archive commit and shard ID. The Pages
workflow checks out that commit, downloads checksum-verified PDF/EPUB inputs,
builds only the assigned shard, verifies its page maps, and deploys `dist/search`.

Existing publication slugs must not be moved between shards merely to rebalance
catalogue order.
