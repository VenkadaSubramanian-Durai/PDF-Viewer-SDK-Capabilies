# AcroForm Fields Feature Page — Content Specification

## Page metadata

| Element | Recommended copy |
|---|---|
| **Page URL** | `https://www.syncfusion.com/pdf-viewer-sdk/acroform-fields` |
| **Title** | PDF AcroForm Filling and Designer SDK | Syncfusion |
| **Meta description** | Add PDF form filling, visual form design, signatures, validation, and form data import and export to your application with Syncfusion PDF Viewer SDK. |
| **H1** | Build complete PDF form experiences into your application |
| **Hero description** | Let users fill, design, sign, validate, and submit interactive PDF forms without leaving your application. Syncfusion PDF Viewer SDK gives developers ready-to-use UI and flexible APIs for building secure, connected AcroForm workflows. |

> **Editorial note:** “AcroForm fields” is the precise product term, but “PDF forms” is clearer for search and first-time visitors. Use both naturally. The shorter `/acroform-fields` slug is recommended because it describes the complete capability set and remains useful as the page expands.

---

## 1. Sticky navbar

Use the standard Syncfusion global navigation.

- **Brand:** Syncfusion
- **Navigation:** Products · Solutions · Resources · Pricing
- **Utility actions:** Sign In · Contact Sales
- **Primary CTA:** Start Free Trial

---

## 2. Hero

**Breadcrumb:** Home / PDF Viewer SDK / AcroForm Fields

**Badge pill:** PDF VIEWER SDK · ACROFORM FIELDS

# Build complete PDF form experiences into your application

Let users fill, design, sign, validate, and submit interactive PDF forms without leaving your application. Syncfusion PDF Viewer SDK gives developers ready-to-use UI and flexible APIs for building secure, connected AcroForm workflows.

**Primary CTA:** Start Free Trial  
**Secondary CTA:** View Live Demo

**Microcopy:** No credit card required · Developer support included

**Hero mockup direction:** Show a PDF application form open in the viewer. Include a populated text field, selected radio button, checked checkbox, dropdown, required-field marker, and signature field. Add a compact side panel titled “Form fields” and a top status pill reading “Ready to submit.” Avoid depicting XFA forms.

---

## 3. Three-up value propositions

## Build end-to-end PDF form workflows

Add form filling, field design, signatures, validation, and data exchange to your application with configurable UI components and programmatic APIs.

### Add intuitive form interactions

Enable users to enter values, select options, and provide signatures through interactive fields embedded directly in your application.

### Configure fields visually or programmatically

Use the Form Designer to create and customize fields, or manage field properties, values, and behavior through APIs.

### Integrate form data with your systems

Prefill fields from application data, retrieve user-entered values, and connect form submissions to APIs, databases, and downstream services.

---

## 4. Alternating feature sections

### 01 — FORM FILLING · UI + API

## Embed PDF Form Filling

Turn existing AcroForms into responsive in-app experiences. Users can enter and revise information through the viewer UI, while developers can retrieve fields and set values programmatically for faster, more accurate data entry.

- Support text boxes, password fields, checkboxes, radio buttons, drop-down lists, list boxes, signature fields, and initial fields.
- Prefill known details from user profiles, application state, or business systems.
- Retain entered values when users save or download the updated PDF.

**Text link:** Explore form filling →

**Mockup direction:** Browser-style viewer with a customer onboarding form. Show a mix of populated text, selection, and choice controls, plus a “65% filled” indicator.

---

### 02 — FORM DESIGNER · NO-CODE UI + APIs

## Design fillable PDF forms

Add interactive fields to an existing PDF without sending the document to a separate authoring tool. The built-in Form Designer makes layout work visual, while APIs support dynamic form creation at runtime.

- Add, move, resize, align, copy, paste, group, reorder, and remove fields.
- Configure names, default values, fonts, colors, borders, alignment, visibility, tab order, and required or read-only states.
- Customize the designer toolbar so each role sees only the tools needed for its workflow.

**Text link:** Discover the Form Designer →

**Mockup direction:** PDF canvas with a selected text field, resize handles, alignment guide, and properties panel. Show field tools for text, checkbox, radio, dropdown, signature, and initials.

---

### 03 — SIGNATURE AND INITIAL FIELDS · ELECTRONIC SIGNING

## Add electronic signatures to PDF forms

Add dedicated signature and initial fields to approval forms, agreements, and acknowledgments. Users can provide a drawn, typed, or image-based electronic signature and place it in the intended field without disrupting surrounding content.

