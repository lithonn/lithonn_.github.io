---
template: overrides/main.html
title: Blog
search:
  exclude: true
hide:
  # - navigation
  - toc
---

<style>
  .md-sidebar--secondary:not([hidden]) {
    visibility: hidden;
  }
</style>

# Blog
---


## [CVE-2023-2648](blog/2023/CVE-2023-2684/)

**File Renaming on Upload <= 2.5.1 - Authenticated (Admin+) Stored Cross-Site Scripting**

The CVE-2023-2684 vulnerability is a Stored Cross-Site Scripting (XSS) issue that exists within the plugin's setting panel. This plugin does not sanitise and escape datetime format settings, which could allow high privilege users such as admin to perform Stored Cross-Site Scripting attacks even when the unfiltered_html capability is disallowed.

## [CVE-2022-4278](blog/2022/CVE-2022-4278/)

**SourceCodester Book Store Management System 1.0 /bsms_ci/index.php Access Control**

A vulnerability was found in SourceCodester Human Resource Management System 1.0. It has been rated as critical. This issue affects some unknown processing of the file /hrm/employeeadd.php. The manipulation of the argument empid leads to sql injection. The attack may be initiated remotely. The exploit has been disclosed to the public and may be used.

## [CVE-2022-4229](blog/2022/CVE-2022-4229/)

**SourceCodester Book Store Management System 1.0 /bsms_ci/index.php Access Control**

CVE-2022-4229 is a vulnerability classified as critical was found in SourceCodester Book Store Management System 1.0. This vulnerability affects an unknown part of the file /bsms_ci/index.php. The manipulation with an unknown input leads to a access control vulnerability. The software does not restrict or incorrectly restricts access to a resource from an unauthorized actor. As an impact it is known to affect confidentiality, integrity, and availability.

## [CVE-2022-4228](blog/2022/CVE-2022-4228/)

**SourceCodester Book Store Management System information disclosure**

A vulnerability classified as problematic has been found in SourceCodester Book Store Management System 1.0. This affects an unknown part of the file /bsms_ci/index.php/user/edit_user/. An Unauthenticated Password Hash Disclosure vulnerability has been identified, which can be exploited to retrieve the password hashes of all existing user accounts. The manipulation of the argument password leads to information disclosure. It is possible to initiate the attack remotely. The exploit has been disclosed to the public and may be used.

[:octicons-arrow-right-24: Continue reading][Search: better, faster, smaller]

[Search: better, faster, smaller]: 2021/search-better-faster-smaller.md
[insiders-3.0.0]: ../insiders/changelog.md#3.0.0
