# Spam policy

## Terminology

### AI or other machine-generated content

For the purposes of this document we use AI to refer to anything that generates text and isn't just 1:1 translating text or spell-checking/grammar-checking text by rewriting it into similarly long text. Terminology may evolve over time and this document should be adjusted accordingly every few years.

This policy is not about AI in general, but AI is a current driver of Spam comments and thus needs to be mentioned, as it causes an imbalance of effort between the creator of the spam (little effort) and the maintainers receiving the spam (a lot of effort).

### Suspicious contribution

Any contribution that makes a reviewer or moderator feel like something is off. While not exhaustive, examples include

- Overly verbose messages (issue/PR descriptions, commit messages, issue/PR comments)
- Changes that don't correspond to the PR description
- Verbose generated comments (esp. those relying to reviewers)
- Excessive use of emoji
- Excessive use of sections explaining already documented policies and practices
- Lots of text for very little and trivial contributions

There are real and even good contributions that check many of these boxes, but usually that means they are very information dense or require lots of context and may just feel verbose initially.

This is vague on purpose, because we do not know what kind of comments will come our way. We will always need to rely on human intutition and experience to judge things. Having a strict set of rules would invite rule lawyering.

Informing a contributor that their messages are hard to process is good even if they are 100% handwritten. If in doubt, reach out to the user.

## Motivation for this policy

Reviewer time is one of the most valuable resources we have. Unfortunately we have seen significant mis-use of AI for producing Spam. AI makes it easy to expand what was a simple bullet point list into paragraphs of repetitious and sometimes nonsensical text. This means with little effort, a lot of effort is required by reviewers to understand these messages or fail to understand nonsensical messages and detect them as such. Irrespective of whether AI tools have been used or a human sat down and wrote a bogus text, this is a waste of reviewer time.

To ensure reviewers and contributors have a good experience we need to prevent spam, identity farming and unintentionally verbose contributions from wasting time.

Since a ban is something easy to rescind, we are opting to ban people more quickly and require them to reach out to moderation.
This inverts the effort imbalance by requiring the user to send us an email, and moves the discussion private, thus not further wasting time of all the other community members who'd otherwise get github or zulip notifications.

## Analyzing the situation

If you see a suspicious contribution, first check the user's profile for previous contributions (either in [rustlang](https://github.com/search?q=org%3Arust-lang+commenter%3Aapiraino) or [anywhere](https://github.com/search?q=commenter%3Aapiraino)).

there are a few outcomes:

* the profile is private
* the user is obviously spamming (many PRs across many repos within a short period of time)
* PRs are small and split in even smaller commits trying to get them more easily through ("GitHub karma farming")
* the user is possibly a bot or at least automating lots of their contribs
* the user just had a very verbose or confusing contrib now and is otherwise fine

### Private profiles

While most private profiles are spam bots trying to hide what they are, there are also users who have set their profiles private. Not being able to get more information on the user, we default to sending the default message and depending on the response of the user, rescinding the warning.

1. Leave the warning message
2. Inform other mods in the mods Zulip stream

### Obvious spam

1. Leave the insta ban message
2. Ban the user
3. Inform other mods in the mods Zulip stream

### Fully or partially automated contribs

It is very hard to distinguish full automation of contributions compared with a user actually doing the contributions and using AI to publish them. We assume the latter, and will thus

1. Leave the insta ban message
2. Ban the user
3. Inform other mods in the mods Zulip stream

This inverts the effort imbalance by requiring the user to first reach out to moderation in order to be able to participate again.
We do not expect moderation to be unduly spammed by frivulous requests, and in either case that is better than everyone getting publicly spammed.

### One off verbose/confusing contrib

This happens, maybe even AI was involved by someone getting their bearings with it.

1. Leave the warning message
2. Inform the other mods, so we have an internal thread tracking this user in case it becomes a repetition

## Copy pastable responses

Copy paste the following when you see a concerning situation. Posting it requires no check-in with other mods, but they need to be informed in the mods Zulip stream

### Warning message and close PR

```!
Hi. This is the moderation team of the Rust project. It looks like you used an LLM without reviewing its output sufficiently.
At that point we become the reviewer of the LLM output, with you relaying our reviews back to the LLM as a proxy.
That is a lot of work without a clear benefit, while being also frustrating for reviewers.

We are closing and locking this PR, but you're welcome to create a new PR with content you created yourself. It is perfectly fine to just leave a one line comment and bullet points otherwise if this is easier for you.

If you would like some help with that, please ensure you're familiar with our [contribution guidelines](https://forge.rust-lang.org/how-to-start-contributing.html) and feel free to either reach out to moderation or ask on the [Zulip stream for general help](https://rust-lang.zulipchat.com/#narrow/channel/122651-general/topic/Feedback.20on.20github.20PR.20UI.2FUX.20changes/with/526008053) from other contributors.

If you are unsure how concise to make your message, you can include the full message in a `<details>` tag and let the reviewer know that some information may be missing from the concise message.

Note that this is a moderation warning. Repetitions of such comments or contributions will result in a ban from our project. You can contact the moderation team to discuss your warning.
```

### Insta ban message and close PR

```!
Hi. This is the moderation team of the Rust project. Your interaction with the Rust project has been identified as spammy, not constructive, or malicious. This goes against our [Code of Conduct](https://github.com/rust-lang/compiler-team/blob/master/CODE_OF_CONDUCT.md).

We are thus banning you as per our policy. You can contact the moderation team to discuss and possibly reconsider your ban.
```
