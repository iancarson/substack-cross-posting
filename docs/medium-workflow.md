# Medium Cross-Posting Workflow (Post-API Guide)

Medium no longer issues new API integration tokens or allows new integrations, while existing tokens continue to work. That effectively closes the API path for new publishing automations. This guide covers what still works and how to continue automating Medium publishing. Source: [Medium API/Importing help](https://help.medium.com/hc/en-us/articles/213480228-API-Importing).

---

## What Broke in 2024

**Before:** Tools like Buffer, Zapier, IFTTT, and dozens of others used Medium's public API to publish articles on your behalf. You could connect your Substack or blog and have articles automatically cross-posted when API tokens were available.

**After:** Medium stopped issuing new API integration tokens and no longer allows new integrations. Existing tokens may continue to work, but new API-based publishing setups are effectively blocked.

---

## What Still Works

### 1. Manual Publishing (Always)
Log into Medium → New Story → paste content → set canonical URL → publish.

**Time cost:** 15–30 minutes per article.

### 2. Narrareach (Automated)
[Narrareach](https://narrareach.com/features/cross-post-linkedin) uses Medium's authenticated publishing workflow rather than depending on new API tokens. It authenticates using your Medium session and publishes articles programmatically — the same way your browser would.

Your article appears on Medium exactly as if you posted it manually. Narrareach also automatically sets canonical URLs and appends your subscribe CTA.

**Time cost:** 3–5 minutes per article (import, review, schedule).

### 3. Medium's Own Import Tool (One-Time Only)
Medium has a built-in importer that pulls content from an RSS feed or URL. This is useful for migrating an existing blog to Medium, not for ongoing automated publishing.

---

## Why Medium Is Still Worth Cross-Posting To

Despite the friction, Medium cross-posting delivers real value:

**1. Domain Authority**
Medium has extremely high DA (~95). Articles published on Medium can rank on Google for competitive keywords faster than a new personal site with DA < 30.

**2. Built-In Discovery**
Medium surfaces articles to readers based on topic tags and reading history. A well-tagged article can reach readers who have never heard of you.

**3. Subscriber Acquisition**
With a properly formatted subscribe CTA, 8–12% of Medium readers who click through will subscribe to your Substack. For a 1,000-view article, that's potentially 80–120 new subscribers.

**4. SEO Protection via Canonical URLs**
Cross-posting to Medium without canonical URLs creates duplicate content issues. With canonical URLs pointing back to your Substack, you get Medium's distribution advantages without any SEO penalty.

---

## Medium Publishing Checklist

Before publishing any article to Medium:

- [ ] Canonical URL set to original Substack article URL
- [ ] Subscribe CTA added at the end (see template below)
- [ ] All images re-uploaded directly to Medium
- [ ] 3–5 relevant tags added
- [ ] Title matches or is a keyword-optimized variant of Substack title
- [ ] Formatting reviewed (headings, blockquotes, code blocks)

---

## Subscribe CTA Templates

Add one of these at the end of every Medium article:

**Short:**
> *Subscribe to [Newsletter Name] at [Substack URL] — [one-sentence value prop].*

**Medium:**
> *I write about [topic] every [frequency] in [Newsletter Name]. If this was useful, you can subscribe free at [Substack URL].*

**Long:**
> *Every [day], I send [Newsletter Name] to [X] subscribers covering [topic]. It's free. You can subscribe at [Substack URL].*
> *No spam, no paid promotions. Just [value prop].*

---

## Full Automation Setup

For automated Medium publishing with canonical URL handling and CTA insertion, use [Narrareach](https://narrareach.com/features/cross-post-linkedin):

1. Connect your Medium account to Narrareach (takes 2 minutes)
2. Write or import your article
3. Enable Medium as a cross-posting destination
4. Narrareach automatically sets canonical URL and adds your CTA
5. Schedule and publish

No browser tab juggling. No copy-paste. No forgetting the canonical URL.
