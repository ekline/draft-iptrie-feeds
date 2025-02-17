---
###
# Internet-Draft Markdown Template
#
# Rename this file from draft-todo-yourname-protocol.md to get started.
# Draft name format is "draft-<yourname>-<workgroup>-<name>.md".
#
# For initial setup, you only need to edit the first block of fields.
# Only "title" needs to be changed; delete "abbrev" if your title is short.
# Any other content can be edited, but be careful not to introduce errors.
# Some fields will be set automatically during setup if they are unchanged.
#
# Don't include "-00" or "-latest" in the filename.
# Labels in the form draft-<yourname>-<workgroup>-<name>-latest are used by
# the tools to refer to the current version; see "docname" for example.
#
# This template uses kramdown-rfc: https://github.com/cabo/kramdown-rfc
# You can replace the entire file if you prefer a different format.
# Change the file extension to match the format (.xml for XML, etc...)
#
###
title: "IP Trie Feeds"
abbrev: "IP Trie Feeds"
category: info

docname: draft-todo-yourname-protocol-latest
submissiontype: independent  # also: "independent", "editorial", "IAB", or "IRTF"
number:
date:
consensus: true
v: 3
area: AREA
workgroup: WG Working Group
keyword:
 - next generation
 - unicorn
 - sparkling distributed ledger
venue:
  group: WG
  type: Working Group
  mail: WG@example.com
  arch: https://example.com/WG
  github: USER/REPO
  latest: https://example.com/LATEST

author:
 -
    fullname: Erik Kline
    organization: Aalyria Technologies, Inc.
    email: ek.ietf@gmail.com

normative:

informative:


--- abstract

TODO Abstract


--- middle

# Introduction

TODO Introduction

<!--

* mention:
  * geofeed finder
  * geofeeds study
* Since 8805 several requests have been received over the years:
  * more extensible format than CSV [cite RFC]
  * richer expression of geographic regions
  * more canonical sources of geograhic names (geonames.org?)
  * some kinds of guarantees for anonymity
  * locations not on Earth
  * support for anycast
  * additional attributes like "end site prefixes"
  * remove all mention of ill-fated, ill-conceived Postal Code
* restress "best effort"
* inline attestations?
* primary attribute in the IP Trie is "geo"
* multiple feeds representing different views of the same data
  * feed for public consumption might be very different from a feed served to Emergency Services consumers (or org-internal consumers)

-->

# Conventions and Definitions

{::boilerplate bcp14-tagged}


# Security Considerations

TODO Security


# IANA Considerations

This document has no IANA actions.


--- back

# Acknowledgments
{:numbered="false"}

TODO acknowledge.
