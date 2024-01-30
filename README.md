# Simple-CSS-Reset

A CSS Reset file circumvents inconsistencies across different browsers when developing websites. All browsers have default rules with properties and values applied to all pages before loading files. Due to the cascading nature of CSS, any styles the browser uses will remain unless explicitly overridden. A CSS Reset file targets all rules that the different browsers apply defaults to and resets them to their minimum possible value.

## Here's a breakdown of the CSS reset codes , along with explanations and key points:

**Purpose of CSS Reset:**

*   To create a consistent and predictable visual foundation across different browsers.
*   To avoid unexpected layout issues caused by variations in default browser styles.
*   To streamline the styling process by starting with a clean slate.

**Key Sections of the Code:**

1.  **Resetting the Box Model:**
    
    *   **Targeted elements:** Nearly all HTML elements.
    *   **Properties reset:**
        *   `margin: 0;`: Removes default spacing around elements.
        *   `padding: 0;`: Removes default padding within elements.
        *   `border: 0;`: Removes default borders.
        *   `font-size: 100%;`: Ensures consistent font sizing.
        *   `font-weight: normal;`: Sets a standard font weight.
        *   `vertical-align: baseline;`: Aligns elements consistently.
2.  **Setting Default Font Family and Size:**
    
    *   **Targeted element:** `body`
    *   **Properties set:**
        *   `font-family: Arial, sans-serif;`: Specifies the default font.
        *   `font-size: 16px;`: Sets the default font size.
        *   `line-height: 1.5;`: Establishes a comfortable line height.
3.  **Resetting List Styles:**
    
    *   **Targeted elements:** `ul`, `ol`
    *   **Property reset:**
        *   `list-style: none;`: Removes bullet points and numbering.
4.  **Removing Default Anchor Text Decoration:**
    
    *   **Targeted element:** `a`
    *   **Property reset:**
        *   `text-decoration: none;`: Removes underlines from links.
5.  **Resetting Button Styles:**
    
    *   **Targeted elements:** `button`, `input`, `optgroup`, `select`, `textarea`
    *   **Properties reset (similar to box model reset):**
        *   `margin: 0;`
        *   `padding: 0;`
        *   `border: none;`
        *   `font-size: 100%;`
        *   `font-family: inherit;`
        *   `vertical-align: baseline;`
6.  **Resetting Form Elements:**
    
    *   **Targeted elements:** `button`, `input[type="button"]`, `input[type="reset"]`, `input[type="submit"]`, `select`, `textarea`
    *   **Properties reset:**
        *   `-webkit-appearance: none;`: Removes browser-specific styling.
        *   `-moz-appearance: none;`: Removes browser-specific styling.
        *   `appearance: none;`: Removes browser-specific styling.
        *   `outline: none;`: Removes outlines when elements are focused.

**Additional Notes:**

*   Consider using a well-established CSS reset stylesheet , which offers a more comprehensive and up-to-date approach.
*   Customize the reset to fit your specific project needs.
*   Use browser developer tools to inspect elements and understand their default styles.
