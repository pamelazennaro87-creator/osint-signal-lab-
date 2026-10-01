# Case 002 — BERILL / IMO 9311531

## Vessel Identity, Name Continuity and Sanctions Trace

### Research question

> **Can the public record establish continuity of IMO 9311531 across changing vessel names, flags, managers and sanctions records without treating a changing attribute as a new vessel identity?**

## Why this case matters

Maritime OSINT creates a classic entity-resolution problem:

- names change;
- flags change;
- owners/managers change;
- databases update at different times;
- sanctions records may use a historical name;
- AIS data is time-sensitive.

The IMO number provides a strong continuity anchor, but the surrounding attributes must still be reconstructed temporally.

## Current public evidence

The Ukrainian GUR sanctions database currently identifies **BERILL, IMO 9311531**, and lists former names including **Lindor** and **Reinel**. It also records historical management information and sanctions across multiple jurisdictions.

Source:
https://war-sanctions.gur.gov.ua/en/transport/ships/470

The UK government designated **IMO 9311531**, then named **AFKADA**, on 9 May 2025 under its Russia sanctions regime, citing carriage of Russian-origin oil/oil products from Russia to a third country.

Source:
https://www.gov.uk/government/publications/list-of-russia-sanctions-targets-9-may-2025/russia-sanctions-9-may-2025

VesselFinder independently associates IMO 9311531 with BERILL and provides a historical sequence containing LINDOR and REINEL.

Source:
https://www.vesselfinder.com/vessels/details/9311531

## Initial continuity chain

**IMO 9311531**

→ Lefkada  
→ Afkada  
→ Reinel  
→ Lindor  
→ Berill

The chain must be treated as a temporal reconstruction, not as a static list.

## Important distinction

A sanctions record naming **AFKADA** in May 2025 and a later database naming **BERILL** do not represent two different ships merely because the names differ.

Conversely, a matching IMO number should not be used to assume that all historical ownership or management claims are simultaneously valid.

## Research questions

1. When did each name become active?
2. Which flag applied at each date?
3. Who was owner, commercial manager and ISM manager at each point?
4. Which claims are first-party versus database-derived?
5. Do sanctions records preserve historical state accurately?
6. Where do sources disagree?
7. Which ownership/management changes are genuine and which reflect delayed database updates?
8. What is the minimum evidence needed to assert continuity?

## Boundary

This case documents public maritime and sanctions records. It does not infer beneficial ownership beyond what sources establish.

**Status:** Active research.
