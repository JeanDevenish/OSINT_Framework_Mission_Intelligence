# OSINT Mission Framework

> A mission-oriented fork of the [OSINT Framework](https://osintframework.com) by [@jnordine](https://github.com/lockfale/OSINT-Framework), reimagined for investigators, journalists, and law enforcement.

---

## What is this?

The original [OSINT Framework](https://osintframework.com) is an outstanding reference organized by **data type** — username, email, IP address, and so on. This fork adds a second navigation layer organized by **investigative mission** — answering not *"what tool searches X?"* but *"I need to find a missing person — where do I start?"*

All credit for the original tool collection goes to [@jnordine](https://github.com/lockfale). This project builds on top of that work.

This is my first Git. I'm just an OSINT investigator sharing a rethought tool.
---

## Missions presented

| Mission | Phases | Focus |
|---|---|---|
| 🔍 Missing Person Search | 4 | Identity anchors, social footprint, physical location, verification |
| 🧒 Missing Children | 4 | Official registries, digital trail, family network, NGO resources |
| 🔐 Privacy Leak / Data Breach | 4 | Credential exposure, paste sites, dark web, document metadata |
| 🗂️ Background Check | 4 | Identity, criminal & court records, financial, property |
| 🏢 Corporate Intelligence | 4 | Registration & structure, infrastructure, litigation, key people |
| 📍 Physical Location Intel | 4 | Image geolocation, IP location, social signals, transport |
| 📰 Disinformation / Fake Accounts | 4 | Account authenticity, media verification, narrative tracking, attribution |
| 🌑 Dark Web & Threat Intel | 4 | Dark web search, threat feeds, credential monitoring, attribution |

---

## Features

- **Mission View** — goal-driven workflows with structured investigative phases
- **Classic Tree View** — the original data-type taxonomy, preserved for power users
- **Phase-by-phase guidance** — each mission is broken into sequential steps with context
- **Tool flags** — `R` requires registration · `T` local install required · `D` Google Dork
- **Search & filter** — search across all tools and filter by category tag
- **Single file** — pure HTML/CSS/JS, no build step, no dependencies

---

## Usage

Open `osint-mission-framework.html` directly in any browser. No server required.

Or clone and drop it into the `public/` folder of an existing OSINT Framework fork.

```bash
git clone https://github.com/yourusername/osint-mission-framework
open osint-mission-framework.html
```

---

## Contributing

New tools should follow the original OSINT Framework contribution format. Additionally, please tag which missions a tool belongs to:

```json
{
  "name": "Example Tool",
  "type": "url",
  "url": "https://example.com",
  "missions": ["missing-person", "background-check"]
}
```

Pull requests welcome. For new missions or phase restructuring, open an issue first.

---

## Credits

This project is based on the [OSINT Framework](https://osintframework.com) originally created and maintained by [@jnordine](https://github.com/lockfale/OSINT-Framework). The tool collection, legend system, and open philosophy are all his work. This fork adds the mission layer on top.

---

## License

MIT — same as the original OSINT Framework.
