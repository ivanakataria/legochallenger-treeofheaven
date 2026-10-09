🌳

# Tree of Heaven Tracker

A treatment companion to iNaturalist — track invasive management, scientist requests, and five-year forecasts. Species ID and biodiversity observations stay on iNaturalist / Seek.

⏰ **Heads up:** this page can't send you a notification on its own after five years — browsers don't allow that. Set a calendar reminder for your five-year check-in date; all the data here will be waiting and ready when you open it again.

## Companion positioning

Works with iNaturalist, not instead of it. Use iNaturalist or Seek to identify and record Tree of Heaven. Bring confirmed spots here to manage treatment status, scientist visits, and long-term clearance.

## 🧒 Two sites, two jobs (kid-friendly)

| | iNaturalist | Our Tree Tracker |
|---|---|---|
| What for? | Finding out **what** a plant or animal is | Helping take care of **Tree of Heaven** |
| Like… | A nature **detective** app | A **to-do list** for trees that need help |
| You do | Take a photo → learn the name | Write down where it is → track treatment |
| Who helps? | Nature fans online | Scientists / helpers who treat trees |
| Big idea | “What did I find?” | “What should we do about it?” |

Easy remember: iNaturalist = **name it**. Our site = **fix it**.

## 🔍 Why this tracker exists

Tree of Heaven is an **invasive species** that spreads fast. iNaturalist is the right place for community ID and biodiversity records. This tool picks up where that leaves off: treatment status, scientist requests, and forecasts for where management should be prioritized.

## 🔎 Field quick-check (confirm on iNaturalist)

Short field checklist to decide whether a plant is worth a closer look. For photo ID and community confirmation, open iNaturalist (taxon *Ailanthus altissima*, taxon_id=57278) or the Seek app — then import the observation here when you're ready to track treatment.

- **Leaves:** long compound leaves (1–4 ft) with 10–41 smooth-edged leaflets, each with 1–2 small notched "teeth" near its base.
- **Smell:** crushed leaves or stems smell like rancid peanut butter or burnt rubber.
- **Bark:** smooth and pale gray, like cantaloupe skin, when the tree is young.
- **Seeds:** clusters of twisted, tan-to-reddish papery samaras (helicopter-style seed pods) in late summer/fall.
- **Where it grows:** disturbed soil — roadsides, fence lines, vacant lots, rail corridors.

## 🌿 iNaturalist — nearby Tree of Heaven

Pull live observations from `https://api.inaturalist.org/v1/observations` (taxon_id=57278). Support geo radius via device location and/or US state place filter. Links: taxon page, browse observations, observe/upload, Seek, iNaturalist home.

Import selected observations into the local treatment tracker (localStorage) with iNat id/uri; skip duplicates. Research-grade → validation confirmed; treatment status still starts as not treated so invasive control is managed here.

## 📍 Trees Near Me (local tracker)

Checks your device's current location against trees already logged in **this** tracker (within about 30 miles) or anywhere in your state. For community observations, use the iNaturalist panel.

## 🧪 Sample Data

This loads **made-up example data** — one entry per year for 5 years (2022–2026), for all 50 states — so you can see how the charts and rankings look with a full dataset. It's simulated, not real field data, so swap it out for your own measurements as you collect them.

## ➕ New treatment site / Measurement

Prefer logging biodiversity observations on iNaturalist first, then import them — or add a treatment site manually when you already know the spot and want to track management.

Date

State

Location details (be specific — you'll want to find this spot again)

City (helps scientists filter requests)

Zip code

Height (ft)

Trunk (in)

\# of trees

Treatment status Notes

## 🔬 Scientist Network & Field Validation

Before a drone treats a tree, a scientist should confirm the sighting really is Tree of Heaven — and after a treatment, someone needs to check back on it. Scientists here are a **sample directory** to show how it would work; swap in your state's forestry extension office, a university plant-diagnostic lab, or a master naturalist program for a real deployment. Community ID still belongs on iNaturalist; this network is for treatment / field validation workflow.

## 👩‍🔬 Scientists

Find near me, or pick a state above.

Click **Request Treatment** on a scientist to pick which logged trees in their state to send them. Sent trees show a **📨 Requested** badge in Full History; once the scientist reports back (in the "Field Requests & Scientist Reports" card below), each tree's status updates automatically.

## 📨 Field Requests & Scientist Reports

Each tree (or cluster) you log gets a field **QR tag** — print it and attach it near the tree. To ask a scientist to start monitoring/treatment: check the trees you want in **Full History** below, then hit "Request Visit" on a scientist above. When they report back, come here to enter their update — which trees they started treating, which are pending, and which turned out not to be Tree of Heaven — and it updates those trees' status everywhere in the app automatically.

Generates realistic sample requests across every state — some states split between two different scientists — with a mix of outcomes: responded with treatment started, responded with only monitoring, responded with trees flagged invalid, and some scientists who haven't responded at all. Loads sample trees first automatically if you haven't already.

## 📊 Scientist Response Tracker

How many requests scientists have responded to, by state.

Filter by state (leave empty for all states; ctrl/cmd-click to pick a few)

## 🧪 Scientist Report Status Breakdown

Across every tree assigned to a scientist so far: how many they've started treating, how many are just being monitored, how many are cleared, how many they've flagged as not actually Tree of Heaven, and how many are still awaiting their report.

## 🧑‍🔬 Scientist Activity — Started vs. Not Started

One bar per scientist you've assigned trees to, so you can see at a glance who has started work and who hasn't responded yet.

## 🗺️ Most Affected States

Top 10 states by total trees counted. Use the dropdown to check any other state.

Check another state

## 📊 Average Height Over Time

Filter by state

## 🌱 Total Tree Count Over Time

Sum of all trees counted, across the states selected above, per year.

## 🚦 Treatment Status Breakdown by Year

Not treated vs. monitoring vs. treating vs. cleared, as a share of total trees counted each year — for quick go/no-go decisions.

## 📍 Tree Status by Location

Current status of every logged site (most recent entry per location) — requests sent to a scientist, monitoring or treatment underway, cleared, or flagged invalid with the reason. Entries imported from iNaturalist show an iNat link.

## 🚁 5-Year Treatment Forecast

Models your drone + *Verticillium nonalfalfae* fungus plan against the top 5 states with the most Tree of Heaven, based on the most recent count logged for each state. Adjust the assumptions and re-run.

\# of drones

Trees treated / drone / yr

Untreated growth %/yr

## 📈 Summary

## 📋 Full History ▸

## 🛠️ Admin

Pick an action below. A browser page can't send email or run on a schedule by itself — each action gets whatever's due ready for you to send or act on with one click whenever you check back in.

## ‹ Back

## 📨 Send Reminders

Scientists who haven't responded to a request at all yet. Set a cadence, then send whoever's overdue a ready-made reminder email.

Remind scientists who haven't responded, every

## ‹ Back

## 🔁 Follow Up on Stalled Monitoring/Treatment

Trees where a scientist responded and started monitoring or treatment, but hasn't reported any progress in 30+ days. Ask them directly whether there's an update, or why it hasn't moved forward.

## ‹ Back

## 🧹 Remove Invalid Trees From Dataset

Trees a scientist has confirmed are **not** actually Tree of Heaven. Review the reason for each, then remove the ones you agree with — this deletes them from your dataset for good (charts and counts update right away).

Saved!
