---
layout: news_post
title: "Ruby 2.6.5 Yayınlandı"
author: "nagachika"
translator: "İsmail Arılık"
date: 2019-10-01 11:00:00 +0000
lang: tr
---

Ruby 2.6.5 yayınlandı.

Bu sürüm güvenlik düzeltmeleri içermektedir.
Ayrıntılar için lütfen aşağıdaki konulara bakın.

* [CVE-2019-16255: Shell#[] ve Shell#test'in bir kod enjeksiyonu güvenlik açığı]({% link tr/news/_posts/2019-10-01-code-injection-shell-test-cve-2019-16255.md %})
* [CVE-2019-16254: WEBrick'te HTTP yanıtı ayırma (Ek düzeltme)]({% link tr/news/_posts/2019-10-01-http-response-splitting-in-webrick-cve-2019-16254.md %})
* [CVE-2019-15845: File.fnmatch ve File.fnmatch?'in bir NUL enjeksiyonu güvenlik açığı]({% link tr/news/_posts/2019-10-01-nul-injection-file-fnmatch-cve-2019-15845.md %})
* [CVE-2019-16201: WEBrick'in Özet erişim kimlik doğrulamasında Düzenli İfade Hizmet Reddi güvenlik açığı]({% link tr/news/_posts/2019-10-01-webrick-regexp-digestauth-dos-cve-2019-16201.md %})

Ayrıntılar için [işleme logları](https://github.com/ruby/ruby/compare/v2_6_4...v2_6_5)na bakın.

## İndirin

{% assign release = site.data.releases | where: "version", "2.6.5" | first %}

* <{{ release.url.bz2 }}>

      BOYUT: {{ release.size.bz2 }}
      SHA1: {{ release.sha1.bz2 }}
      SHA256: {{ release.sha256.bz2 }}
      SHA512: {{ release.sha512.bz2 }}

* <{{ release.url.gz }}>

      BOYUT: {{ release.size.gz }}
      SHA1: {{ release.sha1.gz }}
      SHA256: {{ release.sha256.gz }}
      SHA512: {{ release.sha512.gz }}

* <{{ release.url.xz }}>

      BOYUT: {{ release.size.xz }}
      SHA1: {{ release.sha1.xz }}
      SHA256: {{ release.sha256.xz }}
      SHA512: {{ release.sha512.xz }}

* <{{ release.url.zip }}>

      BOYUT: {{ release.size.zip }}
      SHA1: {{ release.sha1.zip }}
      SHA256: {{ release.sha256.zip }}
      SHA512: {{ release.sha512.zip }}

## Yayın Yorumu

Birçok işleyici, geliştirici ve hata bildirimi sunan kullanıcı bu yayını yapmamızda bize yardımcı oldu.
Katkıları için onlara teşekkür ederiz.
