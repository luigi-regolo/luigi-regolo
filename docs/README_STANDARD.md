# GitHub README Standard — luigi-regolo

Version: 1.0

## 1. Purpose and scope

This document defines a consistent README standard for public repositories maintained by luigi-regolo. It covers layout, language, author attribution, badges, licensing, privacy, technical accuracy, and publication review.

Apply it to existing repositories when they are explicitly selected for review and to new repositories from the start. Adapt technical sections to the actual project type; do not introduce irrelevant content or change functioning code merely to make documentation consistent.

## 2. Language and approval

* Publish public project READMEs in English.
* Before any README is created, rewritten, or published, present the complete proposed text or changes translated into Italian for owner review.
* Obtain explicit approval before committing, pushing, creating a release, or otherwise publishing changes.
* Explain what will change and what will remain untouched.
* Use verified information only. Never invent version numbers, compatibility, features, HACS status, or support commitments.

## 3. Public project identity

* GitHub author/maintainer identifier: luigi-regolo.
* TikTok identifier: @Luigi.regolo.
* Use luigi-regolo as the standard public author attribution when appropriate to the actual copyright ownership.
* Do not unnecessarily publish a legal name, personal email address, location, private system details, or other personal information.
* Do not remove or misattribute copyright notices belonging to other contributors or third parties.

## 4. README structure

Use these sections, in this order, wherever applicable:

1. Project name: Official name as the main heading.
2. Badges: Consistent badges directly below the project name.
3. Overview: Concise, accurate description.
4. Preview: Real screenshots or a demonstration, when useful.
5. Features: Functionality that actually exists.
6. Installation: Tested, up-to-date installation steps.
7. Configuration / Usage: Only instructions relevant to the project.
8. Compatibility / Requirements: Confirmed dependencies and minimum versions.
9. Releases: Link to the project’s GitHub Releases, when available.
10. Copyright & License: Correct ownership statements and applicable license.

Omit non-applicable sections. Do not add a generic Reports, Bug reports, Issues, or Support requests section unless separately approved. Removing a README section does not mean disabling GitHub Issues.

## 5. Badge standard

Use a visually consistent, compact badge style (prefer flat-square), with working destinations. The order is:

1. TikTok: Reuse the exact TikTok badge design already approved for the other repositories; link to @Luigi.regolo.
2. Release: Dynamic badge linked to the latest published GitHub Release; omit when no release exists.
3. License: Show the project’s actual verified license, not an aspirational license.
4. HACS: Use only where relevant; distinguish a custom repository from a repository accepted into the HACS default catalog. Do not claim acceptance while a pull request is pending.
5. GitHub Stars: Dynamic count linked to the repository.

Optional: HACS validation badge, but only if a corresponding GitHub Actions workflow really exists and its status is accurate.

Never fabricate data, use badges that falsely imply official endorsement, or include decorative counters and unrelated statistics. Verify badge links and rendering before publication.

## 6. Standard software license and copyright

The default license for original public software projects is GNU General Public License version 3 only, SPDX identifier GPL-3.0-only.

Before applying or changing a license, review:

* Copyright ownership, prior publication, and any third-party or community contributions.
* Third-party dependencies, copied source, fonts, images, documentation, and other bundled assets.
* Existing license notices and compatibility with the intended distribution.
* The distinction between GPL-3.0-only, GPL-3.0-or-later, and other existing permissions.

Keep the official, unmodified full GPL v3 text in LICENSE for repositories using this license. Make the version-3-only permission explicit in the project’s licensing notice and, where appropriate, source headers: the license text by itself is not a substitute for checking which versions are authorized.

Where accurate, use the following README attribution, updating the year and any additional rightsholders:

Copyright © YYYY luigi-regolo
Original project created and maintained by luigi-regolo.
Licensed under the GNU General Public License version 3 only (GPL-3.0-only). See LICENSE for the full terms.

This standard does not transfer third-party copyright to luigi-regolo. A public GitHub username is an attribution identifier, not by itself proof of legal ownership. Preserve applicable contributor notices and provenance.

