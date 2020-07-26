---
layout: page
title: Bio
permalink: /bio/
acajobs:

    - title:    "Research Project Manager"
      org:      "University College London Centre for Blockchain Technologies"
      orgurl:   "http://blockchain.cs.ucl.ac.uk/"
      country:  "UK"
      start:    "04/2019"
      end:      "present"
    
    - title:    "Teaching and Research Affiliate"
      org:      "École polytechnique fédérale de Lausanne"
      orgurl:   "https://www.epfl.ch/"
      country:  "Switzerland"
      start:    "03/2019"
      end:      "present"
    
    - title:    "Lead Data Analyst"
      org:      "Development International e.V."
      orgurl:   "https://www.developmentinternational.org/"
      country:  "Germany"
      start:    "03/2015"
      end:      "present"

    - title:    "Research Associate"
      org:      "Harvard Business School"
      orgurl:   "https://www.hbs.edu/"
      country:  "USA"
      start:    "01/2019"
      end:      "06/2019"

    - title:    "Project Manager and Research Associate"
      org:      "Institute of Insurance Economics, University of St.Gallen"
      orgurl:   "https://www.ivw.unisg.ch/"
      country:  "Switzerland"
      start:    "08/2016"
      end:      "02/2019"
indjobs:

    - title:    "Intern in Financial Services"
      org:      "University College London Centre for Blockchain Technologies"
      orgurl:   "https://home.kpmg/de/en/home.html"
      country:  "Germany"
      start:    "05/2016"
      end:      "07/2016"
    
    - title:    "Intern in Controlling"
      org:      "Siemens Healthcare GmbH"
      orgurl:   "https://www.siemens-healthineers.com/"
      country:  "Germany"
      start:    "04/2014"
      end:      "04/2016"
    
    - title:    "Intern in Supply Chain Management"
      org:      "Continental Automotive Holding (Shanghai) Co., Ltd."
      orgurl:   "https://www.continental.com/"
      country:  "China"
      start:    "10/2013"
      end:      "03/2014"
---

## Research and Academic Positions

<!-- {% assign thumbnail="left" %} -->

{% for item in page.acajobs %}
*{{item.start}} --- {{item.end}}*
<br />
**{{item.title}}**
<br />
[{{item.org}}]({{item.orgurl}}), {{item.country}}
{% endfor %}

## Industry Experience

<!-- {% assign thumbnail="left" %} -->

{% for item in page.indjobs %}
*{{item.start}} --- {{item.end}}*
<br />
**{{item.title}}**
<br />
[{{item.org}}]({{item.orgurl}}), {{item.country}}
{% endfor %}


<!-- Download [PDF version](http://nitens.org/img/cvtex/cv_template_xetex_caslon.pdf). The PDF should be embedded underneath -- uses Google Docs for embedding and works if the PDF is on dropbox. Works sporadically if PDF is elsewhere too.

{% include embedpdf.html source="http://nitens.org/img/cvtex/cv_template_xetex_caslon.pdf" width=100 height=800 %} -->
