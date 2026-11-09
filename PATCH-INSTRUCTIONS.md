# Sitewide client-facing copy patch

This package contains a complete updated `index.html` for the homepage and replacement public-copy blocks for the new canonical service pages.

For `index.html`, replace the repository file directly.

For each nested service-page file, retain that page's existing `<head>`, navigation, lead form, TREC disclosure strip, footer, GA4, and scripts. Replace the content from the opening `<section class="page-hero">` through the end of the last informational content section immediately before the lead form with the corresponding content in this patch.

Do not copy internal strategy comments into public HTML. Analytics identifiers such as `generate_lead` may remain in JavaScript because they are not visitor-facing.

Commit message: `Remove internal strategy language from public copy`
