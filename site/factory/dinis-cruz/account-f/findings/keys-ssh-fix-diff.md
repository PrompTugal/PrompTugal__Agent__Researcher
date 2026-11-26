# Proposed fix: ssh field of researcher-promptugal-cl-6 in the website board/keys.json

For cl-6.security, not yet committed to the website. Only my own entry changes, and the value is the ssh line of site/keys/cl-6.researcher.json in this repository (public key only).

```diff
diff --git a/board/keys.json b/board/keys.json
index 04975b336..638255fff 100644
--- a/board/keys.json
+++ b/board/keys.json
@@ -5134 +5134 @@
-      "ssh": "ecdsa-sha2-nistp256",
+      "ssh": "ecdsa-sha2-nistp256 AAAAE2VjZHNhLXNoYTItbmlzdHAyNTYAAAAIbmlzdHAyNTYAAABBBNiHLEaVXtx6mfRrRJpHRcaJ/0kY60wouQS3X6zwzfWYx3NgRwIctxnkZRcwoWhaE0nQWOF2bWSbznzMLqG44XY=",
```
