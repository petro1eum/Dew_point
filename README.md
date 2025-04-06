# Acid Dew Point Calculator

[![License: AGPL v3](https://img.shields.io/badge/License-AGPL%20v3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0)

A scientifically accurate web-based calculator for determining acid dew points in industrial gas streams. This tool is essential for preventing acid corrosion in industrial equipment and optimizing process parameters.

## Features

- **Multi-Acid Support:**
  - H₂SO₄ (Sulfuric Acid)
  - HCl (Hydrochloric Acid)
  - H₂S (Hydrogen Sulfide)

- **Advanced Calculation Methods:**
  - Okkes (1987)
  - Verhoff & Banchero (1974)
  - ZareNezhad (2009)
  - Kiang (1981)
  - Antoine Equation (NIST)

- **Comprehensive Analysis:**
  - Dew point temperature calculation
  - Water dew point reference
  - Corrosion risk assessment
  - Material compatibility analysis
  - Interactive graphical visualization

- **Material Corrosion Rates:**
  - Carbon Steel
  - Stainless Steel 304
  - Stainless Steel 316L

- **Bilingual Interface:**
  - English
  - Russian

## Usage

1. Select acid type (H₂SO₄, HCl, or H₂S)
2. Choose calculation method
3. Input parameters:
   - Water content
   - Acid content
   - System pressure
4. Get comprehensive results including:
   - Acid dew point
   - Recommended operating temperature
   - Corrosion risk assessment
   - Material compatibility
   - Interactive graphs

## Scientific Background

The calculator implements various peer-reviewed methods for acid dew point calculation:

- **H₂SO₄:** Uses Okkes (1987) as the primary method, with options for Verhoff (1974) and ZareNezhad (2009)
- **HCl:** Implements Kiang's method (1981)
- **H₂S:** Uses the Antoine equation with NIST data

All calculations include proper unit conversions and take into account system pressure effects.

## Technical Details

- Built with vanilla JavaScript
- Uses Chart.js for data visualization
- Implements TailwindCSS for styling
- No backend dependencies required
- Fully client-side calculations

## Installation

No installation required. Access the calculator directly through:
```
https://raw.githack.com/EdCher/Dew_point/main/dew_calc.html
```

## License

This project is licensed under the GNU Affero General Public License v3.0 (AGPL-3.0). This means:

- You must disclose source code when distributing the software
- Modifications must be released under the same license
- Changes must be documented
- Network use is distribution
- Patents must be licensed under AGPL-3.0

For more details, see the [LICENSE](LICENSE) file.

## Citation

If you use this calculator in your research or industrial applications, please cite:

```bibtex
@software{acid_dew_point_calculator,
  author = {Ed Cherednik aka EdCher},
  title = {Acid Dew Point Calculator},
  year = {2024},
  url = {https://github.com/EdCher/Dew_point}
}
```

## References

1. Okkes A.G. (1987). "Get Acid Dew Point of Flue Gas", Hydrocarbon Processing, July 1987, 53-55.
2. Verhoff F.H., Banchero J.T. (1974). "Predicting Dew Points of Gases", Chemical Engineering Progress 70(8), 71-72.
3. ZareNezhad M. (2009). "A new equation for acid dew-point", Chemical Engineering & Technology 32(4), 585-587.
4. Kiang Y.H. (1981). "Predicting Dewpoints of Gases", Chemical Engineering 88(3), 127-128.
5. NIST Chemistry WebBook, SRD 69 