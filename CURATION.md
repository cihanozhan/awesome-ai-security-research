# Curation policy

## Selection

Include a source when it explains an AI security threat, defense, relevant privacy risk, evaluation method, standard, or structured learning exercise. Prefer original papers, author manuscripts, publisher proceedings, official institutional documents, and the original maintainers of an educational application. An entry should explain what a reader can learn from it.

Select foundational work, useful surveys, representative attack families, critiques of evaluation, and newer work that extends a clearly stated threat model. Recency and citation count alone are insufficient selection criteria.

## Evidence and limits

Titles, source identities, and topical relevance were checked using primary pages, author manuscript records, available abstracts, and report cover pages. This initial curation is not a full-text systematic review, independent reproduction of every experiment, or endorsement of each paper's claims.

A `Paper`, `Survey`, or `Benchmark paper` type describes the source's role. It does not assert peer review. An arXiv link can point to a preprint or an author version of published work. Publication status must be separately confirmed before adding a venue or peer-review claim. The initial registry does not provide a complete peer-review-status field.

An arXiv source year denotes first submission. Other source years use available source metadata or the stated document edition. Missing dates are left empty rather than inferred. Versionless manuscript links may resolve to revisions with changed titles or results.

Link checking confirms a reachable primary record or identifies a retrieval limitation. It does not establish full-text access, scientific validity, safe deployment, or continued availability of a hosted exercise. The validation report distinguishes direct retrieval from web retrieval and publisher-index verification.

## Taxonomy

Categories intentionally overlap across model families and attack surfaces. A paper about federated backdoors belongs in both federated learning security and poisoning. A benchmark may also appear under the system it evaluates. Each source appears at most once within a category and has one record in the central registry.

Keep important distinctions visible:

- Model extraction concerns functionality or model information; training-data extraction concerns private examples.
- Membership inference is different from reconstruction and embedding inversion.
- Prompt injection crosses an instruction/data trust boundary; jailbreaking targets a model's behavioral safeguards.
- Adversarial robustness, ordinary corruption robustness, and general safety are different evaluation targets.
- A controlled research demonstration is not automatically a confirmed production incident.
- International standards, group reports, government guidance, and community frameworks have different authority and scope.

## Counts and duplicates

Each knowledge category must retain at least 25 distinct sources. Practice collections are exempt from that floor. Count a paper once even if it has an arXiv page, a DOI, a PDF mirror, code, and multiple revisions. Separate standards documents can have separate records. A competition's research paper and its rules archive can be separate sources because they serve different reading purposes.

Report both global unique-source counts and category placements. Never present the sum of category counts as globally unique papers.

## Knowledge-only boundary

Do not add stand-alone attack tools, testing frameworks, model scanners, product directories, or installation guides as research entries. Papers that introduce such methods can qualify through their scientific contribution. Intentionally vulnerable educational applications belong only in their dedicated learning collection unless a separate research paper independently qualifies elsewhere.

## Maintenance

Recheck changed titles and URLs before accepting edits. Preserve source IDs when updating a link or manuscript title. Add an access note when a publisher restricts full text. Record a check date and evidence method. Retain historical standards only with explicit edition information. Check the issuing organization before making any claim about current applicability or supersession.

All maintained descriptions, category names, contribution text, and metadata prose must be in English. Preserve official English source titles and proper names.
