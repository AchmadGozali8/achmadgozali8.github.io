---
layout: post
title: Apa itu mocking?
tags: [mocking, programming, tdd, unittest]
image: '/images/posts/mocking.jpeg'
---

# Apa itu Mocking?

Mocking pada dasarnya digunakan pada unit test.

Membuat object untuk mensimulasikan behaviour dari dependency yang digunakan itulah yang disebut mocking.

Jadi misal kita membuat fungsi untuk melakukan pengiriman email, tentu kita tidak ingin tiap test dijalankan email juga selalu dikirimkan. Karena kita tidak ingin menerima spam email dan juga test tidak boleh bergantung pada external services (Email service).

Dengan mocking kita dapat menghindari hal tersebut dengan membuat simulasi object yang sebenarnya.
