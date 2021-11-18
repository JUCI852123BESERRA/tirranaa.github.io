---
layout: post
title: Intel Low-power Chips Hit by New Security Flaw
date:   2021-11-18 20:47:04 +0200
slug: blog
description: A category for general blog posts.
---

## Intel Low-power Chips Hit by New Security Flaw

Debug mode has 'excessive privileges'

![](https://cdn.mos.cms.futurecdn.net/PWnQuGZrReBRM6BFmiCMYj-970-80.jpg.webp)

###### (Image credit: Shutterstock)

The chips in question are Apollo Lake and Gemini Lake (plus Refresh) Atom, Celeron, and Pentium products. They’re all low-power chips used in embedded systems, mobile devices, and cheap laptops. Positive Technologies responsibly disclosed the flaw to Intel (which has put out [an advisory](https://www.intel.com/content/www/us/en/security-center/advisory/intel-sa-00528.html)) before going public, and it has been assigned the reference [CVE-2021-0146](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-0146). It requires physical access to the computer and sees the chip tricked into entering a test debugging mode that has excessively high privileges, from which root encryption keys can be extracted. “The bug can also be exploited in targeted attacks across the supply chain,” said Positive’s Mark Ermolov in a statement. “For example, an employee of an Intel processor-based device supplier could, in theory, extract the Intel CSME firmware key and deploy spyware that security software would not detect.”

A UEFI BIOS update can plug the security hole, and owners of affected systems are advised to look out for an update from their device’s manufacturer.
