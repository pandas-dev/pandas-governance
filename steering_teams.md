# Information

This document starting with "Steering Committee" will become part of the main 
governance document, once approved.

The first paragraph below is the same as in the pull request for the changes to
the front and back matter.

## Steering Committee

The role of the _pandas _Steering Committee is to coordinate the activities of the
different Teams and to ensure that different policies and procedures are carried out in
a consistent manner. The Steering Committee has no routine decision-making authority,
except as detailed herein, although in exceptional circumstances it may be called upon
from time to time to make decisions that are in the best interest of The Project as a
whole. The Steering Committee will itself decide when a circumstance is exceptional.

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
from the slate.  

### Initial Election

The initial slate for the Steering Committee election will consist of 5 or more
candidates who volunteer to be on the slate of candidates for the initial Steering
Committee.  For the initial election, any candidate receiving more than 50% of the total
number of members of the previous _pandas_ core team that register at least one vote
will then become a member of the initial Steering Committee. 

### Subsequent Elections  

Subsequent changes to the membership of the Steering Committee will occur towards the
end of each calendar year.  By November 30 of each year, each member of the Steering
Committee will be asked if they would like to continue in that role. If any member
decides to step down from the Steering Committee, new volunteers will be solicited from
the group of stewards by the Steering Committee.  Those new volunteers will then be on a
slate for an election that will occur by December 15 of that year.  For each year after
the initial election, the current Steering Committee members plus any new volunteers on
the slate will be elected via approval voting, with the top 5 candidates elected as
Steering Committee members for the subsequent year.

## Teams

Each Team has defined responsibilities for different aspects of the project.  As a
general rule, an Individual Contributor can be nominated by a member of a Team to become
a member of that Team, and the Team must unanimously agree to admitting that person to
the Team, since every Team member becomes a Steward of the Project. If a member of a
Team is inactive for more than one year, the Team may unanimously decide to remove that
person from the Team. Each Team will maintain its own private mailing list if the Team
deems it to be necessary. There will also be a mailing list consisting of all Stewards
of all Teams.

Each Team has specific responsibilities as well as Permissions authorities, as defined
below. In addition, specific criteria are used by Team Members to guide decisions on
adding new Members to the Team.

### Core Library Team

#### Responsibilities

