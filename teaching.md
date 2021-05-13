---
layout: page
title: Teaching
permalink: /teaching/
courses:
    - code:     "COMP0076" 
      title:    "MSc Financial Risk Management Project"
      url:      "https://www.ucl.ac.uk/module-catalogue/modules/COMP0076"
      where:    "UCL"
    - code:     "COMP0077" 
      title:    "MSc Computational Finance Project"
      url:      "https://www.ucl.ac.uk/module-catalogue/modules/COMP0077"
      where:    "UCL" 
    - code:     "COMP0163" 
      title:    "Blockchain Technologies"
      url:      "https://www.ucl.ac.uk/module-catalogue/modules/COMP0163"
      where:    "UCL" 
    - code:     "COMP0164" 
      title:    "Digital Finance"
      url:      "https://www.ucl.ac.uk/module-catalogue/modules/COMP0164"
      where:    "UCL" 
    - code:     "FIN-413" 
      title:    "Financial Applications of Blockchains and Distributed Ledgers"
      url:      "https://edu.epfl.ch/coursebook/en/financial-applications-of-blockchains-and-distributed-ledgers-FIN-413"
      where:    "EPFL" 
---

{% for item in page.courses %}
`{{item.code}}`
<br />
[**{{item.title}}**]({{item.url}})
<br />
@ {{item.where}}
{% endfor %}