- Create signature and initial fields through the designer or programmatically.
- Support drawn, typed, and image-based electronic signature experiences.
- Preserve the PDF’s form structure while capturing acknowledgments and approvals.

**Text link:** See signature field capabilities →

**Mockup direction:** Approval form with separate “Signature” and “Initials” fields. Show a compact signature dialog with Draw, Type, and Upload image tabs.

> **Accuracy note:** Electronic signatures and initials are distinct from certificate-based digital signatures and cryptographic signature validation. Link to the dedicated digital-signature capability where that distinction matters.

---

### 04 — IMPORT AND EXPORT · FDF + XFDF + JSON

## Connect PDF forms to APIs and business systems

Move field values independently of the underlying PDF. Prefill a form from stored records, save a user’s progress, submit responses to a service, or restore previously saved data when the document is opened again.

- Import FDF, XFDF, or JSON data and map values to matching form fields.
- Export form values as a downloadable file or application object for custom persistence.
- Use lifecycle events to show progress, handle failures, validate input, or record audit activity.

**Text link:** Learn about form data exchange →

**Mockup direction:** A central PDF form connected to three cards labeled “Customer database,” “REST API,” and “Form archive.” Add format chips for FDF, XFDF, and JSON.

> **Platform note:** Format availability varies by platform. Some Syncfusion desktop and mobile PDF Viewers also support XML. Confirm the platform matrix before presenting XML as universally available.

---

### 05 — VALIDATION AND EVENTS · WORKFLOW CONTROL

## Validate form data before processing

Apply required-field checks before users submit, print, or download a document. Form events give your application the context it needs to guide users, synchronize state, enforce business rules, and respond to every important interaction.

- Identify missing required fields and focus users on the information that needs attention.
- Add custom validation for business-specific formats and rules before continuing.
- React to field creation, selection, updates, movement, resizing, removal, and data import or export.

**Text link:** Explore form validation →

**Mockup direction:** Viewer showing two highlighted required fields and a validation summary reading “2 fields need attention,” with event cards flowing into an application workflow panel.

---

### 06 — FLATTEN FORM DATA · READ-ONLY OUTPUT

## Flatten submitted form data

Convert interactive fields and their submitted values into static PDF content. The captured data remains visible while the fields can no longer be edited—ideal for distribution, record retention, and archival workflows.

- Preserve submitted field values and their visual appearance.
- Prevent further changes to captured form data.
- Add flattening to submission, approval, or archival pipelines.

**Text link:** Learn about flattening PDF forms →

**Mockup direction:** Before-and-after document cards. The first shows interactive field outlines and an edit cursor; the second shows fixed values, a lock icon, and a “Flattened” status pill.

---

## 5. FAQ

## Frequently asked questions

Everything development teams need to evaluate PDF form filling and design with Syncfusion PDF Viewer SDK.

<details>
<summary><strong>What is an AcroForm?</strong></summary>

An AcroForm is the interactive form format built into PDF. It can contain fields such as text boxes, checkboxes, radio buttons, lists, drop-downs, signatures, and initials. Syncfusion PDF Viewer SDK can display and fill existing AcroForms, and supported web viewers can also create and edit fields with the Form Designer. XFA forms are a different PDF form technology and should not be described as supported AcroForms.
</details>

<details>
<summary><strong>Which PDF form fields can users fill or create?</strong></summary>

The web PDF Viewer supports text boxes, password fields, checkboxes, radio buttons, list boxes, drop-down lists, signature fields, and initial fields. Exact field types and designer capabilities can vary by platform, so link visitors to the relevant framework documentation.
</details>

<details>
<summary><strong>Can my application prefill and read form values programmatically?</strong></summary>

Yes. APIs let developers retrieve form fields, update values and properties, reset fields, and connect form state to application logic. This supports scenarios such as pre-populating customer information, saving drafts, validating responses, and submitting data to backend services.
</details>

<details>
<summary><strong>Which formats are supported for form data import and export?</strong></summary>

Syncfusion’s web PDF Viewer supports FDF, XFDF, and JSON form data workflows, including object-based export for custom persistence. Some desktop and mobile platforms also support XML. Format availability should be stated for the specific framework being promoted.
</details>

<details>
<summary><strong>Can the viewer prevent submission when required fields are missing?</strong></summary>

Yes. Required-field validation can run before actions such as submitting, printing, or downloading. Your application can cancel the action, display a message, and direct the user to missing fields. Developers can also apply custom business validation using form values and events.
</details>

<details>
<summary><strong>Are signature fields the same as digital signatures?</strong></summary>

