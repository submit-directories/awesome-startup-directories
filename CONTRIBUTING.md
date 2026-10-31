# Contributing to Awesome Startup Directories

Thanks for helping founders find better places to launch! This list stays useful only if it stays **accurate, live, and spam-free**, so please follow these guidelines.

## What belongs here

A site can be added if it:

- **Is live** and loads without errors at the time of your PR.
- **Accepts submissions** from third-party founders (a submit form, a launch flow, a vendor sign-up, or a community where sharing projects is allowed).
- **Serves a real audience** — launch platforms, directories, review sites, communities, marketplaces, galleries, or startup media.
- **Is not** a link farm, a parked/for-sale domain, a site that redirects to unrelated content, or a page that exists only to sell backlinks.

Paid directories are welcome — just mark them as `Paid` or `Freemium`.

## How to add an entry

1. Pick the most relevant category. If nothing fits, propose a new category in your PR description.
2. Add your row to the **end** of that category's table.
3. Use exactly this format:

   ```markdown
   | [Name](https://example.com) | One-line description, under ~90 characters. | Free / Freemium / Paid | Optional notes. |
   ```

   - **Name**: the site's official name, linked to its homepage (https, no tracking parameters, no referral links).
   - **Description**: neutral and factual. No marketing superlatives ("best", "#1") unless they're part of the name.
   - **Pricing**:
     - `Free` — submitting costs nothing.
     - `Freemium` — a free path exists, plus paid upgrades (e.g. skip-the-queue, featured spots).
     - `Paid` — no free way to get listed.
     - Leave it **blank** if you couldn't confirm it on the site's own submit/pricing page.
   - **Notes**: requirements (badge/backlink, account, queue time), audience, or limits. Any DR, traffic, or dofollow/nofollow claim must come from the site's own page or a public source — write it as "site states …". Never estimate or invent metrics.

4. One site per pull request, please. Fixes to existing entries (dead links, changed pricing) can be batched.

## Updating or removing entries

- **Dead or changed link?** Open a PR removing or fixing it, and mention what you saw (e.g. "domain for sale", "404 on submit page", "redirects to unrelated site").
- **Pricing changed?** Update the cell and add the month/year in Notes if a price is mentioned.

## Sponsors and self-promotion

Adding your own directory is fine if it meets the criteria above — please disclose that you're affiliated with it in the PR description. Sponsored entries are always labeled *(sponsor)*.

## Pull request checklist

- [ ] The link loads and points to the homepage (or the official submission page).
- [ ] The entry is in the right category, at the end of the table.
- [ ] Format matches the other rows; description is one line.
- [ ] Pricing/notes come from the site itself, or are left blank.
- [ ] I've searched the list to make sure it's not a duplicate.

## Code of conduct

Be kind and constructive. Reviews may ask for changes or decline entries that don't fit; it's never personal.

By contributing, you agree that your contributions are released under the [CC0 1.0 Universal](LICENSE) public domain dedication.
