# Atom Economy

Green chemistry calculations and metrics for sustainable chemical processes.

## Overview

This repository contains tools and calculators for measuring atom economy in chemical reactions, a fundamental principle of green chemistry developed by Barry Trost.

## Features

- **Atom Economy Calculator** - Calculate AE for any chemical reaction
- **E-Factor Analysis** - Measure waste generation (kg waste / kg product)
- **Reaction Mass Efficiency (RME)** - Combined efficiency metric
- **Green Chemistry Principles** - 12 principles of sustainable chemistry
- **Industrial Case Studies** - Real-world examples of green chemistry improvements

## Quick Calculation

**Atom Economy Formula:**
```
AE = (MW of Desired Product / Σ MW of All Products) × 100%
```

**Rating Scale:**
- ≥90%: Excellent - Ideal for green chemistry
- 70-89%: Good - Preferable for sustainable processes  
- 50-69%: Moderate - Room for improvement
- <50%: Needs improvement - Consider alternative routes

## Integration

This module is integrated into **Organic OS** at:
- `/sustainability/atom-economy`
- `/atom-economy`

## Example Reactions

| Reaction | Atom Economy |
|----------|-------------|
| Addition reactions | 100% |
| Substitution reactions | <100% |
| Elimination reactions | 100% |

## Resources

- [EPA Green Chemistry Basics](https://www.epa.gov/greenchemistry/basics-green-chemistry#12)
- [Wikipedia: Atom Economy](https://en.wikipedia.org/wiki/Atom_economy)
- [12 Principles of Green Chemistry](https://www.acs.org/greenchemistry/principles.html)

## License

MIT

## Related Repositories

- [Organic OS](https://github.com/sustainabilitybro/ORGANIC-OS) - Full personal operating system
- [Holistic-Alchemy](https://github.com/sustainabilitybro/Holistic-Alchemy) - Transformation framework
