# Broadband Penetration Disparity Between Urban Kathmandu Valley and Rural Hill Districts of Nepal: Data Analysis and Infrastructure Solutions

**Aman Jha**

4th Semester, Bachelor of Information Management (BIM)
Tribhuvan University, Kathmandu, Nepal

**July 2026**

---

## Abstract

Nepal's telecommunications sector has grown impressively over the last decade, with the Nepal Telecommunications Authority (NTA) reporting broadband penetration exceeding 145% by early 2026. But anyone who has lived both in Kathmandu and in a hill district knows these numbers do not tell the full story. This paper examines the real gap between broadband access in the urban Kathmandu Valley and the rural hill and mountain districts. Using publicly available NTA Management Information System (MIS) reports, census data, and survey findings, I show that fixed broadband penetration in Kathmandu Valley stands at roughly 79% of households, while in provinces like Karnali it hovers around 14%. The paper then evaluates three infrastructure models that could help bridge this gap: community mesh networks (building on the work of Mahabir Pun and the Nepal Wireless Networking Project), TV White Space technology, and satellite broadband including Starlink. Each model is assessed for technical feasibility, cost, and scalability in Nepal's unique geography. The paper concludes with policy recommendations for the NTA and Ministry of Communication and Information Technology.

**Keywords:** Broadband penetration, digital divide, Nepal Telecommunications Authority, mesh networks, TV White Space, Starlink, rural connectivity

---

## 1. Introduction

Nepal's Internet story is one of extremes. Walk into any café in Jhamsikhel or Durbar Marg and you will find fiber optic connections pushing 50 Mbps or more, enough to stream 4K video and run video calls without a hitch. Travel five hours by bus from Kathmandu to a hill district headquarters like Dhading Besi, and the experience changes completely. Go further into the rural VDCs (Village Development Committees) of those districts, and the Internet might not exist at all.

The ITU's 2025 report on landlocked developing countries ranked Nepal's mobile broadband penetration at 94.5%, close to the global average (ITU, 2025). But mobile broadband is not the same as fixed broadband. Mobile data serves well for messaging and social media, but it falls short for activities like online classes, large file uploads, telemedicine, or running a business from home. Fixed broadband is where the real disparity shows up.

This paper focuses on that disparity. I have three goals:

1. To lay out the actual numbers from NTA and other sources, separating the headline penetration figure from the reality on the ground.
2. To explain why the gap between Kathmandu Valley and rural hill districts is so wide and stubborn.
3. To look at three infrastructure models that could realistically narrow the gap, with honest assessments of their strengths and weaknesses in the Nepali context.

Before proceeding further, I should clarify the terminology. "Broadband" in this paper follows the NTA definition: Internet access with download speed of at least 256 kbps (though in practice, most of the figures cited refer to connections well above this threshold). "Kathmandu Valley" means the three districts of Kathmandu, Lalitpur, and Bhaktapur. "Hill districts" refers to the districts in the Hill and Mountain ecological zones as classified by the Central Bureau of Statistics, excluding the Tarai.

---

## 2. Literature Review

### 2.1 The Digital Divide in Developing Countries

The digital divide is not a new concept. Van Dijk (2020) distinguished between four levels of access: motivational, material, skills, and usage. In Nepal, the gap exists at every level. Even where material access exists, usage is constrained by digital literacy, language barriers, and the high cost of devices.

The Broadband Commission for Sustainable Development set a target that entry-level broadband should cost less than 2% of monthly GNI per capita (Broadband Commission, 2025). Nepal meets this target for mobile data but falls significantly short for fixed broadband, which cost 7.2% of GNI per capita as of 2024 (ITU, 2025). This is more than three times the recommended threshold.

### 2.2 Prior Studies on Nepal's Internet Access

Several studies have documented Nepal's connectivity challenges. Joshi and Ghimire (2023) analyzed the NTA MIS data from 2018 to 2022 and found that while overall penetration grew, the urban-rural gap widened in absolute terms. The 2021 Nepal Living Standards Survey (NLSS IV) by the National Statistics Office found that only 40.3% of households had Internet access at home, with rural households at 17.4% compared to 79.3% in Kathmandu Valley (NSO, 2023).

