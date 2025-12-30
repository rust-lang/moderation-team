# Venue-specific moderation policy

Rust has a [moderation team] that operates in accordance with the [code of conduct][coc-mod]. Scaling this mod team across Rust's vast set of official venues is tricky, which is why we have venue-specific moderators.

Venue-specific moderators are defined as people who are _not_ on the mod team, but have some level of moderation capabilities on some Rust venues (Discourse, zulip, github).

## Becoming a venue-specific moderator

We currently have a few of these -- the core team members themselves have moderation powers on most platforms, and we have some platform-specific moderators.

Anyone can nominate a platform-specific moderator (you can nominate yourself), however moderation team members need to vouch for them, and there should not be any objections from moderation team members. Don't worry too much about this requirement, we can work it out for individual cases (e.g. you can be vouched for by other venue mods instead and the mod team may allow it).

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
 - For spammers feel free to ban/delete immediately, this is considered a drastic case.

In general, after an incident please send rust-mods a link and mention if/how it was dealt with, so we can keep track and note when folks are repeatedly breaking the rules.

Permanent bans (for anything but outright spam) require the approval of the moderation team as detailed in the [governance rfc].

Longterm moderation issues (e.g. persistent trolls) should be brought up with the mod team. We will also communicate permabans with you (and try to involve you in longterm moderation discussions specific to your venue).

 [moderation team]: http://rust-lang.org/team.html
 [coc-mod]: https://rust-lang.org/policies/code-of-conduct#moderation
 [code of conduct]: https://rust-lang.org/policies/code-of-conduct
 [governance rfc]: https://github.com/rust-lang/rfcs/blob/master/text/1068-rust-governance.md#initial-plan-for-moderation
