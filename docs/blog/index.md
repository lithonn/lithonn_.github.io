---
template: overrides/main.html
title: Blog
search:
  exclude: true
---

<style>
  .md-sidebar--secondary:not([hidden]) {
    visibility: hidden;
  }
</style>

# Blog

## [CVE-2022-4229](2022/CVE-2022-4229/)

**SourceCodester Book Store Management System 1.0 /bsms_ci/index.php Access Control**

<aside class="mdx-author" markdown>
![@squidfunk][@squidfunk avatar]

<span>**msplme** · @Huy3nMy</span>
<span>
:octicons-calendar-24: November 30, 2022 ·
:octicons-clock-24: 5 min read ·
</span>

</aside>
[built-in search plugin]: ../../setup/setting-up-site-search.md#built-in-search-plugin
[@squidfunk avatar]: ../../assets/author/casicon.png
[insiders-4.14.0]: ../../insiders/changelog.md#4.14.0

---

CVE-2022-4229 is a vulnerability classified as critical was found in SourceCodester Book Store Management System 1.0. This vulnerability affects an unknown part of the file /bsms_ci/index.php. The manipulation with an unknown input leads to a access control vulnerability. The software does not restrict or incorrectly restricts access to a resource from an unauthorized actor. As an impact it is known to affect confidentiality, integrity, and availability.

[:octicons-arrow-right-24: Continue reading][Search: better, faster, smaller]

[Search: better, faster, smaller]: 2021/search-better-faster-smaller.md
[insiders-3.0.0]: ../insiders/changelog.md#3.0.0
