# Machine Friendly DDaT
Machine readable UK Government DDaT skills and levels

## What is DDaT?

DDaT is often used as a shorthand to encompass digital, data and
technology roles in government and the skills needed to do them.
Everyone who is considered to be inside DDaT can find a description of
job family and all the levels of seniority inside it. These levels and requirements form the basis
of how you progress through the level and achieve higher levels of seniority and pay.

Where can I learn more? On the
[ Digital, Data and Technology Profession Capability Framework ](https://www.gov.uk/government/collections/digital-data-and-technology-profession-capability-framework)
pages.


## Why this repository?

I sometimes need a machine readable version of parts of DDaT as part of
other processes. This is my *unofficial* conversion of some of the data
into hastily written YAML.

One usage example is comparing levels using a radar chart:
![Radar chart comparing Devops and Lead Devops skills](/images/devops-vs-lead.png "Radar chart comparing required Devops and Lead Devops skills")

## DDaT Levels
In the YAML files I'm currently representing the levels as numbers to
make it easier to generate the radar chart. Some skills are not present
at different levels, apprentices have less categories and management vs
individual contributors at higher levels for example, and for those
cases I've added `N/A` and assigned it a score of `1`

The levels, and their numerical equivalents are:

 * N/A == 1
 * Awareness == 2
 * Working == 3
 * Practitioner == 4
 * Expert == 5

And you can read the
[official skill level descriptions](https://www.gov.uk/guidance/skill-levels-for-digital-data-and-technology-roles)
on GOV.UK


## Job Families

 * [Devops / SRE / Webops](/devops/)


### Author

  [Dean Wilson](https://www.unixdaemon.net)
