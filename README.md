# Waterline: Pool Water Chemistry Console

**Vibe coded.** This was built with an AI coding assistant, not hand-written line by line. It works and the chemistry was researched, but treat it like a quick helpful tool, not audited professional software.

A simple browser dashboard for pool water chemistry. Type in your test readings, get a plain-English read on whether the water's safe and what to add to fix it.

It's one HTML file. No install, no server, nothing to set up. Open it and it works.

**[[Live demo](https://henryadams123.github.io/Waterline-Pool-Console/)]** 

---

## What it does

**Daily mode.** Just the four things you'd check day to day: pH, Free Chlorine, ORP, and water temp.

**Full test mode.** The whole panel, if you've run a complete test: Alkalinity, Calcium Hardness, Cyanuric Acid, Combined Chlorine, Salt, and TDS.

Four sections on the dashboard:

1. **Water Status.** How safe the water is to swim in right now, plus a balance meter (is it corrosive, scaling, or fine).
2. **Parameter Status.** Each reading shown against its ideal range, color-coded, with a "raise it," "lower it," or "you're good" note.
3. **Get Back in Range.** What to add and how much, in the right order.
4. **Advanced Analytics.** Plain-language notes on what might actually be causing an issue, for example: your ORP looks fine, but that's because your pH is low, not because the chlorine is actually working.

## Where the numbers come from

The target ranges and dosing amounts are based on standard pool industry guidelines (Pool & Hot Tub Alliance / CDC), adjusted a bit for your setup: salt system or not, plaster or vinyl, indoor or outdoor. It also factors in that how much chlorine you need depends on your stabilizer (CYA) level, which a lot of basic calculators skip.

This hasn't been checked by a pool professional. Use it as a helpful starting point, not gospel, especially for anything commercial.

## Volume

Type in gallons directly, or use the built-in calculator to estimate volume from your pool's shape and dimensions.

## Tech

Plain HTML, CSS, and JavaScript. No frameworks, no build step, no dependencies beyond a Google Font. Runs entirely in your browser. Nothing gets sent anywhere or saved.
