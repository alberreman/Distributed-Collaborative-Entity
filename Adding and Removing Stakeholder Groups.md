**Adding and Removing Stakeholder Groups from the DCE: Social Governance
Mechanisms Edition**

Upon submission of the Stakeholder Group Proposal to executive management, it
was determined that before accepting any specific stakeholder groups, we must
first determine how stakeholder groups may be added and removed. This is both a
technical and social question. While we have some thoughts about the technical
side of things\*, the social mechanism must first be decided such that
thoughtful analysis and design of the technical component can be considered.

\*You may note reference to Colony and/or other DAO frameworks. We have no
commitment to any of these technologies or companies. We are currently in an
exploratory phase wherein we are considering the potential of existing
platforms, as well as the ways in which we might need to customize them to our
needs.

**BIG BURNING QUESTIONS**

-   How does the DCE decide that someone should be added or taken away?

-   What are the parameters or criteria for stakeholder designation?

-   I imagine there are many reasons that a SH group could get removed. What are
    those reasons?

-   Do the methods for exorcizing them vary between reasons, and does the tech
    solution stand up under all of those circumstances?

**What is a stakeholder?**

>   Stakeholders are the people who have the ability to affect and be affected
>   by the success of our company, and work with us to succeed. Not all of them
>   will necessarily be given formalized stakeholder groups, but all should have
>   a voice in the governance of the company. Whether or not they are have their
>   own stakeholder group, are represented alongside other stakeholders with
>   similar enough interests in a multi-stakeholder group, or are simply
>   represented at the board level without a formalized stakeholder group is to
>   be determined by technical, legal, and practical considerations.

**What does it mean to be a formally represented stakeholder group?**

>   Formally represented stakeholder groups have board representation and voting
>   power. They also might receive some amount of the company’s profits. This
>   gives formal representation to stakeholders so that they can speak to the
>   interests of their group, and negotiate with other groups for the benefit of
>   all.

**Why might we remove a stakeholder group?**

-   As a group, they are no longer sufficiently affected or affecting the
    success of the company as to be considered “stakeholders.”

-   Irreconcilable differences – They just don’t want to be together anymore.

-   They have broken some rule of the organization laid out in the (forthcoming)
    bylaws/manifesto/constitution\* in a significant enough way as to warrant
    booting.

>   \*Some mechanism for immediately removing a group or person from the DCE,
>   not phasing them out. Potentially a universal mechanism to add and remove
>   stakeholder reputation, to diminish their voting power. Colony cannot
>   currently do this, though there may be domain-specific permissions allowing for effectively the same thing. DAOstack can. What if there were separate colonies, not
>   just one colony, so that once a group was barred from the board they’d be
>   cut off from funding. Makes the democracy less direct, but allows greater
>   flexibility in governance models between groups, and more ease in adding and
>   removing groups.

**Why might we want to add a stakeholder group?**

-   a community significantly affected by the DCE is not being represented

-   some group is significantly aiding the success of the DCE that is not being
    represented

**Ways You Could Feasibly Decide to Remove or Add a Stakeholder Group:**

-   A stakeholder group could at any time choose to divorce itself from the
    board or dissolve completely. The governance frameworks for doing so may
    vary between groups, and from the way that a group is exorcised by another
    SH group/the board. For example, a stakeholder group’s decision to leave the
    board might be unilaterally made by the leadership without SH group members
    consensus, if that is how that SH group is governed.

-   dictator

>   **Board-led**

-   (Board members alone could decide.)

-   Board members could pass a resolution that would then be opened to some vote
    by the public. Once decided by the board, a vote is opened to the
    stakeholder groups in a *universal ballot*\*\*

    -   Some minimum amount of support would be needed to pass the resolution.

        -   Of the total people who do vote, a decision is made based on their
            majority or super majority position.

    -   *Or there would be some maximum allowable dissent. Three ways:*

        -   *Maximum dissent of participating voters. Ex: No more than 20% of
            votes can be in opposition to the proposal.*

            -   *Maybe it’s 2/3 majority of the voting participants to overturn
                the board. Get all US government on this shit.*

        -   *No stakeholder group can have more than some percentage of
            opposition.*

        -   *Maximum allowable dissent expressed of total voting-eligible
            population/reputation, not percentage of total voters.*

            -   This seems well suited to a system with low voter participation,
                since the people most likely to vote are those who dissent,
                making the other system potentially unfair, but as voter
                participation goes up, you’d want the bar for maximum dissent to
                increase. But at what rate is a potential nightmare question.
                2/3 might be easier and not notably better.

