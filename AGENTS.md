# PFIC4 Research Packet Instructions

## Project purpose
- This repo is a personal research packet about PFIC4, also called TJP2-associated progressive familial intrahepatic cholestasis.
- The goal is to help future agent sessions research the disease, treatment options, treatment mechanisms, raw ingredients/drug components, evidence limits, and hospitals or programs with PFIC expertise.
- This repo is not medical advice. Frame outputs as research for discussion with a treating hepatology, genetics, transplant, or rare-disease team.
- Keep patient/family-specific details out of committed packet files. If private context is needed, put it only in `markdown/personal.md` and `html/personal.html`; those exact files are ignored by git.

## Git workflow
- For this repo, committing directly to `main` is allowed when the user asks for a commit or push.
- Do not create pull requests unless the user specifically asks for one.
- Still stage files selectively; do not use `git add .`.
- Preserve unrelated local packet changes unless the user asks to include them.

## Current disease model
- PFIC4 is usually framed as autosomal recessive cholestatic liver disease caused by biallelic pathogenic `TJP2` variants.
- `TJP2` encodes tight junction protein 2, also called ZO-2. In the liver, TJP2 helps organize tight junctions around bile canaliculi.
- The working mechanism is a barrier/polarity problem: TJP2 deficiency or dysfunction can disrupt tight-junction organization, claudin-1 localization, and canalicular barrier integrity.
- The downstream concern is bile-acid reflux or leakage into liver tissue, which can drive cholestasis, severe pruritus, hepatocyte injury, fibrosis, cirrhosis, liver failure, and hepatocellular carcinoma concern.
- PFIC4 is not primarily a lifestyle, diet, parenting, or infection-driven disease. Diet, illness, hydration, sleep, and medication tolerance can affect quality of life and nutrition, but they are not the root cause.
- Severity is variable. Do not assume one patient course from genotype alone. Look for objective markers: serum bile acids, bilirubin, AST/ALT, GGT, INR, albumin, platelets, growth, fat-soluble vitamins, pruritus/sleep burden, ultrasound, elastography, fibrosis/cirrhosis, portal hypertension, AFP, and HCC surveillance plan.

## Treatment research focus
- Treat IBAT inhibitors as symptom and bile-acid-burden treatments, not gene repair.
- Maralixibat / Livmarli and odevixibat / Bylvay both inhibit the ileal bile acid transporter in the terminal ileum. The strategy is to reduce intestinal bile-acid reabsorption and lower enterohepatic recirculation back to the liver.
- For PFIC4, the rationale is that if enough bile acids reach the intestine, interrupting reabsorption may lower the circulating bile-acid pool even though the underlying tight-junction defect remains.
- Maralixibat has direct randomized-trial inclusion of a small PFIC4/TJP2 subgroup in MARCH-PFIC. Do not overstate this as large PFIC4-specific evidence.
- Odevixibat is PFIC-labeled, but its pivotal randomized PFIC trial was in PFIC1/PFIC2. Treat PFIC4 use as broader-label/open-label/extrapolated evidence unless a current source says otherwise.
- Also research supportive and escalation options: fat-soluble vitamin replacement, nutritional support, UDCA/ursodiol, rifampicin, cholestyramine/colesevelam/colestipol timing issues, antihistamine or neuromodulator itch strategies where sourced, biliary diversion, ileal exclusion, transplant evaluation, and HCC surveillance.
- When researching raw ingredients, separate active ingredient from excipients and explain why each matters. For drugs, use current labels first and include dose form, strength basis, inactive ingredients, warnings, interactions, monitoring, and age/weight constraints.

