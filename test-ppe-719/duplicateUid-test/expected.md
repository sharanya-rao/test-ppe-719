# Test

## Duplicate Uid test

Test if V2 and V3 have same xref map if there is duplicate uid

### Case1
[uid conflict in one SDP](https://github.com/live1206/docfx/blob/fd1a56f3af787291d45397b9fb48259d651f2196/docs/specs/xref.yml#L334):
- a
- duplicateUid-test\case1\duplicate-in-same-file.yml

### Case2
[Define duplicate uid in conceptual and SDP, should output error and uid cannot be resolved](https://github.com/live1206/docfx/blob/6888051d59e7f7b725d0555005c1caf0216e5b48/docs/specs/xref.yml#L184)
- b
- duplicateUid-test\case2\dupe-id-in-conceptual.yml
