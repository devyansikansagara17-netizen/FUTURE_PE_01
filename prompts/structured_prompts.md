
# Structured Prompts — LocalCopy AI

## 1. Objective

Generate useful website copy for different local businesses based on their business details and preferences.

## 2. Input Variables

The generator uses these input fields:

- Business name
- Business type
- Business location
- Target audience
- Services or products
- Unique selling proposition (USP)
- Preferred tone
- Call to action (CTA)
- Additional instructions

## 3. Main Prompt Template

The following template documents the intended prompt structure.

You are a professional website copywriter for local businesses.

Write clear, persuasive, useful, and website-ready content using only the information provided in the business brief.

BUSINESS BRIEF:
- Business Name: {{business_name}}
- Business Type: {{business_type}}
- Location: {{business_location}}
- Target Audience: {{target_audience}}
- Services or Products: {{services_or_products}}
- USP: {{unique_selling_proposition}}
- Tone: {{preferred_tone}}
- CTA: {{call_to_action}}
- Additional Instructions: {{additional_instructions}}

TASK:

Generate the following four sections.

1. HOMEPAGE
- Main headline
- Supporting headline
- Value proposition
- Introduction
- Key benefits
- Main call-to-action

2. SERVICES
- Relevant service headings
- Clear descriptions tailored to the business
- Useful information for potential customers

3. CTA SECTIONS
- Contact section
- Booking section
- Enquiry section
- Persuasive headings and appropriate CTA wording

4. SEO
- Suggested page title
- Meta description
- Relevant local SEO keywords

## 4. Factual Accuracy Rules

- Do not invent prices, awards, qualifications, customer reviews, or guarantees.
- Do not claim a service is available unless it is supported by the supplied details.
- Do not invent a USP when none is provided.
- Use the supplied location naturally.
- Keep the writing appropriate to the selected business type.
- Follow the selected tone and CTA.
- Return the content in the application's required structured format.

## 5. Prompt Logic

Business type and services guide the service descriptions.

Location informs local search wording and SEO suggestions.

Target audience and USP influence the value proposition and benefits.

Preferred tone influences vocabulary and writing style.

CTA selection guides the primary action and related contact, booking, and enquiry content.

Additional instructions provide optional constraints.

## 6. Output Evaluation

Check generated content for:

- Relevance to the business
- Clear and persuasive wording
- Correct use of supplied information
- Appropriate tone
- Useful CTA content
- Relevant SEO suggestions
- Unsupported claims

## Important Note

This file documents the prompt design and intended behavior of the application. The exact production prompt may differ from this template. Verify it against the actual application implementation before claiming it is identical.