Khatri (2026) in The Diplomat documented individual experiences from Lha (Humla) and Baitadi, reporting students walking 30 minutes for a usable signal. These qualitative accounts match what the numbers suggest.

### 2.3 Community Networks in Nepal

The Nepal Wireless Networking Project, started by Mahabir Pun in 2002, is the most well-known community network initiative in the country. By 2016, it had connected over 200 villages across 15 districts using long-range Wi-Fi links (Pun, 2017). The Wireless for Communities (W4C) program, launched after the 2015 Gorkha earthquake, connected schools and health clinics in Gorkha, Lamjung, and Sindhupalchok districts using solar-powered Wi-Fi (Internet Society, 2020).

But sustainability has been a persistent problem. Pun himself estimates that only about 50% of the community networks he helped establish are still operational (Internet Society Nepal, 2024). The reasons are instructive: lack of local technical skills, difficulty in collecting user fees, and equipment failures in harsh weather.

### 2.4 TV White Space

TV White Space (TVWS) uses unused frequencies in the UHF and VHF television bands to deliver wireless broadband. Because these lower frequencies travel farther and penetrate obstacles better than Wi-Fi's 2.4 GHz and 5 GHz bands, TVWS can cover several kilometers from a single base station (Brewer, 2013). Pilot projects have been conducted in Ghana, the UK, the United States, and New Zealand. In Nepal, a preliminary assessment study using low-cost spectrum analyzers was published in IEEE (Bhattarai et al., 2024), but no large-scale deployment has happened yet. The NTA has not formally opened TVWS for commercial use.

### 2.5 Satellite Broadband and Starlink

Low Earth Orbit (LEO) satellite constellations like Starlink represent a new option for remote connectivity. Starlink had 10 million global subscribers by early 2026, with 2.7 million in the United States alone (New Street Research, 2026). However, Starlink is not yet commercially available in Nepal. The legal barrier is Nepal's requirement that foreign telecommunications companies partner with local firms and comply with ownership regulations under the Telecommunications Act, 1997. As of June 2026, Starlink had held discussions with the NTA but no license has been issued (TechSathi, 2026). SpaceX has not officially applied for a license (Barala, 2026).

---

## 3. Data Analysis: NTA MIS Reports and the Real Picture

### 3.1 The Headline Figure and Its Problems

The NTA's MIS report for Falgun 2082 (February-March 2026) showed broadband penetration at 145.69% (NTA, 2026). This means there are more broadband subscriptions than people. Sounds impressive, but here is the catch: the figure counts mobile SIMs and fixed-line connections separately. A person with two SIM cards and a home fiber connection is counted three times.

More useful is the population penetration rate for fixed broadband. As of Baisakh 2083 (April-May 2026), the NTA reported 34.56 lakh (3.456 million) fiber Internet users (NepaliTelecom, 2026). With a population of 29.16 million (Census 2021), that gives a fixed broadband penetration of about 11.8% — still low by global standards, but growing.

DataReportal's Digital 2026 Nepal report estimated that only 56% of Nepalis were actually online as of late 2025, meaning about 13 million people remain offline (DataReportal, 2026). The NLSS IV finding that only 40% of households have Internet at home is more sobering.

### 3.2 Kathmandu Valley vs. Rural Districts

Table 1 shows the contrast based on the most recent data available:

**Table 1: Internet Access by Geographic Area**

| Area | Household Internet Access (%) | Source |
|------|------------------------------|--------|
| Kathmandu Valley | 79.3 | NLSS IV (NSO, 2023) |
| Urban areas outside KV | 43.2 | NLSS IV (NSO, 2023) |
| Rural areas (national) | 17.4 | NLSS IV (NSO, 2023) |
| Karnali Province | ~14 | Digital Rights Nepal (2025) |
| Bagmati Province (incl. KV) | ~68 | Estimated from NTA data |

The disparity becomes starker when you look at districts. Kathmandu district (population 2.04 million) has more fixed broadband subscribers than all of Karnali Province (population 1.69 million) combined. There is no district-level fixed broadband subscriber data published by NTA in a single table, but the pattern is unmistakable from the ISP concentration data: the top five ISPs (WorldLink, Dish Home, Nepal Telecom, Vianet, Subisu) operate primarily in urban areas, with rural coverage limited to district headquarters at best.

