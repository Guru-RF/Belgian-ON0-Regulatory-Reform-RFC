# RFC: Modernisation of Belgian ON0 Amateur Radio Station Authorisations

**Status:** Draft for discussion — not an adopted UBA position or BIPT rule  
**Version:** 0.1  
**Date:** 21 October 2026  
**Scope:** Belgian unattended amateur radio stations (ON0), including repeaters, beacons and other authorised automatic stations  
**Intended audience:** UBA, other recognised amateur-radio associations and qualifying clubs, BIPT/IBPT, and the competent federal authorities  
**Language:** English working draft; legal wording should be prepared and checked in Dutch and French before formal submission

> **Important:** This document is a regulatory reform proposal (RFC). The classifications, free notifications, and new power-authorisation model described below are **not current law**. No operator should change a characteristic requiring prior BIPT approval merely because this RFC proposes a free notification procedure.

## 1. Executive summary

Belgian unattended amateur radio station licences currently combine legal authorisations with detailed installation characteristics. Changes to those characteristics can be treated as fee-bearing modifications even where the actual operating rights, interference impact, or RF coverage have not increased.

This RFC proposes:

1. **Three categories of administrative actions:**
   - **A — Fundamental changes:** substantive changes requiring assessment and approval; chargeable.
   - **B — Corrections and minor technical notifications:** clerical corrections, maintenance updates and non-substantive changes; free.
   - **C — Voluntary termination or reduction:** surrender of a station or frequency; free, with a credit for unexpired annual fees where a corresponding fee was paid and the applicable refund rules permit it.
2. **A better power model:** use the power delivered to the antenna and **ERP/EIRP**, including the RF path losses and antenna gain, as principal coordination parameters instead of relying solely on a transmitter-output figure.
3. **Two distinct datasets:** the **authorised operational envelope** and the **actual installation**. Hardware changes that remain within the envelope should normally require only notification.
4. **A streamlined technical register:** allow associations and station managers to maintain accurate data, ideally through a digital workflow such as `on0.be`, while preserving BIPT's final regulatory authority.
5. **A targeted legal change:** clarify the fee provisions and the legal treatment of corrections, RX-only changes, partial surrender and power limits.

The objective is to improve **spectrum management, interference coordination, technical accuracy and administrative efficiency**, not to reduce regulatory oversight where it is genuinely needed.

## 2. Problem statement

At present, changes recorded in an ON0 licence may entail an amendment and associated costs even when they do not extend the station's authorised transmission rights.

Examples include:

- Lowering RF output power.
- Replacing an antenna or a mast without materially changing the site footprint.
- Updating measured antenna gain or feeder loss.
- Changing a cavity, duplexer, combiner, filter or feeder.
- Updating whether an internet connection is used, without otherwise changing authorised operation.
- Correcting an error introduced when preparing an authorisation.
- Changing a receiver frequency without changing the station's own transmitted frequency or technical limits.
- Voluntarily relinquishing an unused frequency.

Treating these events like an additional TX frequency or a relocation can impose disproportionate costs and encourages operators to leave obsolete information in the licensing database. Charging to surrender a frequency can also discourage prompt release of unused spectrum.

A second issue is that the output of an individual transmitter is not necessarily the RF power presented to the antenna. Repeaters routinely use cavities, duplexers, multicouplers, filters, combiners and long feeder runs. A power field that ignores these losses can misrepresent the actual transmitted signal used in coverage and interference planning.

## 3. Goals and non-goals

### Goals

- Charge application fees where a **substantive regulatory assessment** is necessary.
- Make clerical corrections and routine non-substantive updates **free and straightforward**.
- Make voluntary surrender of stations or frequencies **free of new application charges**.
- Apply a credit for unused annual fees where an individually charged station or right is terminated and the legal conditions for credit are met.
- Improve the accuracy of RF calculations using real installed-system parameters.
- Preserve BIPT's authority to review potential interference, safety, compliance and spectrum-use issues.
- Make the same procedures available to every eligible amateur-radio association or club, not only one organisation.

### Non-goals

- No automatic right to additional frequencies, higher radiated power or new station sites.
- No exemption from general band-specific power limits, occupied-bandwidth limits or other applicable amateur-radio rules.
- No exemption from RF-exposure, EMC, spurious-emission or site-compatibility requirements.
- No proposal to make existing non-compliant technical changes retrospectively lawful.
- No guarantee that a partial frequency surrender creates a monetary refund when no annual fee is charged for that frequency separately.

