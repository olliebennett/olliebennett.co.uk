---
layout: project
title: QRupted
website: https://www.qrupted.com
website_pretty: qrupted.com
summary: Corrupted QR Codes with custom text overlay.
logo: /assets/img/projects/qrupted.png
date: 2014-01-01
tools:
  - Raw HTML
  - jQuery
  - jquery-qrcode
---

Generate a QR Code with pixellated ASCII text superimposed! Enter your QR data to encode, and some brief text to overlay, and the QR code is created in realtime in your browser.

The concept relies on built-in error correction in the QR Code specification; the encoded data is still accessible despite the central part of the image being mangled.

The QR is generated client-side using an open source [QRcode library](https://larsjung.de/jquery-qrcode/). Anonymous saving or sharing of results is supported by a short-code based save feature.

This project scratched an itch I had for a human-readable or 'glanceable' QR code that gives at least some information or indication of purpose before being scanned. The solution was similar to those which overlaid a generic image or logo on the QR code, but QRupted uses a more integrated design aesthetic.