### 3.3 Fixed Broadband Subscriber Growth

**Table 2: Fixed Broadband Subscribers in Nepal (Selected Periods)**

| Period | Fixed Broadband Subscribers | Source |
|--------|----------------------------|--------|
| Ashadh 2081 (Jun-Jul 2024) | 2,810,771 | NTA MIS |
| Ashadh 2082 (Jun-Jul 2025) | ~3,240,000 | NTA MIS (approx.) |
| Baisakh 2083 (Apr-May 2026) | 3,456,001 | NTA MIS |

The growth is steady but slow — about 6-7% annually. At this rate, it would take years to reach even 50% household penetration. More importantly, the growth is concentrated in areas where fiber is already available.

### 3.4 Mobile vs. Fixed: Two Different Worlds

**Table 3: Mobile vs Fixed Broadband in Nepal (2024-25)**

| Metric | Mobile Broadband | Fixed Broadband |
|--------|-----------------|-----------------|
| Subscriptions per 100 people | 94.5 | 4.8 |
| Cost as % of GNI per capita | 2.0% | 7.2% |
| Primary use | Social media, messaging | Work, study, streaming |
| Rural coverage | 88% (4G) | Very limited |

The data shows that mobile broadband has achieved near-universal coverage in terms of signal availability (88% for 4G), but fixed broadband — which is what matters for meaningful digital participation — remains out of reach for most rural households.

### 3.5 Why the Gap Exists

The reasons are not mysterious. They include:

- **Geography**: Nepal's hills and mountains make fiber deployment expensive. The cost of laying fiber to a remote hill VDC can be 5-10 times the cost in Kathmandu.
- **Population density**: Rural VDCs have low population density. The commercial incentive for ISPs is weak.
- **Electricity**: Many rural areas still face frequent power cuts or have no grid connection at all. Internet equipment is useless without reliable power.
- **Affordability**: Fixed broadband at Rs. 1,000-1,500 per month is expensive for rural households where agriculture is the main income source.
- **Digital literacy**: Even where connectivity exists, many rural users lack the skills to use the Internet productively.

---

## 4. Infrastructure Model 1: Community Mesh Networks

### 4.1 How Mesh Networks Work

A wireless mesh network replaces the traditional hub-and-spoke model with a distributed architecture. Each node (a radio device mounted on a house or a pole) communicates with neighboring nodes, passing data along until it reaches a gateway connected to the backbone Internet. If one node fails, data finds an alternative path.

In the Nepali context, mesh networks are attractive because they use unlicensed spectrum (2.4 GHz and 5.8 GHz bands), which does not require expensive spectrum licenses from NTA. The equipment — typically Ubiquiti or MikroTik radios — costs between NPR 5,000 and NPR 25,000 per node. Solar panels can power the nodes where grid electricity is unavailable.

### 4.2 The Nepal Wireless Experience

Mahabir Pun's project is the best reference point. Starting in 2002 with a 40 km long-range Wi-Fi link from Pokhara to Nangi village, the network grew to cover over 175 villages by 2012 (APNIC Foundation, 2012). The project used modified satellite dishes as antennas and off-the-shelf Wi-Fi equipment.

Key lessons from the Nepal Wireless experience:

- **Technical feasibility is not the problem.** The technology works, even in remote mountains.
- **Sustainability is the real challenge.** Only about 50% of networks survived after external support ended.
- **Local ownership matters.** Networks that failed were often those where the community was not trained to maintain them.
- **Community training must happen early.** Pun advises training local people during the network setup, not after (Internet Society Nepal, 2024).
- **Complementary services help.** Telemedicine, e-learning, and small communication centers can generate revenue to cover operating costs.

### 4.3 Cost Estimate for a Hill VDC Network

Based on figures from the W4C project and current equipment prices:

**Table 4: Estimated Cost for a Mesh Network in One VDC (10-15 hamlets)**

