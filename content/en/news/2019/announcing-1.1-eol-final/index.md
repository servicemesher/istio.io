---
title: Support for Istio 1.1 has ended
description: Istio 1.1 end of life announcement.
publishdate: 2019-10-21
attribution: The Istio Team
aliases:
---

As [previously announced](/news/2019/announcing-1.1-eol/), support for Istio 1.1 has now officially ended.

Since we learned of the security vulnerability [behind our October 8th security release](/news/2019/istio-security-2019-005) while still barely within the 1.1 support period, we decided to extend the 1.1 support period beyond the original announcement and release [1.1.16](/news/2019/announcing-1.1.16).   Then we discovered a [bug in HTTP header size calculation](https://github.com/istio/istio/issues/17735) was introduced by the security release, so we decided to release a fix in one last [1.1.17](/news/2019/announcing-1.1.17) release before closing out the 1.1 series for good.

At this point we will no longer back-port fixes for security issues and critical bugs to 1.1, so we heartily encourage you to upgrade to the latest version of Istio ({{<istio_release_name>}}) if you haven't already.
