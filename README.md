# CTA WAVE Extended Resources

## Introduction
This page collects the extended CTA WAVE extended resources. Some of the documents are public, others are only accessible for CTA WAVE members. The page is separated into different task force and activities:

* [Content Specification Task Force](./#content-specification-task-force)
* Device Playback Task Force
* HTML-5 API Task Force
* CMAF Byte Stream Format Activity
* HLS/DASH Interop TF
* Common Media Header Data

## Content Specification Task Force

### Published Specifications
* [WAVE Content Specification, 2018 Edition, April 2018](https://cdn.cta.tech/cta/media/media/resources/standards/pdfs/cta-5001-final_v2_pdf.pdf) 
* [WAVE Content Specification, 2018 Edition, Amendment 1, December 2018](https://cdn.cta.tech/cta/media/media/resources/standards/pdfs/cta-5001-a-final.pdf) 
* [WAVE Content Specification, 2019 Edition, December 2019](https://cdn.cta.tech/cta/media/media/resources/standards/cta-5001-b-final.pdf)

### Supporting Documents
* [Content Specification Task Force Media Profile Wiki](https://github.com/cta-wave/content-specification-task-force/wiki) 
* [Content Specification Task Force Issues](https://github.com/cta-wave/content-specification-task-force/issues) 
* [DASH-IF Conformance Software Issues](https://github.com/Dash-Industry-Forum/DASH-IF-Conformance/issues)
* [Media Profile Approval Process](https://standards.cta.tech/apps/org/workgroup/cstf/download.php/22529/cstf-00035-v000-WAVE%20Media%20Profile%20Approval%20Process.docx) 
* [CMAF Testable Assertions, Nomor annotated CMAF FDIS](https://standards.cta.tech/apps/org/workgroup/cstf/download.php/26818/latest) 
* [CMAF Technologies under Consideration (TuC)](https://standards.cta.tech/apps/org/workgroup/cstf/download.php/27416/w18591%20Technologies_Under_Consideration_CMAF.doc) 
* [CMAF 2nd Edition FDIS (w18636)](https://standards.cta.tech/apps/org/workgroup/wtwg/download.php/27773/w18636-v4-w18636.zip)
* [DASH Profile for CMAF, ISO/IEC 23009-1:2020/Draft DAM1](https://standards.cta.tech/apps/org/workgroup/wtwg/download.php/29429/29n18626_CTA_WAVE.zip) 
* [DASH-IF “Advanced Ad Insertion in DASH”](https://dashif.org/docs/CR-Ad-Insertion-r5.pdf)

### Internal Drafts
* [WAVE Content Specification, 2018 Edition, Amendment 1, final Word version](https://standards.cta.tech/apps/org/workgroup/cstf/document.php?document_id=25036)
* [WAVE Content Specification, 2019 Edition, 11-07-2019 - TWG Review Draft, Correction](https://standards.cta.tech/apps/org/workgroup/wtwg/document.php?document_id=28517)
* [WAVE Content Specification, CTA-5001-B Content Specification (2019 Edition) – Final Word Version](https://standards.cta.tech/apps/org/workgroup/cstf/download.php/28780/CTA-5001-B%20TxtOnly.docx)
* [WAVE DASH-HLS Interop Specification – 2020 Edition, Skeleton Draft](https://standards.cta.tech/apps/org/workgroup/cstf/document.php?document_id=28924)

## Device Playback Task Force

### Published Specifications
* [Device Playback Capabilities Specification (CTA-5003), Published December 2018 (pdf, public)](https://cdn.cta.tech/cta/media/media/resources/standards/pdfs/cta-5003-final.pdf)
* [Device Playback Capabilities Specification (CTA-5003), Published December 2018 (Word, internal)](https://standards.cta.tech/apps/org/workgroup/dpctf/download.php/25037/CTA-5003.docx)

### Specification Development
* [Draft Specification version 2](https://1drv.ms/w/s!AiNJEPgowJnWgf1djEI_m3uly6_1qQ)
  * includes test content
* [Draft Update: Content Options and Playback for AVC/AAC](https://1drv.ms/w/s!AiNJEPgowJnWgbpZesbLvglzCXVlSg?e=Rh7bg7)
* [Draft Update: Media Capabilities](https://1drv.ms/w/s!AiNJEPgowJnWgpI6nhNJVLWvwn3BWA?e=swV7i9)
* [Github for comments against specification v2](https://github.com/cta-wave/device-playback-task-force)

### Test Resources
* [Repo for the DPCTF Test Runner](https://github.com/cta-wave/dpctf-test-runner)
* [Repo for DPCTF Tests. We prefer to keep the Tests separated from Test Runner](https://github.com/cta-wave/dpctf-tests)
* [Repo for Docker deployment](https://github.com/cta-wave/dpctf-deploy)
* [Test Content](http://dash.akamaized.net/WAVE/index.html)
* [Github for Test Content Issues](github https://github.com/cta-wave/Test-Content)
* Sample Test Content:
  * [Fragmented](http://dash.akamaized.net/WAVE/ContentModel/SinglePeriod/Fragmented)
     * Video:  
       * [Downloadable content](http://dash.akamaized.net/WAVE/ContentModel/SinglePeriod/Fragmented/video1.zip)
       * [Test vector in Test MPD](http://dash.akamaized.net/WAVE/ContentModel/SinglePeriod/Fragmented/ToS_MultiRate_fragmented.mpd)
     * Audio: 
       * [Downloadable content](http://dash.akamaized.net/WAVE/ContentModel/SinglePeriod/Fragmented/audio1.zip)
       * [Test vector in Test MPD](http://dash.akamaized.net/WAVE/ContentModel/SinglePeriod/Fragmented/ToS_HEAACv2_fragmented.mpd)    
  * [Chunked](http://dash.akamaized.net/WAVE/ContentModel/SinglePeriod/Chunked)
     * Video:  
       * [Downloadable content](http://dash.akamaized.net/WAVE/ContentModel/SinglePeriod/Chunked/video1.zip)
       * [Test vector in Test MPD](http://dash.akamaized.net/WAVE/ContentModel/SinglePeriod/Chunked/ToS_MultiRate_fragmented.mpd)
     * Audio: 
       * [Downloadable content](http://dash.akamaized.net/WAVE/ContentModel/SinglePeriod/Chunked/audio1.zip)
       * [Test vector in Test MPD](http://dash.akamaized.net/WAVE/ContentModel/SinglePeriod/Chunked/ToS_HEAACv2_fragmented.mpd)          
        
## HTML-5 API Task Force

### Published Specifications
* [Web Media API Snapshot 2019 (CTA-5000-B) December 2019 (pdf, public)](https://cdn.cta.tech/cta/media/media/resources/standards/pdfs/cta-5000-b-final_v2.pdf)
* [Web Media Application Developer Guidelines (CTA-5002) Published December 2018 (pdf, public)](https://cdn.cta.tech/cta/media/media/resources/standards/pdfs/cta-5002-final.pdf)

### Specification Development


### Test Resources
* Web Media API Snapshot 2018 Test Suite 
  * [Online Hosted Version - Free for Public Access (unblock port 8050)](https://webapitests2018.ctawave.org/)
  * [Open Source version (for porting to e.g., smart TVs)](https://github.com/cta-wave/WMAS)

## CMAF Byte Stream Format

### W3C Specifications
* [W3C Media Source Extensions](https://www.w3.org/TR/media-source/)
* [ISO-based Media File Format (ISOBMFF) Byte Stream Format](https://www.w3.org/TR/mse-byte-stream-format-isobmff/)

### Specification Development
* [Online Draft](https://docs.google.com/document/d/1WNK2JTY6wW1qGqi7pFpsJvF-rowj2ssmI_NxjNQrh7I/edit?usp=sharing)
* [Issues Tracker] (https://github.com/cta-wave/CMAF-Byte-Stream/issues)