| Item | Quantity | Unit Cost (NPR) | Total (NPR) |
|------|----------|-----------------|-------------|
| Outdoor Wi-Fi radios (Ubiquiti LiteBeam) | 15 | 8,000 | 120,000 |
| Backhaul radio (long-range PtP) | 1 | 35,000 | 35,000 |
| Solar panel + battery system | 8 | 15,000 | 120,000 |
| Router/switch at gateway | 1 | 10,000 | 10,000 |
| Cables, poles, mounting hardware | 1 set | 25,000 | 25,000 |
| Installation and training | 1 time | 50,000 | 50,000 |
| **Total** | | | **360,000** |

At current exchange rates, that is roughly USD 2,700 per VDC. The monthly operating cost (backhaul bandwidth, maintenance) might be NPR 10,000-15,000. If 50-100 households share the connection at NPR 300-500 per month, the network can be self-sustaining.

### 4.4 Scalability Limitations

Mesh networks work well for small, geographically concentrated communities. They become harder to manage when scaled to large areas. Bandwidth also decreases with each hop. For video streaming or large file transfers, the number of hops needs to be limited to 3-4. This means the network design needs careful planning.

The mesh model also depends on volunteers or part-time local technicians for maintenance. In communities where young people migrate to cities or abroad for work, finding and keeping trained personnel is difficult.

---

## 5. Infrastructure Model 2: TV White Space

### 5.1 The Technology

TV White Space (TVWS) exploits gaps in the UHF spectrum (470-698 MHz) created by the transition from analog to digital television. These frequencies have much better propagation characteristics than Wi-Fi bands: they travel farther (up to 10 km or more) and penetrate trees, buildings, and terrain better.

The key components are:

- A **White Space Database (WSDB)** that tells devices which frequencies are available at a given location.
- **Master White Space Devices (WSDs)** that query the database and coordinate spectrum use.
- **Client devices** that connect to the master WSDs.

### 5.2 International Precedents

TVWS has been tested in several countries. In Ghana, the "Mamobi" project connected schools and libraries. In the UK, the Orkney Islands pilot connected three ferries and several fixed premises. In New Zealand, TVWS was evaluated for rural communities missed by the Rural Broadband Initiative (Brewer, 2013). The FCC in the United States has formalized TVWS rules under Part 15 Subpart H.

None of these have scaled to nationwide deployment. The technology is mature but the regulatory frameworks and commercial models are still evolving.

### 5.3 Relevance to Nepal

For Nepal, TVWS is potentially a better fit than Wi-Fi mesh for several reasons:

- **Terrain**: TVWS signals penetrate hills and forests better than 2.4/5.8 GHz.
- **Range**: A single base station can cover a whole VDC, reducing the number of nodes needed.
- **Cost**: Fewer base stations means lower capital cost for wide-area coverage.

Bhattarai et al. (2024) conducted spectrum measurements in Nepal using low-cost analyzers and confirmed that significant white space exists in the UHF band, especially outside the Kathmandu Valley where TV broadcasting is limited.

### 5.4 Regulatory Hurdles

The NTA has not yet allocated spectrum for TVWS. Under the Telecommunications Act, 1997, spectrum management is centralized, and any new use requires regulatory approval. The NTA would need to:

1. Establish a geolocation database for TVWS frequencies.
2. Define technical standards for White Space Devices.
3. License spectrum or create an unlicensed regime similar to the FCC's approach.

None of these steps have been taken. The Nepal TVWS pilot that was discussed several years ago never materialized beyond the research stage.

### 5.5 Cost Comparison with Mesh

**Table 5: Estimated Cost: TVWS vs. Mesh for Same VDC**

| Item | TVWS | Wi-Fi Mesh |
|------|------|------------|
| Base stations needed | 2-3 | 10-15 |
| Estimated equipment cost | NPR 500,000-800,000 | NPR 300,000-400,000 |
| Coverage area per node | 5-10 km | 0.5-2 km |
| Monthly bandwidth cost | Similar | Similar |
| Complexity of installation | Higher (requires database setup) | Lower |

TVWS has higher upfront cost but may achieve better coverage with fewer nodes, which matters in very remote areas.

---

## 6. Infrastructure Model 3: Satellite / Starlink

### 6.1 The Starlink Option

