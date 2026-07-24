# Topical Authority — plat.besi.co.id

## Role and boundary

`plat.besi.co.id` should become a non-geographic Indonesian reference and commercial decision-support hub for steel plate and flat-bar products. It serves buyers, estimators, fabricators, maintenance teams, contractors, designers, and owners who need to identify, specify, buy, process, inspect, handle, maintain, or retire plate products.

The domain's existing commercial families are plat hitam or base plate, plat bordes, plat kapal, plat lubang, and plat strip. The knowledge program may explain adjacent plate types when comparison helps a reader, but it must not pretend that every discussed material is stocked. Exact structural design, welding-procedure qualification, vessel or ship classification approval, and occupational-safety authorization remain the responsibility of competent professionals and applicable current documents.

Cannibalization is controlled only within `plat.besi.co.id`. Other Syamsul-owned domains may independently cover steel, fabrication, construction, or procurement from their own editorial viewpoint.

## Evidence audited

- Canonical repository: `cfpages-adistyputriharli/plat.besi.co.id`, branch `main`.
- Static WordPress export with 3,732 tracked files: 2,701 HTML, 28 XML, and one pre-existing Markdown file.
- `README.md` records 2,700 sitemap URLs; `sitemap-complete.xml` also contains 2,700 `<loc>` entries.
- Page sitemap: nine page URLs. Post sitemaps: 2,441 post entries across 14 files.
- 2,440 root-level `jual-*.html` routes: exactly 488 each for plat bordes, plat hitam, plat kapal, plat lubang, and plat strip. These are geography-swapped commercial pages, not 2,440 distinct editorial assets.
- Five product hubs: `/plat-bordes/`, `/plat-hitam/`, `/plat-kapal/`, `/plat-lubang/`, and `/plat-strip/`.
- Other stable pages include `/`, `/jangkauan/`, `/kontak/`, `/tentang/`, `/hello-world/`, `/sample-page/`, and `/404/`.
- 252 tracked paths under `/category/` plus author, comments, feed, and pagination-style archive output; these are discovery or duplicate surfaces rather than independent knowledge coverage.
- Repository claims such as “terlengkap,” “terpercaya,” “harga terbaik,” “SNI,” and “bersertifikat” require product-specific documentary proof before reuse in editorial content.
- No existing article library, field-test dataset, engineering calculations, or verified case-study corpus was found.

## Existing coverage and risks

| Existing URL/pattern | Observed role/problem | Decision | Destination/owner | Verification needed |
|---|---|---|---|---|
| `/` | Broad commercial landing page for steel plate | keep | Commercial overview; link to topic hubs without absorbing their informational intent | Confirm live content, conversion path, canonical, and indexation |
| `/plat-hitam/` | Product-family sales page, also uses “base plate” language | expand | Commercial owner for quote and availability intent; PLT-04 owns neutral education | Verify actual grades, thicknesses, dimensions, certificates, and services |
| `/plat-bordes/` | Product-family sales page for patterned anti-slip plate | expand | Commercial owner for quote intent; PLT-05 owns selection and performance education | Verify patterns, base material, nominal versus measured thickness, and stock |
| `/plat-kapal/` | Product-family sales page with SNI and certificate claims | expand | Commercial owner for supply intent; PLT-06 owns marine-grade education | Verify mill certificates, standards, class acceptance, and stocked grades |
| `/plat-lubang/` | Product-family sales page for perforated plate | expand | Commercial owner for quote intent; PLT-07 owns pattern, open-area, and application education | Verify hole shapes, pitch, margins, materials, dimensions, and fabrication capability |
| `/plat-strip/` | Product-family sales page for strip plate or flat bar | expand | Commercial owner for quote intent; PLT-08 owns identification and selection | Verify manufacturing form, grades, widths, thicknesses, and tolerances |
| `/jual-plat-{family}-{place}.html` | 2,440 near-template geography pages: 488 per family | manual review | Retain only pages with unique local evidence and demand; consolidate the rest into family routes or a useful service-area model | GSC impressions, backlinks, conversions, canonical status, content similarity, and actual fulfillment evidence |
| `/jangkauan/` | Service-area directory | keep | One transparent logistics and coverage route | Verify current delivery areas and avoid duplicating all location-page text |
| `/hello-world/` and `/sample-page/` | WordPress starter content with no authority role | manual review | Remove, redirect, or noindex after checking history | GSC, backlinks, analytics, and current HTTP behavior |
| `/category/**`, `/author/**`, `/comments/**`, `/feed/**` | Archive and duplicate discovery surfaces; 257 tracked archive-family paths | noindex | Navigation only where useful; canonical articles and hubs own search intent | Live robots directives, canonicals, sitemap inclusion, and traffic |
| Sitemap set | 2,700 URLs dominated by templated posts and includes multiple sitemap formats | manual review | One canonical sitemap index containing only intended indexable URLs | Live response codes, lastmod accuracy, duplicates, and Search Console coverage |

