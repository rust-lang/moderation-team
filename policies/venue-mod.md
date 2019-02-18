# Venue-specific moderation policy

Rust has a [moderation team] that operates in accordance with the [code of conduct][coc-mod]. Scaling this mod team across Rust's vast set of official venues is tricky, which is why we have venue-specific moderators.

Venue-specific moderators are defined as people who are _not_ on the mod team, but have some level of moderation capabilities on some Rust venues. Broadly, there are two kinds: Platform moderators (those with moderations powers on, e.g. all of Discourse or Discord), and channel moderators (those with moderation powers on specific channels on a platform, like all the "language team" channels on IRC or Discord). Both operate in much the same way, though the process for becoming one is different.


## Becoming a channel-specific moderator

Usually, teams moderate their own channels to some level, and we'd like to encourage that. Becoming a channel-specific moderator for a team-run channel just requires the team lead to agree. So usually team and working group members will have moderation access on their own channels, and may additionally grant access to other trusted community members who are active in their teams. It is encouraged but not required to let the mod team know when a channel-specific moderator is added.

For non-team-run channels (e.g. #rust) the mod or core team can add moderators. For the mod team this requires there to be some level of agreement within the team (a single moderator cannot do this). The core team is free to come up with their own policy for this (?).

## Becoming a platform-specific moderator

We currently have a few of these -- the core team members themselves have moderation powers on most platforms, and we have some platform-specific moderators on Discord (see [moderators.md](../moderators.md)).

Anyone can nominate a platform-specific moderator (you can nominate yourself), however it requires at least two(?) people from the core or moderation team to vouch for them, and there should not be any objections from moderation team members. Don't worry too much about this requirement, we can work it out for individual cases (e.g. you can be vouched for by other venue mods instead and the mod team may allow it).



## How to moderate

Once you become a venue specific moderator, familiarize yourself with _both_ sections of the [code of conduct].

Venue moderation is _mostly_ in-the-moment stuff -- deescalating live when things get heated. You should feel free to:

 - Deescalate by talking with participants in public or private
   - If leaving a comment in public (especially for a platform like Github or Discourse), it's best to suffix your comment with something that asks them to ping you or the mods privately if they wish to discuss this. Such private discussions tend to be more productive than the same discussion in public, where it sometimes becomes more performative and toxic.
 - Delete messages/comments (keep a copy to send to rust-mods)

If you feel it necessary, you are also allowed to do the following, but preferably discuss it with a mod team member first, and if you've done it _definitely_ send an email to rust-mods about it. Sometimes it's better to deal with the problem first and talk to the mod team later; we trust your judgement in determining if this is the case.

 - Enable short temporary locks on the channel/thread till stuff cools down
 - Kick people from the channel/thread
 - Temporarily ban people from a channel or in drastic cases, the entire platform (if you are a platform moderator)
 - For spammers feel free to ban/delete, this is considered a drastic case.

In general, after an incident please send rust-mods a link and mention if/how it was dealt with, so we can keep track and note when folks are repeatedly breaking the rules.


Permanent bans require the approval of the core team as detailed in the [governance rfc].

Longterm moderation issues (e.g. persistent trolls) should be brought up with the mod team. We will also communicate permabans with you (and try to involve you in longterm moderation discussions specific to your venue).

 [moderation team]: http://rust-lang.org/team.html
 [coc-mod]: https://www.rust-lang.org/en-US/conduct.html#moderation
 [code of conduct]: https://www.rust-lang.org/en-US/conduct.html
 [governance rfc]: https://github.com/rust-lang/rfcs/blob/master/text/1068-rust-governance.md#initial-plan-for-moderation
