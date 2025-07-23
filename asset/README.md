# Asset Organization

This folder contains all the images and media assets for the portfolio website, organized by category for better maintainability.

## Folder Structure

### 📁 `/hero/`
Contains images used in the hero section carousel:
- `1.png`, `2.png`, `3.png` - Color versions of hero cards
- `black1.png`, `black2.png`, `black3.png` - Black & white versions of hero cards

### 📁 `/profile/`
Contains profile and character images:
- `abhishek-profile.png` - Main profile image used in the about section

### 📁 `/experience/`
Contains images related to leadership and experience:
- `tedx-leadership.jpeg` - TEDxSAKEC leadership experience image
- `codeoffduty-leadership.jpeg` - Code Off Duty competition leadership image

### 📁 `/blogs/`
Contains blog post thumbnail images:
- `quantum-chips.jpg` - "Bits vs. Qubits" blog post image
- `federated-learning.jpg` - Federated Learning blog post image
- `quantum-computing.jpg` - Quantum Computing blog post image

### 📁 `/skills/`
Contains technical skills and tools related images:
- `technical-monitor.png` - Technical skills section graphic

### 📁 `/unused/`
Contains images that are not currently used in the website:
- `abhi-colour-2.jpeg` - Alternative profile image (unused)

## Naming Convention

- Use descriptive names that clearly indicate the purpose of the image
- Use hyphens (-) to separate words in filenames
- Keep file extensions lowercase
- Group related images by their usage context

## Usage in HTML

All image paths in the HTML have been updated to reflect this new organization:
```html
<!-- Hero section -->
<img src="asset/hero/1.png" alt="...">

<!-- Profile section -->
<img src="asset/profile/abhishek-profile.png" alt="...">

<!-- Experience section -->
<img src="asset/experience/tedx-leadership.jpeg" alt="...">

<!-- Blog section -->
<img src="asset/blogs/quantum-chips.jpg" alt="...">

<!-- Skills section -->
<img src="asset/skills/technical-monitor.png" alt="...">
```

## Maintenance

When adding new images:
1. Place them in the appropriate category folder
2. Use descriptive filenames
3. Update the HTML references accordingly
4. Update this README if adding new categories
