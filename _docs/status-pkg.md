---
layout: default
title: 包文档翻译状态
summary: 记录了包文档的翻译状态及任务分配。
---

本文档用于记录包文档的翻译状态及任务分配。包文档位于`go/src`内的各包源码注释中。

<pre>
src
├── archive
│   ├── tar  // Liudi Wu: 完成 (Chensi Yuan: 整理)
│   └── zip  // Liudi Wu: 完成 (Chensi Yuan: 整理)
├── bufio    // OlingCat: 部分完成 (Chensi Yuan：整理合并 Liudi Wu 翻译)
├── builtin  // OlingCat: 完成
├── bytes    // Liudi Wu：完成 (Chensi Yuan: 待整理)
├── compress
│   ├── bzip2
│   ├── flate
│   ├── gzip
│   ├── lzw
│   └── zlib
├── container
│   ├── heap
│   ├── list
│   └── ring
├── crypto
│   ├── aes
│   ├── cipher
│   ├── des
│   ├── dsa
│   ├── ecdsa
│   ├── elliptic
│   ├── hmac     // zieckey : *翻译*
│   ├── md5      // Bluek404: *翻译*
│   ├── rand
│   ├── rc4
│   ├── rsa
│   ├── sha1
│   ├── sha256
│   ├── sha512
│   ├── subtle
│   ├── tls
│   └── x509
│       └── pkix
├── database
│   └── sql        // 轩脉刃: 完成 (OlingCat: sql.go *更新*，已标出TODO.)
│       └── driver // 轩脉刃: *翻译*
├── debug
│   ├── dwarf
│   ├── elf
│   ├── goobj
│   ├── gosym
│   ├── macho
│   ├── pe
│   └── plan9obj
├── encoding
│   ├── ascii85 // Xize Dong: *校对*
│   ├── asn1    // Xize Dong: *翻译*
│   ├── base32  // Xize Dong: *待译*
│   ├── base64  // Xize Dong: *待译*
│   ├── binary  // Xize Dong: *待译*
│   ├── csv     // Xize Dong: *待译*
│   ├── gob     // Xize Dong: *待译*
│   ├── hex     // Xize Dong: *待译*
│   ├── json    // Xize Dong: *待译*
│   ├── pem     // Xize Dong: *待译*
│   └── xml     // Xize Dong: *待译*
├── errors // OlingCat: 完成
├── expvar
├── flag   // 轩脉刃: 完成 (OlingCat: *更新*)
├── fmt    // OlingCat & Liudi Wu: 完成
├── go
│   ├── ast
│   ├── build
│   ├── doc
│   ├── format
│   ├── parser
│   ├── printer
│   ├── scanner
│   └── token
├── hash        // zieckey : *待译*
│   ├── adler32 // zieckey : *待译*
│   ├── crc32   // zieckey : *待译*
│   ├── crc64   // zieckey : *待译*
│   └── fnv     // zieckey : *待译*
├───html            // Cipher Chen: *待译*
│   └── template    // Cipher Chen: *待译*
├── image           // 轩脉刃: 完成
│   ├── color       // 轩脉刃: 完成
│   │   └─ palette  // 轩脉刃: *待译*
│   ├── draw        // 轩脉刃: 完成
│   ├── gif         // 轩脉刃: 完成
│   ├── jpeg        // 轩脉刃: *待译*
│   └── png         // 轩脉刃: 完成
├── index
│   └── suffixarray
├── internal
│   └── syscall
├── io         // OlingCat: 完成
│   └── ioutil // OlingCat & Liudi Wu: 完成
├── log
│   └── syslog
├── math      // OlingCat: 完成
│   ├── big   // OlingCat: *翻译*
│   ├── cmplx // OlingCat: 完成
│   └── rand  // OlingCat: *待译*
├── mime
│   ├── internal
│   │   └── quotedprintable
│   └── multipart
├── net
│   ├── http          // OlingCat & Liudi Wu: 完成 (OlingCat: 需整理)
│   │   ├── cgi       // 轩脉刃: 完成
│   │   ├── cookiejar // 轩脉刃: *待译*
│   │   ├── fcgi      // 轩脉刃: 完成
│   │   ├── httptest  // 轩脉刃: 完成
│   │   ├── httputil  // 轩脉刃: 完成
│   │   ├── internal  // 轩脉刃: 完成
│   │   └── pprof     // 轩脉刃: 完成
│   ├── mail          // 轩脉刃: 完成
│   ├── rpc           // 轩脉刃: 完成
│   │   └── jsonrpc   // 轩脉刃: 完成
│   ├── smtp
│   ├── textproto
│   └── url
├── os
│   ├── exec
│   ├── signal
│   └── user
├── path
│   └── filepath
├── reflect
├── regexp
│   └── syntax
├── runtime    // OlingCat: 完成 (OlingCat: 需更新)
│   ├── cgo    // OlingCat: 完成
│   ├── debug  // OlingCat: 完成
│   ├── pprof  // OlingCat: 完成
│   └── race   // OlingCat: 完成
├── sort       // Johntech: 完成 (OlingCat: 已校对)
├── strconv    // OlingCat: *待译*
├── strings
├── sync       // OlingCat: 完成
│   └── atomic // OlingCat: 完成
├── syscall
├── testing
│   ├── iotest
│   └── quick
├── text           // Stone Lion: *翻译*
│   ├── scanner    // Stone Lion: *翻译*
│   ├── tabwriter  // Stone Lion: *翻译*
│   └── template   // Stone Lion: *翻译*
│       └── parse  // Stone Lion: *翻译*
├── time      // OlingCat: *待译*
├── unicode   // OlingCat: 完成
│   ├── utf16 // OlingCat: 完成
│   └── utf8  // OlingCat: 完成
└── unsafe    // OlingCat: 完成
</pre>

