---
layout: page
permalink: /research
title: Research
pubs:

    - title:   "Dating Death: An Empirical Comparison of Medical Underwriters in the U.S. Life Settlements Market"
      author:  "Jiahua Xu"
      journal: "North American Actuarial Journal"
      number:  "24(1):36-56"
      year:    "2020"
      url:     "https://doi.org/10.1080/10920277.2019.1585881"
    - title:   "Fair Value Measurement in the Life Settlement Market"
      author:  "Alexander Braun, Jiahua Xu"
      journal: "Journal of Fixed Income"
      number:  "29(4):100-123"
      year:    "2020"
      url:     "https://doi.org/10.3905/jfi.2020.1.084"
    - title:   "Carbon Trading with Blockchain"
      author:  "Andreas Richardson, Jiahua Xu"
      journal: "The 2nd International Conference on Mathematical Research for Blockchain Economy"
      number:  "Accepted"
      year:    "2020"
      url:     "https://www.marble-conference.org/marble2020-programme"
    - title:   "Segmentally Aware: Know When to Merge and When to Purge"
      author:  "Yao Ma, Jiahua Xu"
      journal: "Journal of Organizational Change Management"
      number:  "33(1):196-214"
      year:    "2019"
      url:     "https://doi.org/10.1108/JOCM-06-2019-0201"
    - title:   "The Anatomy of a Cryptocurrency Pump and Dump Scheme"
      author:  "Benjamin Livshits, Jiahua Xu"
      journal: "Proceedings of the 28th USENIX Security Symposium"
      number:  "1609-1625"
      year:    "2019"
      url:     "https://www.usenix.org/system/files/sec19-xu-jiahua_0.pdf"
    - title:   "Are Insurance Balance Sheets Carbon-Neutral? Harnessing Asset Pricing for Climate-Change Policy"
      author:  "Alexander Braun; Sebastian Utz, Jiahua Xu"
      journal: "The Geneva Papers on Risk and Insurance"
      number:  "44(4):549-568"
      year:    "2019"
      url:     "https://doi.org/10.1057/s41288-019-00142-w"
    - title:   "Semiparametric Value-At-Risk Estimation of Portfolios. A replication study of Dias (Journal of Banking & Finance, 2014)"
      author:  "Jiahua Xu"
      journal: "International Journal for Re-Views in Empirical Economics"
      number:  "3(6):1-20"
      year:    "2019"
      url:     "https://doi.org/10.18718/81781.15"
    - title:   "The Impact of CEO Pay and its Disclosure on Stock Price Crash Risk: Evidence from China"
      author:  "Jiahua Xu, Lan Zou"
      journal: "China Finance Review International"
      number:  "9(4):479-497"
      year:    "2019"
      url:     "https://doi.org/10.1108/CFRI-10-2018-0138"
    - title:   "Equity Incentives and Crash Risk in China's A-Share Market"
      author:  "Jiahua Xu"
      journal: "Asia-Pacific Journal of Risk and Insurance"
      number:  "13(1)"
      year:    "2019"
      url:     "https://doi.org/10.1515/apjri-2018-0025"
    - title:   "Predicting Longevity: An Analysis of Potential Alternatives to Life Expectancy Reports"
      author:  "Jiahua Xu, Adrin Hoesch"
      journal: "Journal of Investing"
      number:  "27(supplement):65-79"
      year:    "2018"
      url:     "https://doi.org/10.3905/joi.2018.27.supplement.065"
---

## Peer-reviewed articles

{% assign thumbnail="left" %}

{% for item in page.pubs %}
[**{{item.title}}**]({% if item.internal %}{{item.url | prepend: site.baseurl}}
{% else %}{{item.url}}{% endif %}){:target="_blank"}
<br />
{{item.author}} ({{item.year}})<br />
*{{item.journal}}*, {{item.number}}
{% endfor %}

## Working papers
