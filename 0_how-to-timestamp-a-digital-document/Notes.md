# Notes on [How to Time-Stamp a Digital Document](https://link.springer.com/article/10.1007/BF00196791) by Stuart Haber & W. Scott Stornetta

This is the legendary paper on the blockchain data structure. It introduces Blockchain data structure as a solution to the following problem: _How to certifying when a document is created or modified?_

## Problem

Essentially, the problem is of timestamping documents in a manner which is beyond any doubt. In other words, **the goal is to propose a Time-Stamping Service (TSS) which makes it infeasible for users to back-date or forward-date their documents even with the collusion of TSS.** Such a TSS would be of great value. For instance, in intellectual property disputes.

## Solutions for Non-Digital Documents

1. Diary Entries
   - Procedure
     - Make daily notes, in a lab notebook.
       - In a sequential order
       - Put date on each note.
       - Leave no pages blank.
     - At regular intervals, get the notebook
       - Stamped by a public notary
       - Or reviewed & signed by a company manager.
   - In case of a dispute, the following can substantiate inventor's claims
     - Physical Evidence
       - Sequentially numbered, sewn-in pages makes it difficult to tamper certain things.
         - Such as adding or removing pages.
         - Though notes on a page maybe modified to an extent.
     - Established Procedure
       - Periodic Stamping increases confidence that other parties can vouch for inventor's claims.
2. Self-Mail
   - Procedure
     - Mail the document as a letter to oneself.
     - On receipt, leave it unopened.
   - In case of a dispute,
     - Time postmarked on the envelope serves as evidence to inventor's claims

### Assumptions

There maybe more elaborate procedures than above. But, they rely on making sure that multiple people handle the records so that any tampering maybe detected by another person.

All such procedures rely on two assumptions:

1. Records can be examined for telltale signs of tampering.
2. There is another perfect entity that views the document and whose integrity & impartiality are beyond doubt.

Such assumptions are even weaker in case of _digital_ documents. This is so for it's extraordinarily easy to tamper with a digital document without any telltale signs.