以下包文档的翻译需要调整为新格式并重新校对：

<pre>
├── archive
│   ├── tar  // Liudi Wu: 完成 (Chensi Yuan: 整理)
│   └── zip  // Liudi Wu: 完成 (Chensi Yuan: 整理)
├── bufio    // OlingCat: 部分完成 (Chensi Yuan：整理合并 Liudi Wu 翻译)
├── builtin  // OlingCat: 完成
├── encoding
│   ├── ascii85 // Xize Dong: *校对*
│   └── asn1    // Xize Dong: *翻译*
├── errors // OlingCat: 完成
├── flag   // 轩脉刃: 完成 (OlingCat: *更新*)
├── fmt    // OlingCat & Liudi Wu: 完成
├── image           // 轩脉刃: 完成
│   ├── color       // 轩脉刃: 完成
│   ├── draw        // 轩脉刃: 完成
│   ├── gif         // 轩脉刃: 完成
│   └── png         // 轩脉刃: 完成
├── io         // OlingCat: 完成
│   └── ioutil // OlingCat & Liudi Wu: 完成
├── math      // OlingCat: 完成
│   ├── big   // OlingCat: *翻译*
│   ├── cmplx // OlingCat: 完成
│   └── rand  // OlingCat: *待译*
├── net
│   ├── http          // OlingCat & Liudi Wu: 完成 (OlingCat: 需整理)
│   │   ├── cgi       // 轩脉刃: 完成
│   │   ├── cookiejar // 轩脉刃: *待译*
│   │   ├── fcgi      // 轩脉刃: 完成
│   │   ├── httptest  // 轩脉刃: 完成
│   │   ├── httputil  // 轩脉刃: 完成
│   │   └── pprof     // 轩脉刃: 完成
│   ├── mail          // 轩脉刃: 完成
│   └── rpc           // 轩脉刃: 完成
│       └── jsonrpc   // 轩脉刃: 完成
├── runtime    // OlingCat: 完成 (OlingCat: 需更新)
│   ├── cgo    // OlingCat: 完成
│   ├── debug  // OlingCat: 完成
│   ├── pprof  // OlingCat: 完成
│   └── race   // OlingCat: 完成
├── sort       // Johntech: 完成 (OlingCat: 已校对)
├── sync       // OlingCat: 完成
│   └── atomic // OlingCat: 完成
├── unicode   // OlingCat: 完成
│   ├── utf16 // OlingCat: 完成
│   └── utf8  // OlingCat: 完成
└── unsafe    // OlingCat: 完成
</pre>
