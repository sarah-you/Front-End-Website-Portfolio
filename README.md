### Renata Medical
🔗 **Live site:** [renatamedical.com](https://www.renatamedical.com/)
**Role:** Front-end development · **Platform:** [add platform] · **Timeline:** Under 1 month, concept to launch

A multi-page marketing and education site for Renata's Minima Pro™ pediatric
stent, serving two audiences: physicians and parents. I built the site from
scratch, coding every page and component to match the Figma designs and using
shared classes so spacing, type size, and fonts stay consistent across the
design system. With a very short deadline, I tested every piece and ran
multiple iterations before launch.

![Physicians and Parents sections](assets/renata/feature-boxes.png)

#### Highlights

**Custom navbar and footer**
Built to adapt across all screen sizes.

**Components coded to the Figma design**
The 5-box layout (3 feature cards plus Physicians/Parents link boxes) and the
4 resource cards were hand-coded, with component swapping so images change
at different screen sizes.

![Resource cards](assets/renata/resource-cards.png)

**News section with "Load More"**
Custom JavaScript loads additional news items on demand.

![Renata in the News](assets/renata/news-section.png)

**Hospital finder (custom JS + CMS + Mapbox API)**
- Hospital data is managed in the CMS and plotted on a Mapbox map
- Search by hospital name, city, address, state, or zip code
- Nearby-hospital logic returns locations within [X miles] of the search,
  using latitude/longitude stored for each hospital
- Clear "no results" messaging and a reset button that restores the map
- Search bar designed and built from scratch, with absolute positioning
  tuned across screen sizes

![Hospital finder](assets/renata/find-hospital.png)
![Hospital finder interaction](assets/renata/find-hospital.gif)

**Forms and integrations**
- JotForm embedded via JavaScript and restyled to match the site
- Three additional custom forms: Parents, Renata Reading Room, and Contact Us
- Reading Room form syncs its submissions to a separate WordPress form
  through Zapier

![Reading Room form](assets/renata/reading-room.png)

**Tech:** HTML · CSS · JavaScript · Mapbox API · JotForm · Zapier · CMS · Figma handoff

---
