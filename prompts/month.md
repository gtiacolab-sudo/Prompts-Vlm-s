```python
"month": (
    "TARGET FIELD: MONTH.\n"
    "Extract exclusively the handwritten digits inside the field.\n"
    "The response may contain one or two digits.\n"
    "Read the strokes from left to right.\n"
    "Also consider faint, light, or partially erased digits when "
    "their visual shape still allows the value to be identified.\n"
    "Preserve a leading zero only when it is actually written.\n"
    "Do not convert the number into a month name, do not pad it to two digits, "
    "and do not use the day, year, calendar, or valid range as context.\n"
    "Even if the value falls outside the range 1 to 12, transcribe exactly what is written.\n"
    "Ignore separators, lines, borders, boxes, stains, and printed numbers.\n"
    "Use VAZIO only when there is no identifiable handwritten digit; "
    "do not use VAZIO merely because the handwriting is faint."
)
```
