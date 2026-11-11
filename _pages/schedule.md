---
layout: page
title: "Intramural Schedule & Locations"
lead: "Fall 2026 intramural dates, game times and fields."
section: Programs

schedule:
  - date: "September 19–20"
    week: Week 1
  - date: "September 26–27"
    week: Week 2
  - date: "October 3–4"
    week: Week 3
  - date: "October 10–11"
    note: "No soccer — Columbus Day"
  - date: "October 17–18"
    week: Week 4
  - date: "October 24–25"
    week: Week 5
  - date: "October 31–November 1"
    week: Week 6
  - date: "November 7–8"
    week: Week 7
  - date: "November 14–15"
    week: Week 8
  - date: "November 21–22"
    week: "Rain date, if necessary"

ages:
  - division: Little Nuggets
    birth_year: "2023"
  - division: U5
    birth_year: "2022"
    generally: Pre-K
  - division: U6
    birth_year: "2021"
    generally: Kindergarten
  - division: U7
    birth_year: "2020"
    generally: 1st grade
  - division: U8
    birth_year: "2019"
    generally: 2nd grade
  - division: U9/10
    birth_year: "2018 & 2017"
    generally: "3rd & 4th grade"
---

Below please find the Fall 2026 Intramural Schedule.

## Fall 2026 Intramural Schedule

{% include schedule-table.html items=page.schedule %}

<div class="callout"><p><strong><em>All times are subject to change awaiting guidance from State, Local and School guidance.</em></strong></p></div>

## Times & Locations

| Age | Girls Saturday | Boys Sunday | Location | Address |
|-----|---------------|-------------|----------|---------|
| **U5** | 9:30 – 10:30 | 10:00 – 11:00 | Pasadena Elementary | 3 Richard Ct, Plainview, NY 11803 |
| **U6** | 11:00 – 12:00 | 11:30 – 12:30 | Pasadena Elementary | 3 Richard Ct, Plainview, NY 11803 |
| **U7** | 11:15 – 12:45 | 11:15 – 12:45 | Jamaica Avenue | 85 Jamaica Ave, Plainview, NY 11803 |
| **U8** | 1:15 – 2:45 (U8/U9) | 1:15 – 2:45 | Parkway Elementary | 300 Manetto Hill Rd, Plainview, NY 11803 |
| **U9** | — | 1:15 – 2:45 | Fern Place School | 1 Fern Pl, Plainview, NY 11803 |

All Little Nuggets sessions take place on Sundays at Jamaica Avenue School.

## Age Guidelines

| Division | Birth Year | Generally |
|----------|-----------|-----------|
{% for age in page.ages %}| {{ age.division }} | {{ age.birth_year }} | {{ age.generally | default: "—" }} |
{% endfor %}

## Friend Requests

The U5 (Pre-K) and U6 (Kindergarten) programs allow for the request to be grouped with 1 friend. We do our best to accommodate these requests but **they are not guaranteed**. We understand that soccer is social as well as developmental at these younger ages, but also have to maintain appropriate team sizes and groups so each child can get the most out of their experience.

For U7 – U9/U10 there will be no friend requests. As the children get older the games get more competitive and providing fair and balanced competition becomes the top priority.

See [Field Locations](fields.html) for maps and directions.
