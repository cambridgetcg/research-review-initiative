# Research review initiative

A separate working repository for evidence-led reviews in mathematics, machine
learning and algorithms. The first case examines a fixed-point proof, tests a
simple instance of its algorithm, and offers a precisely scoped repair.

**Preparation stage.** The public name, legal form, jurisdiction, accountable
correspondent and outside reviewer are not yet selected. This repository does
not establish incorporation or an independent editorial board. Its current
work was prepared by the same operator's agents that develop Zerone; this
relationship is disclosed, not removed by creating a separate repository.

## First review

Read [the technical manuscript](reports/2026-001-demimetric-audit/v0.1/REPORT.md)
and its [reading copy](reports/2026-001-demimetric-audit/v0.1/REPORT.pdf).
The accompanying verifier and source inventory make the bounded checks
repeatable. The report distinguishes exact counterexamples, an explicitly
interpreted algorithm, a repaired auxiliary lemma, and remaining uncertainty.
It is a draft for outside scrutiny, not an externally reviewed publication.

The [complete verification packet](reports/2026-001-demimetric-audit/review-2026-001-v0.1.zip)
is 202,496 bytes. Its SHA-256 is
`a6acae284ebbc8d41964f610e0bfb8d80755b320ef850ba8f9dbdc32dc4ba697`.

## Coordinate follow-up

The [translation note](reports/2026-001-demimetric-audit/followups/translation-v0.1/NOTE.md)
and [three-page reading copy](reports/2026-001-demimetric-audit/followups/translation-v0.1/NOTE.pdf)
explain why changing coordinate zero changes the origin-damped algorithm's
physical answer in a simple case. A proposed convex update removes that bias,
but a further counterexample shows it can still select the wrong solution.
The candidate remains unaccepted as a general repair.

The separate follow-up includes an exact rational checker, stored results,
an SVG figure and internal review. Its `verify_packet.py` checks the file
inventory and hashes; reproduction instructions are in the note. The original
review packet and archive remain unchanged.

## Restricted repair

The [restricted theorem](reports/2026-001-demimetric-audit/followups/restricted-repair-v0.1/NOTE.md)
and [four-page reading copy](reports/2026-001-demimetric-audit/followups/restricted-repair-v0.1/NOTE.pdf)
state sufficient assumptions under which the composite preserves exactly the
common solution set and the declared iteration converges in norm. The proof
handles small inertial input errors without assuming that the original maps
are pairwise nonexpansive. It also explains when the relaxation boundary is
admissible and retains the earlier counterexamples outside these conditions.

The packet includes exact finite checks, primary-source attribution and
internal review. This is a conditional replacement result awaiting outside
review; it does not validate the original article or establish novelty.

## Organisation

The [proposed charter](organisation/CHARTER.md) sets out scope, control, funding,
conflicts, attribution and corrections. The [case workflow](organisation/WORKFLOW.md)
connects a technical question to a review, author reply and recipient-specific
correspondence. [Current status](organisation/STATUS.json) records what exists
and what remains undecided. No outgoing message is queued by these documents.

Reviewers are credited for the work they actually do. Payment and case
selection must not reward accusation counts or particular conclusions. An
outside review requires a separately controlled reviewer and disclosed
conflicts; multiple agents of the same operator are internal checks.

## Relation to Zerone

Zerone's [Research Review reader](https://zerone.ai/research/review/) can display
local contribution history and dependencies. The journal can retain a claim,
concern, repair and conflicting assessments without erasing earlier records.
It currently checks hash consistency, not scientific truth, verified identity
or independent timestamps. This initiative needs no new chain module, token,
reward scheme, service or runtime dependency.

The [first public research checkpoint](https://zerone.ai/research/checkpoints/)
preserves the original 81-record journal and exact copies of all three research
packets. A 501-byte signed bank self-send commits to that journal on `zerone-dev-1`
at height **183706**, transaction
`8DFC740C5326E76B482B6D370F527311CB518934D6B64A4BF5EFDBD2806D0B8E`.
The saved proof verifies the account signature, transaction inclusion and the
original development validator signature; linked height 183707 binds successful
execution, data and gas. The net cost was the advertised `2000000uzrn` development
fee. These funds have no promised value.

The chain holds the journal's digest commitment; the full records and proofs are
downloadable separately. This is a single-operator development storage trial,
not a native scientific Fact, timed review round, independent endorsement or
historical-authorship proof. Earlier failed candidates remain in the journal.
One original internal receipt contained private paths; its public sanitized
derivative is explicitly distinguished by hash in the evidence index.
Organisation drafts, private correspondence and source-paper PDFs remain outside
the public packet. This repository remains private.

## Working records

Preserve versioned reports and disclose substantive corrections. Keep source
rights, private correspondence and identity information explicit. The first
packet links to publisher sources and binds their retained bytes by hash;
access to a paper does not automatically grant redistribution rights.

These files are working drafts. No institutional endorsement, domain ownership,
legal status, funding award or human authorship is claimed.