Primary risks are doorway-like geographic duplication, ambiguous use of “base plate,” unsupported standards or certification claims, confusion among nominal and measured dimensions, unsafe fabrication advice, and collision between neutral guides and existing sales routes.

## Coverage matrix

| Completeness lens | Owning topics | Coverage decision |
|---|---|---|
| Definition, vocabulary, taxonomy, history | PLT-01, PLT-04–PLT-08 | Explain Indonesian trade terms and distinguish product form, pattern, grade, and application without creating synonym pages |
| Anatomy, materials, properties, mechanisms | PLT-03–PLT-09, PLT-13 | Cover plate geometry, material behavior, load path, open area, slip, corrosion, and fabrication response |
| Measurement, dimensions, tolerances, calculations | PLT-02, PLT-07, PLT-10, PLT-14 | Give auditable units, weight and quantity methods, sampling, and acceptance logic; no invented tolerances |
| Need recognition and survey | PLT-01, PLT-09, PLT-14, PLT-17 | Identify the decision, collect service conditions, inspect condition, and define when professional assessment is needed |
| Requirements, comparison, and selection | PLT-03–PLT-10 | Map use conditions to family, grade, geometry, finish, fabrication, and evidence needs |
| Budget and procurement | PLT-02, PLT-10, PLT-14, PLT-15 | Cover takeoff, yield, quotation normalization, certificates, supplier checks, logistics, and acceptance |
| Preparation, fabrication, and installation | PLT-09, PLT-11–PLT-16 | Cover drawings, nesting, cutting, forming, joining, coating, inspection, handling, and K3 stop conditions |
| Handover and operation | PLT-14–PLT-17 | Cover traceability, records, protection, inspection baselines, safe use, and maintenance ownership |
| Troubleshooting, repair, replacement | PLT-13, PLT-14, PLT-17 | Diagnose distortion, corrosion, cracks, wear, coating failure, and repair-versus-replace decisions |
| Stakeholders and site types | PLT-04–PLT-10, PLT-14–PLT-17 | Provide paths for buyers, estimators, workshops, engineers, installers, HSE teams, and asset owners |
| Climate and geography | PLT-03, PLT-06, PLT-13, PLT-15 | Address humid, rainy, coastal, polluted, and outdoor exposure substantively; no place-name swaps |
| New work versus retrofit | PLT-09, PLT-14, PLT-17 | Separate new specification from matching, inspecting, and repairing existing assemblies |
| DIY versus professional | PLT-11, PLT-12, PLT-16, PLT-17 | Allow safe observation and planning while defining stop conditions for hot work, lifting, structural judgment, and repair |
| Safety, failure modes, standards, evidence | PLT-03, PLT-06, PLT-09, PLT-12–PLT-17 | Require current primary documents, competent review, traceability, and hazard controls |
| Environmental and end-of-life | PLT-10, PLT-13, PLT-17 | Cover yield, waste segregation, coating constraints, reuse qualification, and recycling records |
| Editorial formats and search intents | PLT-01–PLT-17 | Mix evergreen guides, decision tables, diagrams, calculators, checklists, diagnostic trees, and evidence-backed commercial support |

All lifecycle stages and applicable lattice lenses have an owner. News is not a dedicated topic because thin trend coverage would decay; material changes belong as dated updates inside the relevant standards, procurement, fabrication, or coating page.

## Topical map