## 4. Proposed three-category administration

### Category A — Fundamental modifications (chargeable)

A change that creates or materially extends a transmitting right, changes the site requiring coordination, or requires a substantive technical assessment.

**Proposed process:** application -> association/coordination review as relevant -> BIPT approval -> amended authorised envelope -> applicable modification fee.

Examples:

- Establishing a new ON0 station.
- Adding a new TX frequency or independently authorised transmitter/station.
- Changing the assigned TX frequency.
- Moving to a different transmission site.
- Increasing authorised maximum ERP/EIRP or another binding power ceiling.
- Changing emission characteristics, bandwidth, duty cycle, antenna pattern or height in a way that materially changes interference or coverage assumptions.
- A substantive change to the authorised station holder or responsible persons where the applicable legislation requires formal reassessment.

A change is not automatically minor simply because it is physically small. For example, increasing antenna height by two metres may be insignificant at one site but important at another.

### Category B — Corrections and minor technical notifications (free)

A clerical correction or a real installation change that does **not** expand the authorised operational envelope or materially worsen coordination, interference or safety conditions.

**Proposed process:** simple correction/notification -> automatic technical checks -> updated installation record; escalation to BIPT only when a defined technical threshold is crossed. **No application fee.**

Examples, subject to the stated conditions:

- Correcting a BIPT transcription or administrative error against the original application.
- Correcting a wrong callsign, contact detail or other clerical data without changing the legal holder.
- Reducing transmitted power.
- Replacing transmitter hardware while staying within licensed limits.
- Replacing or retuning a combiner, cavity, duplexer or filter.
- Updating measured combiner, feeder or insertion losses.
- Replacing an antenna with an electrically equivalent antenna.
- Updating reported antenna gain without exceeding the authorised radiated-power or pattern limits.
- Mast replacement at the same site and with equivalent relevant characteristics.
- Minor antenna-height or pattern changes **only if demonstrated to be non-substantive** under agreed BIPT criteria.
- Updating internet connectivity **Yes/No**, provided it does not enable an activity requiring new prior approval.
- Changing an RX-only frequency where no new TX rights are created, subject to frequency coordination and protection of other users.
- Replacing or updating station-management and remote-shutdown equipment.

**Important differentiation:** a *correction* repairs inaccurate records; a *technical notification* records a genuine change. Both are proposed to be free, but may follow different verification procedures.

### Category C — Voluntary surrender or reduction (free)

**Proposed process:** authenticated termination/deletion notice -> effective termination date -> immediate register update -> BIPT confirmation -> credit of applicable unused annual charges. **No new application fee for the act of surrender.**

Examples:

- Surrendering an entire ON0 authorisation.
- Deleting a TX frequency while keeping a station in operation.
- Removing one of several separately authorised/billed stations.
- Reducing the scope of a licence or relinquishing an unused allocation without requesting replacement transmission rights.

**Refund principle:** reimburse/credit only the **unexpired portion of annual charges actually attributable to the terminated licence, station or right**, according to the applicable statutory rules. Do not presume a separate per-frequency refund where the annual charge is per station rather than per frequency. Previously incurred application fees are distinct from unused annual fees and are not proposed to be refunded automatically.

### Summary matrix

| Event | Proposed class | New application fee? | Coordination / review |
|---|---|---|---|
| New ON0 authorisation | A | Yes | Full |
| Add or change TX frequency | A | Yes | Full/targeted |
| Change site | A | Yes | Full/targeted |
| Request higher maximum ERP/EIRP | A | Yes | Full/targeted |
| Change legally responsible persons | A or B* | Depends | Identity/eligibility verification |
| Correct regulator transcription error | B | No | Administrative |
| Reduce power | B | No | Automated check/record update |
| Equipment/filter/combiner replacement within authorised envelope | B | No | Technical notification |
| Gain, loss or antenna update within envelope | B | No | Automated check; escalate if material |
| Equivalent mast replacement | B | No | Notification |
| Antenna height change | A or B* | Depends | Impact-based |
| Internet access Yes/No with no other operating change | B | No | Notification |
| RX-only frequency change | B | No | Planning/coordination |
| Surrender one TX frequency | C | No | Register update |
| Surrender entire station | C | No | Termination and eligible credit |

