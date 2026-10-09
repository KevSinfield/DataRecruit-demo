# Synthetic candidate portraits (demo only)

These ten WebP files are **AI-generated photorealistic portraits of fictional adults**. They are not real candidates, not scraped, not stock photos and not likenesses of any real or famous person.

## Provenance
- **Supplied by Kev on 8 October 2026** as a single sheet of ten portraits (two rows of five, each captioned with a fictional candidate's name). The generation tool and its terms were not part of that request, so they are not recorded here.
- **Processing:** each portrait was cropped from the sheet (photograph only, caption excluded) to a centred square and saved as a 160 × 160 WebP at quality 80 (about 2.5 to 3.5 KB each), for avatars up to 64 px on high-density screens.
- **Earlier set:** five JPEGs generated on 2 October 2026 (`cand-00x.jpg`, git-ignored, no longer referenced) were switched off by decision D30 because permission to show them could not be documented. They are superseded by this set and are not used.

## Files and mapping
The mapping is by stable candidate id, in `src/lib/portraits.ts`, never by display name.

| Candidate | Id | File |
|---|---|---|
| Marcus Examplemann | ri-cand-1 | marcus-examplemann.webp |
| Sarah Mockwell | ri-cand-2 | sarah-mockwell.webp |
| Daniel Sampleton | ri-cand-4 | daniel-sampleton.webp |
| Avery Placeholder | cand-001 | avery-placeholder.webp |
| James Fixturton | ri-cand-3 | james-fixturton.webp |
| Jordan Mockley | cand-002 | jordan-mockley.webp |
| Sam Demonstrator | cand-003 | sam-demonstrator.webp |
| Alex Fixtureman | cand-007 | alex-fixtureman.webp |
| Quinn Trialson | cand-008 | quinn-trialson.webp |
| Robin Testwell | cand-005 | robin-testwell.webp |

Taylor Fakeman and Drew Sampleford have no portrait and show initials, as does any candidate whose image fails to load.

## Usage terms (checked 8 October 2026, decision D42)
- **Source:** Kev generated the ten portraits directly in ChatGPT with OpenAI's image generation, under his own ChatGPT account, specifically as fictional candidate avatars.
- **Terms read:** OpenAI Europe Terms of Use, https://openai.com/en-GB/policies/terms-of-use/ (updated 16 January 2026): "As between you and OpenAI, and to the extent permitted by applicable law, you ... own the Output. We hereby assign to you all our right, title, and interest, if any, in and to Output." Output may not be unique. The terms contain no ban on commercial or public use of Output; restrictions include infringing others' rights, representing Output as human-generated when it was not, and using Output to build competing models. OpenAI Usage Policies, https://openai.com/policies/usage-policies/ (effective 29 October 2025), forbid impersonation and using a real person's likeness or photorealistic image without consent in ways that could confuse authenticity.
- **Publication decision:** permitted on the public GitHub Pages demo, labelled as fictional and documented here as AI-generated.
- **Limits:** this relies on Kev's statement of origin (the files have no embedded provenance metadata); the portraits have not been checked for resemblance to any real person, and any image reported as resembling one is to be removed; this is not legal advice and the terms can change; the Europe edition was read from OpenAI's public site, not the account's own settings page.

## Rules
- Presentation only: portraits never influence matching, fit assessments, ranking, recommendations or any AI decision. No matching code reads them.
- Decorative: every avatar is hidden from assistive technology (`alt=""`, `aria-hidden`), because the name is always shown beside it.
- Local only: files are served from this folder; nothing is loaded from another host.
- Never add a real candidate's photo to this folder. Production photos would be optional, subject to appropriate data handling (`docs/specs/Data-Protection.md`, not complete), and would never influence matching.