Starlink operates a LEO satellite constellation at an altitude of about 550 km, much closer than traditional geostationary satellites (35,786 km). This gives it much lower latency (20-50 ms vs 600+ ms for GEO satellites) and higher speeds (50-250 Mbps typical). As of May 2026, Starlink had about 10 million global subscribers (New Street Research, 2026).

For Nepal, Starlink's main advantage is that it works anywhere with a clear view of the sky. No fiber, no towers, no local infrastructure needed on the ground. This makes it immediately applicable to remote hill VDCs where no other broadband option exists.

### 6.2 The Barriers

Despite the promise, several barriers prevent Starlink from being a solution in Nepal today:

**Legal:** Nepal's Telecommunications Act requires foreign telecom operators to partner with local firms. The ownership rules effectively require a Nepali partner with significant equity. Starlink has not applied for a license, and the NTA has not indicated whether an application would be approved (Barala, 2026).

**Cost:** Starlink's hardware (the dish and router) costs about $349 (roughly NPR 46,000) and the monthly subscription is $120 (roughly NPR 16,000) for the residential plan. To put that in perspective, NPR 16,000 per month is more than many rural households earn in total. Even the "Starlink Roam" plan at $50/month (NPR 6,600) is out of reach for most.

**Local competition:** Nepal's ISPs have opposed Starlink's entry, arguing that it would undercut local investment in fiber networks while only serving the wealthiest customers (TechSathi, 2026).

### 6.3 Feasibility for Remote VDCs

For community use — such as connecting a school, health post, or village telecenter — Starlink could work. One dish can support dozens of users if the bandwidth is shared. The monthly cost shared across a community would be much more manageable. The hardware cost could be subsidized by the Rural Telecommunications Development Fund (RTDF) or by development partners.

**Table 6: Starlink Feasibility Scenarios for Nepal**

| Scenario | Hardware Cost | Monthly Cost | Feasibility |
|----------|--------------|--------------|-------------|
| Individual household | NPR 46,000 | NPR 16,000 | Not feasible for most |
| Village telecenter (shared) | NPR 46,000 | NPR 16,000 | Feasible with subsidy |
| School or health post | NPR 46,000 | NPR 16,000 | Feasible if funded by RTDF |
| Government office | NPR 46,000 | NPR 16,000 | Feasible within budget |
| Trekking lodge (Roam plan) | NPR 46,000 | NPR 6,600 | Feasible in high-traffic areas |

### 6.4 Other Satellite Options

Starlink is not the only LEO satellite provider. Amazon's Project Kuiper plans to launch service in late 2026 (Broadband Breakfast, 2026). OneWeb (now Eutelsat OneWeb) already has LEO satellites but focuses on enterprise and government customers rather than residential. Traditional GEO satellite providers like HughesNet and Viasat are technically available in Nepal through partnerships with local ISPs, but the high latency (600+ ms) makes them unsuitable for real-time applications like video calls.

If regulatory barriers to Starlink remain, Nepal could explore a public-private partnership model where the government becomes an anchor customer, buying satellite capacity for rural schools, health posts, and ward offices, and then allowing local ISPs or cooperatives to resell the remaining bandwidth to the community.

---

## 7. Comparative Analysis and Recommendations

### 7.1 Which Model Fits Where?

There is no single solution for Nepal's connectivity gap. The appropriate model depends on geography, population density, and existing infrastructure.

**Table 7: Recommended Model by Setting**

| Setting | Primary Model | Secondary Model | Rationale |
|---------|--------------|-----------------|-----------|
| Hill district HQ with road access | Fiber extension | Wi-Fi mesh to nearby hamlets | Fiber already being laid to district HQs; mesh can extend the last mile |
| Remote hill VDC (clustered settlement) | Community mesh | TVWS if available | Mesh cost is low and community can manage it |
| Scattered mountain settlements (5-10 houses) | Starlink (shared) | VSAT (traditional) | No other option is economic for very sparse populations |
| Tarai villages near fiber backbone | Fiber extension | Wi-Fi hotspot | Tarai terrain is flat and fiber deployment is cheaper |
| Schools and health posts everywhere | Starlink (subsidized) | Community mesh | Critical services need reliable connectivity regardless of location |

### 7.2 The Missing Link: The Rural Telecommunications Development Fund

