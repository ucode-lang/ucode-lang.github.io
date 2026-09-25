# ucode-lang

This is the GitHub organization for the [ucode scripting language](https://ucode.mein.io/).

ucode is a small, general-purpose scripting language with ECMAScript-like syntax,
designed for template processing, system scripting, and embedding into C
applications. It emphasizes a small footprint, efficient JSON handling, and a
synchronous programming model, and ships with a set of built-in functions and
bindings for Linux/OpenWrt APIs (ubus, uci, socket, nl80211, ...). The language
is a core part of modern OpenWrt, where it powers the LuCI web interface and the
firewall4 framework, and is embedded in programs such as rpcd and uhttpd.

## Where to start

- [ucode documentation portal](https://ucode.mein.io/) — the most up-to-date
  documentation, including language reference, manual, and installation notes
- [`ucode` repository](https://github.com/ucode-lang/ucode) — the main language
  source (interpreter, C library, modules, tests, and built documentation)
- [Language examples](https://github.com/ucode-lang/ucode/tree/master/examples) —
  embedding ucode into C applications and sample scripts

The ucode package is preinstalled on modern OpenWrt releases; the
[installation section](https://ucode.mein.io/#installation) of the documentation
covers other systems.