## Hospital and expert-center research focus
- Do not rank hospitals as "best" without evidence. Prefer "programs to evaluate" and explain the criteria.
- Start with the PFIC Network hospital directory because it is PFIC-specific, but preserve its caveat that the directory is not exhaustive and the network does not validate every listed provider's experience.
- Prioritize programs with pediatric hepatology, genetic cholestasis experience, PFIC clinical trial or research-network participation, liver transplant capacity, biliary diversion experience, nutrition support, genetics counseling, and willingness to provide second opinions.
- U.S. programs already worth evaluating from current source context include Children's Hospital Colorado, Cincinnati Children's, Johns Hopkins All Children's / Johns Hopkins Pediatric Liver Center, St. Louis University/Cardinal Glennon, Children's Hospital Los Angeles, and Mayo Clinic. Verify current PFIC-specific claims before recommending any one center.
- International programs already worth evaluating from current source context include King's College Hospital / King's College London, The Hospital for Sick Children / University of Toronto, Toronto Centre for Liver Disease, Schneider Children's Medical Centre of Israel, and other PFIC Network directory entries. Verify current appointment paths and pediatric/adult fit.
- For each hospital page or center profile, capture: PFIC mention, cholestasis/genetic liver disease program, named clinicians if public, transplant/biliary surgery capabilities, clinical trials or publications, second-opinion path, insurance/geography constraints, and date accessed.

## Source and evidence rules
- Read Markdown first. `markdown/` is the agent-facing source of truth.
- Use `markdown/source-index.md` first for existing evidence and links.
- For new medical claims, verify against current primary or high-quality sources: drug labels, clinical trials, GeneReviews/NIH, professional guidelines, peer-reviewed papers, hospital program pages, and PFIC Network materials.
- Keep claim strength explicit: direct PFIC4 evidence, broader PFIC evidence, PFIC1/PFIC2 evidence, open-label extension, case report, expert review, label language, or inference.
- Preserve reviewed/accessed dates when updating research docs. If a source is time-sensitive, re-check it before relying on it.
- Do not make up case studies, success rates, rankings, quotes, or numbers.
- List unresolved questions at the end of research outputs when any remain.

## Packet file structure
- Always create both Markdown and HTML files for each PFIC4 research packet document, including disease summaries, hospital research pages, and per-drug pages.
- Store Markdown files in `markdown/` and HTML files in `html/`.
- Use matching basenames for companion files, for example `markdown/livmarli-maralixibat.md` and `html/livmarli-maralixibat.html`.
- Treat Markdown as the source to read and edit first.
- Treat HTML as the human-facing version.
- Whenever Markdown content changes, update the matching HTML in the same change.
- Whenever HTML content changes, update the matching Markdown in the same change.
- Link related HTML pages together so human readers can navigate between the layperson guide, clinician brief, combined packet, drug pages, source index, and future hospital pages.
- Link each HTML page back to its Markdown companion in `../markdown/`.
- Link each Markdown page to its HTML companion in `../html/`.

## Document roles
- `markdown/pfic4-research-packet.md`: combined high-signal packet and first read after this file.
- `markdown/source-index.md`: evidence map and source provenance.
- `markdown/layperson-pfic4-guide.md`: family-facing disease and treatment explanation.
- `markdown/clinician-pfic4-brief.md`: clinician-facing disease, monitoring, trial, and escalation brief.
- `markdown/layperson-tjp2-gene-guide.md`: family-facing explanation of the gene and inheritance.
- `markdown/clinician-tjp2-gene-brief.md`: clinician-facing gene, mechanism, phenotype, and surveillance context.
- `markdown/livmarli-maralixibat.md`: Livmarli active ingredient, formulation, mechanism, PFIC evidence, safety, and cost context.
- `markdown/bylvay-odevixibat.md`: Bylvay active ingredient, formulation, mechanism, PFIC evidence, safety, and cost context.

## Style
- Be concise and direct.
- Use sourced bullets and tables where they improve comparison.
- Avoid false certainty. PFIC4 cohorts are small, and treatment evidence often comes from broader PFIC populations.
- Keep family-facing text plain and careful. Keep clinician-facing text specific enough to support appointment preparation.
- No emojis.
