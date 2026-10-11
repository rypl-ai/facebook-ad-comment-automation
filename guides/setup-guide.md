# Step-by-Step Setup Guide for Facebook Ad Comment Automation

*Last updated: October 11, 2026*

[Back to Main Guide](../README.md) | [Best Practices](best-practices.md) | [ROI Guide](roi-estimation-guide.md)

---

This walkthrough uses [Rypl](https://www.rypl.is) as the example tool; the order of steps is the same in most tools. Setup takes a few minutes, plus the time to gather your facts.

## Before you start

- **Admin access** to the Facebook Page that runs your ads. Instagram accounts must be professional accounts linked to that Page.
- For TikTok ads, access to the TikTok ad account.
- **Your facts:** your website, prices, shipping and returns, and the questions customers ask most.
- **A baseline:** note ROAS, cost per result and typical reply time for the ads you'll compare.

## Step 1: Create an account and describe your business

Sign up at [app.rypl.is/signup](https://app.rypl.is/signup). Describe your business in a few sentences; Rypl builds a starting AI agent and a starter set of moderation rules from it. Every plan starts with a 7-day free trial.

| If you… | Plan |
|---|---|
| Run one business with up to 3 pages | Simple, $19/mo |
| Run several pages or brands and want rules in plain words | Pro, $49/mo |
| Run an agency or need unlimited accounts and pages | Ultra, $89/mo |

No plan limits the number of comments.

## Step 2: Connect your channels

- **Facebook:** click **Connect Facebook** and choose **Business profile** (through your Meta Business portfolio, no re-login) or **Personal profile**. Allow the permissions and select your Pages.
- **Instagram:** comes with the Facebook Page it is linked to.
- **TikTok:** click **Connect TikTok** and authorize your ad account. Rypl handles TikTok ad comments; organic TikTok posts aren't supported.

Everything connects through the official Meta Graph API and TikTok Marketing API.

## Step 3: Fill the knowledge base

This step decides how good the answers are.

- **Website:** links in replies point here, and the agent can learn from the page.
- **Q&A:** your most common questions, with the exact answers you want given.
- **Documents:** up to 3 files (PDF, TXT, DOC, DOCX or CSV), such as a price list, size chart or returns policy.

Be specific: "Ships to the US in 3 to 5 business days, free over $50" beats "Shipping is fast".

## Step 4: Set the agent's voice

- **Tone:** Neutral, Seller, Positive or Direct.
- **Instructions** (up to 4,000 characters): reply length, words to use and avoid, what to say when the agent doesn't know.
- **Where it replies:** comments and messages, comments only, or messages only.
- **How soon:** immediately (default), within a few minutes, within an hour or within a day.

On Pro and Ultra, turn on **Read the post** so the agent knows which product an ad shows.

## Step 5: Set moderation

- **Spam and hate** are hidden automatically.
- **Banned words:** competitor names, rival domains, slurs. `"word"` in quotes matches only the whole word.
- **Filter by tone:** off by default. Leave it off unless your ads draw hostility; complaints should reach a person.
- **Strict Spam & Media Filter:** for ads that attract link spam.
- **Moderation rules** (Pro and Ultra): write them in plain words, for example *hide comments that recommend another store*, and start them in **Review first**.

## Step 6: Go live

In each channel's **AI replies** settings, switch on **Reply with AI** and choose the agent. Moderation runs even with replies off.

## Step 7: Check the first week

Every day:

- [ ] Read the replies in the inbox; each shows the agent that wrote it.
- [ ] Check **All hidden or deleted** and unhide mistakes.
- [ ] Clear **Needs attention**: complaints and rule matches.
- [ ] Add missing facts to the knowledge base.

| Problem | Fix |
|---|---|
| Wrong product facts | Update the knowledge base |
| Real comments hidden | Narrow the banned word (use quotes) or the rule |
| Replies too long or too formal | Adjust instructions or tone |
| The agent can't answer a common question | Add it as Q&A, or run **Suggest improvements** |
| A topic the AI shouldn't touch | Add a **Don't reply** reply rule (Pro and Ultra) |

## Step 8: Compare with your baseline

After two to four weeks, compare ROAS, cost per result, quality ranking and reply time with the numbers you noted before. The [ROI guide](roi-estimation-guide.md) explains how.


## More on rypl.is

- [Facebook comment moderation tool](https://www.rypl.is/facebook-comment-moderation-tool): how Rypl answers and moderates comments on Facebook ads and posts
- [Instagram comment moderation tool](https://www.rypl.is/instagram-comment-moderation-tool): AI replies and moderation for Instagram ads, posts and DMs
- [TikTok ad comment moderation tool](https://www.rypl.is/tiktok-comment-moderation-tool): replies and moderation for comments on TikTok ads
- [How to auto-reply to Facebook comments](https://www.rypl.is/guides/auto-reply-to-facebook-comments): Meta's own options and where AI replies fit
- [How to see and reply to comments on Facebook ads](https://www.rypl.is/blog/how-to-see-comments-on-facebook-ads): find every ad comment, dark posts included
- [Instagram ad comment automation guide](https://www.rypl.is/blog/instagram-ad-comment-automation-guide): permissions, Reels and DMs
- [How to manage comments on TikTok ads](https://www.rypl.is/blog/how-to-manage-tiktok-ad-comments): the complete guide

---

**Need help?** See the [Rypl documentation](https://rypl-ai.github.io/docs/) or email [hey@rypl.is](mailto:hey@rypl.is).

*Part of the [Facebook Ad Comment Automation Guide](../README.md) by [Rypl](https://www.rypl.is).*
