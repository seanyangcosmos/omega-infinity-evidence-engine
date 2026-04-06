# Validation Endpoint Example

POST /validate

Input:

{
  "mechanistic": true,
  "genetic": true,
  "clinical": null
}

Output:

{
  "alignment": "partial",
  "reasoning_type": "translational_constraint",
  "constraint": "missing_clinical_translation",
  "conclusion": "translationally_limited"
}
