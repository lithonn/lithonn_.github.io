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

---

## [CVE-2022-4229](2022/CVE-2023-2684/)

**File Renaming on Upload <= 2.5.1 - Authenticated (Admin+) Stored Cross-Site Scripting**

The CVE-2023-2684 vulnerability is a Stored Cross-Site Scripting (XSS) issue that exists within the plugin's setting panel. This plugin does not sanitise and escape datetime format settings, which could allow high privilege users such as admin to perform Stored Cross-Site Scripting attacks even when the unfiltered_html capability is disallowed.

## [CVE-2022-4229](2022/CVE-2022-4229/)

**SourceCodester Book Store Management System 1.0 /bsms_ci/index.php Access Control**

CVE-2022-4229 is a vulnerability classified as critical was found in SourceCodester Book Store Management System 1.0. This vulnerability affects an unknown part of the file /bsms_ci/index.php. The manipulation with an unknown input leads to a access control vulnerability. The software does not restrict or incorrectly restricts access to a resource from an unauthorized actor. As an impact it is known to affect confidentiality, integrity, and availability.

[:octicons-arrow-right-24: Continue reading][Search: better, faster, smaller]

[Search: better, faster, smaller]: 2021/search-better-faster-smaller.md
[insiders-3.0.0]: ../insiders/changelog.md#3.0.0