No. Signature and initial fields capture an electronic signature—such as a drawn, typed, or image-based mark—within a form. Certificate-based digital signatures use cryptography to establish document authenticity and integrity and are covered by separate Syncfusion signature capabilities.
</details>

<details>
<summary><strong>Can submitted form data be made non-editable?</strong></summary>

Yes. Flattening converts interactive fields and their submitted values into static PDF content. The captured data remains visible while the fields are no longer interactive or editable.
</details>

---

## 6. Resources and documentation

## Start building PDF form workflows

### LIVE DEMO

#### Try PDF form filling

Interact with supported fields and evaluate the end-user form experience in a working Syncfusion sample.

**Link:** [View PDF Viewer demos](https://ej2.syncfusion.com/react/demos/)

### DOCUMENTATION

#### Build with React PDF forms

Learn how to fill fields through the UI or APIs, import existing values, and validate a form before submission.

**Link:** [Read the React form-filling guide](https://help.syncfusion.com/document-processing/pdf/pdf-viewer/react/forms/form-filling)

### DOCUMENTATION

#### Create and manage form fields

Explore the Form Designer workflow for creating, editing, styling, and removing interactive fields.

**Link:** [Explore form creation](https://help.syncfusion.com/document-processing/pdf/pdf-viewer/react/forms/overview-create-forms)

---

## 7. Sibling capabilities

## Build a complete in-app PDF experience

**See all PDF Viewer capabilities →**

### Annotations and review

Add highlights, shapes, free text, stamps, comments, and collaborative markup to PDF workflows.

### Electronic and digital signatures

Support electronic signing experiences and certificate-based digital signature workflows.

### Redaction

Mark and permanently remove sensitive text, images, or regions before documents are shared.

### Page organization

Add, remove, rotate, reorder, and import pages to prepare polished PDF documents.

---

## 8. CTA band

## Bring complete PDF form workflows into your application

Give users one place to fill, design, sign, validate, and submit PDF forms—backed by developer-friendly APIs and Syncfusion support.

**Primary CTA:** Start Free Trial  
**Secondary CTA:** Contact Sales

---

## 9. Footer

Use the standard Syncfusion global footer with the existing five-column layout:

- **Brand:** Syncfusion company description and social links
- **Products:** Developer platforms and product families
- **Resources:** Demos, documentation, blogs, forums, and knowledge base
- **Company:** About, careers, contact, and partners
- **Legal:** Privacy, terms, cookies, and accessibility

Include the standard copyright and legal bar.

---

## Content and implementation notes

- Keep the page focused on product outcomes and evaluation. Put API names and code samples in linked documentation, not in primary landing-page copy.
- Use “PDF form,” “interactive PDF form,” and “AcroForm” naturally. Avoid using “forms” alone in metadata because it is too broad.
- Do not claim XFA support. AcroForms and XFA are different technologies.
- Do not imply that electronic signatures provide certificate-based identity or integrity validation.
- Describe flattening through its application outcome: preserving submitted values as static PDF content and preventing further field editing.
- Localize platform claims. The overall PDF Viewer SDK spans multiple UI stacks, but exact form fields, data formats, designer features, and APIs vary by framework.

## Primary verification sources

- [Syncfusion PDF Viewer SDK overview](https://www.syncfusion.com/pdf-viewer-sdk)
- [React PDF Viewer form-filling feature page](https://www.syncfusion.com/pdf-viewer-sdk/react-pdf-viewer/form-filling-pdf)
- [React form-filling documentation](https://help.syncfusion.com/document-processing/pdf/pdf-viewer/react/forms/form-filling)
- [ASP.NET Core Form Designer documentation](https://help.syncfusion.com/document-processing/pdf/pdf-viewer/asp-net-core/forms/form-designer)
- [JavaScript form data export documentation](https://help.syncfusion.com/document-processing/pdf/pdf-viewer/javascript-es5/forms/import-export-form-fields/export-form-fields)
- [JavaScript form data import documentation](https://help.syncfusion.com/document-processing/pdf/pdf-viewer/javascript-es5/forms/import-export-form-fields/import-form-fields)
- [ASP.NET Core form validation documentation](https://help.syncfusion.com/document-processing/pdf/pdf-viewer/asp-net-core/forms/form-validation)
- [React form field events documentation](https://help.syncfusion.com/document-processing/pdf/pdf-viewer/react/forms/form-field-events)
- [Xamarin AcroForms and flattening documentation](https://help.syncfusion.com/document-processing/pdf/pdf-viewer/xamarin/working-with-pdf-acroforms)
 