* Maintain and develop the _pandas _library (the
  [https://github.com/pandas-dev/pandas/](https://github.com/pandas-dev/pandas/)
  repository)
* Review and Approve or Reject Pull Requests
    * Current guidelines on merging PRs:
      [https://pandas.pydata.org/docs/dev/development/maintaining.html#merging-pull-requests](https://pandas.pydata.org/docs/dev/development/maintaining.html#merging-pull-requests)
* Build and Distribute Releases of the _pandas_ library

#### Permissions

* Has permission to merge anything to the main branch of the _pandas _repository
* Only Team with PDEP voting rights

#### Criteria for Membership

* New Members are nominated after a period of sustained and qualitative contributions
    * Joining heuristic: "is there some aspect of _pandas _where we trust this person to
      get something in without anyone's help?".
    * An existing Member of the Team proposes to promote a new member
* [https://pandas.pydata.org/docs/dev/development/maintaining.html#becoming-a-pandas-maintainer](https://pandas.pydata.org/docs/dev/development/maintaining.html#becoming-a-pandas-maintainer)

### pandas-stubs Team

#### Responsibilities

* Maintenance of `pandas-stubs` repository
  ([https://github.com/pandas-dev/pandas-stubs](https://github.com/pandas-dev/pandas-stubs)) 
    * Triage of issues
    * Reviews of pull requests
    * Merges
    * Releases
        * Delegated to 2 or 3 members

#### Permissions

* Only Team with permission to merge to the main branch of the _pandas-stubs_ repository

#### Criteria for Membership

* New Members are nominated after a period of sustained and qualitative contributions
    * Joining heuristic: "is there some aspect of _pandas-stubs _where we trust this
      person to get something in without anyone's help?".
    * An existing Member of the Team proposes to promote a new member

### Finance Team

#### Responsibilities

* Manage Applications for Grant Proposals for Funding
* Approve Project Expenses
* Ensure that finances are effectively used
* Find funding opportunities from appropriate, ethical sources 

#### Permissions

* No specific technical permissions
* Permissions to make all financial decisions on behalf of the Project
* Determines rates for any paid contributors

#### Criteria for Membership

* Member of one Team for at least three years
* Unanimous Approval of Steering Committee
* Limited to 5 Members

### Infrastructure Team

#### Responsibilities

* Keep the pandas infrastructure up and working, including the servers for the website,
  benchmarks, CI and others as needed.
* Decisions on platform support
* Manage the 1Password repository

#### Permissions

* Usernames and Passwords for various servers

#### Criteria for Membership

* New Members are nominated after a period of sustained and qualitative contributions
    * Joining heuristic: "is there some aspect of the infrastructure where we trust this
      person to manage that part of the infrastructure without assistance?".
    * An existing Member of the Team proposes to promote a new member

### Documentation Team

#### Responsibilities

* Maintain the pandas documentation and its (building) infrastructure

#### Permissions

* Permission to merge to the main branch of the _pandas _repository, with the criteria
  that it is a DOC only PR.

#### Criteria for Membership

* New Members are nominated after a period of sustained and qualitative contributions to
  the documentation

### Code of Conduct Team

#### Responsibilities

* Make sure the _pandas _community is a welcoming and inclusive community.
* Keeping the Code of Conduct
  ([https://pandas.pydata.org/community/coc.html](https://pandas.pydata.org/community/coc.html))
  updated
* Addressing reports of violations of the Code of Conduct

#### Permissions

* Administering the Code of Conduct

#### Criteria for Membership

* At most one Member of another Team can be on the Code of Conduct Team
* Volunteers from the Community are welcome
* Approval by the Steering Committee

### Triage Team

#### Responsibilities

* Help triage issues on the _pandas_ repository (respond to new issues, verify
  reproducibility and ensure a clear description, …)

#### Permissions

* “Triage” permissions for the _pandas_ repository (ability to manage issues without
  write access)

#### Criteria for Membership

* New Members are nominated by a Core Library Team member after a period of sustained
  and qualitative contributions

### Contributor Community Team

#### Responsibilities

* Support and enable Individual Contributors to make contributions to the Project
* Encourage continued contributions from Individual Contributors so that they become
  future members of Teams
* Lead Biweekly New Contributor Meetings
* Organize sprints

#### Permissions

* No special permissions exist for this team

#### Criteria for Membership

* At least 2 members of the Core Library Team should be on this team
* Appointed by the Core Library Team

### Website Team

#### Responsibilities

* Maintain the website; in particular:
    * The active maintainers
    * The institutional partners and sponsors of the project
    * The advertised books
    * Design and technical implementation

#### Criteria for Membership

* At least two Stewards should be on this team.
* Joining heuristic: Would you trust this person to make decisions about the pandas
  website?

#### Permissions

* Permission to merge to the main branch of the _pandas _repository, with the criteria
  that it is a WEBSITE only PR.
* Login credentials for the web server

### Outreach Team

#### Responsibilities

* Announce new _pandas _releases on social channels
* Announce other pandas-related news, such as:
    * Recurring meetings
    * Events (such as sprints)
    * Blog posts (related to _pandas_) by _pandas _members
* Keep communication on-topic. It doesn’t all have to be completely serious, but it
  should be on-topic - let’s not use the social accounts for political soapboxing
* Be respectful of other projects: open source, closed source, etc…they all have real
  humans behind them

#### Permissions

* Usernames and Passwords for various social accounts
    * Twitter/X account 
    * Mastodon account 
    * LinkedIn group management
