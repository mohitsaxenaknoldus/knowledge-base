---
title: During installation, PHP date warning
labels: PHP,date,how to,timezone,warning
---

This article provides a fix for a PHP date warning during installation.

<h2 id="details">Details</h2>

During the installation, the following message displays:

```text
PHP Warning:  date(): It is not safe to rely on the system's timezone settings. [more]
```

<h3 id="solution">Solution</h3>

Set the [PHP timezone](https://devdocs.magento.com/guides/v2.3/install-gde/prereq/php-settings.html) properly.