# AutoConsignRenamer

**AutoConsignRenamer** is a tool designed to automate the renaming and organization of consignment images using Google Vision OCR and database validation. It processes images from the `undetected` folder, extracts consignment details, and organizes files into structured directories.

---

## Features

- Automatically extracts consignment numbers, dates, and company names.
- Renames files based on extracted metadata.
- Organizes images into folders by company name and financial year.
- Validates extracted data against a database.
- Handles special cases like `DOCKET NUMBER`, `GRN`, and `CONSIGNMENT NOTE`.
- Generates logs for processed files and errors.

---

## How to Use

### Step 1: Install Dependencies
Manually install the required Python libraries:
```bash
pip install google-cloud-vision pillow mysql-connector-python
