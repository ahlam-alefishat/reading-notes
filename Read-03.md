# Read-03



# Templating with Mustache
  - **Javascript Templating:** Javascript templating is a fast and efficient technique to render client-side view templates with Javascript by using a JSON data source. The template is HTML markup, with added templating tags that will either insert variables or run programming logic.
  - **Mustache:**  is a logic-less template syntax. It can be used for HTML, config files, source code — anything. It works by expanding tags in a template using values provided in a hash or object.
     - *referred to as “logic-less” because there are no if statements, else clauses, or for loops.*
     - *Instead, there are only tags. Some tags are replaced with a value, some nothing, and others a series of values.*
     - `mustache.js` is a zero-dependency implementation of the *mustache* template system in JavaScript. 
     -  *Mustache:* is a specification for a templating language. 
  - **Install:**
     - You can get Mustache via npm.
        - `$ npm install mustache --save`
  - **Templates:**
     - A *mustache template* is a string that contains any number of mustache tags. Tags are indicated by the double mustaches that surround them. 
     - `{{person}}` is a tag, as is `{{#person}}`. In both examples we refer to person as the tag's key. There are several types of tags available in mustache.js, described below.

     - The *Mustache.tags* property holds an array consisting of the opening and closing tag values. 
     - Set custom values by passing a new array of tags to render(), which gets honored over the default values, or by overriding the Mustache.tags property itself.
        - `var customTags = [ '<%', '%>' ];`

# A Guide to Flexbox
  - *display:* This defines a flex container; inline or block depending on the given value. It enables a flex context for all its direct children.
  - *flex-direction*
  - *flex-shrink* This defines the ability for a flex item to shrink if necessary.
  - *flex* This is the shorthand for flex-grow, flex-shrink and flex-basis combined.
  - *align-items* This defines the default behavior for how flex items are laid out along the cross axis on the current line. 
  - *align-content* This aligns a flex container's lines within when there is extra space in the cross-axis, similar to how justify-content aligns individual items within the main-axis.
  
  