# Treehouse Responsive Layout Sass

# Project Overview

In this project you will convert a CSS stylesheet to Sass. You'll refactor the stylesheet from the "Responsive Layout" project using SCSS partials, variables, extends, and mixins.

# Instructions

1. Create a 'scss' folder in your "Responsive Layout" project.
2. Convert the CSS stylesheet to an SCSS stylesheet, then place it inside the 'scss' folder.
3. Run Sass from the console or with a tool like CodeKit, Workspaces, or any of these.
4. In the 'scss' folder, create subfolders to organize your CSS code into Sass partial files.
   - For example for base styles, layout, components, and so on.
   - Create at least three folders.
5. Group related sections of CSS into SCSS partials.
   - For example, base styles for elements can go inside a \_base.scss partial inside the 'base' folder.
   - Create at least 3 Sass partial files.
6. Import your partials into your project's main SCSS file.
   - When using multiple @import’s make sure they are listed in the correct order for styling.
7. Find repeating patterns in the stylesheet and extract them into placeholder selectors, then extend them wherever necessary.
   - At a minimum create at least one placeholder selector, and use it with the @extend keyword in at least 3 other selectors.
8. Create variables for repeating values.

   - At a minimum create variables for ALL color, font-size and font-family values in your project.
   - Then replace ALL instances of that value with the new variable in your code.

   ```
   // Set the variables:
   $black: #000;

   // Then use them in your code:
   .myClass{
       color: $black;
   }
   ```

9. Write mixins for ALL media queries.
10. Create at least one example of a nested Sass rule. For example:

    ```
    nav {

        ul {
            margin: 0;
            padding: 0;
            list-style: none;
        }

        li { display: inline-block; }

        a {
            display: block;
            padding: 6px 12px;
            text-decoration: none;
        }
    }
    ```

11. No nested rules greater than 3 levels deep. For example:
    ```
    .weather {
        .cities {
            li {
                // no more!
            }
        }
    }
    ```
12. You don’t need to make any changes to your original design, but make sure the site is still responsive and works well on different screen sizes.