| Topic ID | Parent topic | Reader outcome | Required subtopics/questions | Evidence/formats | Boundary | Article target |
|---|---|---|---|---|---|---:|
| PLT-01 | Steel-plate fundamentals and vocabulary | Identify the product being discussed and use trade terms without confusing form, grade, finish, or application | Sheet versus plate; plate versus coil and strip; plat hitam, base plate, bordes, kapal, lubang, strip; hot-rolled surface; product naming; family decision path | Annotated taxonomy, cross-section diagrams, glossary, sourced explanation | Owns definitions and taxonomy; dimensions belong to PLT-02, material grades to PLT-03, and each family’s selection to PLT-04–PLT-08 | 6 |
| PLT-02 | Dimensions, mass, tolerances, and measurement | Read dimensions, calculate theoretical mass, and verify delivered pieces consistently | Thickness, width, length, area, volume, density assumptions, unit conversion, nominal versus actual, weighing, measurement tools, tolerance documents, sampling | Worked calculations, calculator specification, measurement photos, inspection checklist | Owns measurement method and neutral calculations; quantity and quotation decisions belong to PLT-10, acceptance sampling to PLT-14 | 6 |
| PLT-03 | Materials, grades, properties, and documents | Specify evidence appropriate to service instead of choosing from an unsupported grade label | Carbon and alloy context; mechanical and chemical properties; grade equivalence limits; MTC or mill certificate; heat number; standards hierarchy; weldability and toughness implications | Primary standards, certificate anatomy, property matrix, metallurgist or engineer review | Owns grade and evidence concepts; family applications belong to PLT-04–PLT-08, weld execution to PLT-12, acceptance process to PLT-14 | 6 |
| PLT-04 | Plat hitam and base-plate decisions | Distinguish general hot-rolled plate from a fabricated base plate and choose a fit-for-purpose specification | Trade meaning; structural and fabrication uses; base-plate assembly; thickness and flatness questions; holes and edges; alternatives; ordering checklist | Decision table, annotated detail, sample specification, expert review | Owns neutral plat-hitam and base-plate education; `/plat-hitam/` owns sales intent, PLT-09 owns structural design, PLT-11 owns cutting and drilling | 6 |
| PLT-05 | Plat bordes or checker plate | Select patterned plate based on environment, loading, cleanability, and verified slip requirements | Pattern names; base thickness versus pattern height; walking surfaces; drainage; contamination; orientation; support spacing questions; cleaning; alternatives | Pattern photos, measurement diagram, decision table, safety review | Owns bordes selection and use; `/plat-bordes/` owns sales intent, PLT-09 owns structural design, PLT-13 owns corrosion protection | 6 |
| PLT-06 | Plat kapal and marine-service plate | Understand why marine plate is a documented material choice rather than a marketing synonym | Grade and class context; certificates; heat traceability; toughness; weldability; corrosion environment; renewal and repair documentation; non-marine alternatives | Primary class and standard sources, certificate map, decision checklist, qualified expert review | Owns marine-plate education; `/plat-kapal/` owns sales intent, PLT-03 owns generic grade evidence, PLT-12 owns welding execution | 6 |
| PLT-07 | Plat lubang or perforated plate | Specify perforation geometry and open area for function, strength, appearance, and fabrication | Hole shape and diameter; pitch and stagger; open-area calculation; margins; sheet direction; filtration, ventilation, guarding, acoustic and facade uses; clogging and cleaning | Geometry diagrams, calculator, specimen photos, application matrix | Owns perforation design vocabulary and selection; `/plat-lubang/` owns sales intent, PLT-09 owns structural integration, PLT-11 owns fabrication process | 6 |
| PLT-08 | Plat strip or flat bar | Identify strip or flat-bar supply correctly and select dimensions and finish for the intended assembly | Strip versus slit coil and cut plate; edge condition; straightness; common uses; bracing, frames, clamps, rails; twist and distortion; ordering data | Product-form diagram, comparison matrix, measurement checklist, fabrication examples | Owns strip-product selection; `/plat-strip/` owns sales intent, PLT-02 owns calculation, PLT-11 and PLT-12 own processing and joining | 6 |
| PLT-09 | Application requirements and plate specification | Turn service conditions and design intent into a complete, reviewable plate specification | Loads and support concept; temperature, impact, abrasion, fire and corrosion exposure; holes and penetrations; drawings; tolerances; retrofit survey; professional-design thresholds | Requirements worksheet, annotated drawing, decision tree, engineer review | Owns requirements and specification workflow, not engineering approval or numerical member design; family facts belong to PLT-04–PLT-08 | 6 |
| PLT-10 | Quantity, cost, quotation, and procurement | Estimate material, compare offers fairly, and reduce waste and documentary surprises | Takeoff; theoretical versus invoiced weight; nesting allowance; scrap; cutting charges; coating and delivery; lead time; substitution; quotation normalization; supplier evidence | Calculator, RFQ template, bid-comparison table, procurement checklist | Owns purchasing and cost structure, not live price claims; PLT-02 owns weight fundamentals, PLT-14 owns receiving acceptance | 6 |
| PLT-11 | Cutting, drilling, forming, and machining | Choose a processing route and issue workshop information that protects quality and yield | Shearing, sawing, plasma, laser, oxy-fuel, waterjet context; kerf and heat effects; holes; edge preparation; bending direction and radius evidence; nesting; distortion | Process matrix, annotated drawings, before-and-after photos, fabricator review | Owns material-removal and forming choices; PLT-12 owns joining, PLT-14 owns final acceptance, PLT-16 owns safe execution | 6 |
| PLT-12 | Welding, bolting, and joining | Select a joining concept and recognize when qualified welding or engineered connection design is required | Weldability inputs; WPS and welder qualification context; preheat evidence; distortion; weld symbols; bolts and fasteners; dissimilar materials; inspection handoff | Joint diagrams, process checklist, primary procedure references, welding-engineer review | Owns joining process education, not project-specific connection calculations or procedure qualification; PLT-03 owns grade evidence and PLT-16 hot-work controls | 6 |
| PLT-13 | Surface preparation, coating, and corrosion | Match protection and preparation to exposure, fabrication sequence, and inspection plan | Rust mechanisms; mill scale; cleaning grades; blasting and power-tool context; primer and topcoat systems; galvanizing constraints; edge and weld treatment; coating failure | Exposure decision tree, coating-system comparison, defect photos, primary product data | Owns corrosion and surface systems; PLT-06 owns marine-grade identity, PLT-14 owns acceptance records, PLT-17 owns in-service repair decisions | 6 |
| PLT-14 | Inspection, defects, QA, and traceability | Define what to inspect at receipt, after fabrication, and at handover without accepting unsupported claims | Identity and documents; dimensions; flatness; surface condition; lamination and discontinuity context; weld and coating records; sampling; NCR; traceability retention | Receiving checklist, defect atlas, inspection and test plan template, qualified review | Owns quality gates and records, not laboratory certification or engineering disposition; measurement method belongs to PLT-02, repair decisions to PLT-17 | 6 |
| PLT-15 | Packing, lifting, transport, and storage | Prevent injury, distortion, mix-up, and corrosion from supplier dispatch through workshop storage | Bundle identity; lifting plans; magnets, clamps and slings context; edge protection; transport restraint; unloading; stacking; dunnage; ventilation; FIFO; wet-storage response | Handling diagrams, storage checklist, logistics risk assessment, HSE review | Owns material logistics; PLT-16 owns general task hazards, PLT-14 owns receiving acceptance, PLT-17 owns in-service care | 6 |
| PLT-16 | K3 for plate work | Recognize sharp-edge, crush, hot-work, fume, noise, fire, and stored-energy hazards and know when work must stop | Hazard identification; hierarchy of controls; PPE limits; guarding; hot-work permit; ventilation; fire watch; manual handling; lifting exclusion zones; emergency readiness | Task risk matrix, stop-work checklist, safety pictograms, qualified HSE review | Owns hazard-control education, not site permits, legal certification, or method-statement approval; process technique belongs to PLT-11 and PLT-12 | 6 |
| PLT-17 | Inspection, maintenance, repair, reuse, and end-of-life | Monitor installed plate, diagnose deterioration, and make documented repair, replacement, reuse, or recycling decisions | Baselines and intervals; corrosion, wear, distortion and cracking; coating repair; temporary controls; repair-versus-replace; reuse qualification; segregation and recycling | Lifecycle checklist, symptom-to-action tree, repair record template, competent expert review | Owns in-service lifecycle decisions; PLT-13 owns original protection design, PLT-14 owns fabrication acceptance, PLT-16 owns repair-task safety | 6 |

