---
title: Accessibility Conformance Testing (ACT) Overview
permalink: /standards-guidelines/act/
layout: default
github:
  repository: w3c/wai-intro-act
feedbackmail: wai@w3.org
footer: >
  <p><strong>Date:</strong> Updated 3 July 2018.</p>
  <p><strong>Editors:</strong> <a href="https://www.w3.org/People/shadi/">Shadi Abou-Zahra</a> and <a href="http://www.w3.org/People/Shawn/">Shawn Lawton Henry</a>.</p>
  <p>Developed with input from the Education and Outreach Working Group (<a href="http://www.w3.org/WAI/EO/">EOWG</a>) and the <a href=" https://www.w3.org/WAI/GL/task-forces/conformance-testing ">ACT Task Force </a>.</p>
  
---


{::nomarkdown}
{% include box.html type="start" h="2" title="Summary" class="full" %}
{:/}

This page introduces the [Accessibility Conformance Testing (ACT) Rules Format](https://www.w3.org/TR/act-rules-format/) and related documents.

{::nomarkdown}
{% include box.html type="end" %}
{:/}


{::options toc_levels="2" /}

{::nomarkdown}
{% include_cached toc.html type="start" title="Page Contents" %}
{:/}

-   TOC is created automatically.
{:toc}

{::nomarkdown}
{% include_cached toc.html type="end" %}
{:/}

## Introduction

The purpose of the Accessibility Conformance Testing (ACT) effort is to establish and document rules for testing the conformance of web content to accessibility standards, such as Web Content Accessibility Guidelines (WCAG). These test rules address automated, semi-automated, and manual testing. The ACT Task Force aims to make accessibility testing transparent, and thus minimize confusion caused by different interpretations of accessibility guidelines.

## Who ACT is for

The primary audience of Accessibility Conformance Testing (ACT) is developers of accessibility evaluation methodologies and tools. They implement ACT Rules into their products and services. ACT serves as documentation and requirements.

A secondary audience is accessibility experts. They often assist in setting an organization's accessibility policy, and it is important for them to know what the rules do.

Who ACT is **not** for: Users of accessibility tools (web developers, content authors, QA testers, etc.) are not expected to read ACT.

## What is in ACT

* [Accessibility Conformance Testing (ACT) Rules Format 1.0](https://www.w3.org/TR/act-rules-format/) defines the requirements for testing rules, to guide the developers of ACT Rules
* [Accessibility Conformance Testing (ACT) Rules Repository](https://w3c.github.io/wcag-act-rules/) provides a set of vetted testing rules following the ACT Rules Format specification

## Objectives of ACT

* **Establish consensus interpretation of accessibility requirements (Primarily WCAG) around a core set of test rules** &mdash; currently there are varying and often contradictory interpretations of WCAG, which causes confusion and slows down the implementation of web accessibility
* **Provide transparency and comparability of test tools and implementations** &mdash; currently test tools employ their own often proprietary interpretations of WCAG, making test results difficult to interpret, combine, and compare
* **Enable increased tool support by documenting structured testing procedures** &mdash; establishing a common base of test rules allows tool developers to focus on increasing tool support, to reduce the amount of manual testing required

## Status of ACT Rules Format 1.0

[Accessibility Conformance Testing (ACT) Rules Format 1.0](https://www.w3.org/TR/act-rules-format/) is currently a Working Draft. ACT Rule implementations of this specification are currently in development.

### Technical document format

The ACT Rules Format follows the W3C format for technical specifications, which includes several sections at the beginning: links to different versions, editors, copyright, abstract, and status with the link to errata and the email address for comments. Most WAI specifications have a link at the top to the Table of Contents.

## Who develops ACT

[ACT Task Force](https://www.w3.org/WAI/GL/task-forces/conformance-testing/) of the Accessibility Guidelines Working Group ([AG WG]( https://www.w3.org/WAI/GL/)) develops the normative ACT Rules Format specification and supporting materials needed to implement the standard.

The [auto-WCAG Community Group](https://auto-wcag.github.io/auto-wcag/) develops non-normative test rules according to the normative specification. Approved test rules are provided in the [Accessibility Conformance Testing (ACT) Rules Repository](https://w3c.github.io/wcag-act-rules/).

Opportunities for contributing to ACT and other WAI work are introduced in [Participating in WAI](/WAI/participation).

## Additional information

For more information, see:
* [ACT Overview - What is ACT wiki page](https://www.w3.org/WAI/GL/task-forces/conformance-testing/wiki/ACT_Overview_-_What_is_ACT)
* [WCSG Accessibility Conformance Testing (ACT) blog post](https://www.w3.org/blog/2017/04/wcag-accessibility-conformance-testing-act/)
