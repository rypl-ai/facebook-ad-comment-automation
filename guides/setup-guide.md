# Step-by-Step Setup Guide for Facebook Ad Comment Automation

[Back to Main Guide](../README.md) | [Best Practices](best-practices.md) | [ROI Guide](roi-estimation-guide.md)

---

This walkthrough uses [Rypl](https://www.rypl.is) as the example tool, but the general process applies to any comment automation platform. The setup takes approximately 15-30 minutes.

## Prerequisites

Before you start, make sure you have:

- An active Facebook Page connected to your ad account
- Admin access to that Facebook Page
- At least one ad campaign currently running (so you can test with real comments)
- Your product/service information ready to upload (catalogs, FAQs, policies)

## Step 1: Create Your Account

Sign up at [app.rypl.is/signup](https://app.rypl.is/signup). All plans include a 7-day free trial — no credit card required to start.

**Choose your plan based on your needs:**

| If you... | Recommended Plan |
|---|---|
| Run 1 Facebook Page, getting started | Simple ($19/mo) |
| Run up to 20 pages, need AI intelligence | Pro ($49/mo) |
| Run an agency with unlimited clients | Ultra ($89/mo) |

You can always upgrade later. Start with Simple if you want to test the waters.

## Step 2: Connect Your Facebook Page

After creating your account, you will be prompted to connect your Facebook Page through Meta's OAuth flow:

1. Click "Connect Facebook Page"
2. Log in with your Facebook account (must have admin access to the Page)
3. Select which Pages you want Rypl to manage
4. Grant the requested permissions

**Permissions explained:**

- **Read page content**: Allows the tool to see comments on your ads and posts
- **Manage page conversations**: Allows the tool to respond to comments and hide spam
- **Read page insights**: Allows the tool to access engagement metrics

All access is through the official Meta Graph API. Your credentials are never stored — the tool receives an access token from Meta directly.

**Troubleshooting connection issues:**

- Make sure you are an admin (not just an editor) of the Facebook Page
- If the Page does not appear in the list, check that it is published and not restricted
- Try disconnecting and reconnecting if you recently changed Page roles

## Step 3: Prepare and Upload Your Knowledge Base

This is the most important step. The quality of automated replies depends entirely on the quality of the information you provide.

### What to Upload

**Product catalog** (recommended: PDF or CSV)
- Product names, descriptions, prices
- Available sizes, colors, variants
- Stock status / availability
- Key features and specifications

**FAQ document** (recommended: CSV with Question and Answer columns)
- Top 20-50 questions customers ask
- Clear, concise answers for each
- Include questions about shipping, returns, sizing, compatibility

**Brand voice guidelines** (recommended: TXT)
- Your brand's tone (casual, professional, friendly)
- Phrases you commonly use
- Phrases or terms to avoid
- How to handle different types of inquiries

**Shipping and return policies** (recommended: TXT)
- Delivery timeframes by region
- Shipping costs or free shipping thresholds
- Return window and conditions
- Refund processing time

**Website URL**
- Your store or landing page
- The AI can reference this for real-time product data

### Tips for Better Knowledge Base

- Be specific: "Shipping takes 3-5 business days to US addresses" is better than "Shipping is fast"
- Keep information current: remove discontinued products, update seasonal promotions
- Include pricing: if the AI does not know prices, it cannot answer the most common question
- Cover edge cases: what happens if an item is out of stock? what about international orders?

## Step 4: Configure Brand Voice

Set the parameters for how the AI communicates with your audience:

**Tone**: Choose between casual, balanced, or professional. Most e-commerce brands work best with "balanced."

**Response length**: Set a target length for replies. For ad comments, 1-3 sentences is ideal — long responses get ignored in comment threads.

**Language behavior**: The AI automatically detects the language of each comment and responds in the same language. If you serve specific markets, you can prioritize certain languages.

**Custom instructions**: Add any specific guidance:
- "Always include a link to our store when answering product questions"
- "Never discuss competitor products"
- "Use the customer's first name if they mention it"
- "Include emoji sparingly" or "Do not use emoji"

## Step 5: Set Moderation Rules

Define what should be automatically hidden:

### Default rules (recommended to keep enabled)

- Profanity and offensive language
- Spam patterns (repeated text, excessive links, promotional comments)
- Known bot patterns

### Custom rules to consider

- **Competitor brand names**: Hide comments mentioning specific competitors
- **Negative keywords**: Industry-specific terms that indicate harmful content
- **URL patterns**: Block links to competing stores or irrelevant websites
- **Sensitivity level**: Adjust how aggressively the moderation filters content (start moderate, adjust based on false positive rate)

### What NOT to hide

- Legitimate complaints (these need a response, not suppression)
- Questions that seem negative but are genuine inquiries
- Comments in languages you do not recognize (the AI handles multi-language natively)

## Step 6: Activate Your AI Agent

Enable automated replies and moderation:

1. Select which Facebook Pages to activate on
2. Choose which ad campaigns to include (start with one to test)
3. Enable moderation (spam hiding)
4. Enable auto-replies
5. Set operating hours (24/7 recommended — this is the whole point)

**Recommended approach**: Start with a single campaign that receives moderate comment volume (20-50 comments/day). This gives you enough data to evaluate performance without risking your highest-performing campaigns during the learning period.

## Step 7: Monitor and Optimize (First Week)

The first week is critical. Plan to spend 15-20 minutes per day reviewing the automation's performance.

### Daily checklist

- [ ] Review all automated replies from the past 24 hours
- [ ] Check hidden comments for false positives (legitimate comments incorrectly hidden)
- [ ] Note any questions the AI answered incorrectly or incompletely
- [ ] Check response time metrics (should be under 60 seconds)
- [ ] Compare ad quality metrics to your pre-automation baseline

### Common first-week adjustments

| Issue | Solution |
|---|---|
| AI gives incorrect product info | Update knowledge base with correct data |
| Too many comments being hidden | Lower moderation sensitivity |
| Legitimate complaints being hidden | Add exceptions to moderation rules |
| Replies are too long/short | Adjust response length in brand voice settings |
| Replies sound too formal/casual | Adjust tone settings or provide example replies |
| AI cannot answer certain questions | Add that information to knowledge base |

### After the first week

- Expand to additional campaigns
- Reduce review frequency to every other day, then weekly
- Start tracking ROAS and CPC improvements against your baseline
- Update the knowledge base as you discover new common questions

## What to Expect

### First 24 hours

- The AI begins responding to new comments on activated campaigns
- Spam and negative comments start getting hidden
- You will see response time drop dramatically

### First week

- AI reply quality improves as it processes more context from your knowledge base
- You will identify gaps in your knowledge base content
- Comment threads start looking cleaner and more engaging

### First month

- Expect approximately 10% improvement in ROAS from combined moderation and reply effects
- Ad quality scores should begin improving in Ads Manager
- Your team has significantly more time freed up from manual comment management

---

**Need help?** Visit the [Rypl Documentation](https://rypl-ai.github.io) for detailed guides on every feature, or contact [hey@rypl.is](mailto:hey@rypl.is).

*Part of the [Facebook Ad Comment Automation Guide](../README.md) by [Rypl](https://www.rypl.is).*
