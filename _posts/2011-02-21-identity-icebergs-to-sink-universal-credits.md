---
title: "Identity Icebergs to sink Universal Credits"
date: 2011-02-21 09:31:01
categories: [Governance, Risk, Security, Strategy]
tags: [Cabinet Office, DfE, DWP, EAS, federation, GCloud, Id Management, SAML2, Shibboleth, TUO, Universal Credits]
layout: post
---

Does the Cabinet Office talk to the Cabinet Office - or any other Department for that matter?  Last week's <a href="http://bit.ly/ezInls" target="_blank">Local Government Delivery Council</a> also had two related presentations; "Identity Assurance for Public Services" by the Cabinet Office and  "Employee Authentication Services (EAS)" by DfE and DWP.

Put these into the context of "<a href="http://lenand.wordpress.com/wp-content/uploads/2011/02/ctocidm.pdf" target="_blank">HMG CTO Council - Government Employees Strategy for management of Identities - Version 1.1 - 1 February 2011. </a>" This noble document has some excellent content as far as it goes - but look at the juicy bits it deems out of scope.
<ul>
	<li><em>"Access control of data within a single system or organisation</em></li>
	<li><em>Entitlements of a validated identity within a single system</em></li>
	<li><strong><em>Authorisation services and other capabilities enabled by identity management </em></strong></li>
	<li><em>Citizen and Individual authentication even for access to government services or visitors to government sites</em></li>
	<li><em>Identity Management of systems, devices and other entities </em></li>
	<li><em>Audit and accounting requirements other than by reference to their need." </em></li>
</ul>
Most, if not all of these are required by real live systems, especially in Local Government.  They are probably the hard bit where most guidance is needed.  <a href="http://bit.ly/eEqzB5" target="_blank">Federated identity management protocol</a>s do understand how to include these options.  For example the use of Shibboleth 2 in the education sector can easily differentiate between children and teachers in Web based application systems.

EAS has been around for years in DWP.  It has been recently used for the "Tell Us Once" (TUO) project, authenticating for multiple agencies handling common citizen data.  They have discovered the need for, and have implemented, some employee attributes that allow differential access to application systems. This is out of the scope of the strategy above, but they found they had to do it.  Every Local Authority (LA), and there are hundreds of them, needs guidance on this because most do not have the internal skills and knowledge to interoperate with external identity providers (like EAS, but there are lots more). A common standard for federating identity, supported with standard software, is the only sensible way to proceed.

Finally, there was a bomb shell from the Cabinet Office.  As part of the stakeholder engagement process, they presented  "<em>a federated approach through which a person is able to assert a trustworthy identity</em>".  Here are some of the enlightening aspects of a working federated system:
<ul>
	<li>delivered for DWP <a href="http://lenand.wordpress.com/wp-content/uploads/2011/03/universalcredit.pdf" target="_blank">Universal Credits</a> in <em><strong>April 2012</strong></em></li>
	<li>provided 'by the market', presumably meaning non-funded</li>
	<li>dependent on external verification of identity by third parties (such as banks) selected by the citizen</li>
	<li>LAs will provide an Identity Hub which collects personal data and matches with the external credentials (this is a minefield, not just icebergs)</li>
	<li>links with biographic, health, wealth and education data by attributes</li>
	<li>links with DVLA</li>
	<li>links with an 'official' address file</li>
	<li>not dependent on a centralised identity register</li>
	<li>Oh, and by the way, it will run on the GCloud. Trebles all round.</li>
</ul>
The aspirations are wonderful, straight out of the junior management consultant's handbook, but three simple questions illustrate the risks involved:
<ol>
	<li>Does the Identity Management industry, working with hundreds of LAs, have the capacity to deliver in such a time scale?</li>
	<li>Does the Cabinet Office (or anybody else?) have a Technical Architecture that is fit for purpose and compliant with the <a href="http://bit.ly/hTH8KH" target="_blank">CTO Council </a>strategy?</li>
	<li>Identity management ignorance crippled the development of <a href="http://bit.ly/hy7d7f" target="_blank">ContactPoint</a> - why is it so much easier and simpler for Universal Credits?</li>
</ol>