The GPL allows commercial use and redistribution subject to its terms, and requires preservation of applicable copyright notices in redistributed copies. It does not require users merely running the software to publicly advertise or credit the author.

The GPL license itself has no license fee or recurring charge. Its warranty disclaimers and limitations of liability apply only to the extent permitted by law: no license eliminates all legal risk. GitHub or third-party paid services are a separate matter; never enable paid services or change spending controls without explicit approval.

Existing repositories: Do not silently replace an existing MIT or other license, and do not purport to revoke licenses already granted for earlier releases. Check the legal and technical implications repository by repository before any update. Non-software repositories, including profile/documentation-only repositories, require a separate licensing assessment; do not impose a software license mechanically.

## 7. Versions and releases

* Use the approved concise numbering convention, such as 1.0 → 1.1 → 1.2 → 2.0; do not automatically impose 1.0.0.
* Display the actual tag/version of the published release rather than silently changing its format.
* Use GitHub Releases as the source for release badges. Do not present an unpublished draft, tag alone, or planned version as a published release.
* Do not rewrite existing release tags or history for cosmetic reasons.

## 8. Screenshots and media

* Prefer genuine screenshots that demonstrate the real project.
* Keep preview widths, proportions, and presentation consistent across related Home Assistant cards without altering the underlying interface unnecessarily.
* Ensure reasonable readability on desktop, mobile, and tablet.
* Remove private floor plans, addresses, credentials, camera images, access details, sensitive entity IDs, and other personal data before publication.
* Use only media that you have the rights to distribute, with any required attribution.

## 9. Home Assistant and HACS

For relevant repositories:

* Verify installation instructions, hacs.json, release packaging, Home Assistant compatibility, and supported configuration methods against the actual repository and current HACS requirements.
* Clearly distinguish manual installation, HACS custom repository, and HACS default-catalog inclusion.
* A successful validation workflow or an open HACS pull request does not equal inclusion in the default catalog.
* Keep GitHub Issues enabled where required by the current HACS default-catalog checks, even when the README does not contain an Issues section.
* Publish only verified minimum versions, limitations, and compatibility claims.

## 10. Privacy, security, and costs

Before publication, check README text, linked files, images, and examples for exposed API keys, tokens, passwords, secrets, personal details, infrastructure identifiers, real IP addresses, private URLs, logs, and Home Assistant instance details.

Do not include copyrighted third-party material without suitable permission. Do not claim that the software is perfectly secure, risk-free, officially endorsed, or guaranteed compatible.

A README update must not enable paid APIs, subscriptions, GitHub billing features, cloud resources, or workflows with possible costs without separate, explicit owner approval and a cost review.

## 11. Change and publication checklist

Before changing a README:

1. Read the current README and related files.
2. Check the actual license, ownership notices, release, dependencies, and relevant HACS state.
3. Identify only the necessary documentation changes.
4. Provide the proposed English text and full Italian translation for approval.
5. Confirm the precise scope and obtain explicit owner approval.
6. Apply only the approved changes; leave source code, releases, GitHub settings, and HACS pull requests untouched unless separately authorized.
7. Review GitHub rendering, badge URLs, screenshots, install instructions, licensing language, and privacy.
8. Report the actual changes and any outstanding risks or exceptions.

Avoid unnecessary edits to recently published repositories. Any exception requires specific prior approval.

## 12. Standard maintenance and exceptions

Treat this document as the shared source of truth for README work. Changes to the standard require owner review and approval. Keep the GitHub copy and ChatGPT Project source file synchronized after each approved revision.

Where a legal, technical, privacy, or platform requirement conflicts with this standard, pause, explain the conflict, and request approval for a documented exception rather than forcing uniformity.

## Official references

* [GNU GPL v3 — full license](https://www.gnu.org/licenses/gpl-3.0.en.html)
* [SPDX: GPL-3.0-only](https://spdx.org/licenses/GPL-3.0-only.html)
* [HACS publisher requirements](https://www.hacs.dev/docs/publish/start/)
* [HACS default-catalog requirements](https://www.hacs.dev/docs/publish/include/)
* [Shields.io](https://shields.io/)
