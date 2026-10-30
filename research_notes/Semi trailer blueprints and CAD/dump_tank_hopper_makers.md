# Public blueprints, dimensioned spec sheets, CAD and manuals from North American dump, side dump, belly dump, live-floor, hopper, transfer and tank trailer makers (excluding MAC Trailer and East Manufacturing)

Method note (applies to all sections): checked 30 Oct 2026. I fetched about 40 manufacturer domains with curl, crawled the literature, download, brochure and manual pages, and pulled out every link ending in pdf, dwg, dxf, step, stp, igs, zip, sat or x_t. I downloaded about 45 PDFs, checked their metadata with pdfinfo and their text with pdftotext, and looked at page renders to see whether each one has a real dimensioned drawing or only a list of specs. I queried Google Patents by assignee. A finding marked "(search snippet)" or "(unverified)" means I could not open the source directly (bot wall, 403/410/502, or no time) and only saw a search-engine summary of it.

## Q1. Which manufacturers publish downloadable spec sheets or drawings with dimensions? (Direct URLs and what each shows)

### Takeaway
SmithCo (side dumps) and Keith Walking Floor (floor systems) publish real dimensioned line drawings. SmithCo's sell sheets have dimensioned side and rear elevations. Keith's installation drawings are formal sheets with a title block and isometric details. Timpte, Ranco, Trail King, Etnyre and Pitts publish long PDF spec sheets and brochures with numeric dimensions (lengths, widths, sidewall heights, kingpin settings, hopper openings, capacity tables), but these are photos plus spec tables, not drawings. Tank makers (Heil, Polar, Wabash/Brenner/Walker, LBT, Tremcar) publish almost nothing dimensional on their own sites. Their dimensions show up mainly in dealer-hosted build sheets (Halé Trailer, Littlejohn, TruckPaper, MyLittleSalesman).

### Cited Findings