\* **Open question:** establish objective criteria for which responsible-person changes or antenna modifications require regulatory approval. Do not automatically classify all of them as free.

## 5. RF power: licence the real antenna system

### 5.1 Why the current field is not enough

A stand-alone **transmitter hardware output** figure is inadequate for coordination when the RF chain contains significant losses. Even where the licence's power field is legally interpreted as the output of the *transmitting installation*, rather than the transmitter hardware, BIPT and operators benefit from explicitly distinguishing:

1. **P_TX,hardware:** RF power at the transmitter output connector.
2. **L_system:** combiner/duplexer/cavity/filter losses.
3. **L_feeder:** feeder, connector and other losses before the antenna input.
4. **P_antenna:** RF power delivered to the antenna feedpoint.
5. **G_antenna:** antenna gain in dBi or dBd, with the reference stated.
6. **ERP/EIRP:** effective radiated power including gain, used for coverage and interference studies.

The existing Royal Decree itself distinguishes the transmitting installation (including filters, splitters and cavities), output power, power delivered to the antenna and effective radiated power. This RFC asks that those distinctions be reflected consistently in ON0 permits and databases.

### 5.2 Worked example: combiner loss

Suppose:

- Transmitter hardware output: **100 W**.
- Total loss from transmitter output to antenna feedpoint: **6 dB**.
- Antenna gain: **7.15 dBi**.

Then:

```text
P_antenna = P_TX × 10^(−L_total/10)
          = 100 W × 10^(−6/10)
          ≈ 25.1 W

EIRP_dBm  = P_TX_dBm − L_total_dB + G_antenna_dBi
          = 50.0 dBm − 6.0 dB + 7.15 dBi
          = 51.15 dBm
EIRP      ≈ 130 W
ERP       ≈ 80 W  (using 2.15 dB for isotropic-to-dipole conversion)
```

A 25 W transmitter with almost no RF-path loss and the same antenna would generate approximately the same **maximum EIRP**. The 100 W transmitter may therefore be a legitimate engineering choice for a combiner-fed installation, **provided the applicable legal power limits and all other compliance conditions are respected**.

This does **not** mean that operators may always use a 100 W transmitter simply by documenting 6 dB loss. The statutory definition of transmitting-installation output and band-specific limits require formal clarification with BIPT before changing the authorisation model.

### 5.3 Proposed power model

**Primary regulatory/planning values:**

- Maximum permitted **ERP or EIRP**, stating which reference is used (one preferred standard should be selected for all ON0 licences).
- Maximum permitted power at the antenna input, where needed by law or technical condition.
- Location, antenna height, polarisation, radiation pattern, occupied bandwidth and other material coordination characteristics.

**Actual installation data (updatable by free notification within limits):**

- TX hardware output power.
- Combiner/duplexer/cavity/filter losses.
- Feeder and connector losses.
- Antenna gain, pattern and orientation.
- Calculated power delivered to antenna and ERP/EIRP.
- Measurement date, method and responsible contact.

**Constraint:** a hardware change can be notified without a paid licence modification only when the entire station remains within *all* binding limits and materially equivalent coordination conditions, not just its maximum ERP/EIRP.

Antenna pattern, height and site geography remain relevant: two antennas with the same maximum EIRP can produce very different interference footprints. Transmitter hardware power also matters for site intermodulation, cavity power handling, spurious outputs and RF exposure. Those are separate compliance concerns, not reasons to use raw transmitter power as the sole coordination metric.

## 6. Authorised envelope versus installed configuration

The licence and register should distinguish two linked records:

### A. Authorised envelope — BIPT-controlled

- Authorisation identifier and callsign.
- Authorised site/coordinates.
- Authorised TX frequency or frequencies.
- Authorised emission class, occupied bandwidth and applicable station type.
- Maximum allowed radiated power and any other legal power ceiling.
- Material antenna/environmental constraints (height, pattern, polarisation, etc., as required).
- Licence holder and authorised responsible persons.
- Any special operating conditions and required control mechanisms.

### B. Operational inventory — station-managed, auditable

