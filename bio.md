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

education:
    
    - title:    "Postdoctoral Fellow in Finance"
      org:      "College of Management of Technology, École polytechnique fédérale de Lausanne"
      orgurl:   "https://www.epfl.ch/schools/cdm/"
      country:  "Switzerland"
      advisor:  "Prof. Dr. Semyon Malamud"
      advurl:   "https://www.epfl.ch/labs/sfi-sm/"
      start:    "03/2019"
      end:      "02/2020"    
    - title:    "Visiting Fellow in Business Economics"
      org:      "Graduate School of Arts and Sciences, Harvard University"
      orgurl:   "https://gsas.harvard.edu/"
      country:  "USA"
      advisor:  "Prof. Dr. Lauren H. Cohen"
      advurl:   "http://laurenhcohen.com/"
      start:    "08/2017"
      end:      "06/2019"    
    - title:    "Ph.D. in Management"
      org:      "School of Management, University of St. Gallen"
      orgurl:   "https://www.unisg.ch/en/universitaet/schools/management"
      country:  "Switzerland"
      advisor:  "Prof. Dr. Alexander Braun"
      advurl:   "https://www.alexandria.unisg.ch/persons/2621"
      start:    "08/2016"
      end:      "02/2019"    
    - title:    "Visiting Fellow in Blockchain Economics"
      org:      "Department of Computing, Imperial College London"
      orgurl:   "https://www.imperial.ac.uk/computing"
      country:  "UK"
      advisor:  "Prof. Dr. Benjamin Livshits"
      advurl:   "https://www.doc.ic.ac.uk/~livshits/"
      start:    "10/2018"
      end:      "01/2019"    
    - title:    "M.Sc. in Management"
      org:      "Area Banking, Finance & Insurance, Business School, University of Mannheim"
      orgurl:   "https://www.bwl.uni-mannheim.de/finance/"
      country:  "Germany"
      advisor:  "Prof. Dr. Peter Albrecht"
      advurl:   "https://www.bwl.uni-mannheim.de/albrecht/"
      start:    "08/2014"
      end:      "07/2016"
    - title:    "Erasmus Program"
      org:      "Vienna University of Economics and Business"
      orgurl:   "https://www.wu.ac.at/"
      country:  "Austria"
      start:    "01/2016"
      end:      "07/2016"
    - title:    "Bachelor in Management"
      org:      "Department of Accounting, School of Management, Fudan University"
      orgurl:   "https://www.fdsm.fudan.edu.cn/En/Accounting.aspx"
      country:  "China"
      advisor:  "Prof. Dr. Haina Shi"
      advurl:   "https://www.fdsm.fudan.edu.cn/en/teacher/preview.aspx?UID=111838"
      start:    "08/2010"
      end:      "07/2014"
    - title:    "Exchange Program"
      org:      "Desautels Faculty of Management, McGill University"
      orgurl:   "https://www.mcgill.ca/desautels/"
      country:  "Canada"
      start:    "08/2012"
      end:      "01/2013"
    - title:    "Global BBA Program"
      org:      "McCombs School of Business, University of Texas at Austin"
      orgurl:   "https://www.mccombs.utexas.edu/"
      country:  "Austria"
      start:    "07/2012"
      end:      "08/2012"
---

## Research and Academic Positions

<!-- {% assign thumbnail="left" %} -->

{% for item in page.acajobs %}
*{{item.start}} --- {{item.end}}*
<br />
**{{item.title}}**
<br />
[{{item.org}}]({{item.orgurl}}){:target="_blank"}, {{item.country}}
{% endfor %}

## Educational Experience

{% for item in page.education %}
*{{item.start}} --- {{item.end}}*
<br />
**{{item.title}}**
<br />
[{{item.org}}]({{item.orgurl}}){:target="_blank"}, {{item.country}}{% if item.advisor %}
<br />
Advisor: [{{item.advisor}}]({{item.advurl}}){:target="_blank"}
{% endif %}
{% endfor %}

## Industry Experience

<!-- {% assign thumbnail="left" %} -->

{% for item in page.indjobs %}
*{{item.start}} --- {{item.end}}*
<br />
**{{item.title}}**
<br />
[{{item.org}}]({{item.orgurl}}){:target="_blank"}, {{item.country}}
{% endfor %}


<!-- Download [PDF version](http://nitens.org/img/cvtex/cv_template_xetex_caslon.pdf). The PDF should be embedded underneath -- uses Google Docs for embedding and works if the PDF is on dropbox. Works sporadically if PDF is elsewhere too.

{% include embedpdf.html source="http://nitens.org/img/cvtex/cv_template_xetex_caslon.pdf" width=100 height=800 %} -->
