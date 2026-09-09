# What IRCC Ready Docs does

**IRCC Ready Docs** is a free web app that helps Canadian immigration applicants prepare documents for IRCC online uploads: compress to size limits, merge checklist slots, flatten IMM forms, crop visa photos, and check files before the portal rejects them.

Live: [docs.getnorthpath.com](https://docs.getnorthpath.com)

It is a **mini SaaS**: a focused product with working tools, long-form guides, IMM form pages, program checklists, templates, and country tips, plus an optional path into a GetNorthPath consultation. It is **not** a full immigration case management system. That lives on [getnorthpath.com](https://www.getnorthpath.com). See [ABOUT.md](../ABOUT.md).

---

## Problem it solves

IRCC portals often reject files for practical reasons applicants hit every week:

- A single upload capped at **4 MB** (some fields **2 MB**)
- Wrong formats or broken merges on fillable IMM forms (“Please wait…”)
- Visa photos that fail the **35×45 mm** crop
- Loose scans that need cleaning, combining, or page numbers

Generic PDF software is not built around those IRCC upload problems. This product is.

---

## Product surfaces

```
docs.getnorthpath.com
├── Home            hub for tools, templates, guides, forms, checklists, countries, FAQ
├── Toolkit hub     /northpath-docs-app catalog of live tools and resources
├── Tools           15 in-browser tools (Word to PDF coming soon)
├── Guides          IRCC size, formats, merge, flatten, photo, scan tips
├── IMM forms       what each form is for and how to prepare it
├── Checklists      program document lists with size targets
├── Templates       free practice templates with tool CTAs
├── Countries       tips by source country (/from/…)
└── Consult CTA     optional free GetNorthPath call
```

Details: [FEATURES.md](FEATURES.md) · [WORKFLOW.md](WORKFLOW.md) · [RULES.md](RULES.md)

---

## What it is

- A **document toolkit** aimed at IRCC upload rules (size, format, flatten, photo)
- A **content site** (guides, form hubs, checklists, templates, country notes)
- A **lead in** to GetNorthPath if you want a human consult
- Available in **2 languages** (English default; French at `/fr/…`)
- Free to use; tools run **in your browser** so application files are not uploaded to a GetNorthPath server for compress, merge, flatten, or check

## What it is not

- Not an official IRCC or Government of Canada tool
- Not a guarantee that IRCC will accept a file
- Not legal advice or a substitute for reading the form instructions you are filing
- Not a full desktop PDF editor for every office workflow
- Not the same as GetNorthPath’s paid application workspace
- Not the [OINP Calculator](https://oinp.getnorthpath.com) (Ontario points) or [AORTrack](https://track.getnorthpath.com) (PR timelines)

---

## How a typical visit goes

1. Land on the home hub or open a specific tool URL
2. Pick the stuck step (too big, will not merge, wrong photo, and so on)
3. Run the matching tool in the browser
4. Optionally read the linked guide, form page, or checklist
5. Optionally check the file with the IRCC File Checker
6. Optionally book a free GetNorthPath consult

No account is required to use the tools. Some downloads may ask for an email to unlock; that collects contact details only, not your document file. See GetNorthPath [Privacy](https://www.getnorthpath.com/privacy) and [Terms](https://www.getnorthpath.com/terms).

---

## Accuracy stance

| Source | Role |
| --- | --- |
| [IRCC on canada.ca](https://www.canada.ca/en/services/immigration-citizenship.html) | Official program and upload rules |
| [Application forms and guides](https://www.canada.ca/en/immigration-refugees-citizenship/services/application/application-forms-guides.html) | Current IMM forms and instructions |
| Form-specific IRCC pages | Official downloads for each IMM form |

If this app and canada.ca disagree, **canada.ca wins**.

---

## Privacy and leads

Document processing for the tools runs in the browser session. Optional email unlock or consult forms may collect contact details so GetNorthPath can follow up. Those submissions are covered by GetNorthPath [Privacy](https://www.getnorthpath.com/privacy) and [Terms](https://www.getnorthpath.com/terms). Application files used in the tools are not uploaded to a GetNorthPath server for compress, merge, flatten, or check.

---

## Related GetNorthPath products

| Product | Job |
| --- | --- |
| **IRCC Ready Docs** (this) | Free document tools and IRCC upload guides |
| **GetNorthPath platform** | End to end application workspace ($299 CAD) |
| **OINP Calculator** | Ontario PNP points and education |
| **AORTrack** | Community PR milestone timelines |
| **CRS calculator** | Federal Express Entry ranking |

© GetNorthPath Inc. Not affiliated with IRCC or the Government of Canada.