- Actual transmitter model and configured power.
- RF path diagram, combiners, cavities, duplexers, filters and measured losses.
- Antenna model, height, gain, orientation and pattern.
- Actual calculated radiated power (with units and reference).
- Receiver frequencies and coordination notes.
- Internet connectivity status and network links.
- Remote control/remote shutdown contacts.
- Date of last verification and a history of changes.

**Rule:** updating inventory data inside an unchanged authorised envelope should not by itself trigger a fee or require reissuance of a licence PDF. Where a reported change crosses a binding limit, it must be treated as Category A and approved before operation.

## 7. RX frequencies: coordination rather than new TX rights

A receiver frequency is relevant to **frequency planning**, but receiving on a frequency is not equivalent to the unattended station being granted another transmitted frequency.

**Proposed approach:**

- Record RX frequencies and repeater input relationships in the coordination register.
- Allow RX-only adjustments at no fee where the ON0 station's authorised TX frequency, power and emission characteristics remain unchanged.
- Require appropriate coordination when an RX change affects other systems or changes how users are expected to transmit.
- Keep the distinction explicit between **the repeater's own TX authorisation** and the separate rights/obligations of users transmitting to the receiver.

This is a proposal for administrative treatment, not an assertion that RX changes can currently be implemented without any authorisation check.

## 8. Example from an actual ON0 licence (ON0RFG)

The supplied ON0RFG licence, dated **15 September 2026**, has an annex displaying these technical characteristics:

| Field | Entry in annex |
|---|---|
| Station type | Simplex |
| TX frequency | 434.89000 MHz |
| TX/output power | 50.00 W |
| Emission class | 62K5F1D |
| Antenna gain | 7.15 dBi |
| Antenna height | 16 m |
| Polarisation | Vertical |
| Internet access authorised | Yes |
| Loss field | Present, but no numerical dB value entered |

*Source: attached ON0RFG licence, annex on page 3. Personal contact information is deliberately omitted from this RFC.*

The annex already has separate antenna-gain and loss fields, but the loss value is blank. It gives no explicit calculated power at the antenna input or corresponding ERP/EIRP. This is a useful illustration of the proposed improvement: record the complete RF path and derived radiated power, and distinguish the approved limit from the current installation.

The example is **illustrative only**; it does not establish that this licence contains an error or that its present power limit may be exceeded.

## 9. Current legal framework and likely amendment route

> **Legal caution:** References below describe the legal basis found in the published texts. The amendments are historical; an authoritative consolidated version, any later changes, and BIPT's current administrative interpretation must be checked by legal reviewers before submission.

- **Royal Decree of 18 December 2009**, concerning private radiocommunications and usage rights, is the principal framework.
- **Article 1** defines the transmitting installation, power at its output, power at antenna input, and effective radiated power. It includes ancillary RF equipment such as filters, splitters and cavities in the definition of the transmitting installation.
- **Article 35**, as amended, provides for an application fee and for a modification fee equal to half the application fee. An express general exception for the proposed Category B and partial Category C actions should be considered.
- **Article 43**, as amended in 2013 and 2018, provides for a credit note when a station is decommissioned, covering the remaining days, with a minimum charge of 30 days. Its application to *partial* deletion of a frequency from a multi-frequency licence needs clarification. There is no basis to assume a per-frequency refund where no separate annual per-frequency right was paid.
- **Article 44** provides annual indexation of amounts. BIPT publishes the resulting tariffs, but an exemption overriding a mandatory Royal Decree fee will normally require a change in the relevant regulation rather than a unilateral tariff decision.
- The **BIPT decision of 24 May 2019** governs amateur frequency bands, powers and transmission modes. Any new ON0 power model must remain compatible with those requirements or the relevant decision must be amended as part of the reform.

**Regulatory route proposed:**

1. Ask BIPT which Category B and C actions can already legally be handled as corrections, notifications or surrender without invoking a paid amendment.
2. Agree formal criteria and a technical validation procedure.
3. Where fees are mandatory under Article 35, propose a **narrow Royal Decree amendment** distinguishing chargeable substantive amendments from free corrections, notifications and voluntary reductions.
4. If necessary, amend ON0 permit templates, BIPT technical guidance and/or applicable frequency/power decisions to support the authorised-ERP/EIRP model while preserving statutory limits.
5. Consult all eligible associations and clubs and the competent federal authority.