>   **Stakeholder-led**

-   Member of a SH group could also introduce a referendum, which is then voted
    on within that SH group. If it has some amount of support:

    -   The proposal is considered by the board. The board votes. If the board
        accepts the proposal, a vote is opened to the whole DCE. Barring 2/3
        majority rejection, the proposal is adopted.

>   \*\* *Universal ballots* are determined by popular vote, where individuals’
>   voting power is weighted according to the total voting power of the
>   stakeholder group to which they belong, and amount of reputation they
>   possess in proportion to the total amount of reputation in their stockholder
>   group.

1.  For example, if a stakeholder group together holds 10 percent of the total
    voting power, and an individual owns 10 percent of the voting power within
    that stakeholder group, their vote in a universal ballot is 1 percent of the
    total voting power.

**On referendums more generally:**

-   Referendums can begin at the board or SH group level.

-   All referendums must adhere to the stated values and rules of the DCE.

    -   There maybe needs to be a process for rejecting an “illegal” referendum.
        This might be the place of the court, which would be comprised of
        individuals from all SH groups. However, it is possible that the board
        could be a better group to stop an illegal outcome (because of legal
        accountabilities and accountabilities to their stakeholder group) and
        the fastest way to get things done.

-   A referendum could be submitted by anyone in any stakeholder group. It could
    then join a list of submitted referendums, like in the Genesis DAO. People
    would stake their reputation on either side, though there is no risk of
    losing or gaining reputation. It would just be staked so that the people
    with more rep get more say.

-   If the proposal could get enough support behind it at the “local” level –
    within the stakeholder group – then it could be pushed up to the level of
    the DCE to be discussed at the board level.

-   Any stakeholder-led referendum will need to get some minimum amount of
    support in its local stakeholder group.

**Software Considerations**

**Two technical possibilities for the highest level of the DCE – “The Board”:**

This level is comprised of representatives from stakeholder groups, and
potentially also of representatives with no formalized stakeholder group. The
board controls the budget, though whether this is held in a contract and is
cryptocurrency is very much uncertain. It is also possible that they hold the
bulk of company stock – again, potentially in a wallet and potentially not,
depending on whether our securities are tokenized. The board is also responsible
for the distribution of profit sharing, which again may or may not be done
through cryptocurrency. If the DCE is a colony, or a collection of colonies, it
may be the case that the board distributes tokens to be used for the
distribution of tasks and therefor the building of reputation. It may be
possible that no blockchain-based solution is necessary for the board.

**A multisig** (or set of multisigs),

>   Separate from the colony/ies and individual stakeholder groups. Elected
>   representatives are signers on it, who then vote on funding decisions and
>   other board decisions. This board could hold the trusts potentially – easy
>   to boot people from board to add and remove stakeholder groups. Allows
>   diverse governance frameworks: Colony, DAOstack, Aragon, Democracy Earth, or
>   entirely off-chain.

**A metacolony** -

>   Head of/attached to all colonies. Booting people from the board or
>   organization would be less straight forward, but possible. Maybe you could
>   tag each SH group with some \#skill, and then if one SH group was removed,
>   all future votes would just not include that \#skill in the vote, and no
>   longer distribute \$ to that group. (Probably not currently possible with
>   Colony, not sure if it is something you could change.) Reputation would just
>   slowly decay over time. You could also just slowly phase a SH group out by
>   not removing them from board-level votes, but instead just stop funding
>   them. It is unclear if a metacolony could have representative governance –
>   certainly not as the tech stands now, but this may or may not be changeable.
