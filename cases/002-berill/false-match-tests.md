# BERILL — False-Match Tests

## Test 1 — Name-only matching

**Fail.**

A vessel name can change and can also be reused.

## Test 2 — IMO-only matching

**Strong but contextual.**

IMO 9311531 is a much stronger continuity key than a name, but historical attributes still require temporal validation.

## Test 3 — Manager-only matching

**Fail.**

A management company can manage multiple vessels and can change over time.

## Test 4 — Sanctions-name matching

**Fail if used alone.**

The UK record uses AFKADA while later sources use BERILL. The underlying IMO is the bridge.

## Test 5 — Cross-source temporal consistency

**Required.**

The same IMO should be tested across:

- name;
- flag;
- owner;
- manager;
- sanctions date;
- port history;
- source update date.

## Current conclusion

Public evidence strongly supports that the names belong to the same IMO-identified vessel, while individual ownership/management states require date-specific source validation.

> **Entity continuity and attribute continuity are different claims.**
