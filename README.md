# Line up and take command

A tutorial about how to use various CLI tools to remove the tedium and toil from processing information.

Given at the [SouthWest Cyber Security Forum (SWCSF)](https://swcsf.org/) at 6:30pm on Monday, February 5, 2024.

Topics covered: ASN lookups, text search, manipulating both CSV and JSON data, downloading and manipulating HTML, and format conversion with the excellent pandoc.

## Autonomous System Numbers (ASNs)

- [asn](https://github.com/nitefood/asn): a neat little shell script to pull the following information about domains/ip addresses
  - ASN
  - RPKI validity
  - BGP stats
  - IPv4v6
  - Prefix
  - URL
  - ASPath
  - Organization
  - IP reputation
  - IP geolocation
  - IP fingerprinting
  - Network recon
  - lookup API server
  - Web traceroute server
- [GitHub Topic: asn-lookup](https://github.com/topics/asn-lookup)

## Open Data Sources

A few good places to grab open data sets:

- [City of Phoenix Open Data](https://www.phoenixopendata.com/)
- [U.S. National Park Service API](https://www.nps.gov/subjects/digital/nps-data-api.htm)
- [Free Worldwide Aviation Database](https://www.openaip.net/)
- [OpenFarm](https://openfarm.cc): a free and open database and web application for gardening knowledge
- [awesome-json-datasets](https://github.com/jdorfman/awesome-json-datasets): A curated list of awesome JSON datasets that don't require authentication.
- [awesome-transit](https://github.com/MobilityData/awesome-transit): Community list of transit APIs, apps, datasets, research, and software
- [awesome-twitter-data](https://github.com/shaypal5/awesome-twitter-data): A list of Twitter datasets and related resources.

### And some YouTube Channels for `yt-dlp` below

- [SWCSF](https://www.youtube.com/@SWCSF)
- [Netsec Explained](https://www.youtube.com/@NetsecExplained)

## Retrieving Data

- [xh](https://lib.rs/crates/xh): a Rust equivalent to [httpie](https://github.com/httpie/cli?tab=readme-ov-file#:rp:). There are also the venerable [curl and Wget](https://daniel.haxx.se/docs/curl-vs-wget.html).
- [yt-dlp](https://github.com/yt-dlp/yt-dlp): A youtube-dl fork with additional features and fixes
- [Yt-dlp Commands: The Complete Tutorial For Beginners (2024)](https://ostechnix.com/yt-dlp-tutorial/)

## Text Search

- [ripgrep](https://crates.io/crates/ripgrep): ripgrep is a line-oriented search tool that recursively searches the current directory for a regex pattern while respecting gitignore rules.
- [ripgrep listing on Lib.rs drama](https://gitlab.com/lib.rs/main/-/issues/121)
- [ripgrep_all (rga)](https://lib.rs/crates/ripgrep_all): ripgrep, but also search in PDFs, E-Books, Office documents, zip, tar.gz, etc

## CSV

- [csvlens](https://lib.rs/crates/csvlens): Command line csv viewer
- [xsv](https://lib.rs/crates/xsv): A high performance CSV command line toolkit.
- [qsv](https://lib.rs/crates/qsv): A high performance CSV data-wrangling toolkit.
- [hck](https://lib.rs/crates/hck): A sharp cut(1) clone.
- [choose](https://lib.rs/crates/choose): A human-friendly and fast alternative to cut and (sometimes) awk

## JSON

- [jless](https://lib.rs/crates/jless): A command-line JSON viewer
- [jaq](https://lib.rs/crates/jaq): Just another JSON query tool (a Rust alternative to [jq](https://github.com/jqlang/jq?tab=readme-ov-file#jq))
- [livejq](https://lib.rs/crates/livejq): An alternative jq implementation in rust for continuous parsing without crashing on invalid JSON
- [fltn](https://lib.rs/crates/fltn): Flattens a serialized data structure making it greppable (a Rust alternative to [gron](https://github.com/tomnomnom/gron?tab=readme-ov-file#gron))
- [jindex](https://lib.rs/crates/jindex): Enumerate the paths through a JSON document
- [dts](https://lib.rs/crates/dts): A tool to deserialize, transform and serialize data between different encodings

## HTML Processing

- [gimme](https://lib.rs/crates/gimme): Pull useful data out of your clipboard.
- [lychee](https://lib.rs/crates/lychee): A fast, async link checker
- [linkify](https://lib.rs/crates/linkify): Finds URLs and email addresses in plain text. Takes care to get the boundaries right with surrounding punctuation like parentheses.
- [htmlq](https://lib.rs/crates/htmlq): Like jq, but for HTML.
- [web-grep](https://lib.rs/crates/web-grep): A Grep Tool for HTML or XML

## General Format Conversion

- [Pandoc - index](https://pandoc.org/)
