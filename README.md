# CAD Handoff Checklist

A practical six-step review before sharing a DWG, DXF or PDF deliverable. Use this checklist with the receiving application and the recipient’s actual requirements; file readability alone does not prove a complete handoff.

## 1. Keep the editable source

- Preserve the original drawing before conversion or revision.
- Export a separate deliverable with a clear revision name. Keep a short note of what changed, the intended recipient and the required output.

## 2. Choose the recipient's next task

- Further drafting: agree on an editable format and version that the receiving application supports.
- Review or printing: provide a PDF alongside the editable source when appropriate.
- Manufacturing or machine processing: confirm the recipient's specific format, units and geometry requirements; a readable PDF is not a substitute.

## 3. Check units and one known dimension

- Identify the drawing units; measure a distance whose expected value is known.
- Use the same endpoints when comparing source and output. Record the value and unit.
- Resolve a discrepancy before delivery. Changing paper size does not convert drawing units.

## 4. Inspect more than the outline

- Compare text, dimension labels, special characters, layers and blocks in the exported drawing.
- Check that the required layers are visible and repeated details remain in the correct positions.
- Review missing-font, external-reference or image warnings. Do not assume that opening successfully proves complete compatibility.

## 5. Review the PDF sheet

- Confirm paper size, portrait or landscape, page bounds and required layers.
- Zoom into small labels and thin linework; inspect clipping near every edge.
- Distinguish fit-to-page presentation from a specified printed scale. For scaled printing, check the PDF viewer's print settings and verify a known distance on the printed sheet.

## 6. Reopen the actual deliverable

- Open the downloaded or exported file in the receiving application, not just the original workspace.
- Repeat the dimension, text, layer and block checks. Compare the PDF separately.
- Send the checked file, retain the source and flag any unresolved differences in the handoff note.

## Copyable handoff note

```text
Drawing / revision:
Recipient and intended task:
Editable file and agreed version:
Review PDF:
Drawing units:
Known distance: [endpoints] / expected [value + unit] / delivered [value + unit]
Receiving application / version checked:
Required layers, fonts and external references:
Changes in this revision:
Unresolved differences or required follow-up:
Checked by / date:
```

Example: for a room layout containing a known 1000 mm reference line, measure the same endpoints in the exported DXF. A result of 1 instead of 1000 requires a unit/scale check before delivery. A PDF that looks correct does not resolve that discrepancy in the editable file.

## Example resource and relationship

The [CAD format-exchange guide](https://cadeditor.io/cad-converter/) provides one browser-tool example of choosing an editable exchange or a PDF review copy. Its supported routes are product-specific, not a compatibility promise for other CAD tools.

Prepared by Ethan Lee, product contact for CADEditor.


## Scope

This repository contains an independent drafting checklist and handoff template. It does not contain CADEditor application source, customer drawings or a CAD conversion engine. The checklist does not prescribe manufacturing tolerances; use the recipient’s approved technical requirements.
