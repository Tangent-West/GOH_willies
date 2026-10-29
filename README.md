# Willie’s Remedy · Plan. Don’t Ban.

Campaign working plan · November 10–December 10, 2026 · Draft for team review

Build on the supplied Willie’s campaign kit to turn awareness into completed Tell Congress actions. Lead with Willie’s farmer legacy, explain the people behind hemp, and finish with a clear invitation to act and share.

## Campaign direction

**Message:** Plan. Don’t Ban. Keep the good growing.

**Primary action:** Review, personalize, and submit a message through the campaign’s Tell Congress experience. The source kit links to [Congress Plus](https://www.congressweb.com/nationalhempassociation/TakeAction/oneAction/lettergroupid/3) and [The Goodness of Hemp](https://thegoodnessofhemp.org/). These are supplied destinations, not independently verified here.

**Creative approach:** Reuse the supplied Willie photography, black and cream palette, GOH lime, and rounded navy CTA treatment. Keep one main action per placement. Use the four social treatments as repeatable anchors and keep carousel slides in their supplied order.

**Channels:** Six emails, supporting Instagram and Facebook posts, carousel reshares, and stories. Use Instagram’s bio link and the direct action link on Facebook. Adapt the supplied feed artwork for stories before posting.

## Email and creative calendar

Dates and creative pairings below come from the supplied campaign plan. Countdown wording is provisional until the campaign owner confirms the deadline.

| Date, 2026 | Purpose | Supporting social creative | Email package |
|---|---|---|---|
| Nov 10 | Launch through Willie’s farmer legacy | Treatment 1: Willie’s Legacy; full carousel | [Launch](assets/03-Dated-emails/01-November-10/) |
| Nov 17 | Show the farmers and businesses behind hemp | Treatment 4: Keep the Good Growing; carousel slides 2–3 | [Farmer story](assets/03-Dated-emails/02-November-17/) |
| Nov 24 | Thank farmers and invite participation | Treatment 2: Farmers and Freedoms | [Thanksgiving](assets/03-Dated-emails/03-November-24/) |
| Dec 1 | Begin the proposed final countdown | Treatment 3: Make Your Mark | [Countdown](assets/03-Dated-emails/04-December-01/) |
| Dec 8 | Remind people who have not acted | Treatment 1 or carousel slide 4 | [Final reminder](assets/03-Dated-emails/05-December-08/) |
| Dec 10 | Make the final planned ask | Carousel slide 4 or Treatment 3 | [Final send](assets/03-Dated-emails/06-December-10/) |

Support with the full carousel November 12, farmer story November 19, community thanks November 26, carousel reshare December 3, and a story reminder December 9. These supporting dates follow the source plan; they are not scheduled posts.

## Participation and measurement

Use Willie’s eligible, opted-in audience and established email send time. Where action completion data is available through an agreed consent and matching process, thank completed participants and ask them to share. Use final reminders for people who have not completed the action.

Primary result: completed Tell Congress actions. Supporting measures: delivered emails, unique action clicks, click-to-completion rate, and completions by email or social source. Confirm source tracking survives into the action-platform export before reporting attributed results. If completion data is unavailable, report clicks separately and do not call them completed actions.

## Details to resolve before launch

- Campaign partner: Willie’s Remedy, as confirmed by the project owner. Original kit artwork and copy remain preserved unchanged.
- Confirm the legislative status and actual deadline before using the source’s December 11 claims or countdown graphics. Policy language is preserved from the kit and has not been independently verified in this handoff.
- The source promotes a Willie Nelson signed-bottle giveaway. Confirm the promotion details, entry mechanism, eligibility, rules URL, and dates before using those lines.
- Replace email preference and unsubscribe placeholders with the email provider’s live links. Check rendering and every CTA in that provider.
- Keep seasonal product notes secondary to advocacy, as in the November 24 and December 1 source emails.
- If the deadline or legislative situation changes, pause countdown content and replace it with a verified update and useful next action.

## Asset reference database

[Browse all 53 assets](ASSET-CATALOG.md). The catalog includes stable asset IDs, categories, dates where supplied, relative file paths, formats, file sizes, PNG dimensions, SHA-256 checksums, and draft status.

- [JSON database](asset-catalog.json): portable data for future integrations.
- [SQLite database](asset-catalog.sqlite): local queries with no server or account required.
- [Original plan](assets/02-Campaign-plan/Willies-November-December-Campaign.docx).
- [All email copy](assets/02-Campaign-plan/all-email-copy.txt).
- [Social captions](assets/04-Social/willies-social-captions.txt).
- [Source kit notes](assets/README.txt).

Example SQLite query:

```sql
SELECT id, name, path, send_date
FROM assets
WHERE category = 'Dated email'
ORDER BY send_date, name;
```

No audience records or giveaway entrant data belong in this public asset catalog.

## GitHub access

Repository: [Tangent-West/GOH_willies](https://github.com/Tangent-West/GOH_willies).

Browse the campaign plan here and open the linked asset catalog for individual files. Download HTML files to view their designs locally; GitHub file views display their source.

Each asset has a relative link that works in GitHub. Direct download URLs follow:

```text
https://raw.githubusercontent.com/Tangent-West/GOH_willies/main/assets/<asset-path>
```

Use the exact path from the JSON catalog, excluding its initial `assets/`, and URL-encode spaces. The SQLite file is downloadable; GitHub does not provide a hosted SQLite query service.

## Provenance

All 53 files under `assets/` were extracted unchanged from the October 29 revision of `Willies-Plan-Dont-Ban-Campaign.zip`. The revised team-supplied photographs replace the earlier concert photography throughout the email and social exports. Final artwork remains for team review. The overview and catalogs organize that source material. Original filenames, copy, and graphics are preserved. No campaign emails, social posts, or action submissions have been sent.
