# Week 2 Task: Implementation of Responsive Web Design

## 1. Project overview
This project is a responsive landing page for a fictional Creative Studio. The aim is to create a clear, attractive layout that adapts to desktop, tablet and mobile screens using HTML5 and CSS3.

## 2. Technologies used
- **HTML5:** semantic page structure using `header`, `nav`, `main`, `section`, `article` and `footer`.
- **CSS3:** colors, typography, spacing, cards, decorative shapes, hover effects and responsive layouts.
- **CSS Grid and Flexbox:** to arrange the hero area, service cards, navigation and footer.
- **Media queries:** breakpoints at 900px, 640px and 360px to adapt the layout for different viewport sizes.
- **Viewport meta tag:** helps the page use the device's actual screen width.

## 3. Responsive implementation details
- On larger screens, the hero section uses two columns and the services section displays three cards in one row.
- At widths up to 900px, content spacing and illustration sizing are reduced to fit medium screens.
- At widths up to 640px, the hero becomes a single-column layout, service cards stack vertically, and the navigation is simplified to avoid crowding.
- At widths up to 360px, buttons and artwork are adjusted further for narrow mobile screens.
- The CSS uses flexible widths such as `width: calc(100% - 36px)`, `min()` and `clamp()` so content can scale without relying on one fixed screen size.
- Decorative artwork is made from CSS shapes, so the page does not depend on large image files to create its main visual.

## 4. How to run the project
1. Extract the project ZIP file.
2. Open the `Week2_Responsive_Web_Design` folder in Visual Studio Code.
3. Keep `index.html` and `style.css` in the same folder.
4. Open `index.html` in a browser. If the Live Server extension is installed, right-click `index.html` and select **Open with Live Server**.

## 5. Testing plan and evidence
Test the page at these example viewport widths using the browser's responsive device toolbar:

| Device category | Example viewport | What to check |
|---|---:|---|
| Desktop/laptop | 1366px wide | Two-column hero, horizontal navigation and three service cards |
| Tablet | 768px wide | Comfortable spacing, readable text and no horizontal overflow |
| Mobile | 375px wide | Single-column hero, stacked service cards and visible contact button |
| Small mobile | 320px wide | No unwanted horizontal scrolling; content remains readable |

**Important:** These are planned test sizes, not claimed test results. After opening the page, check each size and update this section with your actual observations. Capture screenshots of the desktop and mobile views if the internship submission allows evidence.

## 6. Expected outcome
The page is designed to rearrange its content based on screen width. The navigation, hero section, service cards, about section and footer use responsive CSS rules so visitors can read and navigate the page on different devices.

## 7. Conclusion
This task demonstrates how HTML provides the structure while CSS controls the visual design and responsive behavior. Media queries, Grid, Flexbox and flexible sizing help the same webpage adapt to multiple screen sizes. Testing on actual browser viewport sizes is an important final step before submission.
