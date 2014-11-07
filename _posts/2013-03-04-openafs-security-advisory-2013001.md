---
title: OpenAFS Security Advisory 2013-001
layout: page
category: news
---

#### 2013-03-04 - OpenAFS Security Advisory 2013-001

OpenAFS servers versions before 1.6.2 for all platforms.   An attacker
with the ability to manipulate AFS directory ACLs may crash the
fileserver hosting that volume. In addition, once a corrupt ACL is
placed on a fileserver, its existence may crash client utilities
manipulating ACLs on that server. This vulnerability is being tracked as
CVE-2013-1794.

-   [Go to the advisory](/security/OPENAFS-SA-2013-001.txt)
