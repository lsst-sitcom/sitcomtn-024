..
  Technote content.

  See https://developer.lsst.io/restructuredtext/style.html
  for a guide to reStructuredText writing.

  Do not put the title, authors or other metadata in this document;
  those are automatically added.

  Use the following syntax for sections:

  Sections
  ========

  and

  Subsections
  -----------

  and

  Subsubsections
  ^^^^^^^^^^^^^^

  To add images, add the image file (png, svg or jpeg preferred) to the
  _static/ directory. The reST syntax for adding the image is

  .. figure:: /_static/filename.ext
     :name: fig-label

     Caption text.

   Run: ``make html`` and ``open _build/html/index.html`` to preview your work.
   See the README at https://github.com/lsst-sqre/lsst-technote-bootstrap or
   this repo's README for more info.

   Feel free to delete this instructional comment.

:tocdepth: 1

.. Please do not modify tocdepth; will be fixed when a new Sphinx theme is shipped.

.. sectnum::

.. TODO: Delete the note below before merging new content to the main branch.

.. note::

   This technote details the charge to the Summit Power Reliability and Risk Evaluation Task who will perform an analysis of the current and anticipated state of the summit electrical system including possible failure scenarios. It will also analyze how information gets communicated to stakeholders and which procedures need to be in place to ensure an appropriate level of risk during summit-based commissioning and operational activities.

   This document is to be considered as an initial draft.

.. Add content here.
.. Do not include the document title (it's automatically added from metadata.yaml).

Context
=======

The summit system has experienced three electrical events within a 10-day period (Nov 24 through December 4th, 2021) that compromised systems on the summit. 
During these events, the systems in place to protect the hardware experienced did not meet the intended design and failures occurred. 
Furthermore, the notification of the failures did not reach the stakeholders within an amount of time where their reaction may have helped mitigate the on-going problems. 
Lastly, an analysis is required to determine if the information available on-site is sufficient to perform mitigation activities in the event of a power and/or network failure. 
This includes sufficient materials delivered by personnel responsible for hardware/instruments on the summit. 

Motivation
==========

As the Rubin project transfers from construction into commissioning, the amount of sensitive hardware and the number critical procedures (e.g. lifts) will be performed. 
The critical utilities must be in place and meet their reliability specifications to achieve the acceptable level of risk required to stay within the Rubin project cost and schedule constraints.
As a result of the recent shortcomings at multiple levels, this charge facilitates a review of the system as implemented and planned to both minimize the occurrence of such events and maximize the effectiveness of the response team in an event of a failure.

Scope and Deliverables
======================

This group is being assembled to review the current events and current system shortcomings.  
The group is to report their findings and make a series of recommendations to potentially augment and/or clarify the current requirements, processes, procedures, and communication mechanisms to stakeholders in the event of a power loss or transient.

The following items shall be addressed by the group:

#. Document the recent causes for recent power and/or system failures. An analysis of previous events should be performed when relevant.

#. Document the series of events after the issues arose and impacts. 
   Identify areas of concern where on-site/off-site coordination, team communication breakdowns and/or a lack of documented procedures hindered progress.
   
   - This includes alert systems and/or communication channels to the appropriate stakeholders that may or may not have been in place
  
#. What system components are specifically identified as critical (from either a downtime or equipment safety standpoint) and require additional redundancy to remain operational and/or be powered down gracefully during electrical transients or outages? 
   These are items that impact operations beyond the window of the power outage and not simply items that are to be on the building UPS power.
   
   - Are the identified systems specified, installed, functional, and verified against their requirements? Are the requirements sufficient? 
   - Are there additional items to be identified as critical?

#. What corrective actions must be accomplished immediately to ensure safety to equipment currently on the summit in the event of an electrical transient or power loss?
   Note that making the system safe does not necessitate that it be functional.

#. Identify the summit equipment that is susceptible to damage and/or failure if electrical transients occur:
   
   - What are the current system requirements (in LSE-30 and below) that aim to protect these systems?
   - What is the level of acceptable risk to these systems and how is it defined?
   - Are the requirements sufficient to obtain the level of acceptable risk?
   - Have the requirements been covered and verified such that the current hardware systems do not surpass the level of acceptable risk?

#. What corrective actions must be put in place prior to resuming activities that were halted and/or reduced as per the recommendations in question 4?

#. What further systems and/or procedures should be put in place to reduce risk in the future? 
   Identify deadlines where appropriate.

#. What mechanisms need to be in place for on-the-ground personnel to get the required information they need to address issues encountered during power and/or network failures? 
   What training is required for on-site personnel such that they can access required materials during outages?

#. What activities are planned to ensure the required power and networking systems are properly specified and verified prior to the LSST-Cam pre-ship review? 
   Are there additional requirements and/or verification activities necessary to ensure safe operation upon delivery? 
   Are failure scenarios addressed as part of the pre-ship review criteria?


Timeline
========

This group is to complete items 1-4 of this charge by December 20th, with items 5 and 6 to be completed by January 10th (TBR), and items 7-10 delivered Feb 10th (TBR).


Aspects Considered Out-Of-Scope
===============================

#. Creation of the LCR to support any suggested changes
#. Design of the components and/or systems to incorporate any new functionality


Task Force Members (TBR)
========================

The number of members is intentionally small to facilitate a rapid turn-around of the deliverables. 
When required, team members are expected to summon additional personnel, specifically those responsible for systems on the summit, for individual meetings to capture additional information. 
It is recommended that the team meet multiple times per week but for shorter intervals to facilitate a tighter and focused response loop.

- Camera Team Representative (Chair)  - Travis Lange (Diane as a backup?)
- Summit Electrical Engineer - Luis Vergara (Juan Fabrega another option but may be too busy)
- Summit Facilities Representative - Oscar Nunez
- SIT-Com representative with operations experience - Erik Dennihy or Bruno Quint
- IT Representative - Cristian Silva (delegate to  Heinrich or Julio?) 


.. .. rubric:: References

.. Make in-text citations with: :cite:`bibkey`.

.. .. bibliography:: local.bib lsstbib/books.bib lsstbib/lsst.bib lsstbib/lsst-dm.bib lsstbib/refs.bib lsstbib/refs_ads.bib
..    :style: lsst_aa

