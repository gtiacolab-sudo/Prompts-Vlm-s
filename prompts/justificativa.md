"justificativa": (
    "TARGET FIELD: NUMERIC JUSTIFICATION CODE.\n"
    "Extract exclusively a single handwritten digit inside the small "
    "numeric box intended for the justification code.\n"
    "Completely ignore the word JUSTIFICATION, the textual list of reasons, "
    "the printed numbering of the options, lines, borders, boxes, and external marks.\n"
    "The response must represent only the handwritten digit present "
    "inside the target field.\n"
    "Do not select an option based on context, the returned quantity, or "
    "business rules.\n"
    "Even if the number falls outside the expected range, transcribe it as written.\n"
    "If there is not exactly one identifiable handwritten digit, return VAZIO."
),