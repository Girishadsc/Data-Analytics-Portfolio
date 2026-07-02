# Invoice Extraction using OpenAI

## Overview
This project uses prompt engineering with OpenAI to extract structured data from unstructured invoice text.

---

## Objectives
- Extract invoice fields (name, amount, date, items)
- Convert unstructured text into structured JSON
- Validate and clean extracted output
- Demonstrate API-based automation

---

## Methodology
- Designed structured prompts for extraction
- Used zero-shot and few-shot prompting
- Parsed model output into JSON format
- Handled incomplete or noisy inputs

---

## Example Output

```json
{
  "vendor": "",
  "invoice_date": "",
  "total_amount": "",
  "items": []
}
```

---

## Tools Used
- OpenAI API
- Python
- JSON parsing
- Jupyter Notebook