Nepal already has a policy mechanism to fund rural connectivity. The Rural Telecommunications Development Fund (RTDF), established under the Telecommunications Act, collects 2% of the annual revenue from all telecom operators. The fund is meant to subsidize connectivity in unserved areas.

In theory, the RTDF could finance mesh networks, TVWS pilots, or Starlink installations for community use. In practice, the fund has been underutilized. According to media reports, large sums have accumulated without being spent effectively. The National Broadband Policy, 2071 (2015) specifically mentions the RTDF as a vehicle for rural broadband expansion, but implementation has been slow.

### 7.3 Policy Recommendations

Based on the analysis in this paper, I offer the following recommendations:

**To the NTA:**

1. **Publish district-level fixed broadband subscriber data.** Currently, the MIS reports give aggregate figures but not district-by-district breakdowns. Transparent data would help target interventions where they are most needed.
2. **Open a TVWS regulatory framework.** Start with a pilot project in 2-3 hill districts, working with the Nepal Wireless Networking Project or academic institutions to test the technology in real conditions.
3. **Simplify licensing for community networks.** The current licensing regime was designed for commercial telecom operators. Community networks should be able to operate under a lighter regulatory framework, as recommended by the Internet Society.
4. **Clarify the legal pathway for LEO satellite providers.** Whether for Starlink or other providers, having clear rules would allow the market to respond to rural demand.

**To the Ministry of Communication and Information Technology:**

5. **Activate the RTDF for community broadband projects.** Establish a simple grant program that VDCs and rural municipalities can apply for to set up mesh networks or satellite telecenters.
6. **Include broadband in the definition of universal service.** The current universal service obligation focuses on voice telephony. Expanding it to include broadband would align Nepal with global best practices.
7. **Bundle connectivity with digital literacy programs.** Having Internet is not the same as using it productively. The government's IT Decade (2024-2034) should include a major digital literacy component alongside infrastructure spending.

### 7.4 A Rough Budget

**Table 8: Estimated Budget for a 5-District Pilot Program**

| Activity | Cost (NPR crores) | Source |
|----------|-------------------|--------|
| Mesh networks in 50 VDCs | 1.8 | At NPR 3.6 lakh per VDC |
| TVWS pilot (3 districts) | 0.5 | Equipment, database setup, monitoring |
| Starlink for 100 schools/health posts | 0.5 | At NPR 50,000 per site (subsidized hardware + 1 year service) |
| Digital literacy training | 0.3 | Training of trainers, materials |
| Monitoring and evaluation | 0.2 | Baseline survey, impact assessment |
| **Total** | **3.3** | |

NPR 3.3 crores is roughly USD 250,000 — a modest sum that the RTDF could cover from its existing balance.

---

## 8. Conclusion

The NTA's headline broadband penetration figure of 145% creates the impression that Nepal is well on its way to universal connectivity. The reality is more complex. Fixed broadband in the Kathmandu Valley is now fast and reliable by South Asian standards — Nepal actually tops the region in Ookla speed tests. But step outside the urban centers and the picture changes. Thousands of VDCs in the hills and mountains remain either unconnected or dependent on unreliable mobile data.

This paper has examined three infrastructure models that could help close the gap. Community mesh networks, proven by the Nepal Wireless Networking Project, are the most cost-effective for clustered hill settlements but face sustainability challenges that require local ownership and training. TV White Space technology has strong technical potential for Nepal's terrain but needs regulatory action from the NTA to move beyond the research phase. Satellite broadband, specifically Starlink, offers a "anywhere" solution but remains blocked by regulatory barriers and cost constraints, though shared community models could make it viable for schools and health posts.

None of these models is a silver bullet. The solution for Nepal will be a mix of technologies tailored to each setting, funded by the RTDF and other mechanisms, and backed by digital literacy programs. The technology exists. What has been missing is the political will and institutional capacity to deploy it at scale.

The IT Decade's target of NPR 3,000 billion in ICT exports is ambitious. But before Nepal can export digital services, its own citizens need access to them. Bridging the broadband gap between Kathmandu Valley and the hill districts is not just a connectivity problem — it is a question of equity.

---

## References

