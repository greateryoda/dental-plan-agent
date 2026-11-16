# Dental Plan Agent

Dictate a dental treatment plan; the agent maps it to the clinic price list (208 services, EUR), asks clarifying questions and generates a priced PDF that is regenerated from the answers.

- Voice input: browser speech recognition (Chrome / Edge)
- Plan reader: rule-based parser (stages, services, FDI teeth, quantities, prices, discounts, programmes)
- Rule checks: implant system missing, lower-jaw sinus lift, crown/implant count, conflicting prices, unpriced items
- Pricing: deterministic engine (discounts, free programmes, sedation hours, ranges)
- PDF: jsPDF, versioned with a change log

Built for the AI-Powered SDLC build challenge, Université Côte d'Azur.
