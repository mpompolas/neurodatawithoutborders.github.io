---
title: "NeurodataWithoutBorders: Neurophysiology FAQ"
layout: default
excerpt: "NWB:N FAQ"
sitemap: false
permalink: /faq
---


# Frequently Asked Questions

## Does it make sense to start using NWB:N 2.0 now, or is it more sensible to wait?

Yes. A first public beta release of PyNWB (for Python 2.7.x and >3.5) and NWB 2.0 has been released in
November 2017 in conjunction with the Annual Society for Neuroscience Meeting (SfN). The intent of this beta
release was to enable early adopters to start exploring the new format and software. While development on NWB 2.0 has
been progressing rapidly, further changes to the APIs as well as the format are still planed between this beta
and the first full release of NWB 2.0. However, overall we expect that most of these changes will be small so that
the current API and format provide a good starting point for exploring and beginning adoption of the format.
The current development plan is available here: http://nwb-overview.readthedocs.io/en/latest/development_plan.html

## Is NWB:N 2 stable?

NWB:N 2 is currently under **active development**. The APIs and schema may change at any time. While many parts of the
format and APIs have stabilized, the goal of the beta development phase is to enable users to begin adoption of
NWB:N 2, develop the codes needed to convert data to NWB:N 2 and to test the schema and APIs. The goal of the beta phase is also
to finalize changes to the schema and API features to allow us to ensure stability once the full release occurs
as well as to improve testing and documentation.

## I would like to use NWB:N. How do I get started?

See the <a href="{{ site.url }}{{ site.baseurl }}/gettingstarted">Getting Started</a> page for more information.

## What is the difference between pynwb, nwb-schema and api-python?

**PyNWB** is the current Python reference read/write API for the NWB:N 2.x format.
The **nwb-schema** repo is used to manage development on the data standard schema. End-users
who want to use NWB:N typically do not need to worry about the **nwb-schema** repo
as the current schema is always installed with the corresponding API (whether it
is PyNWB for Python or MatNWB for Matlab). **api-python** is a deprecated write-only
API designed for NWB:N 1.0.x files. **PyNWB** also provides support for reading some
NWB:N 1.0.x files from popular data repositories, such as the
[Allen Cell Types Atlas](http://celltypes.brain-map.org/) via the
pynwb/legacy module.

## Does PyNWB support NWB:N 1.0.x files?

PyNWB includes the pynwb/legacy module
which supporta reading of NWB:N 1.0.x files from popular data repositories, such as the
[Allen Cell Types Atlas](http://celltypes.brain-map.org/) . For NWB:N 1.0.x files from other sources
the millage may vary in particular when files are not fully format compliant, e.g., include
arbitrary custom data or are missing required data fields.

## What has changed between NWB:N 1.0x and 2.0?

See the <a href="http://nwb-schema.readthedocs.io/en/latest/format_release_notes.html" target="_blank">release notes of the NWB:N format schema</a> for details about changes to the format schema. For details about changes to the specification language see the <a href="http://schema-language.readthedocs.io/en/latest/specification_language_release_notes.html" targe="_blank">specification language release notes</a>. With reagrd to software, NWB:N 2 marks a full reboot and introduced with PyNWB, MatNWB, nwb-docutils, nwb-schema etc. several new packages and repositories while tools, e.g., api-python that were created for NWB:N 1.x have been deprectated. 

## How do I install PyNWB?

See the PyNWB documentation for details
<a href="http://pynwb.readthedocs.io/en/latest/getting_started.html#installation" target="_blank">here</a>

## Who can I contact for questions?

For details please review our  <a href="{{ site.url }}{{ site.baseurl }}/contributing">Contributing Guidelines</a>

* For technical contributions (specifically, if you have found a bug or want to request a new feature) you can create an issue on the approbriate GitHub repository.
* For questions, e.g., about how to use NWB:N, you can use the [google group](https://groups.google.com/forum/#!forum/neurodatawithoutborders) .
* To receive updates about NWB at large you can sign up for the [mailing list](http://visitor.r20.constantcontact.com/manage/optin?v=001nQUq2GTjwCjZxK_V2-6RLElLJO1HMVtoNLJ-wGyDCukZQZxu2AFJmNh6NS0_lGMsWc2w9hZpeNn74HuWdv5RtLX9qX0o0Hy1P0hOgMrkm2NoGAX3VoY25wx8HAtIZwredcCuM0nCUGodpvoaue3SzQ%3D%3D) .
* For informal discussions between developers, users, and teams you can also join [https://nwb-users.slack.com](https://nwb-users.slack.com) .

## How do I contribute to PyNWB?

For details on how to contribute to PyNWB see our
<a href="{{ site.url }}{{ site.baseurl }}/contributing">Contributing Guidelines</a>

## Does pynwb support both python 2.7 and python >3.5?

Yes