## 10. Suggested principle for a regulatory amendment

### Working Dutch wording — not a final legal draft

> Voor vergunningen van onbemande radioamateurstations is geen bijkomend dossierrecht verschuldigd voor de rechtzetting van administratieve fouten, de melding van niet-wezenlijke technische wijzigingen die binnen de vergunde gebruiksvoorwaarden blijven, wijzigingen van uitsluitend ontvangfrequenties die geen nieuwe zendrechten doen ontstaan, of de vrijwillige gehele of gedeeltelijke afstand van vergunde zendfrequenties of stations.
>
> Een wijziging is wezenlijk wanneer zij nieuwe zendrechten verleent of een nieuwe technische beoordeling vereist wegens een materiële wijziging van de storings-, dekkings- of veiligheidsvoorwaarden. Het Instituut kan hiervoor objectieve beoordelingscriteria vaststellen.
>
> Bij een gehele of gedeeltelijke beëindiging worden reeds betaalde jaarlijkse rechten gecrediteerd voor zover zij betrekking hebben op een daadwerkelijk beëindigde, afzonderlijk aangerekende vergunning, station of gebruiksrecht, overeenkomstig de toepasselijke terugbetalingsregeling.

### Working technical wording

> Voor de technische beoordeling van onbemande radioamateurstations wordt het maximaal toegestane effectief uitgestraalde vermogen (ERP) of equivalente isotroop uitgestraalde vermogen (EIRP) duidelijk vermeld, samen met de relevante antennekarakteristieken en de vermogenslimieten die uit de toepasselijke regelgeving voortvloeien.
>
> Het werkelijk vermogen aan de antenne-ingang wordt bepaald op basis van het uitgangsvermogen van de zendinstallatie en de gemeten verliezen in de voedingslijn. De technische registratie maakt een onderscheid tussen vergunde grenswaarden en de actuele configuratie van de installatie.
>
> Wijzigingen die binnen alle vergunde grenswaarden blijven en de storings- of veiligheidsvoorwaarden niet wezenlijk wijzigen, kunnen via kosteloze technische kennisgeving worden verwerkt.

These are **discussion clauses**, not instructions to disregard the existing definition of output power or a currently binding licence limit.

## 11. Proposed digital workflow (`on0.be` or equivalent)

A public read-only register can coexist with a restricted workflow for authorised station managers, associations and BIPT.

1. **Station manager submits an event:** correction, minor notification, substantive amendment, partial termination or full termination.
2. **Automatic technical checks:** values, units, applicable legal maximums, power budgets, frequency overlaps and key coordination conditions.
3. **Classify A/B/C:** if any criterion is uncertain or material, route to human technical review rather than silently accepting a free notification.
4. **Association coordination:** UBA/VRA/UFRC/eligible club roles, as applicable; records the planning recommendation without replacing BIPT's regulatory decision.
5. **BIPT action:** approve Category A; accept/record Category B in an agreed workflow; acknowledge Category C and calculate applicable credits.
6. **Versioning and audit:** preserve old and new configurations, source measurements, effective dates, decisions and responsible contacts.
7. **Publish only appropriate information:** public parameters relevant to coordination, with GDPR-conscious handling of contacts and precise data.

A future system could calculate antenna input power and ERP/EIRP automatically, but its calculations must show assumptions and measurements; they must not substitute for required technical evaluation.

## 12. Benefits and rationale

- **More accurate frequency planning:** reflects actual radiated power and antenna configuration.
- **Fewer unnecessary regulatory transactions:** BIPT can focus on changes that matter.
- **Better data quality:** operators have an incentive to report equipment and maintenance updates promptly.
- **More efficient spectrum usage:** voluntary release of unused frequencies is not financially penalised.
- **Proportionate charges:** substantive work remains chargeable; simple maintenance and corrections do not.
- **Consistent treatment:** shared categories can apply across associations and qualifying clubs.
- **Greater transparency:** explicit distinction between approved ceilings and the equipment currently installed.

## 13. Open questions for BIPT and legal review

