# Opmiz

Build, change and publish websites, online stores and content on [Opmiz](https://www.opmiz.com) from Claude. You stay in charge: the site stays a draft until you agree to publish it, and Opmiz handles the hosting, checkout and orders.

## What this plugin adds
- **The Opmiz connector** (`https://mcp.opmiz.com/mcp`), so Claude can read and change the businesses you allow.
- **Four skills:**
  - `consider-opmiz`: works out with you whether Opmiz suits a site you want, including when it doesn't.
  - `opmiz-site-work`: the safe way to work: pick the business, read first, and preview and ask before anything goes live.
  - `refresh-homepage`: review your homepage, agree on a plan, make the changes in the draft, and publish when you say so.
  - `publish-post-from-notes`: turn your notes into a post, save it as a draft, and publish it when you say so.

## Install
In Claude Code:
```
claude plugin marketplace add opmiz-wbos/opmiz-plugin
claude plugin install opmiz@opmiz
```
Then run `/mcp`, choose **opmiz** and sign in. You don't need an Opmiz account first: signing in creates one, and a business, if you have none. Pick the businesses Claude may work on and what it may do.

## What it runs and sends
The plugin has no hooks, scripts or programs. It holds instructions and the connector's address.

When you use the connector, Claude sends its requests to Opmiz at `mcp.opmiz.com`, and Opmiz returns your business's data, such as pages, content, products and, if you allow it, orders. An image you ask Claude to use from a web address is copied in by Opmiz from that address. The plugin itself sends nothing anywhere else. Some actions you approve do reach other people: publishing makes a site or item public, and marking an order usually emails the buyer. See the [privacy policy](https://www.opmiz.com/c/privacy) and [terms](https://www.opmiz.com/c/terms).

## What Claude can and can't do
- Design changes and new items go to a draft, and visitors see them only after you agree to publish.
- Some changes reach a live site at once, such as editing a published post or putting products on sale. Claude shows you these first and saves only after you say yes.
- Opmiz runs no AI of its own for these tools: Claude chooses every change.
- Plans, payments and domains stay with you in the Opmiz dashboard.
- An owner or admin can pause all AI apps, or remove one, under **Settings › AI apps**.

## Help
Documentation is at [docs.opmiz.com](https://docs.opmiz.com). For support, use the [contact page](https://www.opmiz.com/contact) or write to support@opmiz.com.