**SmithCo (side dumps, Le Mars, IA). This is the best "blueprint-like" public material in the dump segment.**
- The literature page lists about 19 sell sheets and brochures as direct PDFs on a CDN. The models covered are SX1, SX2, SX3, SX4, SX5, SX6, SX7, CP-20, CPSHV-20, MHVSR, SHV, TMB, The Brute, Feedlot, Custom Mine Trailers, the 2025 Popular Options brochure and the Ag brochure — [SmithCo literature](https://sidedump.com/support/literature)
- The SX2 sell sheet (2 pp, Adobe InDesign) has **dimensioned side-elevation line drawings of three configurations (SX2-4034, SX2-4236, SX2-3734)** and a rear elevation, with overall and axle-position dimension strings. Its spec table gives:
  - frame length 39'5", tub length 34', width 8'6" or 9'6"
  - height 8'3" at the tub side and 9'6" at center
  - 2" kingpin at an 18" setting
  - 3500 PSI cylinders with a 5" bore, two 25,000 lb axles
  - water-full 23/24 cu yd and heaped 31/32 cu yd
  - [SX2 PDF](https://tawdry-bushbuck.files.svdcdn.com/production/images/SmithCo-SX2-sell-sheet-web-4-9-24.pdf?dm=1712696333) (I viewed the render)
- The SX7 sell sheet gives frame length 53', tub 40', width 102", height 8'7" at the tub side and 9'7" at center, a 16" kingpin setting, three 25,000 lb axles, 26.8 cu yd water-full and 35.6 cu yd heaped — [SX7 PDF](https://tawdry-bushbuck.files.svdcdn.com/production/docs/SmithCo-sx7-sellsheets-web.pdf?dm=1677101497)
- Other direct sheets, with the same layout presumed but not each opened:
  - [SX1](https://tawdry-bushbuck.files.svdcdn.com/production/docs/SmithCo-SX1_2021-02-24-205408.pdf?dm=1614200048)
  - [SX3](https://tawdry-bushbuck.files.svdcdn.com/production/images/SmithCo-SX3-Brochure-4-18-24-web-opt.pdf?dm=1716391737)
  - [SX4](https://tawdry-bushbuck.files.svdcdn.com/production/docs/SmithCo-SX4_2021-02-24-205415.pdf?dm=1614200055)
  - [SX5](https://tawdry-bushbuck.files.svdcdn.com/production/images/SmithCo-SX5-sell-sheet-web-4-9-24.pdf?dm=1712696357)
  - [SX6](https://tawdry-bushbuck.files.svdcdn.com/production/docs/SmithCo-sx6-sellsheets-web.pdf?dm=1677101493)
  - [CP-20](https://tawdry-bushbuck.files.svdcdn.com/production/images/SmithCo-CP-20-sell-sheet-web-4-9-24.pdf?dm=1712696699)
  - [SHV tub](https://tawdry-bushbuck.files.svdcdn.com/production/images/SmithCo-SHV-tub-sell-sheet-web-4-9-24.pdf?dm=1712696293)
  - [MHVSR tub](https://tawdry-bushbuck.files.svdcdn.com/production/images/SmithCo-MHVSR-tub-sell-sheet-web-4-9-24.pdf?dm=1712696312)
  - [TMB](https://tawdry-bushbuck.files.svdcdn.com/production/images/SmithCo-TMB-sell-sheet-web-4-9-24.pdf?dm=1712696749)
  - [The Brute](https://tawdry-bushbuck.files.svdcdn.com/production/images/The-BRUTE-FINAL_2025-03-28-144011_xydh.pdf?dm=1743172812)
  - [Popular Options 2025](https://tawdry-bushbuck.files.svdcdn.com/production/images/SmithCo-Popular-Options-Brochure-2025.pdf?dm=1753969130)
  - [Mine trailers](https://tawdry-bushbuck.files.svdcdn.com/production/docs/SmithCo-2021-Custome-Mine-Trailers-Sell-Sheet.pdf?dm=1722283932)
  - [Full brochure](https://tawdry-bushbuck.files.svdcdn.com/production/docs/SMITHCO-BROCHURE-all-together-HighRez.pdf?dm=1614200179)
- A "Spec Your Trailer" learning-center page also exists — [SmithCo spec guide](https://sidedump.com/learning-center/spec-your-trailer)

**Ranco (end, frameless, belly and side dumps). The site carries "Ranco by Western" branding, and the brochure footers say Dragon Products, LLC.**
- The brochure index has 26 model pages. Each one links a single PDF on the Webflow CDN. Models include:
  - Tandem Belly Dump Switchgate, Extra Capacity Pup, Steel/Aluminum Mini
  - LW21-40-2/-40-3/-42-3, 14-24-4P 4-axle
  - Aluminum Extruded Double Wall, Drill Cutting, Super 12 Elliptical
  - Frameless High Cube, Anvil Quarter Frame, Frameless Anvil
  - SD22-42-2/-3 side dumps, and roll-off units
  - [Ranco brochures](https://www.ranco.com/brochures)
- The Frameless High Cube PDF is one raster page made in Photoshop: a photo plus a spec list. It gives 95 cu yd, 45' OAL, 43' tub length, 102" walls, 96" body width, 102" axles, half-round AR400 tub, and a 9" 5-stage hoist with a 320" stroke. There is **no line drawing** — [PDF](https://cdn.prod.website-files.com/65d945c49e17995575ffae2d/65e8eee13afda4fc51ba87ed_Ranco-Frameless-High-Cube-End-Dump.pdf)
- The Wet Sand Switchgate belly dump sheet (2 pp, InDesign) gives 23 cu yd, OAL 40 ft, OW 102", an upper hopper opening of 102"×188", a lower hopper opening of 64"×64" and 10-ga AR250 hopper sheets. Its footer reads "Dragon Products, LLC" — [PDF](https://cdn.prod.website-files.com/65d945c49e17995575ffae2d/67acb3e6c46bbf14f68e869b_WetSandSwitchgate.pdf)
- SD22-42-3 side dump: one raster spec page — [PDF](https://cdn.prod.website-files.com/65d945c49e17995575ffae2d/65e8f0a4e51836e0c08b8e0a_Ranco-SD22-42-3-3-Axle-Side-Dump.pdf)
- Branding evidence: the ranco.com header logo file is named `headerlogo-sm-byline-Western.png`, and the homepage carousel shows "Dragon Frac Tank Trailer" and a "Dragon 165 BBL vac trailer" — [ranco.com](https://www.ranco.com/). The corporate relationship is unverified.

**Vantage Trailers (belly and end dumps)**
- `vantagetrailers.com` is now a parked GoDaddy "for sale" page. `vantagetrailer.com` redirects to `dragonproductsltd.com/vantage-trailers/`, which returned HTTP 451 to my client, so I found no public spec sheets — [vantagetrailer.com redirect](https://www.vantagetrailer.com/)

**Travis Body & Trailer (aluminum end dumps and frameless/half-round)**
- The factory site returns 403 to automated clients (curl and WebFetch) — [travistrailers.com](https://www.travistrailers.com/)
- A dealer-hosted build sheet (Halé Trailer, Word, 2 pp) gives body length 39 ft, side height 63", 46.7 cu yd, .190" side gauge, kingpin setting "10" ahead of floor sheet", and the grain door, tarp and light options — [Halé PDF](https://trailerimages.haletrailer.com/inv/docs/trailer/012716-2018TRAVIS-1.pdf)

**Trail King (bottom dumps, side dumps and live-bottom)**
- The TKSSD steel side dump product page carries an HTML spec table:
  - lengths 20'2" / 29'11" / 35'11"–39'8" / 40'8"–46'8" / 47'8" / 49'
  - tub lengths 18' to 39', overall height 9'10"–9'11"
  - water-level capacity 11 to 24 cu yd; full capacity starts at 15 cu yd
  - [TKSSD page](https://www.trailking.com/products/tkssd-steel-side-dump/)
- The downloadable brochures are 6-page image PDFs generated by Chromium (feature photos, e.g. "Large 11'6" clam"), not drawings:
  - [TKBD bottom dump PDF](https://www.trailking.com/wp-content/uploads/2025/04/tkbd-bottom-dump-2023.pdf)
  - [TKSSD PDF](https://www.trailking.com/wp-content/uploads/2025/04/tkssd-steel-side-dump-2023.pdf)
  - [TKBD page](https://www.trailking.com/products/tkbd-bottom-dump/)
- (Search snippet, not opened) Halé Trailer hosts Trail King dealer spec PDFs for live-bottom models, e.g. an OLB32-102 "Advantage Series" giving kingpin-to-center-of-last-axle 31'11" and OAL 36'7":
  - [example Halé PDF](https://trailerimages.haletrailer.com/inv/docs/trailer/113019-2017TRAILKNG-1.pdf)
  - [series PDF](https://trailerimages.haletrailer.com/inv/docs/series/112950-112954-1.pdf)

**CPS (Commercial Power Systems, now a Manac brand)**
- `cpstrailers.com` redirects to `manac.com/us/en`. Product pages include CPS steel side dump and Maxwing aluminum/steel dumps — [CPS side dump](https://manac.com/us/en/trailers/cps-steel-side-dump)
- I found no spec PDFs. Manuals are covered under Q3.

**Doepker (Saskatchewan: grain hoppers, Super B, end/clam/cross dumps)**
- The site is JavaScript-rendered, and every page returns the same 23 KB shell. The sitemap lists product pages and a "brochure" sub-page: [Super B brochure page](https://doepker.com/trailers/grain/super-b-grain/brochure), [Impact end dump](https://doepker.com/trailers/gravel/impact-end-dump), [Tridem clam dump](https://doepker.com/trailers/gravel/tridem-clam-dump), [Tridem cross dump](https://doepker.com/trailers/gravel/tridem-cross-dump), [Tridem steel 3-hopper](https://doepker.com/trailers/grain/tridem-steel-3-hopper) — [Doepker sitemap](https://www.doepker.com/sitemap.xml)
- I could not extract the brochure content (unverified whether it includes drawings).

**Timpte (aluminum hoppers)**
- The brochure page links nine PDFs, among them the 2026 Super Hopper, 2024 Roughneck, Tender, Thunder 7000, Gravity-Flow, EZ-Flow Override, RTAC Doubles and the Australian brochure — [Timpte brochures](https://timpte.com/learn-more/brochures-and-apparel/)
- The 2026 Super Hopper brochure (20 pp, InDesign) has:
  - a model matrix: standard lengths 21'11"–42'2", Super Cube 43', spread-axle and tri-axle 48'/50', widths 96"/102", heights 66"–84"
  - spec pages, e.g. a 50,000 lb lift capacity "located from king pin: 123"" and a 17" ride height
  - **capacity tables** in ft³ by length × height × width, both heaped and water-level, for Ag and split hoppers
  - photos only; no line drawings on the pages I sampled
  - [PDF](https://timpte.com/wp-content/uploads/2026/09/2026-Super-Hopper-Brochure-072226.pdf)
- The 2024 Roughneck brochure (12 pp) gives 39' length, 96" width, 66" sidewall, 138" overall height, a **20" kingpin location**, 25" ground clearance, a 24"×26" single hopper, and 720 ft³ level / 850 ft³ heaped — [PDF](https://timpte.com/wp-content/uploads/2025/02/2024-Roughneck-Brochure_v2.2.pdf)

**Wilson Trailer (Pacesetter and other hoppers)**
- The site returns 403 (bot protection) to automated fetches. Via search snippet, the Pacesetter page lists:
  - length 34'–53', width 96"–102", sides 66"–114"
  - kingpin 22" standard, traps 27"×31", 8.25×24.5 wheels
  - [Pacesetter page](https://www.wilsontrailer.com/trailers/pacesetter/)
- A grain brochure PDF exists (indexed by search; 403 to my client) — [grain brochure](https://www.wilsontrailer.com/wp-content/uploads/pdfs/brochures/grain/grain-brochure.pdf)

**Neville Built (grain and tank-chassis trailers)**
- Product Data Sheets are hosted on CloudFront, e.g. [Drop Deck data sheet](https://d3id0shqq95792.cloudfront.net/images/products/Neville-Built-Trailers-Drop-Deck-Trailers-Product-Data-Sheet-v2.14.26.pdf) and [Livestock data sheet](https://d3id0shqq95792.cloudfront.net/images/products/Neville-Built-Trailers-Livestock-Trailers-Product-Data-Sheet-v2.14.26.pdf)
- The grain and tank-chassis pages exposed no PDF link to my crawler — [grain trailers](https://nevillebuilt.com/trailers/grain-trailers), [tank chassis](https://nevillebuilt.com/trailers/tank-chassis-trailers)

**Cornhusker 800 (hoppers)**
- Only an owner's manual is offered (see Q3) — [Cornhusker warranty/manual page](https://www.cornhusker800.com/warranty-manual/)

**Midland (Midland Manufacturing: end, side and bottom dumps, SandRunner)**
- Only operator manuals and warranty forms are offered (see Q3) — [Midland downloads](https://midlandtrailers.com/downloads/)

**Etnyre (lowboys, asphalt transports, Falcon live-bottom)**
- The brochure page links about 55 PDFs — [Etnyre brochures](https://etnyre.com/brochures/)
- The asphalt "transports booklet" (36 pp) gives, for example, "7,250/7,500 Nominal Gallons, Tare 8,700 lbs" and a steel barrel of 7,000 gal with tare 11,600 lbs — [PDF](https://etnyre.com/wp-content/uploads/2021/09/transportsbooklet.pdf)
- The lowboy line brochure: [L-TRL-23](https://etnyre.com/wp-content/uploads/2023/05/L-TRL-23.pdf)
- Falcon is a **live-bottom (belt) trailer, not a belly dump**. (Search snippet) MoDOT hosts a Falcon LB-236 spec sheet: 36 cu yd, 36' length, 42" belt — [MoDOT PDF](https://www.modot.org/sites/default/files/documents/general_services/trailers/jimhawktrucktrailersinfo.pdf)

**Pitts (heavy haul and forestry; live-floor per listings)**
- The June 2026 full-line PDFs have dimension tables, e.g. LB60-22GT: 52'10" OAL, 26' deck, 22" loaded deck height, 12'-8" gooseneck. These cover lowboys, not dumps — [HH full line](https://pittstrailers.com/wp-content/uploads/2026/07/pitts_HH_full_line_june2026.pdf), [Forestry full line](https://pittstrailers.com/wp-content/uploads/2026/07/pitts_forestry_full_line_june_2026.pdf)

**Ledwell (bulk-haul feed, vacuum and hydraulic-tail trailers)**
- The sales-literature page links about 45 one-page sheets — [Ledwell sales literature](https://ledwell.com/resources/sales-literature/)
- The Bulk-Haul Classic sheet (Illustrator) shows photos and feature bullets only, with **no dimensions** — [PDF](https://ledwell.com/wp-content/uploads/Ledwell-Bulk-Haul_Classic_Sales-Sheet.pdf)

**Ox Bodies (dump bodies and Ox trailers)**
- The resource center links literature for the Stampede, Chisholm, Maverick, Stockyard, Classic Alum and Vertex Alum bodies, plus installation and operation instructions — [Ox resource center](https://www.oxbodies.com/resource-center/), e.g. [Vertex Alum literature](https://www.oxbodies.com/wp-content/uploads/2026/06/Ox-Bodies-Vertex-Alum-Literature.pdf), [installation instructions](https://oxbodies.com/wp-content/uploads/2021/08/ox-installation-instructions.pdf)

**Keith Walking Floor (live-floor systems)**
- See Q2. This is the only true installation/engineering drawing set found in the whole scope.

**Tank makers: what is public**
- **Wabash tank (Brenner and Walker brands).** `brennertank.com` and `walkerep.com` both redirect to `onewabash.com`. The tank PDFs are marketing one-pagers with **no dimensions**:
  - [Tank Trailer Overview](https://onewabash.com/docs/default-source/tank-trailer-downloads/Tank-Trailer-Overview.pdf)
  - [Chemical one-pager](https://onewabash.com/docs/default-source/tank-trailer-downloads/chemical-tanks-one-pager.pdf)
  - [FRP overview](https://onewabash.com/docs/default-source/tank-trailer-downloads/frp-tanks-overview-sheet.pdf)
  - [Sanitary one-pager](https://onewabash.com/docs/default-source/tank-trailer-downloads/sanitary-tanks-one-pager.pdf)
  - [Parts solutions](https://onewabash.com/docs/default-source/tank-trailer-downloads/tank-trailer-parts-solutions.pdf)
  - [Wabash tank products](https://onewabash.com/products/trailers/tank-trailers/products)
- **Heil Trailer.** The brochures page returned HTTP 502 on repeated attempts on 30 Oct 2026 — [heiltrailer.com/brochures](https://heiltrailer.com/brochures/)
  - (Third-party, unverified) DocHub hosts a Heil "Specification Sheet Form Rev 12-09-2013". It references model ST 4600 20 S1 and drawing number 721-0025T — [DocHub](https://www.dochub.com/fillable-form/256716-specification-sheet-form-rev-12-09-heil-trailer)
- **Polar Tank Trailer.** I found no OEM spec PDFs. Halé Trailer hosts Polar build specs (5 pp, Word). They give:
  - 9,500 gal, five compartments (3500/1200/1000/1000//2800)
  - aluminum shell, .204" bottom and .180" top/sides
  - heads and baffles .250" and .190"
  - OAL 44'6"
  - [Halé Polar 2017 PDF](https://trailerimages.haletrailer.com/inv/docs/trailer/015217-2017POLAR-1.pdf), [series PDF](https://trailerimages.haletrailer.com/inv/docs/series/014934-014936-1.pdf)
- **LBT (Omaha).** `lbtinc.com` is a tactical-gear Shopify store, not LBT the tank maker — [lbtinc.com](https://lbtinc.com/)
  - Dealer listings give LBT DOT 406 9,200 gal, 5 compartments (3100/1250/1100/1100//2650), 96" width, 3.3 psig, OAL 42'4.5" — [MyLittleSalesman listing](https://mylittlesalesman.com/2025-lbt-9200-gallon-5-compartment-dot-406-disc-brakes-fuel-tanker-trailer-12373736)
  - (Search snippet) LBT is described as formerly Fruehauf, Omaha; its 5,000th unit came in 2007 — [Bulk Transporter](https://www.bulktransporter.com/equipment/cargo-tanks-trailers/article/21647369/lbt-celebrates-5000th-unit-off-the-line)
- **Tremcar.** See Q6.

### Inferences
- In the dump and side-dump segment, the "blueprint" a public user can actually get is SmithCo's dimensioned elevation drawings. Everyone else publishes dimensions as tables or prose, though Timpte's capacity tables and Trail King's HTML tables are dense enough to rebuild a general arrangement.
- Tank OEMs deliberately keep geometry off the web (barrel OD, compartment split, MAWP). The best public geometry comes from dealer build sheets and listings, which often quote OD, compartment split and OAL. One example is a Tremcar 66.375" OD DOT-407.
- None of the brochure PDF metadata names a CAD tool. The creators are Adobe InDesign, Photoshop and Illustrator, MS Word, QuarkXPress and Chromium, so the brochures are re-drawn or photographed rather than exported from CAD.

### Gaps
- I could not machine-retrieve Wilson, Travis, Heil (502), Doepker (JS shell), Merritt (`merritt-trailers.com` 403) or Vantage/Dragon (451). These sites may hold more spec PDFs.
- I could not find working OEM domains for Jet Co, Construction Trailer Specialists (`ctstrailers.net` is a parked "/lander" page), Dorsey (`dorseytrailers.com` is parked), Galion, J&L Tank, Hallco or Beall. I found no spec documents for them.
- Western Trailer's homepage navigation shows only specialty lines (glass, military/aerospace, wind tower), with no dump pages or PDFs — [westerntrailer.com](https://www.westerntrailer.com/). Its relationship to the "Ranco by Western" branding is unverified.
- Fruehauf (fruehaufinc.com) offers only van brochures ([Composite](https://fruehaufinc.com/wp-content/uploads/2025/10/Fruehauf-Composite-Brochure.pdf), [Sheet & Post](https://fruehaufinc.com/wp-content/uploads/2025/10/Fruehauf-Sheet-Post-Brochure.pdf)). I found no dump or tank material.
- Kann (kannmfg.com) publishes refuse and construction truck-body sheets only (e.g. the Stratum dump body); I found no trailers. Rogers (rogerstrailers.com) is a lowboy maker with series PDFs, which is out of scope.

## Q2. Is downloadable CAD (DWG/DXF/STEP) offered anywhere, or online configurators that produce drawings?

### Takeaway
I found no DWG, DXF, STEP, IGES or native CAD file on any OEM site in scope, and no configurator that outputs drawings. The closest thing to body-builder CAD support is Keith Walking Floor. Without a login, it publishes PDF installation drawings and "Trailer Design Requirements" documents that trailer OEMs use to integrate the floor. Third-party CAD sites (GrabCAD, TurboSquid, 3dcadbrowser) hold user or artist models, not OEM data.

### Cited Findings
- The crawl of literature, download and manual pages on Ranco, SmithCo, Timpte, Etnyre, Ledwell, Midland, Ox, Manac/CPS, Cornhusker, Pitts, Trail King, Neville, Fruehauf, Rogers, Kann, Keith and Wabash returned **zero** CAD-format links, only PDFs. Sources: the pages listed in Q1, e.g. [Etnyre brochures](https://etnyre.com/brochures/), [SmithCo literature](https://sidedump.com/support/literature)
- **Keith Walking Floor** download library (WordPress Download Manager). The public listing is at [Keith downloads](https://www.keithwalkingfloor.com/downloads/) and [dealer resources](https://www.keithwalkingfloor.com/dealer-resources/); I enumerated it through the site's public WP REST endpoint. It includes:
  - Installation drawings: [V-Floor V-9](https://www.keithwalkingfloor.com/download/keith-v-floor-v-9-installation-drawings/), [V-9 Asphalt](https://www.keithwalkingfloor.com/download/keith-v-floor-v-9-asphalt-installation-drawings/), [V-18](https://www.keithwalkingfloor.com/download/keith-v-18-v-floor-installation-drawings/), [KFD 425](https://www.keithwalkingfloor.com/download/keith-kfd425-installation-drawings/), [Drop Deck](https://www.keithwalkingfloor.com/download/keith-drop-deck-installation-drawings/)
  - Design requirements for trailer builders: [V-Floor/V-Sweep Trailer Design Requirements](https://www.keithwalkingfloor.com/download/keith-v-floor-v-sweep-design-requirements/), [Wide Slat V-Floor/V-Sweep Trailer Design Requirements](https://www.keithwalkingfloor.com/download/keith-wide-slat-v-floor-v-sweep-trailer-design-requirements/)
  - Installation manuals: [Running Floor II](https://www.keithwalkingfloor.com/download/keith-running-floor-ii-installation-manual/), [Running Floor II metric](https://www.keithwalkingfloor.com/download/keith-running-floor-ii-metric-installation-manual/), [LeakProof III](https://www.keithwalkingfloor.com/download/keith-lpiii-installation-manual/), [KMD 175](https://www.keithwalkingfloor.com/download/keith-kmd-175-installation-manual/), [KFD](https://www.keithwalkingfloor.com/download/keith-kfd-installation-manual/), [KICD container](https://www.keithwalkingfloor.com/download/keith-kicd-container-installation-manual/), [J-MAX with aluminum sub-deck](https://www.keithwalkingfloor.com/download/keith-j-max-flooring-with-aluminum-sub-deck-installation-manual/)
  - Municipal specs: [V-Floor municipal specs](https://www.keithwalkingfloor.com/download/keith-v-floor-municipal-specs/)
- The Keith files download as PDFs after a normal browser session cookie is set. No login is needed: a cookieless request returns 403, and a request with the session cookie returns 200 application/pdf.
- The Drop Deck Installation Drawings file is 2 pp. It is a **formal engineering drawing sheet** with a zoned border, title block, isometric section details and numbered installation notes ("Standard 3.5" flooring drop deck… sub-deck alignment is critical"). PDF producer: Acrobat 10.1.8 / GPL Ghostscript 8.15 (I viewed the render) — [Keith Drop Deck drawings](https://www.keithwalkingfloor.com/download/keith-drop-deck-installation-drawings/)
- GrabCAD hosts only user-uploaded generic models, e.g. a "tank trailer 31000L", a "cement tank trailer 35 m³" and a "41600 Lts Aluminium Road Tank". I found no OEM-published model (search snippet) — [GrabCAD user models example](https://grabcad.com/yalcin-12/models)
- TurboSquid sells an artist mesh, "2026 Tremcar 7000 Gallon Tank Trailer". This is a visualization model, not OEM CAD (search result; the page returned 403 to direct fetch) — [TurboSquid listing](https://www.turbosquid.com/3d-models/3d-2026-tremcar-7000-gallon-tank-trailer-silver-2600789)
- 3dcadbrowser offers a generic "Dump Trailer" model in STEP/DWG and other formats; it is not tied to any OEM (search snippet) — [3dcadbrowser](https://3dcadbrowser.com/3d-model/dump-trailer-124622)

### Inferences
- OEMs give body builders and dealers CAD, if at all, privately through dealer portals or on request. The only "builder-facing" public engineering documents are from component and floor-system suppliers (Keith).
- Dimensional reconstruction of these trailers from public data would have to rely on the SmithCo elevations, the Keith installation drawings, patent figures (Q4) and dealer build sheets.

### Gaps
- I did not check TraceParts or 3D Warehouse item by item (time). Search turned up no OEM trailer models on them.
- I could not check whether Wilson, Travis, Heil, Doepker or Merritt have dealer-portal CAD, because their sites block automated access.

## Q3. Owner's and parts manuals with exploded views or dimensioned diagrams (direct URLs)

### Takeaway
Midland, CPS (Manac), Heil (via NHTSA), Cornhusker 800, Etnyre, Keith and Manac publish full operator, parts or service manuals as open PDFs. Midland's manuals include numbered exploded component views with item and description callouts. Keith's parts catalogs and installation manuals are the richest exploded and parts content.

### Cited Findings
- **Midland** manuals (InDesign). The bottom dump manual is 108 pp and the side dump manual 101 pp. Both have numbered figures (e.g. "Fig. 1 Principal systems… Fig. 3 Hydraulic system… Fig. 9 Coupling components"). Bottom dump p.61 has **Fig. 61 Spindle Components**, an exploded view with a 40-plus item callout table (I viewed the render). Links:
  - [Bottom Dump manual 2021](https://midlandtrailers.com/wp-content/themes/midland/downloads/operator-manuals/Bottom_Dump_Trailer-Manual-2021.pdf)
  - [Side Dump manual](https://midlandtrailers.com/wp-content/themes/midland/downloads/operator-manuals/Midland-Mfg-Operators-Manual-Side-Dump.pdf)
  - [End Dump manual 2021](https://midlandtrailers.com/wp-content/themes/midland/downloads/operator-manuals/Midland-Mfg-End-Dump-Trailer-Manual-2021-Web.pdf)
  - [SandRunner manual Apr 2024](https://midlandtrailers.com/wp-content/themes/midland/downloads/operator-manuals/66269B_Midland_Manual-SandRunner-Apr2024_webReady.pdf)
- **CPS Side Dump Operator Manual** (60 pp, InDesign, Oran MO). It has numbered figures (VIN location, ID plate) and a torque-requirements section — [CPS manual](https://media.manac.com/webfolder_download/2c475897230d4e26bc5b57d56f4ad3f5/431c2a3ba9aa850287a187e401a54a0e65b501d3/file.pdf). The **Manac** operator's manual 303 8051 04/2023 is 36 pp, made in QuarkXPress — [Manac manual](https://media.manac.com/webfolder_download/9b24f0a964d37a0f32a9f99667d5e2dd/9bae9c07813a52d7c7f0b3f6de266d02ececdd49/file.pdf). Index page: [Manac operator's manuals](https://manac.com/us/en/operator-s-manuals)
- **Heil Petroleum Trailer Owner's/Operator's Manual** (67 pp, MS Publisher, ©2012). NHTSA hosts it in its manufacturer-communications (TSB) archive. It has numbered figures (Figure 1 identification plate, Figures 2–6) — [NHTSA-hosted Heil manual](https://static.nhtsa.gov/odi/tsbs/2016/MC-10166613-9999.pdf)
- **Cornhusker 800 Owner's Manual** (54 pp, MS Word) includes a "Wiring Diagram for Hopper Trailers" (TOC p.43) and kingpin and hopper inspection guidance. Text search found no dimension drawings — [Cornhusker manual](https://www.cornhusker800.com/wp-content/uploads/2022/07/Cornhusker-800-Owners-Manual.pdf)
- **Etnyre** manuals page has about 60 PDFs, including the M-401/M-402/M-403 series and RTN operation and parts manuals (MO-RTN, MP-RTN), e.g. [MP-RTN-17](http://etnyre.com/wp-content/uploads/2023/09/MP-RTN-17_STATIC.pdf) and [M-751-25](http://etnyre.com/wp-content/uploads/2025/08/M-751-25.pdf) — [Etnyre manuals](https://etnyre.com/manuals/)
- **Keith** parts catalogs: [Running Floor II parts catalog](https://www.keithwalkingfloor.com/download/keith-running-floor-ii-parts-catalog/) (15.4 MB PDF, downloaded), plus [LeakProof III](https://www.keithwalkingfloor.com/download/keith-leakproof-iii-parts-catalog/), [KMD 250/300](https://www.keithwalkingfloor.com/download/keith-kmd-250-and-300-parts-catalog/) and [S-Drive](https://www.keithwalkingfloor.com/download/keith-s-drive-parts-catalog/). Service: [Running Floor II DX service manual](https://www.keithwalkingfloor.com/download/keith-running-floor-ii-dx-service-manual/)
- **Ox** trailers operator's manual (4 pp, Word; text only) — [PDF](https://oxbodies.com/wp-content/uploads/2021/08/ox-trailers-operators-manual.pdf)
- **Trail King** product-support PDF (parts/sales contacts) — [PDF](https://www.trailking.com/wp-content/uploads/2026/02/ProductSupport_PartsSales_NDSD_Jan_2026_With_Finance.pdf)

### Inferences
- NHTSA's TSB and manufacturer-communications archive (static.nhtsa.gov/odi/tsbs/) is an under-used public source for OEM trailer manuals and service bulletins. Tank and trailer OEMs must submit dealer communications there, so other Heil, Polar, Brenner or Tremcar documents are likely retrievable by searching NHTSA's database (not exhaustively searched).

### Gaps
- I found no public parts manuals for Wilson, Timpte, Travis, Ranco, SmithCo, Doepker, Polar, LBT or Tremcar. SmithCo, Timpte and Trail King point to online parts stores or departments instead.

## Q4. Notable patents with structural drawings (numbers and links)

### Takeaway
Google Patents assignee searches give a usable set of drawing-bearing patents for most of these makers. Design patents (e.g. Doepker's hopper trailer, Manac's bottom-dump beam) are made up entirely of drawings and show overall geometry. Figure counts are from Google Patents metadata where captured.

### Cited Findings
- **Tremcar Inc.**:
  - [US11014486B2](https://patents.google.com/patent/US11014486B2/en) "Tank trailer operating system": ground-level access to cleaning, venting, inspection and loading devices; inventor Daniel Tremblay; priority 2014-04-23; granted 2021-05-25; 13 figures
  - [CA3168374A1](https://patents.google.com/patent/CA3168374A1/en) "Tank trailer with fluid collection system" (2020)
  - [US7140211B2](https://patents.google.com/patent/US7140211B2/en) and [CA2467217C](https://patents.google.com/patent/CA2467217C/en): tamper detection security for a tank trailer (2003)
  - [CA2447358A1](https://patents.google.com/patent/CA2447358A1/en)
  - (Google Patents assignee query, `assignee=Tremcar`: 6 results)
- **Heil Trailer / Heil Co.**:
  - [US6457630B1](https://patents.google.com/patent/US6457630) Tank trailer construction (2000)
  - [US20160129826A1](https://patents.google.com/patent/US20160129826A1/en) Multi-material tank trailer body
  - [US10183804B2](https://patents.google.com/patent/US10183804) / [US20160052708A1](https://patents.google.com/patent/US20160052708A1/en) Tank trailer having integrated heat panels
  - [US20180017214A1](https://patents.google.com/patent/US20180017214A1/en) Composite LPG tank trailer
  - [US9527423B2](https://patents.google.com/patent/US9527423B2/en) Container for particulate material (dry bulk)
  - [US7475910B1](https://patents.google.com/patent/US7475910B1/en) Container having internal bulkhead
  - [US20170129549A1](https://patents.google.com/patent/US20170129549A1/en) Trailer fairing access panel
- **Polar Tank Trailer**:
  - [US10099529B2](https://patents.google.com/patent/US10099529B2/en) Automatically deploying lift axle control
  - [US20170101261A1](https://patents.google.com/patent/US20170101261A1/en) Insulated rear head for transport tank
  - [US20170283119A1](https://patents.google.com/patent/US20170283119A1/en) Drain spout for sanitary trailers
  - [US20170190276A1](https://patents.google.com/patent/US20170190276A1/en) Product pump drive / CAN system
- **Travis Body & Trailer**:
  - [US5509724A](https://patents.google.com/patent/US5509724A/en) Multiple axle quarter frame end dump trailer (1994)
  - [US5431475A](https://patents.google.com/patent/US5431475A/en) Body for end dump trailer (1993)
  - [US6719360B1](https://patents.google.com/patent/US6719360B1/en) Trailer body construction (2002)
  - [CA2211333A1](https://patents.google.com/patent/CA2211333A1/en) Swing-away dump blocks
  - [US10625651B1](https://patents.google.com/patent/US10625651) "End dump trailer and modular extrusions therefor" came up in the Travis search; its assignee is unverified
- **Vantage**:
  - [US20090085394A1](https://patents.google.com/patent/US20090085394A1/en) Belly dump trailer (2007)
  - [US7971926B2](https://patents.google.com/patent/US7971926B2/en) Reduced-weight wall construction
  - [US20080143142A1](https://patents.google.com/patent/US20080143142A1/en) Double-wall extruded panel nose
  - [US20070007759A1](https://patents.google.com/patent/US20070007759A1/en) Reduced-weight beam
  - [US6592170B2](https://patents.google.com/patent/US6592170B2/en) Bottom rail
  - [US20020053814A1](https://patents.google.com/patent/US20020053814A1/en) Tapered trailer with horizontal seams
- **SmithCo**:
  - [US6905175B1](https://patents.google.com/patent/US6905175B1/en) Bidirectional side dump trailer with improved tub lift system (2003)
  - [US9150135B1](https://patents.google.com/patent/US9150135B1/en) Coupling member for side dump trailer (2012)
  - [US20240083526A1](https://patents.google.com/patent/US20240083526A1/en) Kingpin assembly (2022)
- **Timpte**:
  - [US8371657B2](https://patents.google.com/patent/US8371657B2/en) Storage hopper assembly (2010)
  - [US6814532B1](https://patents.google.com/patent/US6814532B1/en) Self-unloading, bottom discharge trailer (2003)
  - [CA2374078A1](https://patents.google.com/patent/CA2374078A1/en) Belt trap door closure
  - [US3248151A](https://patents.google.com/patent/US3248151A/en) Chip dump trailer (1964)
- **Wilson Trailer**:
  - [US10889429B2](https://patents.google.com/patent/US10889429B2/en) Converting a commodity trailer with gates (2018)
  - [CA2261522A1](https://patents.google.com/patent/CA2261522A1/en) Trap closure device for trailer hoppers (1998)
  - [US4437699A](https://patents.google.com/patent/US4437699A/en) Monocoque trailer/body side construction (1981)
- **Trail King**:
  - [US12528399B2](https://patents.google.com/patent/US12528399B2/en) Grain trailer (priority 2019)
  - [US20120086194A1](https://patents.google.com/patent/US20120086194A1/en) Saddle frame for pneumatic bulk trailer
- **Doepker**:
  - [US9340140B1](https://patents.google.com/patent/US9340140B1/en) / [CA2869439C](https://patents.google.com/patent/CA2869439C/en) Dry goods bulk trailer with uninterrupted slope sheet (2014)
  - Design patent [USD786942S1](https://patents.google.com/patent/USD786942S1/en) Hopper trailer, all drawings
  - [CA2690684C](https://patents.google.com/patent/CA2690684C/en) Dump trailer with adjustable tipping hinge (2009)
- **Manac / CPS**:
  - Design patents [USD920855S1](https://patents.google.com/patent/USD920855S1/en) Lightweight bottom dump trailer beam and [USD938317S1](https://patents.google.com/patent/USD938317S1/en) connector plate (Manac Trailers USA, 2018)
  - [US20220135137A1](https://patents.google.com/patent/US20220135137A1/en) Light-weight beam assembly
- **Midland Manufacturing Ltd**:
  - [US20210023975A1](https://patents.google.com/patent/US20210023975A1/en) Fracturing sand dump trailer (2019)
  - [CA2250413C](https://patents.google.com/patent/CA2250413C/en) Control device for trailer gates
  - [CA2058661A1](https://patents.google.com/patent/CA2058661A1/en) Road vehicle having a rear dump box
- **Etnyre**:
  - [US6386818B1](https://patents.google.com/patent/US6386818B1/en) Live bottom trailer with extendible rear (2000)
  - [US5934862A](https://patents.google.com/patent/US5934862A/en) / [US6186732B1](https://patents.google.com/patent/US6186732B1/en) Conveyor mechanism (Falcon-type live bottom)
- **Hallco (live floor)**:
  - [US8887896B1](https://patents.google.com/patent/US8887896B1/en) Liquid-tight reciprocating floor
  - [US10059527B1](https://patents.google.com/patent/US10059527B1/en) Raised reciprocating slat conveyor with floor pan
  - [US11713196B1](https://patents.google.com/patent/US11713196B1/en) Mounting a conveyor drive
  - [US7926646B1](https://patents.google.com/patent/US7926646B1/en) Double-sealed bearingless conveyor
- **Trinity Trailer Mfg (Idaho, belt trailers)**:
  - [US9555730B1](https://patents.google.com/patent/US9555730B1/en) Discharge apparatus for self-unloading bulk material bed
- **Dorsey Trailer LLC**:
  - [US20260131865A1](https://patents.google.com/patent/US20260131865A1/en) Side rail for trailer (2024)
- **Western Trailer Co.**:
  - [US20210214009A1](https://patents.google.com/patent/US20210214009A1/en) Attaching crossmembers
  - [US4475672A](https://patents.google.com/patent/US4475672A/en) Hopper discharge device (Whitehead)
- **Merritt Equipment** (historic): [US3796457A](https://patents.google.com/patent/US3796457A/en) Trailer construction (1972)
- **Ledwell**: only [US5690465A](https://patents.google.com/patent/US5690465A/en) (carcass pickup vehicle), which is not trailer-relevant
- Other relevant design and utility patents surfaced by search, assignees not verified:
  - [USD483697S1](https://patents.google.com/patent/USD483697) End dump trailer
  - [US9085331B1](https://patents.google.com/patent/US9085331) Teardrop semi end dump trailer
- Source for the counts: Google Patents assignee queries run 30 Oct 2026 — [Google Patents](https://patents.google.com/)

### Inferences
- Patent figures are the most reliable public source of **structural cross-sections** for these trailers: wall extrusions, rails, beams and slope sheets. Vantage, Travis, Manac and Doepker have the most structurally detailed sets.

### Gaps
- Google rate-limited the assignee queries for Keith Manufacturing, J&L Tank, Galion and Jet Co. Keith Walking Floor patents (inventor Raymond Keith Foster) are numerous but not listed here.
- The "Ranco" and "Neville" assignee queries were swamped by unrelated companies (Ranco Inc. thermostats). LBT, Ox Bodies and CTS returned no results.

## Q5. CAD/CAE software evidence by company (job postings, case studies, trade press)

### Takeaway
Direct evidence is thin. The confirmed or near-confirmed data points are:
- SmithCo: SolidWorks and AutoCAD, from a 2026 job post.
- Polar Tank Trailer: AutoCAD drawings plus Autodesk Inventor and Vault, from a Designer III job post (search snippet; the page has since expired).
- MaXfield, a Canadian tank-trailer builder: moved from AutoCAD to Inventor to SolidWorks Premium with Simulation, Routing and PDM (Javelin case study).

I found **no public evidence** of the CAD or design-calculation software used by Tremcar, Heil, Wabash/Brenner/Walker, LBT, Wilson, Timpte, Doepker, Manac, Ranco, Vantage or Travis.

### Cited Findings
- **SmithCo (Le Mars, IA).** A "Mechanical Design Engineer" listing (dated 5 Aug 2026 per the search snippet) says to "Design and develop parts, assemblies, and trailer systems using SolidWorks and AutoCAD", produce manufacturing drawings and print packages, and have "CAD software, preferably SolidWorks". The page returned 403 to direct fetch — [SolidProfessor job 358084](https://jobs.solidprofessor.com/job/358084/mechanical-design-engineer/), [SmithCo on SolidProfessor](https://jobs.solidprofessor.com/company/15281/smithco-manufacturing/)
- **Polar Tank Trailer.** A "Designer III" posting (search snippet): "Read and decipher AutoCAD drawings. Operate Inventor and Vault to create accurate drawings"; US citizen or green card required. The listing now returns HTTP 410 — [mediabistro posting](https://www.mediabistro.com/jobs/1957380761-designer-iii), [second posting](https://www.mediabistro.com/jobs/2014625688-designer-iii)
- **MaXfield (Alberta; tank trailers about half of its business)**:
  - AutoCAD 2D in the 1990s, then Autodesk Inventor in 2000
  - after five years, "engineers continually reverted back to AutoCAD 2D"
  - moved to **six seats of SOLIDWORKS Premium in early 2006**, valuing SOLIDWORKS Simulation (structural), Routing (piping) and PDM
  - "A tank trailer includes between 500 and 750 individual components"
  - [Javelin case study](https://www.javelin-tech.com/3d/expanding-efficiencies-canadian-tank-trailer-design/)
- **Trail King.** A "Senior Engineer (TKM159)" posting in Mitchell, SD, pays $95K–$115K; the snippet names no CAD package — [TheLadders](https://www.theladders.com/job/senior-engineer-tkm159-trail-king-industries-mitchell-sd_84543620)
- **Wilson Trailer.** A "Manufacturing Engineering Technician — CNC/CAD Specialist" posting in Lennox, SD, starts at $25/h; the snippet names no CAD package — [Vaia listing](https://talents.vaia.com/companies/wilson-trailer-company/manufacturing-engineer-tech-cnc-cad-specialist-151459587/)
- **Tremcar.** Searches in English and French for Tremcar design, drafting or engineering postings that name SolidWorks, Inventor or AutoCAD found nothing. The only Tremcar posting found was for production (welding/assembly). A CSSDHR school-board partnership document exists but has no CAD details — [SimplyHired Tremcar listing](https://www.simplyhired.ca/job/eB99AurmC4JE0wQ1ehxK5cpq9CfeC6ceeYNgD-89ipE4yIWSSvcmKA), [CSSDHR partnership PDF](https://www.cssdhr.gouv.qc.ca/wp-content/uploads/2019/10/Partenariat-SAE-Tremcar-F-19-12-2018.pdf)
- Context only (other trailer builders, from search snippets):
  - Kinetic Custom Trailers (Waco, TX): "3D models and 2D drawings for trailer structures… using SolidWorks" — [designproject.io](https://designproject.io/jobs/jobs/mechanical-design-technologist-engineer-eit-at-kinetic-custom-trailers-15t7yq)
  - A tanker-systems engineer's LinkedIn describes Autodesk Inventor with Inventor Nastran for structural analysis — [LinkedIn profile](https://ro.linkedin.com/in/manuel-ungureanu)
- PDF metadata on every OEM brochure or manual I downloaded names DTP tools (InDesign, Photoshop, Illustrator, QuarkXPress, Word, Publisher, Chromium), not CAD. Keith's drawing PDF was distilled through Acrobat 10 / Ghostscript, so it carries no CAD signature (see the Q1–Q3 PDF links).

### Inferences
- Based on regional peers and the evidence above, SolidWorks (with Simulation/PDM) and Autodesk Inventor/Vault (with AutoCAD for legacy 2D) are the likely tools across this segment. That is an inference, not a confirmed fact for any company other than SmithCo, Polar and MaXfield.
- Cargo-tank design calculations for DOT 406/407/412 (shell thickness, head design, accident-damage protection) are typically done in spreadsheets or ASME Section VIII calculation software and then signed off by the registered Design Certifying Engineer (see Q7). I found no public source naming the calculation package for any maker in scope.

### Gaps
- I found no vendor case studies (Dassault, Autodesk, PTC, Siemens) for Tremcar, Heil, Wabash tank, Wilson, Timpte, Doepker, Manac, Travis, Ranco or Vantage. A LinkedIn people-search (skills fields) would likely fill this in, but it needs a login and was not attempted.

## Q6. Tremcar (the user's "Trimcar"): websites, products, spec sheets and drawings, software, patents

### Takeaway
Tremcar (Saint-Jean-sur-Richelieu, QC) builds TC/DOT 406, 407, 412 and 423 cargo tanks plus sanitary, dry-bulk, farm-pickup and vacuum tanks. Its website sits behind a reCAPTCHA "Bot Verification" wall, so I could not inventory any OEM PDFs. Public dimensional data comes from dealer listings (OD, MAWP, length, compartments). Tremcar holds at least 6 patents and applications, the main drawing-rich one being US11014486B2. I found no public evidence of its CAD or design software.

### Cited Findings
- `tremcar.com` and `tremcar.com/en` both serve a reCAPTCHA "Bot Verification" interstitial to non-browser clients; I did not bypass it — [tremcar.com](https://www.tremcar.com/)
- The NHTSA vPIC manufacturer record lists:
  - Tremcar, 790 Avenue Montrichard, St-Jean-sur-Richelieu, QC
  - **WMI 2TL**
  - makes/models: "Dry-Bulk, Farm-Pick Up, Non-Code, Sanitary, TC/DOT 406, TC/DOT 407, TC/DOT 412, TC/DOT 423"
  - a Chief Engineer as the listed contact (record updated 15 Jul 2020)
  - [NHTSA vPIC Tremcar](https://vpic.nhtsa.dot.gov/decoder/Manufacturer/Details/19927)
- A dealer listing for model 30114SF describes a "DOT-407 / TC-407 SS chemical tanker… tandem… cylindrical **66.375" O.D.**… MAWP 25 PSIG, test 45 PSIG, temp 250 F" (search snippet) — [TruckPaper 2026 Tremcar 7000 gal](https://www.truckpaper.com/listing/for-lease/251443183/2026-tremcar-7000-gallon?print=1)
- Other listings:
  - a 2027 4-axle TC-407 unit in 316 stainless with OAL 48'6" — [TruckPaper 2027 Tremcar](https://www.truckpaper.com/listing/for-sale/258310543/2027-tremcar?print=1)
  - a 2009 9,500 gal double-conical DOT 407 — [TruckPaper 2009](https://www.truckpaper.com/listing/for-sale/250718931/2009-tremcar-9500-gal?print=1)
  - pneumatic dry bulk from 1,000 to 1,625 ft³ — [MyLittleSalesman 1000 ft³](https://www.mylittlesalesman.com/2024-tremcar-1000-cu-ft-aluminum-dry-bulk-pneumatic-tank-trailer-12530408), [TruckPaper 1625 ft³](https://www.truckpaper.com/listing/for-lease/251442429/2026-tremcar-1625-cu-ft?print=1)
- Company background (search snippets):
  - founded 1962 by the Tougas brothers as A & L Tougas Ltd; family-owned by the Tremblays
  - "one of the 4 largest tank trailer manufacturers in North America"
  - (snippet) four Canadian and two US plants, including Strasburg, Ohio (mainly petroleum)
  - [truckertotrucker Tremcar](https://truckertotrucker.com/tremcar-trailers), [Trucknews "Tremcar reaches a milestone"](https://www.trucknews.com/features/tremcar-reaches-a-milestone/) (403 to direct fetch)
- Product videos: [Trucknews: Tremcar hot product and petroleum trailers](https://www.trucknews.com/videos/tremcar-hot-product-and-petroleum-trailers-2)
- Patents (Google Patents, `assignee=Tremcar`, 6 results):
  - [US11014486B2](https://patents.google.com/patent/US11014486B2/en), inventor Daniel Tremblay, 13 figures, layout of ground-level side-mounted operating devices
  - [CA3168374A1](https://patents.google.com/patent/CA3168374A1/en)
  - [US7140211B2](https://patents.google.com/patent/US7140211B2/en)
  - [CA2467217C](https://patents.google.com/patent/CA2467217C/en)
  - [CA2447358A1](https://patents.google.com/patent/CA2447358A1/en)
- Software: no Tremcar-specific CAD, CAE or tank-calculation evidence found (see Q5). A TurboSquid artist model of a Tremcar 7000 gal tank exists, but it is not OEM data — [TurboSquid](https://www.turbosquid.com/3d-models/3d-2026-tremcar-7000-gallon-tank-trailer-silver-2600789)

### Inferences
- As a DOT/TC specification cargo-tank builder, Tremcar must hold Design Certifying Engineer certificates, including drawings and calculations, for each design type (49 CFR 178.320; Canada's CSA B620/TC equivalents). Those stay private (Q7).
- The most useful public Tremcar "geometry" is the combination of dealer listings (OD, length, MAWP), the US11014486B2 figures and the NHTSA vPIC model list.

### Gaps
- I could not verify Tremcar's own spec sheets or brochure PDFs (bot wall). A human browser visit is needed.
- I found no Transport Canada / CSA B620 facility-registration listing for Tremcar (not researched).
- The plant list (Saint-Jean-sur-Richelieu plus others, and Strasburg OH) comes from search snippets only.

## Q7. DOT cargo-tank regulatory filings: what is public versus not (49 CFR 178.320 / 178.345 / 180.417 / 107 Subpart F)

### Takeaway
Design drawings and calculations for DOT 406, 407 and 412 cargo tanks are **required to exist and be certified, but are not filed with or published by PHMSA or FMCSA**. The Design Certifying Engineer gives a certificate, including the sketches, drawings and calculations, to the manufacturer. The manufacturer retains it, and the owner retains the certificates and the ASME U1A data report. What is public:
- the registry of cargo-tank facilities (FMCSA CT numbers, searchable)
- PHMSA special permits and interpretation letters
- NHTSA manufacturer-identification and TSB/recall documents

### Cited Findings
- 49 CFR 178.320(b) **design certification**:
  - "(1) Each cargo tank or cargo tank motor vehicle design type… must be certified… by a Design Certifying Engineer who is registered in accordance with subpart F of part 107"
  - "(2) …The certificate must include the sketches, drawings, and calculations used for certification. Each certificate, including sketches, drawings, and calculations, shall be signed by the Design Certifying Engineer"
  - "(3) The manufacturer shall retain the design certificate at his principal place of business for as long as he manufactures DOT specification cargo tanks"
  - [49 CFR 178.320 (LII)](https://www.law.cornell.edu/cfr/text/49/178.320)
- 49 CFR 178.320(a) defines **"design type"** as tanks made "to the same engineering drawings and calculations… same cross-sectional dimensions… length varying by no more than 5 percent… volume varying by no more than 5 percent" — [49 CFR 178.320](https://www.law.cornell.edu/cfr/text/49/178.320)
- 49 CFR 178.345-15 requires the manufacturer to provide **the owner** with:
  - for each design type, a certificate signed by a responsible official and a DCE
  - for ASME tanks, the ASME Section VIII manufacturer's data report
  - for each CTMV, a Registered Inspector certificate
  - the registration numbers of the manufacturer, DCE and Registered Inspector must appear on the certificates
  - [49 CFR 178.345-15](https://www.law.cornell.edu/cfr/text/49/178.345-15)
- 49 CFR 180.417(a): the owner must retain "the manufacturer's certificate, the manufacturer's ASME U1A data report, where applicable, and related papers… throughout his ownership… and for one year thereafter". Motor carriers using the tank must obtain copies — [49 CFR 180.417](https://www.law.cornell.edu/cfr/text/49/180.417)
- 49 CFR 107.502: registrants receive "a separate registration number… for each cargo tank manufacturing, assembly, repair facility" — [49 CFR 107.502](https://www.law.cornell.edu/cfr/text/49/107.502)
- PHMSA interpretations (search snippets):
  - DCE registration runs through the employer
  - issuing a CT registration number "is not an approval or endorsement… of the qualifications of any person" (citing 107.504(f))
  - [PHMSA interp 140010](https://www.phmsa.dot.gov/sites/phmsa.dot.gov/files/legacy/interpretations/Interpretation%20Files/2014/140010.pdf), [PHMSA interp 080125](https://www.phmsa.dot.gov/sites/phmsa.dot.gov/files/legacy/interpretations/Interpretation%20Files/2008/080125.pdf)
- FMCSA administers cargo-tank facility registration (CT numbers for manufacture, assembly, inspection, testing, DCE certification and repair). It offers a public "Search for Cargo Tank Facilities" tool and a data.gov dataset, "SAFER – Cargo Tank Facility", listing manufacturer and repair facilities. These are listings, not drawings — [FMCSA Cargo Tank Registration and Resources](https://www.fmcsa.dot.gov/carrier-safety/hazardous-materials-safety/cargo-tank-registration-and-resources), [data.gov SAFER Cargo Tank Facility](https://catalog.data.gov/dataset/safer-cargo-tank-facility), [FMCSA registration form](https://www.fmcsa.dot.gov/sites/fmcsa.dot.gov/files/2023-06/cargo%20tank%20facility%20registration%20form%206-6-23%20508_0.pdf)
- PHMSA **special permits** are public and can describe design and material deviations. Example: DOT-SP 14573, issued to Polar Tank Trailer, LLC, covers DOT 406/407/412 tanks built from duplex stainless steels (search snippet; 403 to direct fetch; expiry 2028-05-31 per snippet) — [DOT-SP 14573](https://www.phmsa.dot.gov/hazmat/documents/offer/SP14573.pdf/offerserver/SP14573)
- NHTSA public records add manufacturer-identity data (vPIC/Part 566: WMI, models, engineering contact role) and dealer communications or manuals (e.g. the Heil manual in the TSB archive) — [NHTSA vPIC Tremcar](https://vpic.nhtsa.dot.gov/decoder/Manufacturer/Details/19927), [NHTSA-hosted Heil manual](https://static.nhtsa.gov/odi/tsbs/2016/MC-10166613-9999.pdf)
- Access note: eCFR (ecfr.gov) redirected automated requests to unblock.federalregister.gov, so I quoted the CFR text from Cornell LII — [LII 49 CFR 178.320](https://www.law.cornell.edu/cfr/text/49/178.320)

### Inferences
- Public versus private:
  - **Private:** DCE certificates with drawings and calculations (held by the manufacturer), U1A/data reports and certificates (held by the owner and carrier), and the inspection and test reports under 180.417(b)
  - **Public:** who is registered (FMCSA CT search), special permits and their conditions, PHMSA interpretations, and NHTSA identity and TSB/recall documents
- A used-tank buyer or owner can legally obtain the certificate package, sometimes including the certified drawings, through the 180.417 owner chain. In practice this is the main non-public channel through which cargo-tank "blueprints" circulate.

### Gaps
- I did not test the live FMCSA cargo-tank facility search (e.g. for Tremcar, Heil, Polar or LBT CT numbers). The data.gov dataset's current access URL is unverified.
- I did not research the Canadian equivalent (Transport Canada facility registration under CSA B620/B622, TC 406/407/412 marks).
- Not checked: whether NHTSA recall filings (Part 573 reports) for these tank makers include drawings. Many Part 573 packets include parts diagrams, so this is a promising next step.
