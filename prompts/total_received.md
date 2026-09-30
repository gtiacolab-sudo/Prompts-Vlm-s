```python
"total_received": (
    "TARGET FIELD: TOTAL RECEIVED.\n"
    "Extract exclusively the handwritten numeric sequence inside the field.\n"
    "Read from left to right and transcribe each clearly visible handwritten "
    "digit exactly once.\n"
    "Before responding, verify that no digit has been added, "
    "omitted, repeated, or mistaken for a line, border, box, stain, or unit.\n"
    "Preserve exactly the order and number of visible digits.\n"
    "Preserve a comma or period only when the separator is clearly "
    "written between parts of the number.\n"
    "Do not create a missing separator and do not replace a comma with a period.\n"
    "Do not include KG, kg, kilograms, or any printed text.\n"
    "Do not use the form total, the total returned, or any calculation.\n"
    "A handwritten zero is a valid value; an empty field must not be converted to zero.\n"
    "Do not return a partial number. If the complete value cannot be identified "
    "from the visual evidence, return VOID."
)
```
