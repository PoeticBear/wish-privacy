# P01 preparation and R01 publication record

This branch is a **reviewable draft**, not a public policy deployment. Do not merge/push it to the Pages source or deploy until the final R01 approval. Base: `main` at `2d29e1fd59a4892ab0cedbb67c3b513d4588e0ab`; old index blob `f5ad3548dfa843d74dacef2922f0f2d01c3983b8`. No repository-specific AGENTS/CLAUDE instructions or workflow files existed in that baseline.

Prepared files: complete English `index.md`, materially equivalent Simplified Chinese `privacy-zh-Hans.md`, English `support.md`, Simplified Chinese `support-zh-Hans.md`. They describe the account-free code delivered through C14 in PoeticBear/wish-workspace. User originals, OS permissions, local cleanup, backup copies, support email and earlier Apple authorizations are kept distinct.

## Owner policy decisions and acceptance

- [x] Owner accepted the prepared English/Chinese policy/help diff on November 2, 2026 (Asia/Shanghai). Final-build reconciliation remains an R01 requirement.
- [x] Owner confirmed `sihang8973@gmail.com` as the monitored operator contact in the same approval. Mailbox responsiveness was not tested.
- [x] Owner approved support-only correspondence retained until manual deletion, with no fixed automatic retention period promised and deletion requests through the published address.
- [ ] Reconcile actual off-device support-email retention with App Store privacy answers and any optional-disclosure exemption. Local photo processing alone is not off-device collection. No unconditional “Data Not Collected” answer is approved by this branch.
- [ ] Record any final code/data-flow change and update both languages before publication.

Owner approval: “Approve the preparation diff and email practice.” This permits a focused preparation-branch commit/push only. Public deployment, actual effective-date insertion and final store disclosures remain R01 actions. The owner separately confirmed that the requested app artwork and animation are original; font/software licenses remain third-party conditions.

## Privacy-label handoff

C13 found no app photo upload, app cloud sync, behavioral analytics/ad SDK, tracking, broad library request, AI processing or private-photo widget sharing. First-party required-reason manifests declare actual local defaults and statically included Lottie file-metadata uses; a required-reason API is not itself a collected-data category.

User-initiated support email is different: the operator can retain sender address/body/selected attachments off device. Apple's [App Privacy Details](https://developer.apple.com/app-store/app-privacy-details/) defines collection by off-device access/retention, and permits optional disclosure only when every applicable condition is met. Do not assume external email or absence of an app account automatically exempts it. S01 must record whether that exemption is substantiated; otherwise prepare the relevant email/user-content support declarations, no tracking. This website's hosting security logs are disclosed separately from the app's local data flow.

## Expected public URLs — not claimed live in this draft

- English privacy / existing app policy URL: https://poeticbear.github.io/wish-privacy/
- Simplified Chinese privacy: https://poeticbear.github.io/wish-privacy/privacy-zh-Hans.html
- English support: https://poeticbear.github.io/wish-privacy/support.html
- Simplified Chinese support: https://poeticbear.github.io/wish-privacy/support-zh-Hans.html

Use these exact `.html` paths in cross-links; GitHub Pages Markdown rendering/URLs must be checked after approved deployment. No HTTP 200 for a new draft URL is asserted here. The app's existing privacy root stays stable, and native Help remains usable without waiting for this site.

## R01 deployment/read-back — not performed

1. Verify the final app artifact/version/build/source, actual QA/media acceptance, rights inventory and policy/label approval. Update this diff if final behavior differs.
2. Confirm actual Pages source configuration and any deployment workflow. Do not assume a branch named main is the serving source without reading the settings/last deployment at delivery time.
3. On the approved publication change, replace **every** `PUBLICATION_DATE_PENDING` with the actual publication/effective date, update both languages, and remove the `DRAFT_NOT_PUBLISHED` preparation banners and “does not replace” draft text. Do not backdate to September, planning day or an unobserved release date. Record publication and app availability separately if they differ.
4. Review the exact final diff; deploy only through the approved R01 action. Record source commit, date/time, Pages deployment ID/state and actual served-page result. Do not merge a document containing unresolved publication markers.
5. Open all four public URLs on phone and desktop. Record response status, visible title/date/body, language parity, links/contact and absence of current AI/account/blessing claims. Inspect rendered tables, narrow layouts, code markers and browser caching. A repository diff is not proof of the served page.
6. Verify both Apple help links and website privacy links. Apple manages prior authorization; test neither automatic revocation nor a new login to clear local records. Verify mailto opens the intended address; never send an unsolicited test email.
7. In App Store Connect, save/read back the approved policy and support URLs independently. Verify Review Notes, privacy labels, media, attached Build ID and availability against the final package; a published policy alone does not perform these actions.
8. Record remaining failures and stop submission until required read-backs/acceptance are complete. Submission, approval and public availability are distinct later observations.
