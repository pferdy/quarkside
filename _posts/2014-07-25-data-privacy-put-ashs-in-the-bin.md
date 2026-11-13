---
title: "Data Privacy: Put ASHs in the bin"
date: 2014-07-25 22:25:53
categories: [Governance, Privacy, Technology]
tags: [FAME, HSCIC, Mydex, PDS, Shadbolt]
layout: post
---

There’s a <a href="https://www.gov.uk/government/consultations/protecting-personal-health-and-care-data" target="_blank">consultation</a> about the regulations for protecting personally identifiable data. The government proposes allowing a number of local organisations to create secure Accredited Safe Havens (ASHs). They will have access to information from peoples’ personal care records, which could be used to identify an individual.

The consultation assumes a solution that there is a need to transfer such data into an ASH.  Quarkside suggest that an alternative is inherently safer. Instead of moving data to an ASH, it stays put in a Personal Data Store (PDS). A PDS resolves the problems of consent by only releasing data for analysis without personally identifiable data.  This could be controlled by Mydex.

The back of a beer mat design goes something like this:
<ul>
	<li>People control their own health and care records in a suitably encrypted data store.</li>
	<li>Data is held in 5* format in triple stores and using URIs appropriately (ask Sir Nigel Shadbolt how to do it).</li>
	<li>Explicit consent has to be given for the extraction (or viewing) of any attribute. This avoids any data which could lead to identification being stopped at source. The consent could also be given by an Accredited Data Attorney (ADA). An ADA could be the person or any single person who has been trusted to give consent to release data for sharing purposes.</li>
	<li>If an Accredited Data Processor (ADP) wishes to use anonymised data then temporary rights are given by the ADA. Data may be given an expiry period after which any copies of the source data are destroyed. The ADP would be allowed to stored summarised data for analytical purposes.</li>
	<li>Any joins of personal data are done within the domain of the PDS and the method of performing those joins and hidden from the ADP. The risks are reduced for loss of privacy. If you go back to the principles of <a href="http://www.fame-uk.org/" target="_blank">FAME</a> you will see the nine principles that can make this work. The Identity Management problem is solved at source. Sharing data from multiple agencies is logically performed in an infrastructure that is like a walled garden.</li>
	<li>Each time data is released to an ADP, then the source identity would be irreversibly hashed by the ADA. The regulations would be so much simpler to implement.</li>
	<li>The ADA can release personally identifiable data to multiple agencies, such as health and social care. Again this must be time limited and the agencies would be obliged to destroy data, without any rights to store archives that contain personally identifiable data. A PDS is the repository for health and social care records.</li>
</ul>
Big data technology has advanced to the stage where this has become possible. Give control of sharing to the citizen. Acknowledge that people have ownership rights to their data, even if it is collected and stored by the NHS (or any other ADP). If you don’t create ASHs, you don’t need to regulate them