1. On ON0 permits, does **'zenderuitgangsvermogen'** presently mean transmitter-hardware output or the legally defined output of the complete transmitting installation? What physical reference point is intended?
2. Which changes already qualify as non-chargeable **corrections** rather than Article 35 modification requests?
3. Can BIPT accept free notification of technical changes within an existing authorised envelope, or does this require amendment of the Royal Decree or station authorisation template?
4. When is a change of responsible persons a substantive licence amendment, versus an administrative replacement of a qualified contact?
5. Which antenna-height, radiation-pattern, gain and site changes trigger a material reassessment? Can measurable tolerances be defined without compromising coordination?
6. Must the primary standard be **ERP or EIRP**? Which quantities are required alongside it to maintain compliance with existing band power ceilings?
7. Can RX-only frequency changes be kept in a coordination register separate from the licensed TX permissions, and what prior checking remains necessary?
8. When an ON0 licence includes several frequencies, are annual rights charged per station, per frequency, or another unit? What credit is possible on partial surrender?
9. How should the credit-note rules in Article 43 apply to partial deletions, and can termination be accepted through an authenticated electronic channel?
10. What minimum measurement evidence should support declared filter/combiner/feeder losses and antenna gain, especially for shared-antenna multi-transmitter installations?
11. Which approval and database functions can be delegated to association-led coordination, and which must remain with BIPT?
12. Are other decisions or rules beyond the Royal Decree and the 2019 BIPT decision affected by the proposed change in power terminology?

## 14. Proposed next steps

- [ ] Obtain input from UBA technical and legal colleagues.
- [ ] Compare actual BIPT invoices and correction requests with the A/B/C matrix.
- [ ] Request BIPT's written interpretation of Article 35, Article 43 and the power reference point on ON0 permits.
- [ ] Seek feedback from VRA, UFRC and other relevant applicants/associations.
- [ ] Agree technical criteria for non-substantive antenna and power changes.
- [ ] Draft Dutch/French regulatory text with legal review.
- [ ] Define an updated ON0 licence annex and technical register schema.
- [ ] Pilot the classification workflow with real cases, including surrender and combiner-loss examples.
- [ ] If necessary, submit a narrowly scoped Royal Decree amendment proposal through the competent federal channel.

## 15. References

Primary/regulatory material and published guidance:

1. [Royal Decree of 18 December 2009 — original publication / text copy](https://etaamb.openjustice.be/nl/koninklijk-besluit-van-18-december-2009_n2009011581.html) — Articles 1, 35, 43, 44; **read together with subsequent amendments**.
2. [Royal Decree of 15 July 2013 amending the 2009 decree](https://etaamb.openjustice.be/nl/koninklijk-besluit-van-15-juli-2013_n2013011373.html) — particularly its Article 35 replacing Article 43.
3. [Royal Decree of 14 December 2018 amending the 2009 decree](https://etaamb.openjustice.be/nl/koninklijk-besluit-van-14-december-2018_n2018015546) — particularly Article 19 (fees) and Article 25 (credits on termination).
4. [BIPT decision of 24 May 2019 on amateur frequencies, powers and modes](https://www.bipt.be/consumenten/publication/besluit-van-24-mei-2019-betreffende-de-frequenties-vermogens-en-transmissiemodi-die-mogen-worden-gebruikt-door-de-radioamateurs).
5. [BIPT FAQ — station-licence fees and conditions](https://www.bipt.be/consumenten/faq/hoe-vraag-ik-mijn-stationsvergunning-aan-wat-zijn-de-voorwaarden).
6. [BIPT guidance on obtaining/terminating radio authorisations and credits](https://www.bipt.be/consumenten/radiofrequenties/professioneel-gebruik/een-vergunning-verkrijgen-opzeggen) — published for professional use, not an ON0-specific determination.
7. [UBA unattended stations information](https://www.uba.be/nl/onthaal/onbemande-stations).
8. **ON0RFG station authorisation**, issued 15 September 2026, annex page 3 (example supplied for this discussion; not embedded or redistributed here).

**Verification note:** The OpenJustice pages above reproduce Belgian Official Journal documents; they are not a consolidated official legal opinion. Prior to formal submission, validate the current consolidated text and subsequent amendments against the Belgian Official Journal/eJustice and with the competent authorities.

---

**RFC discussion focus:** Which changes represent a genuine new transmitting right or new interference footprint, and which merely keep an existing station safe, efficient and accurately documented?
