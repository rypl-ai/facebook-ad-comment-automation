# Step-by-Step Setup Guide for Facebook Ad Comment Automation

*Last updated: November 19, 2026*

[Back to Main Guide](../README.md) | [Best Practices](best-practices.md) | [ROI Guide](roi-estimation-guide.md)

---

This walkthrough uses [Rypl](https://www.rypl.is) as the example tool; the order of steps is the same in most tools. Setup takes a few minutes, plus the time to gather your facts. For every screen in detail, see the [Rypl documentation](https://www.rypl.is/docs).

## Before you start

- **Access to the Facebook Page** that runs your ads. Instagram accounts must be professional (business or creator) accounts linked to that Page.
- For TikTok ads, access to the TikTok ad account in TikTok for Business.
- **Your facts:** your website, prices, shipping and returns, and the questions customers ask most.
- **A baseline:** note ROAS, cost per result and typical reply time for the ads you'll compare.

## Step 1: Create an account and describe your business

Sign up at [app.rypl.is/signup](https://app.rypl.is/signup) with Google or email. Say what you sell, what people ask, how replies should sound, what to hide and what you want to handle yourself, and add your website. Rypl drafts an agent (instructions, tone and Q&A) and a starter set of banned words and moderation rules. Edit anything; nothing goes live until you turn it on. Every plan starts with a 7-day free trial.

| If you… | Plan |
|---|---|
| Run one brand, with AI replies on up to 3 channels | Simple, $19/mo |
| Run several brands, want rules in plain words, or want the API and MCP server | Pro, $49/mo |
| Run an agency or need unlimited accounts and channels | Ultra, $89/mo |

A channel is a Facebook Page with its linked Instagram account, or a TikTok ad account. You can connect more channels than your plan's number: moderation runs on all of them, and only channels with AI replies on count. No plan limits the number of comments.

## Step 2: Connect your channels

During sign-up you connect one account; add more once the trial has started. Later, open **Channels** and click **Connect channel**.

- **Facebook:** choose **Business profile** (through your Meta Business portfolio, recommended because it doesn't need re-login) or **Personal profile**. Allow the permissions and select your Pages.
- **Instagram:** comes with the Facebook Page it is linked to and doesn't count as an extra channel.
- **TikTok:** choose **TikTok ads**, sign in to TikTok for Business and authorize your ad accounts. Rypl handles comments on TikTok ads; organic TikTok posts and TikTok messages aren't supported.

Everything connects through the official Meta Graph API and TikTok Marketing API. If a Page or Instagram account doesn't appear, see [Why doesn't my Page or Instagram account appear in Rypl?](https://www.rypl.is/docs/troubleshooting/why-doesnt-my-page-appear)

## Step 3: Fill the knowledge base

This step decides how good the answers are. It is on the agent's **Knowledge** tab.

- **Website:** links in replies point here, and the agent can learn from the page. Click **Read it again** when your site changes.
- **Q&A:** your most common questions, with the answers you want given.
- **Documents:** up to 3 files of 3 MB each (PDF, TXT, DOCX or a CSV product list), such as a price list, size chart or returns policy. Use text-based files; a scan can't be read.

Changes are learned when you save. Be specific: "Ships to the US in 3 to 5 business days, free over $50" beats "Shipping is fast".

## Step 4: Set the agent's voice

On the agent's **Persona** tab:

- **Tone:** Neutral, Seller, Positive or Direct.
- **Agent Instructions** (up to 4,000 characters): reply length, words to use and avoid, what to say when the agent doesn't know.

On the **Replies** tab:

- **Replies to:** comments and messages, comments only, or messages only.
- **How soon:** immediately (default), within a few minutes, within an hour or within a day. On a new Facebook Page, *Within a few minutes* is the safer start.
- **Read the post** (Pro and Ultra): replies take the ad into account, so "how much?" gets the price of the product it shows.

## Step 5: Check moderation

Moderation is set per channel and in **Global rules**, the card at the top of **Channels**.

- **Banned words:** competitor names, rival domains, slurs. Up to 50 in Global rules and 50 more per channel. `scam` matches words that start with "scam", `*scam*` matches it anywhere, and `"scam"` only the whole word.
- **Spam & media filter:** hides comments with links, attachments or competitor mentions. Click the channel's row and switch it on under **Moderation**.
- **Filter by tone:** off by default. Leave it off unless your ads draw hostility; complaints should reach a person.
- **Moderation rules** (Pro and Ultra): write them in plain words, for example *hide comments that recommend another store*, and pick an action. Set **When a rule matches** to **Review first** while you test them, then **Apply automatically**.

The sign-up turns these on for the channels you pick. On a channel you add later, the Spam & media filter and Filter by tone start off, so check its row.

## Step 6: Go live

On **Channels**, pick an agent on the channel's row and switch on **Replies**. It saves at once; to do several channels, tick their rows and click **Enable AI**. Moderation runs even with Replies off, and only new comments are handled.

## Step 7: Check the first week

Every day, in the **Inbox**:

- [ ] Read the replies under **AI replies**; each shows the agent that wrote it.
- [ ] Check **Hidden or deleted** and unhide mistakes; each comment says why it was hidden.
- [ ] Clear **Needs attention**: complaints, urgent comments and rule matches (rule matches also have their own **Needs review** view).
- [ ] Add missing facts to the knowledge base.

| Problem | Fix |
|---|---|
| Wrong product facts | Update the knowledge base |
| Real comments hidden | Narrow the banned word (use quotes) or the rule |
| Replies too long or too formal | Adjust instructions or tone |
| The agent can't answer a common question | Add it as Q&A, or run **Suggest improvements** on the Persona tab |
| A topic the AI shouldn't touch | Add a **Don't reply** reply rule (Pro and Ultra) |

## Step 8 (optional): Connect an AI app or a script

On Pro and Ultra, the trial included, you can work with your comments outside the Inbox. In **Settings**, under **MCP and API Keys**, click **Connect** and pick Claude Code, Cursor, VS Code, Gemini CLI, or **Other app or API** for a script or data warehouse. You choose what the app may read, on which channels and for how long; hiding comments and changing moderation rules stay off unless you switch them on, and no app can reply or delete. Then ask it, for example, "What are customers complaining about this week?" More in [How to get Facebook, Instagram and TikTok ad comments through an API or MCP](https://www.rypl.is/blog/facebook-instagram-tiktok-comments-api).

## Step 9: Compare with your baseline

After two to four weeks, compare ROAS, cost per result, quality ranking and reply time with the numbers you noted before. The [ROI guide](roi-estimation-guide.md) explains how.


## More on rypl.is

- [How do I sign up for Rypl?](https://www.rypl.is/docs/getting-started/how-do-i-sign-up): the sign-up, step by step
- [How do I connect a Facebook Page to Rypl?](https://www.rypl.is/docs/getting-started/how-do-i-connect-facebook)
- [How do I connect TikTok ads to Rypl?](https://www.rypl.is/docs/getting-started/how-do-i-connect-tiktok-ads)
- [How do I turn on AI replies in Rypl?](https://www.rypl.is/docs/getting-started/how-do-i-turn-on-ai-replies)
- [How do I connect Claude Code, Cursor or another AI app to Rypl?](https://www.rypl.is/docs/api/how-do-i-connect-an-ai-app)
- [Facebook Comment Moderation Tool with AI Auto-Replies](https://www.rypl.is/facebook-comment-moderation-tool): how Rypl answers and moderates comments on Facebook ads and posts
- [Instagram Comment Moderation Tool with AI Replies](https://www.rypl.is/instagram-comment-moderation-tool): Instagram ads, posts and DMs
- [TikTok Ad Comment Moderation Tool with AI Replies](https://www.rypl.is/tiktok-comment-moderation-tool): comments on TikTok ads
- [How to auto-reply to Facebook comments](https://www.rypl.is/guides/auto-reply-to-facebook-comments): Meta's own options and where AI replies fit
- [How to See and Reply to Comments on Facebook Ads (2026 Guide)](https://www.rypl.is/blog/how-to-see-comments-on-facebook-ads): find every ad comment, dark posts included
- [Instagram Ad Comment Automation: The Complete Guide (2026)](https://www.rypl.is/blog/instagram-ad-comment-automation-guide): permissions, Reels and DMs
- [How to Manage Comments on TikTok Ads: The Complete Guide](https://www.rypl.is/blog/how-to-manage-tiktok-ad-comments)

---

**Need help?** See the [Rypl documentation](https://www.rypl.is/docs), the [Rypl Docs on GitHub Pages](https://rypl-ai.github.io/docs/), or email [hey@rypl.is](mailto:hey@rypl.is).

*Part of the [Facebook Ad Comment Automation Guide](../README.md) by [Rypl](https://www.rypl.is).*
