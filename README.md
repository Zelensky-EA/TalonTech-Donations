# TalonTech 3D Lab Estimator

A single-page estimator and print log for the Everett Alvarez High School TalonTech program.

## Publish with GitHub Pages

1. Create a GitHub repository and upload `index.html` to its top level.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Select the `main` branch and `/ (root)`, then save.
5. Open the Pages URL GitHub provides and test one submission.

No build step is required. The page loads Tailwind CSS, Font Awesome, Google Fonts, and jsPDF from public CDNs, so visitors need internet access.

## Before publishing

- Confirm the Google Form is accepting responses.
- Confirm its field IDs still match the `formData.append(...)` entries in `index.html`.
- Submit a test project and verify every value reaches the response sheet.
- If a dedicated **TalonTech Member** question is added to the form, replace the current description-appending behavior with that question's entry ID.

## Pricing

Default prices are configured near the start of the JavaScript section and in the option `data-cost` attributes. Staff can also override each price directly in the estimator without editing the source.

## Public-code note

Everything in `index.html`, including the Google Form submission URL and field IDs, will be visible publicly. These values are not passwords, but no API keys, passwords, student records, or other secrets should be placed in the file.
