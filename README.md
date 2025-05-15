# AQA A Level Art and Design Grade Calculator

## Overview

The AQA A Level Art and Design Grade Calculator is an interactive web tool designed to help students  quickly calculate grades based on component marks according to the AQA examination board's grading criteria from the previous year. This calculator provides grade predictions for all AQA Art and Design subjects including Fine Art, Photography, Textiles, 3D Design, and Graphic Communication.

![Screenshot 2025-05-15 215537](https://github.com/user-attachments/assets/9ce64ce3-00d6-45be-a735-60d03be22975)

## Features

- **Grade Calculations**: Calculate grades based on official AQA grade boundaries for all Art & Design pathways
- **Component Weighting**: Proper weighting of Component 1 (60%) and Component 2 (40%)
- **Grade Boundary Information**: Shows both upper and lower grade boundaries with marks needed
- **User-Friendly Interface**: Clean, responsive design that works on desktop and mobile devices
- **Visual Feedback**: Celebratory confetti animation when results are displayed
- **Audio Feedback**: 3-second applause sound effect upon grade calculation
- **Countdown Timer**: Dynamic countdown to the May 16th, 2025 deadline (12pm)
- **Module Selection**: Support for all AQA Art and Design specializations:
  - Art, Craft & Design (7201)
  - Fine Art (7202)
  - Graphic Communication (7203)
  - Textile Design (7204)
  - 3D Design (7205)
  - Photography (7206)

## Live Demo

The calculator is available at: [surreyteaching.org/artdesgradecalc](https://surreyteaching.org/artdesgradecalc)

## Technical Details

### Technologies Used
- HTML5
- CSS3
- Vanilla JavaScript
- [canvas-confetti](https://github.com/catdad/canvas-confetti) for celebratory animations

### Browser Compatibility
- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers (responsive design)

## Usage Instructions

1. Select your Art & Design module from the dropdown menu
2. Enter your Component 1 mark (out of 96)
3. Enter your Component 2 mark (out of 96)
4. Click "Calculate Grade"
5. View your results, including:
   - Scaled component marks
   - Total mark (out of 480)
   - Final grade
   - Upper and lower grade boundaries

## Grade Boundaries Information

The calculator uses the following grade boundaries for most modules:
- A*: 399 marks (83.1%)
- A: 370 marks (77.1%)
- B: 313 marks (65.2%)
- C: 257 marks (53.5%)
- D: 201 marks (41.9%)
- E: 145 marks (30.2%)

Photography (7206) has slightly different boundaries:
- A*: 409 marks (85.2%)
- A: 390 marks (81.3%)
- B: 336 marks (70.0%)
- C: 282 marks (58.8%)
- D: 228 marks (47.5%)
- E: 175 marks (36.5%)

## Installation

To run this calculator locally:

1. Clone the repository:
```
git clone https://github.com/RahulPatel12/AQA-Art-Design-Grade-Calculator.git
```

2. Navigate to the project directory:
```
cd AQA-Art-Design-Grade-Calculator/artdesgradecalc
```

3. Open `index.html` in your preferred web browser

## Hosting on Your Domain

To host this calculator on your own domain:

1. Fork this repository
2. Enable GitHub Pages in your repository settings
3. Configure your custom domain DNS settings:
   - Add A records pointing to GitHub Pages IP addresses for the apex domain
   - Add a CNAME record for any subdomains pointing to your GitHub Pages URL

## Development

### Project Structure
- `index.html` - Main application file with HTML, CSS, and JavaScript
- `sounds/` - Directory containing audio files (if hosted locally)
- `README.md` - Project documentation

### Contributing
If you'd like to improve the calculator:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## Credits

- Developed by: [Rahul Patel](https://github.com/RahulPatel12)
- Grade boundary data source: AQA Examination Board
- Confetti effects: [canvas-confetti](https://github.com/catdad/canvas-confetti)

## Contact

For questions or feedback, please contact:
- GitHub: [@RahulPatel12](https://github.com/RahulPatel12)
- Website: [Surrey Teaching](https://surreyteaching.org)

---

Surrey Teaching 2025.
