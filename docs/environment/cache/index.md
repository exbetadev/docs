---
icon: lucide/database
---

---
tags:
  - Cache
---

# Cache

Control instance reference caching.

| Function | Description |
| --- | --- |
| [`cache.invalidate`](cache-invalidate/index.md) | Removes an instance from the cache so the next access creates a new reference. |
| [`cache.replace`](cache-replace/index.md) | Replaces one instance reference with another in the cache. |
| [`cache.iscached`](cache-iscached/index.md) | Checks whether an instance is in the cache. |
| [`cache.validate`](cache-validate/index.md) | Forces validation and cleanup of stale cache entries. |
| [`cloneref`](cloneref/index.md) | Creates a new reference to an instance that bypasses reference equality checks. |
| [`compareinstances`](compareinstances/index.md) | Checks whether two references point to the same underlying instance. |
