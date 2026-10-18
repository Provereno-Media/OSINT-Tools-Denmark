# OSINT-Tools-Denmark
<img src="https://upload.wikimedia.org/wikipedia/commons/9/9c/Flag_of_Denmark.svg" alt="Denmark_FLAG"/>
A list of OSINT resources and tools that may be useful to you when conducting investigations related to Denmark. Most of the resources and tools has versions in Danish, some also in English. Since 1 September 2025, beneficial-owner (reelle ejere) data in the CVR register is no longer open to the public: access requires MitID login and a declared legitimate interest, following the CJEU judgment of 22 November 2022 (C-37/20, C-601/20). Several portals could block access via VPN or proxy. Enter names with Danish letters (æ, ø, å).


![Last updated](https://img.shields.io/github/last-commit/Provereno-Media/OSINT-Tools-Denmark?label=Last%20updated)

## Contributions
Feel free to join this project — [OSINT For Countries V2.0](https://github.com/Provereno-Media/OSINT-for-countries-V2.0)

## Table of contents:
 - [Open Data portals](#open-data-portals)
 - [Legal Entities](#legal-entities)
 - [Cadastral and other Maps](#maps)
 - [Vehicles](#vehicles)
 - [People, phones, social etc.](#people)
 - [Public procurements](#public-procurement)
 - [WHOIS](#whois)

## Open Data portals
(Country Open Data, Stock Exchange, Courts)
- [Statistikbanken (Statistics Denmark — StatBank)](https://www.statistikbanken.dk/) — Statistics Denmark's database of official statistical tables on population, economy, business, housing, elections and more, with downloads and an API. *Lang: DA, EN.* 
- [Nationalbankens Statistikbank (Danmarks Nationalbank — Statistics Bank)](https://nationalbanken.statistikbank.dk/) — central bank statistics: interest rates, lending and deposits, balance of payments, securities and exchange rates. *Lang: DA, EN.* 
- [Datavejviser (Danish Open Data Guide)](https://www.datavejviser.dk/) — national catalogue of public-sector datasets from Datafordeleren, Statistics Denmark, Danmarks Miljøportal and about 170 other publishers; search by keyword, topic or publisher. *Lang: DA.* 
- [Open Data DK](https://www.opendata.dk/) — municipal and regional open-data portal (OS2opendatadk): datasets on transport, environment, population, budgets and more from Danish municipalities. *Lang: DA.* 
- [Datafordeleren (Basic Data Distributor)](https://datafordeler.dk/) — Climate Data Agency's distribution platform for the national basic-data registers: companies (CVR), addresses (DAR), buildings (BBR), cadastre (MAT), property, geography and maps; free API access with registration. CPR data is restricted to authorities. *Lang: DA.* 
- [Retsinformation](https://www.retsinformation.dk/) — official database of all laws, executive orders and circulars in force, plus Folketing documents and Ombudsman reports. *Lang: DA.* 
- [Domsdatabasen (Danish Courts' Judgments Database)](https://domsdatabasen.dk/) — published judgments of Danish courts since January 2022 (about 8,400 decisions as of July 2026); not all judgments are published. *Lang: DA.* 
- [Statstidende (Danish Official Gazette)](https://www.statstidende.dk/) — Civil Affairs Agency's gazette with all notices required by law: bankruptcies, estates of deceased persons (dødsboer), compulsory auctions, debt restructuring, company dissolutions; searchable, with search subscriptions. *Lang: DA.* 
- [Finanstilsynet — OAM (Danish FSA — Company Announcements)](https://oam.finanstilsynet.dk/) — Officially Appointed Mechanism: stored regulatory announcements of listed issuers (annual reports, major shareholdings, insider trades). *Lang: DA, EN.* 

## Legal Entities
- [CVR — Det Centrale Virksomhedsregister (Central Business Register)](https://datacvr.virk.dk/) — Danish Business Authority register of all companies and sole traders: CVR number, address, status, management, legal owners, history and filed annual reports; search by name, CVR number or person. Free, no login. Beneficial-owner data has been closed to the public since 1 Sep 2025 (MitID + legitimate interest). Blocks automated access. *Lang: DA, EN.* 
- [Skattestyrelsen — Skatteoplysninger for selskaber (Tax Agency — Corporate Tax Information)](https://sktst.dk/om-os/skatteoplysninger-for-selskaber) — public tax lists for the last five income years: taxable income, deficit and tax paid by limited companies, cooperatives, foundations and associations. Sole traders are not covered; for jointly taxed groups only the administration company is shown. *Lang: DA.* 
- [Finanstilsynets virksomhedsregister (Danish FSA — Register of Companies)](https://virksomhedsregister.finanstilsynet.dk/) — financial institutions supervised or licensed by the Danish FSA, plus entities that are only registered and not supervised. *Lang: DA, EN.* 
- [Paqle](https://www.paqle.dk/) — media profiles of about 1 million Danes and 850,000 companies: press mentions, published accounts and management roles. Free account for basic search. *Lang: DA.*
- [CVR API](https://cvrapi.dk/) — third-party API and simple lookup of CVR data (also Norway); handy for bulk checks of CVR numbers. *Lang: DA.*
- [North Data](https://www.northdata.com/) — North Data covers company data in Denmark as part of its XL package, which includes comprehensive information on companies, key persons, and financials
- [Tesari First Resort](https://tesari.ai/) — Tesari is an all-source intelligence platform designed for high-stakes environments, with applications ranging from trade compliance and supply chain illumination to financial crime investigations and complex litigation. It is a paid platform that offers a Tech for Good (Community Impact) Programme for OSINT practitioners and journalists.

## Maps
(Cadastral Maps, GIS etc.)
- [Tinglysning.dk (Digital Land Registry)](https://www.tinglysning.dk/) — Land Registration Court portal for the land register (tingbog), vehicle register (bilbog), personal register (personbog) and cooperative-housing register; owners, mortgages and charges on a property can be looked up free of charge, many queries without MitID (more data with login). *Lang: DA.* 
- [Matriklen.dk (Cadastral Map)](https://www.matriklen.dk/) — official cadastral map of all properties: parcel area and location, notes and historical information; search by cadastral number, address, BFE number or place name. *Lang: DA.* 
- [OIS — Den Offentlige Informationsserver (Public Information Server)](https://www.ois.dk/) — state database that collects information on properties in Denmark from public registers, such as ownership and building data. *Lang: DA.* 
- [Vurderingsportalen (Property Valuation Portal)](https://www.vurderingsportalen.dk/) — Danish Property Assessment Agency's public property valuations by address, with valuations from different years on a map. *Lang: DA.* 
- [Skråfoto (Oblique Aerial Photos)](https://skraafoto.dataforsyningen.dk/) — oblique aerial imagery of all of Denmark from several angles, from the Agency for Data Supply and Infrastructure. *Lang: DA.* 
- [Historiske kort (Historical Maps)](https://dataforsyningen.dk/map/historiske-kort) — Dataforsyningen viewer of historical topographic and cadastral maps of Denmark. *Lang: DA.* 
- [Danmarks Arealinformation (Danish Area Information)](https://danmarksarealinformation.miljoeportal.dk/) — Danmarks Miljøportal map of environmental and land-use data: protected nature, soil contamination, groundwater, planning zones. *Lang: DA.* 
- [Plandata.dk — Kort (Planning Data Map)](https://kort.plandata.dk/) — national map of local plans, municipal plans, zoning and planning decisions. *Lang: DA.* 
- [Dataforsyningen (Data Supply)](https://dataforsyningen.dk/) — Climate Data Agency's portal for free public geodata: map viewers, web services, downloads and APIs (addresses, orthophotos, elevation models). *Lang: DA.* 

## Vehicles
### Land
- [Motorregistret — Køretøjsopslag (Motor Register — Vehicle Lookup)](https://motorregister.skat.dk/dmr-kerne/koeretoejdetaljer/visKoeretoej) — Motor Agency's public lookup of technical vehicle data by registration plate or VIN, without login; owners are not shown. Temporarily offline as of 2026-10-13 (see [motorst.dk](https://motorst.dk/)). *Lang: DA.* 
- [Nummerplade.net](https://www.nummerplade.net/) — free lookup by plate or VIN: inspection reports, mileage history, registered debt in the vehicle register (Bilbogen), VIN and technical data. *Lang: DA.*
- [TjekBil](https://www.tjekbil.dk/) — free registration-plate check of vehicle data. *Lang: DA.*

### Maritime
- [Skibsbladet — Danish Ship Register](https://shipregister.dma.dk/) — Danish Maritime Authority's public ship sheet for vessels in the Danish Ship Register and Danish International Ship Register, including historical data (BEK no. 35/2023). *Lang: DA, EN.* 
- [DMA — AIS data](https://www.dma.dk/safety-at-sea/navigational-information/ais-data) — Danish Maritime Authority page on access to historical AIS data from Danish waters (the land-based AIS system is now run by the Danish Emergency Management Agency). As of 2026-10-13 the linked download server web.ais.dk has an expired TLS certificate. *Lang: EN, DA.* 
- [VesselFinder](https://www.vesselfinder.com/) — live AIS vessel map with vessel and port database. 💲 Freemium: live map free; some features paid. *Lang: EN.*
- [Equasis](https://www.equasis.org/) — international database of ship and shipping-company safety information: IMO number, flag, owner, manager, inspections. Free registration required. *Lang: EN.* 

### Aviation
- [OY-REG — Danish Civil Aircraft Register](https://oy-reg.dk/register/) — non-official compiled register of about 7,400 current and historical OY- registrations (aeroplanes, gliders, helicopters, balloons) with type, construction number, years and previous registrations. Cross-check against the Danish Civil Aviation and Railway Authority. *Lang: EN.*
- [ADS-B Exchange](https://globe.adsbexchange.com/) — live and historical aircraft tracking without filtering of blocked aircraft; search by registration, ICAO hex or callsign. *Lang: EN.*

## People
(Names, Addresses, Yellow Pages, White Pages etc.)
- [Krak](https://www.krak.dk/) — person and company directory: search private persons by name, address or phone number; data come from telecom operators, unlisted numbers are not shown. Also a "who called" lookup of unknown numbers. Blocks automated access. *Lang: DA.*
- [De Gule Sider (Yellow Pages)](https://www.degulesider.dk/) — business and person directory with the same telecom data as Krak; search by name, phone or address. Blocks automated access. *Lang: DA.*
- [Folketinget — Medlemmer (Danish Parliament — Members)](https://www.ft.dk/da/medlemmer) — profiles of MPs with their registered positions and financial interests (hverv og økonomiske interesser). Blocks automated access. *Lang: DA, EN.* 
- [Advokatnøglen (Danish Bar — Lawyer Search)](https://www.advokatnoeglen.dk/) — Danish Bar and Law Society's register of all Danish lawyers; search by name, firm, postal code, jurisdiction or practice area. *Lang: DA, EN.* 
- [Autorisationsregistret (Register of Authorised Health Professionals)](https://stps.dk/sundhedsfaglig/autorisation/autorisationsregistret) — Danish Patient Safety Authority register of all authorised health professionals and cosmetic treatment clinics; search by authorisation ID, name or profession, with current authorisation status. *Lang: DA, EN.* 
- [Arkivalieronline (Danish National Archives — Digitised Records)](https://www.rigsarkivet.dk/arkivalieronline/) — Rigsarkivet's digitised documents: church books, censuses and other sources (only about 2% of the collections are digitised). *Lang: DA, EN.* 
- [Danish Family Search](https://www.danishfamilysearch.dk/) — free genealogy site with transcribed censuses, church books, conscription rolls and street indexes. *Lang: DA, EN.*
- Try [OSINT Industries](https://app.osint.industries) and don't forget about the [Digital Profiler's Toolkit](https://github.com/paulpogoda/Digital-Profiler-s-Toolkit)

## Public procurement
- [udbud.dk](https://udbud.dk/) — national portal of public tender notices from Danish contracting authorities. *Lang: DA.* 
- [Klagenævnet for Udbud — Afgørelsesportal (Complaints Board for Public Procurement — Decisions)](https://klfu.naevneneshus.dk/) — decisions of the procurement complaints board: disputed tenders, parties and rulings. *Lang: DA.* 
- [SKI — Staten og Kommunernes Indkøbsservice (National Procurement Service)](https://www.ski.dk/) — central purchasing body: framework agreements, suppliers and contract terms used by state and municipalities. *Lang: DA.* 
- [Konkurrence- og Forbrugerstyrelsen — Udbud (Competition and Consumer Authority — Procurement)](https://kfst.dk/udbud) — regulator pages on procurement rules, analyses of public-private cooperation and FAQ. *Lang: DA, EN.* 
- [TED — Tenders Electronic Daily](https://ted.europa.eu/en/) — EU procurement-notice search; filter by country Denmark for above-threshold notices and contract awards. *Lang: EN, multi.* 

## WHOIS
- [Punktum dk — Search .dk domain](https://punktum.dk/en/search-dk-domain) — official .dk registry lookup: status, creation date, registrant name and contacts, name servers. Registrants with name and address protection in CPR are anonymous. *Lang: DA, EN.* 
- [Punktum dk — Disclosure of data on anonymous registrants](https://punktum.dk/en/articles/procedure-for-the-disclosure-of-data-on-anonymous-persons) — procedure for requesting data on anonymous .dk registrants; the registrant is informed about the request. *Lang: DA, EN.* 
- [IANA — .dk Delegation Record](https://www.iana.org/domains/root/db/dk.html) — official delegation data for .dk: registry operator, technical contacts and WHOIS server `whois.punktum.dk`. *Lang: EN.*
- [RIPE Database Query](https://apps.db.ripe.net/db-web-ui/query) — RIPE NCC WHOIS for IP ranges and AS numbers allocated to Danish networks. *Lang: EN.*
- [ViewDNS.info](https://viewdns.info/) — reverse IP, reverse WHOIS, IP history, DNS records and subdomain discovery. *Lang: EN.*

---

## Contributing

To contribute to this repository:
1. Verify all links are working and accessible
2. Provide accurate descriptions of database contents
3. Follow the 7-category structure
4. Include official government sources when available
5. Submit pull requests with detailed change descriptions

## Legal Disclaimer

This repository is for educational and legitimate investigative purposes only. Users are responsible for:
- Complying with all applicable laws and regulations
- Respecting terms of service for all databases and tools
- Using information ethically and responsibly
- Obtaining proper authorization when required

The information provided is for informational purposes only and should not be considered legal advice.

---

**Repository maintained by the [OSINT-for-Countries-V2.0 community](https://github.com/Provereno-Media/OSINT-for-countries-V2.0)**
