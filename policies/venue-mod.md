# Venue-specific moderation policy

Rust has a ["Venue moderation" team][venue-mods] that operates in accordance with the [code of conduct][coc-mod]. Scaling this mod team across Rust's vast set of official venues is tricky, which is why we have venue-specific moderators.

Venue-specific moderators are defined as people who are _not_ on the mod team, but have some level of moderation capabilities on Rust venues (Discourse, Zulip, Github).


This work is entirely separated from that of the *mediators* (a.k.a. ["Moderation team"][moderation team] - yes the name is a bit confusing) which are responsible for handling internal conflicts within the project, where a private resolution and discretion is warranted).

## Becoming a venue-specific moderator

Anyone can nominate a platform-specific moderator (you can nominate yourself), however moderation team members need to vouch for them, and there should not be any objections from moderation team members. Don't worry too much about this requirement, we can work it out for individual cases (e.g. you can be vouched for by other venue mods instead and the mod team may allow it).

Remember that venue moderators can become the frontpage of the entire Rust project when they take action which could affect people in various ways. For this reason we invite you to think about before doing something, take your time and consult with the team. At the same time remember that every decision is *reversible*, so don't hesitate to take initiative. We all learn to become moderators and this only comes with experience so this is a place where mistakes can happen. The important thing is that they can be reversed.

Also, be vigilant but don't get paranoid about having to read everything everywhere: this work is not paid, it's best-effort and nobody expects anyone on duty 24/7. We prefer to distribute the work on multiple people across different timezones.

## How to moderate

Once you become a venue specific moderator, familiarize yourself with _both_ sections of the [code of conduct].

Venue moderation is _mostly_ in-the-moment stuff -- deescalating live when things get heated. You should feel free to:

 - Deescalate by talking with participants in public or private
   - If leaving a comment in public (especially for a platform like Github or Discourse), it's best to suffix your comment with something that asks them to ping you or the mods privately if they wish to discuss this. Such private discussions tend to be more productive than the same discussion in public, where it sometimes becomes more performative and toxic.
 - Delete messages/comments (keep a copy to send to rust-mods, either via email at *rust-mods at rust-lang dot org* or on Zulip)

If you feel it necessary, you are also allowed to do the following, but preferably discuss it with a mod team member first, and if you've done it _definitely_ communicate it to rust-mods about it. Sometimes it's better to deal with the problem first and talk to the mod team later; we trust your judgement in determining if this is the case.

 - Enable short temporary locks on the channel/thread till stuff cools down
 - Kick people from the channel/thread
 - Temporarily ban people from a channel or in drastic cases, the entire platform (if you are a platform moderator)
 - For spammers feel free to ban/delete immediately, this is considered a drastic case.

In general, after an incident please send rust-mods a link and mention if/how it was dealt with, so we can keep track and note when folks are repeatedly breaking the rules.

Permanent bans (for anything but outright spam) require the approval of the moderation team as detailed in the [governance rfc].

Longterm moderation issues (e.g. persistent trolls) should be brought up with the mod team. We will also communicate permabans with you (and try to involve you in longterm moderation discussions specific to your venue).

### Github-specific tips

When dealing with disrupting behaviour on GitHub (any repository under the [`rust/rust-lang`][rust-lang-org] organization) and want to report it, open the three-dots menu of the issue/pr comment and choose "Report content"; a notification thread is opened on Zulip and all the mods get notice.

Note that if you block or report a Github profile from their profile page (example https://github.com/oli-obk), you'll just prevent that user from interacting with *your* repositories, not with the Rust organization.

In case of clear spam or other disrupting behaviour, also report to Github itself, you'll help Github nuking the profile (but don't expect prompt action from them).

[moderation team]: https://rust-lang.org/governance/teams/moderation
[venue-mods]: https://rust-lang.org/governance/teams/moderation/#team-mods-venue
[coc-mod]: https://rust-lang.org/policies/code-of-conduct#moderation
[code of conduct]: https://rust-lang.org/policies/code-of-conduct
[governance rfc]: https://github.com/rust-lang/rfcs/blob/master/text/1068-rust-governance.md#initial-plan-for-moderation
[rust-lang-org]: https://github.com/rust-lang/rfcs/blob/master/text/1068-rust-governance.md#initial-plan-for-moderation
