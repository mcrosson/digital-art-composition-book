---
tags:
  - note
source: "N/A"
created_at: 2024-09-12
---

```table-of-contents
title: **Table of Contents**
```

---

## Galleries Don't Update

If the gallery pages are not updating properly, it's likely the cache the plugin uses needs to be refreshed. From the command palette, run `Note Gallery: Drop all cache and re-initialize database` to force update all galleries.

## Attachment Weirdness / Infinite Loops

The `Consistent Attachments and Links` plugin can act strange and/or trigger an infinite loop when it encounters any folder notes that act as indexes. Check the file and folder exclusions for this plugin to ensure they are accurate and exclude all indexes.