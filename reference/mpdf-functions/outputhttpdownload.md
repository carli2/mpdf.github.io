---
layout: page
title: OutputHttpDownload()
parent_title: mPDF functions
permalink: /reference/mpdf-functions/outputhttpdownload.html
modification_time: 2022-01-08T12:00:50+00:00
---

mPDF &ge; 8.1.2

OutputHttpDownload – Finalise the document and return binary data of resulting PDF

# Description

void **OutputHttpDownload**(string <span class="parameter">$filename</span>)

# Parameters

<span class="parameter">$filename</span>

: The filename to send for the downloaded file.

# Examples

## Example #1

```php
<?php

$mpdf = new \Mpdf\Mpdf();
$mpdf->WriteHTML('Hello World');

$mpdf->OutputHttpDownload('download.pdf');
```

# Changelog

<table class="table">
<thead>
<tr>
    <th>Version</th>
    <th>Description</th>
</tr>
</thead>
<tbody>
<tr>
    <td>8.1.2</td>
    <td>Method was added.</td>
</tr>
</tbody>
</table>