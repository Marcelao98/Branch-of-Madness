# 🌪️ Branch of Madness

> Learning Git by writing a story with parallel timelines and time travel.

## What is this?

It's not a project. There is no code here, only a story.

The repository is a universe. Every commit is a moment in its history, and every branch is a parallel timeline where something happened differently. What if the meteor had missed the dinosaurs? Make a branch and find out.

The goal is to learn what Git is actually doing under the commands I used to memorize without understanding, using a story instead of code so the history is easy to picture.

## How Git maps to the story

| Git | In the story |
|---|---|
| Commit | A moment frozen in history |
| `main` | The original timeline |
| Branch | A parallel timeline that splits off at some moment |
| `git switch` | Jumping between timelines |
| `git checkout <commit>` | Traveling back in time to look around |
| Merge | Two timelines colliding into one |
| Merge conflict | Two realities disagree about what happened, and you decide which one wins |
| `git reset` | Rewinding time |
| `git revert` | Undoing an event by adding a new event that cancels it |
| `git rebase -i` | Rewriting history itself |
| `git cherry-pick` | Stealing one event from another timeline |
| `git reflog` | The time traveler's diary: it remembers timelines everyone else forgot |

## The plan

The challenges get harder as the story grows:

- Split the timeline: what if the meteor missed?
- Collide two timelines and resolve the conflict by hand
- Rewind with `reset` (soft, mixed, hard) and feel the difference
- Erase a timeline, then bring it back with `reflog`
- `cherry-pick` an event from one reality into another
- Rewrite history with `rebase -i`
- Force push where nobody's around to complain
- Cause temporal disasters and learn how to get out of them

## Rules of the multiverse

1. The story doesn't have to make sense.
2. Every chapter has to teach something about Git.
3. If a timeline breaks, even better — that's where the learning happens.

## Why?

Because studying data engineering made me dependent on Git in day-to-day work, but never forced me to actually *understand* it. So I decided to create a consequence-free universe to break everything until it clicks.

---

*No dinosaurs were permanently harmed in the making of this repository. Probably. Check the reflog.*
