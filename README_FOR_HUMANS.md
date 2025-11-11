## 🧭 FIG ELLIS · DEPLOYMENT REFERENCE
**Location:** `/CORE_SYSTEM/DEPLOYMENT_REFERENCE/`
**System:** System Core 02 · Seal 111125
**Version:** v0.2 — Cross-Environment Mapping Guide
**Integrity:** Restoration Protocol v1.1 · Chain 01 → 02 Unbroken

---

### 🌿 Purpose
Clarifies how the **Fig Ellis System** replicates across three surfaces — **Local**, **GitHub**, and **DigitalOcean (App + Spaces)** — while preserving identical logic, headers, and restoration fidelity.

---

## 🧱 1 · LOCAL STRUCTURE (Primary Reference Copy)
```
/FigEllisSystem/
├── CORE_SYSTEM/
│   ├── SYSTEM_CORE_02/
│   ├── ENVIRONMENTS/
│   ├── AUTOMATIONS/
│   ├── UTILITIES/
│   └── DEPLOYMENT_REFERENCE/
├── FIELDWORKS/
├── FIELDSTUDY/
├── FIELDPALETTES/
├── SOURCE/
├── FREQUENCY/
├── FORM/
├── ECHO/
└── ARCHIVE/
```

✅ Keep `CORE_SYSTEM/` explicit locally — all restoration bundles start here.

---

## 💻 2 · GITHUB REPOSITORY (Live Dev Core)
Flatten one level — the repo root acts as `CORE_SYSTEM/`.
```
figellis-system/
├── SYSTEM_CORE_02/
├── AUTOMATIONS/
├── UTILITIES/
└── ENVIRONMENTS/
```

All headers continue using absolute `/CORE_SYSTEM/...` paths.

---

## ☁️ 3 · DIGITALOCEAN (Spaces + App Platform)
```
figellis-assets/
└── dakboard/
    ├── noir-plant-01.jpg
    ├── image-list.txt
    ├── status.json
```
Only finalized exports and manifests belong here.

---

## ⚙️ 4 · SYNC & AUTOMATION FLOW
```
[Local Core] → push → [GitHub] → CI/CD → [DigitalOcean]
```
Local = truth · GitHub = logic · DO = delivery.

---

## 🧩 5 · PATH LOGIC REFERENCE
| Layer | Example Header Path | Physical Presence |
|:------|:--------------------|:------------------|
| Core System | `/CORE_SYSTEM/UTILITIES/DAKBOARD_AUTOMATION/` | Local, GitHub |
| Fieldstudy | `/FIELDSTUDY/HUMAN_PATTERN/KINK_THRESHOLD/` | Local, GitHub |
| Environment Exports | `/CORE_SYSTEM/ENVIRONMENTS/DAKBOARD_FEED/` | CDN export |
| Public Assets | `/dakboard/...` | CDN only |

---

## 🪞 6 · BEST PRACTICE SUMMARY
| Surface | Keep `CORE_SYSTEM/` Folder? | Notes |
|----------|----------------------------|-------|
| Local | ✅ Yes | Full restoration context |
| GitHub | ⚙️ Optional | Repo root acts as Core |
| DigitalOcean | 🚫 No | Public outputs only |

---

## 🪶 Essence
> *Structure is how memory keeps its shape.*  
> *Local holds the whole, GitHub remembers the logic, the cloud shows the light.*