Total plan: 17 parent topics and 102 article briefs.

## Related-domain opportunities

- `besi.co.id` may explain the wider steel-product taxonomy and link conceptually to plate as one form; this domain still owns complete plate-specific guidance.
- `batang.besi.co.id`, `bajaringan.besi.co.id`, and other product subdomains can provide independent comparisons where a project chooses among plate, bar, sections, or light-gauge systems.
- Construction and fabrication domains may cite plate details from their application perspective, while `plat.besi.co.id` remains responsible for plate identity, specification, processing, QA, and lifecycle.
- Cross-domain overlap is allowed. Links should be earned by reader usefulness and clear ownership of the destination intent, not used to suppress coverage here.

## Consolidation plan

1. Export GSC and analytics data for all 2,440 `jual-*` pages; group by family and locality, then compare impressions, clicks, links, leads, canonicals, and textual uniqueness.
2. Keep a location page only when it has unique fulfillment evidence, useful local logistics, or meaningful demand. Consolidate weak variants into the five family routes or `/jangkauan/` with mapped redirects when justified.
3. Preserve the five commercial family URLs and separate their quote intent from the proposed neutral guides. Product pages may summarize and link to guides; guides may link to product routes only at a legitimate buying step.
4. Remove archive and starter-page URLs from indexable sitemaps after checking history. Apply canonical or noindex controls according to each surface’s function.
5. Replace the overlapping sitemap set with one maintainable canonical index after live URL verification.
6. Do not publish new knowledge URLs until proposed slugs have been checked against the live deployment, not only this repository snapshot.

