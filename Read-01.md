# Read -01
# **Responsive web design**
   -  is the practice of building a website suitable to work on every device and every screen size, no matter how large or small, mobile or desktop.
   - *focused around* providing an intuitive and gratifying experience for everyone.

   - **Responsive** generally means to react quickly and positively to any change.
      - **Adaptive** means to be easily modified for a new purpose or situation, such as change.
         - *A combination of the two is ideal, providing the perfect formula for functional websites.*

   - broken down into three main components:
     - 1. Flexible layouts
         - is the practice of building the layout of a website with a flexible grid, capable of dynamically resizing to any width.
         -  do not advocate the use of fixed measurement units, such as pixels or inches.
     - 2. Media queries
         -  built as an extension to media types commonly found when targeting and including styles.
         - provide the ability to specify different styles for individual browser and device circumstances, the width of the viewport or device orientation for example.
         - use the `@media` rule inside of an existing style sheet to avoid any additional HTTP requests. 
         - *Logical operators* in media queries help build powerful expressions.
     - 3. Flexible media

# **All About Floats**
   - What is "Float"?
      - is a CSS positioning property.
         - left. 
         - right. 
         - none (the default).
         - Inherit (which will assume the float value from that elements parent element).

   - What are floats used for?
      - used to create **entire web layouts**.
      - helpful for layout in smaller instances.
    
   - Clearing the Float:
      - `clear` property set on it will not move up adjacent to the float like the float desires, but will move itself down past the float.
         - 1. `Both` : clears floats coming from either direction.
         - 2. `Left` and `Right`: can be used to only clear the float from one direction respectively.
         - 3. `None` : is the default, which is typically unnecessary unless removing a clear value from a cascade.
         - 4. `Inherit` : is strangely not supported in Internet Explorer.

### **The Great Collapse**
   - Collapsing almost always needs to be dealt with to prevent strange layout and cross-browser problems. 
    
### **Techniques for Clearing Floats**
   - The Empty Div Method
   - The Overflow Method
      - This method can be beautifully semantic as it may not require additional elements. 
      -  Also bear in mind that the overflow property isn't specifically for clearing floats. Be careful not to hide content or trigger unwanted scrollbars.
   - The Easy Clearing Method
      -  uses a clever CSS pseudo selector (:after) to clear floats

### **Problems with Floats**
   - Floats often get beat on for being `fragile`.
      - **Pushdown** is a symptom of an element inside a floated item being wider than the float itself
         - IE will expand the float to contain the image
         - Quick fix: `overflow: hidden` to cut off excess.
      - **Double Margin Bug** 
         -  Quick fix: `display: inline`
      - **The 3px Jog**
         - Quick fix: set a width or height on the affected text.
      - **the Bottom Margin Bug**
         - Quick fix: using bottom padding on the parent instead.