APNIC Foundation. (2012). *Nepal Wireless Networking Project*. ISIF Asia. https://apnic.foundation/our-impact/nepal-wireless-networking-project/

Barala. (2026). *Starlink in Nepal: News, Laws & Price (2026 Update)*. https://barala.com.np/blog/starlink-in-nepal/

Bhattarai, A., Rijal, B., & Shakya, S. (2024). An assessment study on TV White Space in Nepal using low-cost spectrum analyzer. *IEEE Conference Publication*. https://ieeexplore.ieee.org/document/10625461

Brewer, J. (2013). *TV White Space Technology for Rural Telecommunications*. InternetNZ. https://internetnz.nz/assets/Archives/Jonathan_Brewer_Suitability_of_White_Space_Technology_report.pdf

Broadband Commission for Sustainable Development. (2025). *Target 2: Make Broadband Affordable*. https://www.broadbandcommission.org/advocacy-targets/2-affordability/

DataReportal. (2026). *Digital 2026: Nepal*. https://datareportal.com/reports/digital-2026-nepal

Digital Rights Nepal. (2025). *State of Digital Rights and Safety in Nepal 2024*. https://digitalrightsnepal.org/

Internet Society. (2020). *Community Networks in Nepal*. https://internetsociety.org.np/community-networks-in-nepal/

Internet Society Nepal. (2024). *Community Networks: Closing the Digital Divide*. https://internet.org.np/blog/community

ITU. (2025). *Measuring Digital Development: Facts and Figures 2025 – Focus on Landlocked Developing Countries*. https://www.itu.int/hub/publication/d-ind-ict_mdd-2025-2/

Joshi, S., & Ghimire, P. (2023). Urban-rural digital divide in Nepal: An analysis of NTA MIS data 2018-2022. *Journal of ICT Development in Nepal*, 4(1), 45-62.

Khatri, Y. (2026, May 14). Nepal's digital divide: Why millions still lack affordable Internet access. *The Diplomat*. https://thediplomat.com/2026/05/nepals-digital-divide-why-millions-still-lack-affordable-internet-access/

National Statistics Office. (2023). *Nepal Living Standards Survey 2022/23 (NLSS IV)*. Government of Nepal. https://data.nsonepal.gov.np/

Nepal Telecommunications Authority. (2015). *National Broadband Policy, 2071*. https://cdn.techsansar.com/img/Nepal-Broadband-Policy-2071-EN.pdf

Nepal Telecommunications Authority. (2024). *MIS Report, Ashadh 2081*. https://nta.gov.np/uploads/contents/MIS%20Report_2081%20Ashadh.pdf

Nepal Telecommunications Authority. (2026). *MIS Report, Falgun 2082*. https://nta.gov.np/

NepaliTelecom. (2026, June 15). *Fiber Internet Users in Nepal: 34.77 Lakh | Latest NTA Data*. https://www.nepalitelecom.com/internet-users-isp-in-nepal

New Street Research. (2026). *Starlink subscriber analysis*. Cited in Broadband Breakfast, May 14, 2026.

Pun, M. (2017). Bringing Internet to Nepal's remote, mountainous villages. *Internet Society Blog*. https://www.internetsociety.org/blog/2017/06/bringing-internet-nepals-remote-mountainous-villages/

TechSathi. (2026, June 2). *Starlink in Nepal: Opportunities, Challenges, Impact on ISPs*. https://techsathi.com/starlink-in-nepal-opportunities-challenges-impact-on-isps/

Van Dijk, J. (2020). *The Digital Divide*. Polity Press.

---

## Appendix: Key Definitions

- **Broadband**: Internet access with download speed of at least 256 kbps, per NTA definition.
- **Fixed Broadband**: Wired connections (fiber, ADSL, cable) that serve a specific location.
- **Mobile Broadband**: Internet access through cellular networks (3G, 4G, 5G).
- **Penetration Rate**: Number of subscriptions divided by population, expressed as a percentage.
- **Household Penetration**: Percentage of households with at least one Internet connection.
- **VDC**: Village Development Committee, the former lowest administrative unit in Nepal (now replaced by wards under rural municipalities, but still commonly used in reference).
- **MEAL**: Monitoring, Evaluation, Accountability, and Learning.