## Internal-link architecture

- `/` introduces the five commercial families and links to the PLT-01 plate-knowledge hub.
- PLT-01 acts as the vocabulary and navigation hub, then sends readers to measurement (PLT-02), grade evidence (PLT-03), family guides (PLT-04–PLT-08), and requirements (PLT-09).
- Each family hub links to exactly six child briefs and laterally to only the measurement, grade, fabrication, protection, or procurement pages needed for that decision.
- PLT-09 begins the project lifecycle: requirements → quantity and procurement (PLT-10) → processing (PLT-11) → joining (PLT-12) → protection (PLT-13) → acceptance (PLT-14) → logistics (PLT-15) → safe execution (PLT-16) → in-service lifecycle (PLT-17).
- Diagnostic pages link to prevention, immediate safe controls, inspection, and repair or replacement; they do not funnel every symptom directly to a sales page.
- Commercial family routes receive contextual links from selection and procurement pages. Location pages must not become default related links.
- Every article links upward to its parent hub; parent hubs list all children; related IDs in `ARTICLE_CATALOG.md` define the first lateral-link graph.

## Evidence and editorial standards

- Verify grade names, tolerances, test methods, certification, and regulatory statements against current primary standards, manufacturer or mill documents, class rules, or qualified experts before publication.
- State whether each dimension or mass is nominal, theoretical, measured, ordered, or invoiced. Show assumptions and units in every calculation.
- Never treat “SNI,” “ship plate,” “base plate,” “anti-slip,” or a grade-equivalence table as proof of suitability. Match the actual certificate, service condition, design, and responsible approval.
- Safety and engineering pages need qualified review, explicit stop conditions, and a clear distinction between educational planning and authorized execution.
- Use original annotated product and defect photographs where possible. Do not invent tests, customer projects, certificates, prices, field performance, or firsthand experience.
- Date standards-sensitive pages and maintain an evidence register with source edition, access date, reviewer, and next review date.
- Keep Indonesian terminology primary, with English equivalents where they improve document matching and procurement.

## First bounded publication cluster

Wave W1 contains 12 assets:

- PLT-01-01 and PLT-01-02: central taxonomy and plate-versus-sheet decision.
- PLT-02-01 and PLT-02-02: dimension reading and theoretical-mass calculation.
- PLT-03-01 and PLT-03-04: grade selection inputs and mill-certificate reading.
- PLT-04-01, PLT-05-01, PLT-06-01, PLT-07-01, and PLT-08-01: one authoritative entry point for each existing product family.
- PLT-10-01: an RFQ data checklist that connects learning to legitimate procurement.

This cluster is coherent because it lets a buyer identify the product, quantify it, understand documentary evidence, enter any existing family, and prepare a comparable inquiry without publishing unsafe design advice. Monitor indexation, impressions grouped by intent, calculator or checklist completion, movement from guides to the relevant family page, qualified inquiries with complete specifications, and query/page overlap. Review cannibalization at 30, 60, and 90 days before expanding the next wave.

## Definition of done

- All 17 topic hubs and their 102 bounded briefs are published or deliberately retired through an editorial decision log.
- Every published claim has the evidence level specified in the catalog; standards-sensitive and safety-critical pages have documented competent review.
- Proposed slugs pass live-route collision checks and every article has a unique primary intent, explicit exclusions, parent link, and useful lateral links.
- Existing family pages and geographic pages have documented keep, consolidate, redirect, canonical, or noindex decisions supported by GSC, links, conversion, and live-response evidence.
- Sitemap, canonical, archive, and indexation controls expose only intended URLs.
- Content performance is reviewed by indexation, impressions by intent, engagement or task completion, qualified leads, and same-domain cannibalization—not rankings alone.
- No city-swapped knowledge articles, fabricated evidence, unsupported certification claims, or ambiguous neutral-plus-sales pages are introduced.
