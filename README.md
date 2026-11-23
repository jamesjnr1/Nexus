# Nexus

**One system. Everything connected.**

Nexus is a personal dashboard that brings academics, business, leadership, finance, ideas and personal development into one place.

## What's inside

- **Today**: a focus task, week progress, the six areas at a glance, everything due next, and calendar, money and growth summaries.
- **Academics**: courses, assignments and deadlines, and a weekly study plan.
- **Business**: BeyondX, Flokefama, fraudX, Home Office Group and other ventures, each with its own tasks.
- **Leadership**: Parliament meetings, a constituent issue tracker, campaign tasks and leadership goals.
- **Finance**: a budget gauge, daily spending chart, category tiles for quick logging, a money calendar, trends, a category breakdown, budgets and savings goals, all in GH₵.
- **Ideas**: capture ideas, score each on desirability, feasibility and viability (DFV), and see them ranked and plotted.
- **Growth**: a CS50W tracker, a programming practice streak and heatmap, a reading list, and leadership goals.

Quick capture: type in the top bar, e.g. `Pitch review tomorrow` (Task) or `45 lunch` (Expense). Press `/` to jump to it.

## Tech

A single static `index.html` (HTML, CSS and vanilla JS). There's no build step and no dependencies.

## Deploy on Vercel

1. Import this repo at vercel.com/new.
2. Framework preset: **Other**. Leave the build command and output directory empty.
3. Click Deploy.

## Where data is stored

- **On Vercel or any static host**, data is saved in your browser (localStorage). Use **Export data** and **Import data** in the sidebar to back it up or move it to another device.
- **On claude.ai**, data syncs privately to your account. Google Calendar events and the Claude features (Plan my week, Develop with Claude) are also available there.

## Brand

`brand/nexus-logo.svg` is the full lockup and `brand/nexus-mark.svg` is the app icon. Colours: ink `#0f1213`, vermilion `#e5482d`, light `#eceeef`. Typeface: DM Sans.
