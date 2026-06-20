
# ClaimVision AI

AI-Powered Multi-Modal Damage Claim Verification System

## Overview

ClaimVision AI is an intelligent damage claim verification platform that analyzes user claims and uploaded images to determine whether a damage claim is supported, contradicted, or lacks sufficient evidence.

The system uses Google's Gemini 2.5 Flash multimodal model to inspect visual evidence and generate structured claim assessments.

## Live Demo

ClaimVision allows users to submit:

- Car damage claims
- Laptop damage claims
- Package damage claims

and receive an AI-generated verdict in seconds.

## Features

### Damage Detection
- Detects visible damage from uploaded images
- Supports multiple object categories
- Identifies damaged components

### Claim Verification
- Supported
- Contradicted
- Not Enough Information

### Evidence Assessment
- Validates image quality
- Checks evidence sufficiency
- Provides image-grounded reasoning

### Severity Analysis
- Low
- Medium
- High

### Structured Output
Returns:

- Issue Type
- Damaged Part
- Claim Status
- Severity
- Supporting Images
- AI Justification

## Supported Objects

| Object | Examples |
|----------|----------|
| Car | Dent, scratch, broken parts |
| Laptop | Cracked screen, hinge damage |
| Package | Torn packaging, crushed box |

## Technology Stack

- Python
- Google Gemini 2.5 Flash
- Replit
- HTML/CSS
- JavaScript

## System Workflow

User Claim
↓
Image Upload
↓
Gemini Vision Analysis
↓
Evidence Validation
↓
Damage Classification
↓
Severity Assessment
↓
Final Verdict

## Example Output

```json
{
  "issue_type": "crack",
  "object_part": "screen",
  "claim_status": "supported",
  "severity": "high"
}
```

## Performance

- Average response time: ~3 seconds
- Supports 3 object categories
- Powered by Gemini Vision
- Designed for multimodal claim verification

## Hackathon Project

Built for the Multi-Modal Evidence Review Challenge.

The project demonstrates how multimodal AI can automate insurance and damage-claim verification workflows while providing transparent, image-grounded explanations.

## Author

Vavileti Venkata Kiran

GitHub:
https://github.com/venkatakiranvavileti-ops

## License

MIT License
