# LOCAL SEO MODIFIER

## Location-Based SEO Enhancement

---

## 🎯 Purpose

This modifier adds location-specific SEO elements to any content. Apply this after the main prompt to ensure local relevance and capture "near me" and location-based searches.

---

## 📋 PROMPT ADDITION

```
=== LOCAL SEO MODIFIER ===

Apply these local SEO enhancements to all content:

**LOCATION PARAMETERS:**
- Primary City: [INSERT: Johannesburg]
- Region: [INSERT: Gauteng]
- Country: [INSERT: South Africa]
- Service Areas: [INSERT: Sandton, Randburg, Pretoria, Centurion]
- Neighborhoods: [INSERT: Specific areas covered]

---

## KEYWORD MODIFICATIONS

### Add Location Keywords
Integrate these naturally throughout the content:

**Primary Location Keywords:**
- "[service] in Johannesburg"
- "[service] Gauteng"
- "best [service] Johannesburg"
- "[service] near me in [city]"
- "[service] [area/neighborhood]"

**Secondary Location Keywords:**
- "[service] Sandton"
- "[service] Pretoria"
- "[service] Randburg"
- "[service] [neighborhood]"
- "local [service] [city]"

**Long-tail Location Keywords:**
- "affordable [service] Johannesburg"
- "best [service] near [landmark]"
- "[service] [city] reviews"
- "[service] open Saturday [city]"
- "emergency [service] [city]"

---

## LOCAL CONTENT ELEMENTS

### 1. Location Integration
Add 5-8 natural location mentions throughout content:
- Opening paragraph: Mention primary city
- Service section: List 2-3 areas served
- Process section: Reference local considerations
- Conclusion: Call to action with location

### 2. Neighborhood References
Include specific local references:
- "Serving patients throughout [Johannesburg] and surrounding areas including [Sandton], [Randburg], [Pretoria], and [Centurion]"
- "Conveniently located in [area] with easy access from [highway/landmark]"
- "Our [city] practice serves patients from [neighborhood 1], [neighborhood 2], and beyond"

### 3. Local Context
Add relevant local information:
- "In [Johannesburg], [topic] is particularly important because [local reason]"
- "Residents of [Gauteng] often ask about [topic] because [local context]"
- "Compared to other [cities/regions], [Johannesburg] patients typically [behavior/stat]"

### 4. Service Area Description
Include a dedicated section:
```

## Serving [Johangesburg] and Gauteng

Our dental practice proudly serves patients throughout [Johannesburg] and the greater [Gauteng] region. From our convenient location in [area], we're easily accessible for residents of [Sandton], [Randburg], [Pretoria], [Centurion], and surrounding communities.

Whether you're in [neighborhood 1] or [neighborhood 2], our team is here to provide exceptional [service] to our local community.

````

---

## LOCAL SCHEMA MARKUP

Add this JSON-LD for local business:

```json
{
  "@context": "https://schema.org",
  "@type": "DentalClinic",
  "name": "[Business Name]",
  "address": {
    "@type": "PostalAddress",
    "streetAddress": "[Street Address]",
    "addressLocality": "Johannesburg",
    "addressRegion": "Gauteng",
    "postalCode": "[0000]",
    "addressCountry": "ZA"
  },
  "telephone": "[Phone Number]",
  "openingHours": ["Mo-Fr 08:00-17:00", "Sa 09:00-13:00"],
  "priceRange": "$$",
  "areaServed": {
    "@type": "Place",
    "name": "Johannesburg, Gauteng"
  }
}
````

---

## "NEAR ME" OPTIMIZATION

### Capture "Near Me" Searches

Include natural phrases that match "near me" search patterns:

- "Find a [service] near you in [Johannesburg]"
- "[Service] near me" → Address this with: "For patients throughout [Johannesburg], finding quality [service] is easy when you know what to look for."
- "Best [service] near me" → Address with: "If you're searching for the best [service] in [Johannesburg], here's what you need to know."
- "[Service] near [landmark]" → Reference local landmarks

### Directional Keywords

Include phrases people use when searching locally:

- "[service] in central Johannesburg"
- "[service] on [main road]"
- "[service] close to [landmark]"
- "[service] in the [area] area"

---

## GOOGLE BUSINESS PROFILE OPTIMIZATION

Align content with Google Business Profile:

### Categories

Ensure matching categories in GMB:

- Primary: [Dentist / Service Category]
- Secondary: [Related services offered]

### Services List

Match these exactly in your GMB:

1. [Service 1]
2. [Service 2]
3. [Service 3]
4. [Service 4]
5. [Service 5]

### Attributes to Include

- [x] Wheelchair accessible
- [x] Accepts new patients
- [x] Emergency services
- [x] Online bookings
- [x] Male/Female practitioners

---

## LOCAL LINK BUILDING OPPORTUNITIES

### Local Citations

Ensure NAP consistency across:

- [x] Google Business Profile
- [x] Facebook Page
- [x] Yelp
- [x] Hotfrog
- [x] Cylex
- [x] Brownbook

### Local Backlink Targets

- [x] Johannesburg Chamber of Commerce
- [x] Gauteng business directories
- [x] Local news sites
- [x] Community organizations

---

## LOCAL CTA EXAMPLES

**With Phone:**
"Schedule your [service] today. Call [phone] to book your appointment at our [Johannesburg] practice."

**With Location:**
"Visit our [Sandton] clinic for [service]. Located at [address], serving all of [Johannesburg]."

**With Booking:**
"Ready to [benefit]? [Book online] now for your [service] consultation."

**Community Focus:**
"Proudly serving the [Johannesburg] community with quality [service] since [year]."

---

## CONTENT PLACEMENT GUIDE

| Element              | Placement                      | Frequency  |
| -------------------- | ------------------------------ | ---------- |
| City name (primary)  | H1, intro, 2-3 body sections   | 5-8 times  |
| Region name          | 2-3 sections                   | 3-5 times  |
| Neighborhoods        | 2-3 mentions each              | 6-10 total |
| "Near me" phrases    | Throughout content             | 3-5 times  |
| Service area mention | Dedicated section + conclusion | 2 times    |

---

## FINAL LOCAL SEO CHECKLIST

- [ ] Primary city in title (H1)
- [ ] City/region in meta description
- [ ] Location in first 100 words
- [ ] 5-8 natural location mentions
- [ ] Neighborhoods referenced
- [ ] Service area described
- [ ] "Near me" search terms addressed
- [ ] Local schema markup suggested
- [ ] NAP consistent throughout
- [ ] Local CTA included
- [ ] Google Business Profile aligned

---

_Apply this modifier after MASTER_PROMPT_SYSTEM and content prompt_
