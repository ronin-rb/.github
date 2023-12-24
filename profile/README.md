![Ronin](./profile/header.svg#gh-light-mode-only)
![Ronin](./profile/header_dark_mode.svg#gh-dark-mode-only)

# ronin-rb

* [Website](https://ronin-rb.dev/)
* [Discord](https://discord.gg/6WAb3PsVX9) |
  [Mastodon](https://infosec.exchange/@ronin_rb)

## Description

[Ronin][website] is a free and Open Source [Ruby] toolkit for security research
and development. Ronin contains many different [CLI commands](ronin-synopsis)
and [Ruby libraries][ronin-rb] for a variety of security tasks, such as
encoding/decoding data, filter IPs/hosts/URLs, querying ASNs, querying DNS,
HTTP, [scanning for web vulnerabilities][ronin-vulns-synopsis],
[spidering websites][ronin-web-spider],
[install 3rd party repositories][ronin-repos-synopsis] of
[exploits][ronin-exploits] and/or
[payloads][ronin-payloads], [run exploits][ronin-exploits-synopsis],
[write new exploits][ronin-exploits-examples],
[managing local databases][ronin-db-synopsis],
[fuzzing data][ronin-fuzzer], and much more.

## Repositories

* [ronin] - A Ruby toolkit for security research and development.
* [ronin-support] - A support library for Ronin.
* [ronin-core] - A core library for all ronin libraries.
* [ronin-repos] - Third-party git repository support for ronin.
* [ronin-fuzzer] - A highly configurable fuzzing library and CLI for Ruby.
* [ronin-db] - A common database library for managing and querying security
  data.
* [ronin-db-activerecord] - ActiveRecord backend for the Ronin Database.
* [ronin-dns-proxy] - A configurable DNS proxy server library.
* [ronin-listener] - A small CLI utility for receiving exfiltrated data over
  DNS or HTTP.
* [ronin-listener-dns] - A DNS server for receiving exfiltrated data sent via
  DNS queries. ronin-listener-dns can be used to test for XML external entity
  (XXE) injection
* [ronin-listener-http] - A HTTP server for receiving exfiltrated data sent via
  HTTP requests.
* [ronin-web] - A collection of common web security commands and libraries.
* [ronin-web-browser] - [WIP] A Ruby library for automating the Chrome web
  browser.
* [ronin-web-server] - A custom Ruby web server based on Sinatra.
* [ronin-web-spider] - A collection of common web spidering routines.
* [ronin-web-user_agents] - Generates random but realistic User-Agent strings.
* [ronin-code-asm] - A Ruby DSL for crafting Assmebly programs and Shellcode.
* [ronin-code-sql] - A Ruby DSL for crafting SQL Injections.
* [ronin-vulns] - Tests URLs for Local File Inclusion (LFI),
  Remote File Inclusion (RFI), SQL injection (SQLi), Cross Site Scripting (XSS),
  Server Side Template Injection (SSTI), and Open Redirects.
* [ronin-post_ex] - Ruby API for Post-Exploitation.
* [ronin-payloads] - A Ruby micro-framework for writing and running exploit
  payloads.
* [ronin-exploits] - A Ruby micro-framework for writing and running exploits
  and payloads.
* [ronin-wordlists] - [WIP] A library and tool for managing wordlists.
* [ronin-brute] - [WIP] A micro-framework and tool for bruteforcing credentials.
* [ronin-nmap] - [WIP] A Ruby library for working with nmap.
* [ronin-masscan] - [WIP] A Ruby library for working with masscan.
* [ronin-recon] - [WIP] A micro-framework and tool for performing
  reconnaissance.
* [docker] - `Dockerfile`s for the `ronin` docker images.
* [scripts] - The `ronin-install.sh` installer script and the `ronin-dev.sh`
  development environment setup script.
* [ronin-rb.github.io] - The website.

[Ruby]: https://www.ruby-lang.org
[website]: https://ronin-rb.dev/
[ronin-rb]: https://github.com/ronin-rb/
[ronin]: https://github.com/ronin-rb/ronin#readme
[ronin-synopsis]: https://github.com/ronin-rb/ronin#synopsis
[ronin-support]: https://github.com/ronin-rb/ronin-support#readme
[ronin-repos]: https://github.com/ronin-rb/ronin-repos#readme
[ronin-repos-synopsis]: https://github.com/ronin-rb/ronin-repos#synopsis
[ronin-core]: https://github.com/ronin-rb/ronin-core#readme
[ronin-db]: https://github.com/ronin-rb/ronin-db#readme
[ronin-db-synopsis]: https://github.com/ronin-rb/ronin-db#synopsis
[ronin-db-activerecord]: https://github.com/ronin-rb/ronin-db-activerecord#readme
[ronin-dns-proxy]: https://github.com/ronin-rb/ronin-dns-proxy#readme
[ronin-dns-proxy-synopsis]: https://github.com/ronin-rb/ronin-dns-proxy#synopsis
[ronin-dns-proxy-examples]: https://github.com/ronin-rb/ronin-dns-proxy#examples
[ronin-fuzzer]: https://github.com/ronin-rb/ronin-fuzzer#readme
[ronin-listener]: https://github.com/ronin-rb/ronin-listener#readme
[ronin-listener-synopsis]: https://github.com/ronin-rb/ronin-listener#synopsis
[ronin-listener-dns]: https://github.com/ronin-rb/ronin-listener-dns#readme
[ronin-listener-dns-examples]: https://github.com/ronin-rb/ronin-listener-dns#examples
[ronin-listener-http]: https://github.com/ronin-rb/ronin-listener-http#readme
[ronin-listener-http-examples]: https://github.com/ronin-rb/ronin-listener-http#examples
[ronin-web]: https://github.com/ronin-rb/ronin-web#readme
[ronin-web-browser]: https://github.com/ronin-rb/ronin-web-browser#readme
[ronin-web-server]: https://github.com/ronin-rb/ronin-web-server#readme
[ronin-web-spider]: https://github.com/ronin-rb/ronin-web-spider#readme
[ronin-web-user_agents]: https://github.com/ronin-rb/ronin-web-user_agents#readme
[ronin-code-asm]: https://github.com/ronin-rb/ronin-code-asm#readme
[ronin-code-sql]: https://github.com/ronin-rb/ronin-code-sql#readme
[ronin-vulns]: https://github.com/ronin-rb/ronin-vulns#readme
[ronin-vulns-synopsis]: https://github.com/ronin-rb/ronin-vulns#synopsis
[ronin-post_ex]: https://github.com/ronin-rb/ronin-post_ex#readme
[ronin-payloads]: https://github.com/ronin-rb/ronin-payloads#readme
[ronin-exploits]: https://github.com/ronin-rb/ronin-exploits#readme
[ronin-exploits-synopsis]: https://github.com/ronin-rb/ronin-exploits#synopsis
[ronin-exploits-examples]: https://github.com/ronin-rb/ronin-exploits#examples
[ronin-wordlists]: https://github.com/ronin-rb/ronin-wordlists#readme
[ronin-wordlists-synopsis]: https://github.com/ronin-rb/ronin-wordlists#synopsis
[ronin-wordlists-examples]: https://github.com/ronin-rb/ronin-wordlists#examples
[ronin-brute]: https://github.com/ronin-rb/ronin-brute#readme
[ronin-brute-synopsis]: https://github.com/ronin-rb/ronin-brute#synopsis
[ronin-brute-examples]: https://github.com/ronin-rb/ronin-brute#examples
[ronin-nmap]: https://github.com/ronin-rb/ronin-nmap#readme
[ronin-nmap-synopsis]: https://github.com/ronin-rb/ronin-nmap-synopsis#readme
[ronin-nmap-examples]: https://github.com/ronin-rb/ronin-nmap-examples#readme
[ronin-masscan]: https://github.com/ronin-rb/ronin-masscan#readme
[ronin-masscan-synopsis]: https://github.com/ronin-rb/ronin-masscan-synopsis#readme
[ronin-masscan-examples]: https://github.com/ronin-rb/ronin-masscan-examples#readme
[ronin-recon]: https://github.com/ronin-rb/ronin-recon#readme
[ronin-recon-synopsis]: https://github.com/ronin-rb/ronin-recon#synopsis
[ronin-recon-examples]: https://github.com/ronin-rb/ronin-recon#examples
[docker]: https://github.com/ronin-rb/docker#readme
[scripts]: https://github.com/ronin-rb/scripts#readme
[ronin-rb.github.io]: https://github.com/ronin-rb/ronin-rb.github.io
