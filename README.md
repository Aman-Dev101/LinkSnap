<h1 align="center">LinkSnap</h1>
<p align="center">A URL shortener with click analytics. Paste a long link, get a short one, and see how many times it was opened.</p>

<p align="center">
  <img src="https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black" alt="React" />
  <img src="https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Express-000000?logo=express&logoColor=white" alt="Express" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/status-in%20progress-yellow" alt="Status" />
</p>

## About
LinkSnap turns any long URL into a short link. Every visit to a short link redirects to the original page and increases its click counter, which is shown in a simple dashboard.

## Features
- [ ] Create a short link from any URL
- [ ] Redirect short links to the original URL
- [ ] Count clicks per link
- [ ] Dashboard listing all links and their clicks
- [ ] React interface

## API
| Method | Route | Description |
|---|---|---|
| POST | `/api/links` | Create a short link |
| GET | `/:code` | Redirect to the original URL |
| GET | `/api/links` | List links with click counts |

## Tech stack
| Layer | Technology |
|---|---|
| Frontend | React |
| Backend | Node.js, Express |
| Database | PostgreSQL |

## Screenshots
Coming soon.

## Getting started
Setup instructions will be added as the project is built.

## Author
Aman Mishra · [GitHub](https://github.com/Aman-Dev101)
