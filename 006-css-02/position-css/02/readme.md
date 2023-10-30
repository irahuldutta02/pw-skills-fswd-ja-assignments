### 02. Explain the difference between Absolute and Relative positioning.
1. Absolute Positioning:
   - Absolute positioning is a CSS property that allows you to position an element relative to its nearest positioned ancestor, which means an ancestor element that has a CSS position property set to "relative," "absolute," "fixed," or "sticky."
   - When you apply absolute positioning to an element, it is taken out of the normal document flow. This means it does not affect the layout or position of other elements on the page.
   - The element's position is specified using properties like "top," "right," "bottom," and "left," which determine how far the element is from the edges of its nearest positioned ancestor.
   - If there is no positioned ancestor, the element will be positioned relative to the initial containing block, usually the viewport (the visible area of the browser window).

        ```css
        .absolute-element {
        position: absolute;
        top: 20px;
        left: 30px;
        }
        ```

2. Relative Positioning:
   - Relative positioning is also a CSS property used to position an element, but it does so relative to its normal position within the document flow.
   - When you apply relative positioning to an element, it retains its space in the document flow, meaning it still affects the layout and positioning of other elements around it.
   - The element's position can be adjusted using properties like "top," "right," "bottom," and "left," but these adjustments are relative to the element's normal position.

        ```css
        .relative-element {
        position: relative;
        top: 10px;
        left: -5px;
        }
        ```