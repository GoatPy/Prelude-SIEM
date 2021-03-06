# Prelude-SIEM

Prelude-SIEM is brought to you by CS (http://www.c-s.fr)
under GPLv2 license : https://www.prelude-siem.org

Copying and distribution of this library, with or without modification,
are permitted in any medium without royalty provided the copyright
notice and this notice are preserved. This file is offered as-is,
without warranty of any kind.

For commercial use, if you need another license than GPLv2, please
contact CS : contact.prelude@c-s.fr

# Prelude-SIEM Overview

Prelude is an agentless, universal, and hybrid security information and event management (SIEM) system. Prelude collects, normalizes, sorts, aggregates, correlates and reports all security-related events independently of the product brand or license. Security events are normalized to an IDMEF format, allowing native support with almost all security related event from an IT equipment.

While a malicious user (or software) may be able to evade the detection of a single IDS (NIDS, HIDS, etc.), it becomes exponentially more difficult to get around the defenses when there are multiple protection mechanisms. Prelude comes with a large set of sensors, each of them monitoring different kind of events. Prelude permits alert collection to WAN scale, whether its scope covers a city, a country, a continent or the world.

Prelude claims that it is a SIEM system capable of inter-operating with all the systems available on the market.[3] It is natively compatible with: AuditD, Nepenthes, NuFW, OSSEC, Pam, Samhain, Sancp, Snort, and Suricata but anyone can write its own sensors or utilize some of the 3rd party sensors that are available, given Prelude's opened APIs and librairies.

## Prewikka

Basic interface for displaying events

Project : https://github.com/Prelude-SIEM/prewikka

## Prelude-Correlator

Alert correlation module

Project : https://github.com/Prelude-SIEM/prelude-correlator

## Prelude-LML

Log file manager

Project : https://github.com/Prelude-SIEM/prelude-lml

## Prelude-LML-Rules

Rules for Prelude-LML

Project : https://github.com/Prelude-SIEM/prelude-lml-rules

## Prelude-Manager

Events reception and storage

Project : https://github.com/Prelude-SIEM/prelude-manager

## LibPrelude

Communication library between modules

Project : https://github.com/Prelude-SIEM/libprelude

## LibPreludeDB

Library to access the database

Project : https://github.com/Prelude-SIEM/libpreludedb

## LibIDMEF

Library to manipulate IDMEF objects

Project : https://github.com/Prelude-SIEM/libidmef

## LibIODEF

Library to manipulate IODEF objects

Project : https://github.com/Prelude-SIEM/libiodef
