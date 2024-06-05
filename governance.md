# _pandas_ Project Governance and Decision-Making

The purpose of this document is to formalize the governance process used by the pandas
project in both ordinary and extraordinary situations, and to clarify how decisions are
made and how the various elements of our community interact, including the relationship
between open source collaborative development and work that may be funded by for-profit
or non-profit entities.


The official version of this document, along with a list of
individuals and institutions in the roles defined in the governance
section below, is contained in The Project Governance Repository at:

[https://github.com/pandas-dev/pandas-governance](https://github.com/pandas-dev/pandas-governance)

## Summary

_pandas_ is a community-owned and community-run project. Major technical changes to the
project are managed by the PDEP (pandas enhancement proposal) process, described in
PDEP-1 at https://pandas.pydata.org/pdeps/0001-purpose-and-guidelines.html .  Because of
the large scope of the project, the project is managed by a number of different teams,
who each have responsibilities for different aspects of the project.  A Steering
Committee, elected on an annual basis, coordinates the activities of the different
teams.

## The Project

The pandas Project (The Project) is an open source software project sponsored
by the 501(c)3 NumFOCUS Foundation. NumFOCUS provides pandas with fiscal, legal, and
administrative support to help ensure the health and sustainability of the project.
The goal of The Project is to develop open
source software that is the fundamental high-level building block for doing practical,
real world data analysis in Python. Additionally, it has the broader goal of becoming
the most powerful and flexible open source data analysis / manipulation tool available
in any language. The Software developed by
The Project is released under the BSD (or similar) open source license,
developed openly and hosted on public GitHub repositories under the [`pandas-dev`
GitHub organization](https://github.com/pandas-dev).  Examples of Project Software
include the main pandas code repository, pandas website, and the pandas-stubs library.

The Project is developed by a team of distributed developers, called
Contributors. Contributors are individuals who have contributed code,
documentation, designs or other work to one or more Project repositories.
Anyone can be a Contributor. Contributors can be affiliated with any legal
entity or none. Contributors participate in the project by submitting,
reviewing and discussing GitHub Pull Requests and Issues and participating in
open and public Project discussions on GitHub, mailing lists, and
other channels. The foundation of Project participation is openness and
transparency.

The Project Community consists of all Contributors and Users of the Project.
Contributors work on behalf of and are responsible to the larger Project
Community and we strive to keep the barrier between Contributors and Users as
low as possible.

The Project is formally affiliated with the 501(c)3 NumFOCUS Foundation
([https://numfocus.org](https://numfocus.org)), which serves as its fiscal
sponsor, may hold project trademarks and other intellectual property, helps
manage project donations and acts as a parent legal entity. NumFOCUS is the
only legal entity that has a formal relationship with the project (see
Institutional Partners section below).

## Governance

This section describes the governance and leadership model of The Project.

The foundations of Project governance are:

-   Openness & Transparency
-   Active Contribution
-   Institutional Neutrality

To manage the project, there are different Teams that each have responsibility for
specific aspects of the project. Collectively, the members of all Teams are referred to
as _Stewards_ of the project.  Individuals may be members of more than one Team.

## Steering Committee

The role of the _pandas_ Steering Committee is to coordinate the activities of the
different Teams and to ensure that different policies and procedures are carried out in
a consistent manner. The Steering Committee has no routine decision-making authority,
except as detailed herein, although in exceptional circumstances it may be called upon
from time to time to make decisions that are in the best interest of The Project as a
whole. The Steering Committee will itself decide when a circumstance is exceptional.
The Steering Committee may not override a PDEP.  When the Steering Committee meets to
discuss an issue, the members of the Steering Committee are responsible for soliciting
input from members of the relevant Teams.

The Steering Committee may create a working group to consider changes to the governance
model described in this document, including the creation of new Teams that support the
goals of The Project. Changes to the governance model will require a voting process and
approval equivalent to the process described in PDEP-1, with the exception that all
Stewards are eligible to vote.  

The Steering Committee may appoint temporary working groups to work on issues, such as
governance, that fall outside the scope of responsibilities for the existing Teams.

The ideal composition of the Steering Committee consists of 5 people.  The Steering
Committee will be chosen via an approval voting process from a slate of nominees,
meaning that each person who is eligible to vote may vote for more than one candidate
from the slate.  All members of each Team, except the Code of Conduct Team, are 
eligible to vote.  

### Initial Election

The initial slate for the Steering Committee election will consist of 5 or more
candidates who volunteer to be on the slate of candidates for the initial Steering
Committee.  For the initial election, the members of the previous _pandas_ core team
will vote via an approval voting process.  The top 5 candidates receiving votes
will then become members of the initial Steering Committee. 

### Subsequent Elections  

Subsequent changes to the membership of the Steering Committee will occur towards the
end of each calendar year.  By October 31 of each year, each member of the Steering
Committee will be asked if they would like to continue in that role. If any member
decides to step down from the Steering Committee, new volunteers will be solicited from
the group of stewards by the Steering Committee.  Those new volunteers, along with any
current Steering Committee members who wish to remain on the Steering Committee,
will then be on a
slate for an election that will occur by November 15 of that year.  For each year after
the initial election, the current Steering Committee members plus any new volunteers on
the slate will be elected via approval voting, with the top 5 candidates elected as
Steering Committee members for the subsequent year.

The terms of each member of the Steering Committee are from January
1 to December 31 of each calendar year, and Steering Committee members may serve for
any number of multiple terms, provided that they are re-elected in each annual election.


## Teams

Each Team has defined responsibilities for different aspects of the project.  As a
general rule, an Individual Contributor can be nominated by a member of a Team to become
a member of that Team, and the Team must agree to admitting that person to
the Team, since every Team member becomes a Steward of the Project. If a member of a
Team is inactive for more than one year, the active members of the Team 
may decide to remove that
person from the Team. 
Decisions about admittance or removal of Team members should be made by the Team as a
whole, as long as there are no objections from active team members.

Each Team will maintain its own private mailing list if the Team
deems it to be necessary. There will also be a mailing list consisting of all Stewards
of all Teams.

Each Team has specific responsibilities as well as authorities over permissions, as
defined below. In addition, specific criteria are used by Team Members to guide
decisions on adding new Members to the Team.

The description of each Team can be found in https://github.com/pandas-dev/pandas-governance/teams.md .

**THE DETAILS OF THE TEAMS IN THAT DOCUMENT ARE IN A SEPARATE PULL REQUEST**

### Conflict of interest

It is expected that all Stewards will be employed at a wide
range of companies, universities and non-profit organizations. Because of this,
it is possible that Stewards will have conflict of interests. Such conflict of
interests include, but are not limited to:

-   Financial interests, such as investments, employment or contracting work,
    outside of The Project that may influence their work on The Project.
-   Access to proprietary information of their employer that could potentially
    leak into their work with the Project.

All Stewards shall disclose to the Steering Committee
any conflict of interest they may have. Stewards with a conflict of
interest in a particular issue may participate in Team discussions on that
issue, but must recuse themselves from voting on the issue, if such
a vote is necessary.  If a conflict of interest is not disclosed and later uncovered,
it will be left to the Steering Committee to decide how to handle the lack of disclosure
on a case-by-case basis

### Private communications of the Steering Committee

To the maximum extent possible, Team discussions and activities will be
public and done in collaboration and discussion with the Project Contributors
and Community. The Steering Committee will have a private mailing list that will be used
sparingly and only when a specific matter requires privacy. When private
communications and decisions are needed, the Steering Committee will do its best to
summarize those to the Community after eliding personal/private/sensitive
information that should not be posted to the public internet.

## Institutional Partners and Funding

The Stewards are the primary leaders of the project. No outside
institution, individual or legal entity has the ability to own, control, usurp
or influence the project other than by participating in the Project as
Contributors and Stewards. However, because institutions can be an important
funding mechanism for the project, it is important to formally acknowledge
institutional participation in the project. These are Institutional Partners.
An Institutional Contributor is any individual Project Contributor who
contributes to the project as part of their official duties at an Institutional
Partner. Likewise, an Institutional Steward is any Steward
who contributes to the project as part of their official duties at an
Institutional Partner.
With these definitions, an Institutional Partner is any recognized legal entity
in the United States or elsewhere that employs at least one Institutional
Contributor or Institutional Steward. Institutional Partners can be
for-profit or non-profit entities.
Institutions become eligible to become an Institutional Partner by employing
individuals who actively contribute to The Project as part of their official
duties. To state this another way, the only way for an Institutional Partner to
influence the project is by actively contributing to the open development of
the project, on equal terms with any other member of the community of
Contributors and Stewards. Merely using Project Software in
an institutional context does not allow an entity to become an Institutional
Partner. Financial gifts, which are recognized on the _pandas_ web site,
do not enable an entity to become an Institutional
Partner. Once an institution becomes eligible for Institutional Partnership,
the Steering Committee must nominate and approve the Partnership, after soliciting
input from the Stewards.
If at some point an existing Institutional Partner stops having any contributing
employees, then a one year grace period commences. If at the end of this one year period
they continue to not have any contributing employees, then their Institutional
Partnership will lapse, and resuming it will require going through the normal process
for new Partnerships.

An Institutional Partner is free to pursue funding for their work on The
Project through any legal means. This could involve a non-profit organization
raising money from private foundations and donors or a for-profit company
building proprietary products and services that leverage Project Software and
Services. Funding acquired by Institutional Partners to work on The Project is
called Institutional Funding. However, no funding obtained by an Institutional
Partner can override the Steering Committee. If a Partner has funding
to do pandas work and the Steering Committee decides to not pursue that work as a
project, the Partner is free to pursue it on their own. However in this
situation, that part of the Partner’s work will not be under the pandas
umbrella and cannot use the Project trademarks in a way that suggests a formal
relationship.

Institutional Partner benefits are:

- Acknowledged on the _pandas_ website, in talks and T-shirts.
- Ability to acknowledge their own funding sources on the _pandas_ websites, in
  talks and T-shirts.
- Ability to influence the project through the participation of their Steward.

A list of current Institutional Partners is maintained at the page
https://pandas.pydata.org/about/sponsors.html .


## Document History

Original Version:  February 15, 2016
Complete Revision:  ???, 2024

## Acknowledgments

Portions of this document were adapted from the [NumPy governance document](https://numpy.org/doc/stable/dev/governance/governance.html).

## License

To the extent possible under law, the authors have waived all copyright and related or 
neighboring rights to the pandas project governance and decision-making document,
as per the [CC-0 public domain dedication / license](https://creativecommons.org/publicdomain/zero/1.0/).

