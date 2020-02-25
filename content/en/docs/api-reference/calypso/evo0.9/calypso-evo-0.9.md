---
title: "Keyple Calypso – Evolution 0.9"
linkTitle: "2. Keyple Calypso Evo 0.9"
date: 2020-02-24
weight: 2
description: >
  Revised Calypso API 0.9
---

The selection API
The role of this API is
to detect the presentation of a particular Calypso PO,
to select the target application (in the ISO7816-4 sense),
to execute additional commands (among a reduced set) following the selection.
The data produced by this mechanism is a CalypsoPo object (instance of the generic keyple-core object AbstractMatchingSe).
The CalypsoPo object contains the information derived from the FCI analysis received in response to the selection command as well as the data received in response to any additional commands that may have been executed.