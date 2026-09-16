<p align="center">
  <img src="https://www.taylorurl.com/images/TaylorURL-Logo.png" width="200" alt="TaylorURL" />
</p>

<h1 align="center">TaylorURL</h1>

<p align="center">
  <b>Custom websites and JavaScript applications for local businesses.</b>
</p>
<p align="center">
  A web development company in Baytown, Texas, working across the greater Houston area.<br />
  <a href="https://taylorurl.com">taylorurl.com</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/React-19-2f6bff?style=for-the-badge&logo=react&logoColor=white" alt="React 19" />
  <img src="https://img.shields.io/badge/Vite-7-2f6bff?style=for-the-badge&logo=vite&logoColor=white" alt="Vite 7" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-3-2f6bff?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS 3" />
  <img src="https://img.shields.io/badge/Supabase-4f86ff?style=for-the-badge&logo=supabase&logoColor=white" alt="Supabase" />
  <img src="https://img.shields.io/badge/Vercel-2f6bff?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel" />
</p>

<br />

## What TaylorURL is

TaylorURL LLC builds the site or the application a business actually runs on,
rather than a template it has to fit itself into. The work does not stop at a
handover: every site here is hosted, watched from outside, and repaired by the
same hands that wrote it, and what each one is doing right now is published on
the [status board](https://www.taylorurl.com/status).

Most of what is in this organisation is one business's site. The rest is the
studio's own site, the tools more than one project depends on, and the
applications built to be used rather than visited.

<br />

## The studio

| Repository | What It Is |
| :--- | :--- |
| [taylorurl-com](https://github.com/TaylorURL/taylorurl-com) | The studio's own site and operations console. Every route is rendered to static HTML at build time, analytics are first-party and cookieless, and the console carries the traffic, uptime, mailing list and outreach behind a sign-in. [taylorurl.com](https://taylorurl.com) |

## Tools

| Repository | What It Is |
| :--- | :--- |
| [sunday](https://github.com/TaylorURL/sunday) | A checkpoint in front of every action a coding agent takes. The rule runs in the execution path and refuses, instead of sitting in a document the model has to remember. Go, and free to use. |
| [sunday-standards](https://github.com/TaylorURL/sunday-standards) | The checklists, standards and skills Sunday is run with here, published as a profile anyone can add underneath their own. |
| [split-rail](https://github.com/TaylorURL/split-rail) | The attribution rail that closes every TaylorURL site. One React component, no dependencies and no build step, taken as a dependency rather than copied, so changing the bar changes every site at once. |

## Applications

| Repository | What It Is |
| :--- | :--- |
| [domebreak-com](https://github.com/TaylorURL/domebreak-com) | DomeBreak — a real-time strategy missile game played on the living world map. React and MapLibre GL in the browser, Electron on the desktop. [domebreak.com](https://domebreak.com) |
| [smyrnatools-com](https://github.com/TaylorURL/smyrnatools-com) | The internal operations platform for Smyrna Ready Mix: fleet, people and plant performance across every region and plant, each record carrying a verification state and a full change history. [smyrnatools.com](https://smyrnatools.com) |
| [impressivaprinting-com](https://github.com/TaylorURL/impressivaprinting-com) | A print-shop storefront with a client portal and an admin back office. [impressivaprinting.com](https://impressivaprinting.com) |
| [setxfootball-com](https://github.com/TaylorURL/setxfootball-com) | Signups and shirt orders for a local youth football league. [setxfootball.org](https://setxfootball.org) |

## Client sites

| Repository | Who It Is For |
| :--- | :--- |
| [baytowngocarts-com](https://github.com/TaylorURL/baytowngocarts-com) | Speedway 146, a go-kart track in Baytown, Texas. [baytowngokarts.com](https://baytowngokarts.com) |
| [deluxlavello-com](https://github.com/TaylorURL/deluxlavello-com) | Delux Financial Solutions. [deluxlavello.com](https://deluxlavello.com) |
| [deluxfitbyangie-com](https://github.com/TaylorURL/deluxfitbyangie-com) | DeluxFit by Angie, a personal training program. [deluxfitbyangie.com](https://deluxfitbyangie.com) |
| [dickinsonbayoufleeting-com](https://github.com/TaylorURL/dickinsonbayoufleeting-com) | Dickinson Bayou Fleeting, a barge fleeting company. [dickinsonbayoufleeting.com](https://dickinsonbayoufleeting.com) |
| [djrxexcellence-com](https://github.com/TaylorURL/djrxexcellence-com) | Dylan Jordan of RE/MAX Excellence in Dayton, Texas, with a Supabase-backed listing manager. [djrxexcellence.com](https://djrxexcellence.com) |
| [fadedbarbershop-com](https://github.com/TaylorURL/fadedbarbershop-com) | Faded Barber Shop in Liberty, Texas. [fadedbarbershop.com](https://fadedbarbershop.com) |
| [hollingsheadharbor-com](https://github.com/TaylorURL/hollingsheadharbor-com) | Hollingshead Harbor. [hollingsheadharbor.com](https://hollingsheadharbor.com) |
| [rootriseholdings-com](https://github.com/TaylorURL/rootriseholdings-com) | Rise & Root Holdings. [rootriseholdings.com](https://rootriseholdings.com) |

<br />

## How the work is built

- **One stack, so a fix travels.** Nearly every project is React 19 on Vite with
  Tailwind, deployed to Vercel, with Supabase carrying the database, the auth
  and the serverless work. A pattern that is right once is right everywhere it
  is used next.
- **Shared code is a dependency, not a copy.** The rail every site closes with
  is a package pinned to a version. A copy in each project is a bar nobody can
  change; one package is a bar changed once.
- **Versions are dates.** Releases are calendar-versioned, and a pull request
  moves the version exactly once, so a number on a page says when it was cut
  rather than how many times somebody remembered to increment it.
- **Errors report themselves.** Every live site posts the errors a real browser
  hits to a queue that files them, works them, and checks the fix against the
  live page. The result is public on the [status board](https://www.taylorurl.com/status).
- **Nothing is written by hand twice.** The checklists a project is held to
  before it ships — design, SEO, performance, stack and database — are the ones
  published in [sunday-standards](https://github.com/TaylorURL/sunday-standards).

<br />

## Working together

New work starts at [taylorurl.com](https://taylorurl.com), or at
[trenton@taylorurl.com](mailto:trenton@taylorurl.com).

Sunday is free to use on any number of machines, for personal or commercial
work, under the licence in its own repository. A client's site is published to
be read; the business it belongs to owns it.
