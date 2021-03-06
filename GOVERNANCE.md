# OpenJS Cross Project Council

For the current list of Team members, see the project
[README.md](./README.md).

## Members

The [openjs-foundation/cross-project-council](https://github.com/openjs-foundation/cross-project-council) GitHub
repository is maintained by the Team and additional Members who are
added on an ongoing basis.

## Team Membership

Team Membership is not time-limited. There is no fixed size of the Team.

There is no specific set of requirements or qualifications for Team Membership beyond these rules.

The following groups automatically have membership and can request to be added to the github team:

* OpenJS Foundation Voting Members
* OpenJS Foundation Regular Members
* OpenJS Foundation Board of Directors
* OpenJS Foundation Project Maintainers

## Team Meetings

The Team meets weekly on Zoom.us. A designated moderator
approved by the Team runs the meeting. Each meeting should be
published to YouTube.

Items are added to the Team agenda that are considered contentious or
are modifications of governance, contribution policy, Team membership,
or release process.

The intention of the agenda is not to approve or review all patches;
that should happen continuously on GitHub and be handled by the larger
group of Collaborators.

Any community member or contributor can ask that something be added to
the next meeting's agenda by logging a GitHub Issue. Any Collaborator,
Team member or the moderator can add the item to the agenda by adding
the ***cross-project-council-agenda*** tag to the issue.

Prior to each Team meeting the moderator will share the agenda with
members of the Team. Team members can add any items they like to the
agenda at the beginning of each meeting. The moderator and the Team
cannot veto or remove items.

The moderator is responsible for summarizing the discussion of each
agenda item and sends it as a pull request after the meeting.

## Consensus Seeking Process

The Team follows a
[Consensus Seeking](http://en.wikipedia.org/wiki/Consensus-seeking_decision-making)
decision-making model.

When an agenda item has appeared to reach a consensus, the moderator
will ask "Does anyone object?" as a final call for dissent from the
consensus.

If an agenda item cannot reach a consensus, a Team member can call for
the item to be decided by a vote or to table the issue to the next
meeting. In both cases the decision must be seconded by a majority of the Team
or else the discussion will continue. Simple majority wins. Only Active
Members participate in a vote.

## Election process for Non-Impact Voting CPC members

As per the [CPC charter](https://github.com/openjs-foundation/cross-project-council/blob/master/CPC-CHARTER.md), the non-impact projects elect 2 voting CPC members:

> up to two (2) Voting members may be nominated by the non-impact projects
  based on a process set by the CPC.
These members will be elected for a term of 1 year as follows:

* Once a year an issue will be opened in the CPC repo announcing that the period for
  nominations is open.

* Any member from one of the non-impact projects can self-nominate emailing the chair of the CPC with their
  interest in running for the CPC.

* The nomination period will be open for 2 weeks at which point the CPC chair will list the nominees in the
  issue.

* Each of the candidates listed will be asked to open an issue in the CPC repo which includes the following:
  * Projects they are part of
  * Description of their background
  * The reasons they would like to act as the non-impact CPC voting member
  * Confirmation that they can devote the required time/effort.
  * Their employer (if applicable). This is needed due to the limitations
    on maximum employer representation in the CPC voting members.

* The projects will be asked to confirm membership as identified by the nominees.

* Each non-impact project will nominate two `voters` through a process of their choosing.

* Each voter will be able to vote for as many or as few candidates as they wish.

* Those candidates who receive the greatest number of votes will be confirmed as
  the winners. In the case of a tie between 2 or more candidates, the winner will be
  chosen randomly unless:
   * There are only 2 candiates tied for the largest number of votes, in which case those 2
     candidates will be the winners, 
   * all but one of the candidates that are tied for the number of votes choose to conceed.

## Aproving Project Charters

Per the [CPC charter section 5](https://github.com/openjs-foundation/cross-project-council/blob/master/CPC-CHARTER.md#section-5-responsibilities-and-expectations-of-the-cpc), the voting CPC members are responsible for approving project
charters and changes to them.

Approval of the initial charter or changes to an existing charter will
be requested by opening an issue requesting approval in the cross-project-council
[repository](https://github.com/openjs-foundation/cross-project-council/)

The request is approved when:

* there are no outstanding objections
* there are two or more approvals by voting CPC members
* the board has been consulted in the case of substantial changes
* The issue has been open for at least 14 days

## Merging PRs into this Repository

Pull requests that do not change the charter or governance of the CPC can be merged into
this repository provided the following conditions have been met:

* there are no outstanding objections
* there are two approvals by CPC members
* the PR has been open for at least 72 hours

Pull requests that change governance of the CPC must meet the following conditions
in addition to the ones listed for regular PRs.

* The PR has been open for at least 14 days OR consensus is reached in a meeting
  with quorum of voting members.

Pull requests that change the charter of the CPC must meet the following conditions
in additon to the ones listed for changing CPC governance:

* The text of the PR must be approved by a simple majority of the voting members.
* The text of the PR must be approved by the board.

If consensus cannot be reached, a pull request may still be landed after a vote
by the Voting CPC members to override outstanding objections.
