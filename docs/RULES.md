# IRCC upload rules (public overview)

IRCC Ready Docs is built around the upload constraints applicants hit on IRCC portals. This page summarizes the rules the tools and guides target. It is **not** official IRCC policy.

If anything here disagrees with [canada.ca](https://www.canada.ca/en/services/immigration-citizenship.html) or the form you are filing, **the official page wins**.

Live product: [docs.getnorthpath.com](https://docs.getnorthpath.com)

---

## File size

| Rule of thumb | Notes |
| --- | --- |
| **4 MB** per uploaded file | Common cap on many IRCC online fields |
| **2 MB** on some fields | Stricter portals; Compress PDF includes a 2 MB preset |
| **1 MB** preset | Available in Compress PDF for tighter targets |

Guide: [IRCC file size limit](https://docs.getnorthpath.com/guides/ircc-file-size-limit) · Tool: [Compress PDF to 4 MB](https://docs.getnorthpath.com/compress-pdf-to-4mb)

---

## File formats

Commonly accepted types for online uploads include **PDF**, **TIFF**, **JPG**, **PNG**, **DOC**, and **DOCX**. What is allowed still depends on the specific form or portal field.

Guide: [IRCC accepted file formats](https://docs.getnorthpath.com/guides/ircc-file-formats)

---

## Fillable IMM forms and merge failures

IMM forms are often fillable PDFs. Merging them with other documents can show a blank page or a “Please wait…” message.

| Step | Why |
| --- | --- |
| Validate / complete the form in the software you used | Generates barcodes and finalizes fields where required |
| Flatten AcroForm fields | Turns fillable fields into static page content so the form merges like a normal PDF |
| Then merge | Combine with supporting documents for one checklist slot |

Some forms use true dynamic XFA fields that only Adobe Reader can flatten. If merge still fails after this site’s flatten tool, open the form once in Adobe Reader, save it, and try again.

Guide: [Why IMM forms will not merge](https://docs.getnorthpath.com/guides/cannot-merge-ircc-forms) · Tool: [Flatten IMM Form](https://docs.getnorthpath.com/flatten-imm-form)

Flattening is **one way**. Keep your original filled copy if you need to edit later.

---

## Photos

| Spec | Notes |
| --- | --- |
| Canada visa photo | **35×45 mm** framing; export at IRCC pixel sizes |
| PR / citizenship photos | Related but not always identical to the visa baseline |

Tools: [Canada Visa Photo](https://docs.getnorthpath.com/canada-visa-photo), [Resize Image](https://docs.getnorthpath.com/resize-image) · Guides: [visa photo requirements](https://docs.getnorthpath.com/guides/canada-visa-photo-requirements), [PR / citizenship photo](https://docs.getnorthpath.com/guides/canada-pr-photo)

---

## File checker (heuristic)

The [IRCC File Checker](https://docs.getnorthpath.com/ircc-file-checker) gives an in-browser pass/fail on format, size, and (heuristically) hidden form fields that can break merging.

It is **not** an official IRCC verdict. Always follow the upload instructions on the form you are filing.

---

## Privacy note for these rules

Compress, merge, flatten, photo, and checker tools run in the browser. Application files are not uploaded to a GetNorthPath server for those operations. Optional email unlock on some downloads may collect an email address only; see [Privacy](https://www.getnorthpath.com/privacy).

---

## Related

- [WORKFLOW.md](WORKFLOW.md): stuck-on sequences
- [FEATURES.md](FEATURES.md): full URL inventory
- Official forms index: [IRCC application forms and guides](https://www.canada.ca/en/immigration-refugees-citizenship/services/application/application-forms-guides.html)
