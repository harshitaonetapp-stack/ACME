---
source_item_id: 64
message_id: "doc:ACME:01-source/documents/BRD-TESTTWO-v3.0.docx"
thread_key: "doc:ACME:01-source/documents/BRD-TESTTWO-v3.0.docx"
project: "ACME"
source_type: "brd"
doc_version: "v3.0"
from: ""
date: "2026-10-28T10:13:13.933818+00:00"
subject: "BRD-TESTTWO-v3.0.docx"
---

Business Requirements Document
Courier Partner Portal - Release 2
Version 2.0  |  Prepared for TESTTWO  |  27 October 2026
1. Background
The portal went live in August. Operations staff have been using it daily for scheduling pickups. This document covers the second release. Background material on the original rollout is held in the Release 1 pack and is not repeated here.
2. Scope
In scope: pickup scheduling, driver assignment, and the daily operations report. Out of scope: billing, which remains on the legacy system until Q2.
3. Requirements
Ref | Requirement | Notes
R-01 | Operations staff must be able to reschedule a pickup to a different date without cancelling and re-creating it. The driver assigned to the original slot should be released automatically. | Raised by the Mumbai hub team.
R-02 | The daily operations report currently shows pickup counts for the wrong timezone. Pickups booked after 6:30 PM IST are counted against the following day. This must be corrected so the report matches what staff see on screen. | Reported 14 October. Affects reconciliation.
R-03 | When a driver is assigned to a pickup, send them an SMS with the address, the contact name and the scheduled window. The message must go out within two minutes of assignment. | SMS gateway already licensed.
R-04 | The client has asked whether pickup slots should be restricted to the hub's operating hours, or whether staff should be allowed to book outside them with a warning. A decision is needed before R-01 can be built. | Open question - needs confirmation from the client.
4. Appendix
Glossary, the Release 1 change log and the original hub survey are attached separately and form no part of the requirements above.
