# Read 14
# CSS Transforms
## Transform Syntax:
div {
  -webkit-transform: scale(1.5);
     -moz-transform: scale(1.5);
       -o-transform: scale(1.5);
          transform: scale(1.5);
}


### 2D Transforms#two-dimensional-transforms:
* 2D Rotate:

HTML :(<figure class="box-1">Box 1</figure>
<figure class="box-2">Box 2</figure>

)

CSS
(box-1 {
  transform: rotate(20deg);
}
.box-2 {
  transform: rotate(-55deg);
}
)
* 2D Scale:
HTML
(<figure class="box-1">Box 1</figure>
<figure class="box-2">Box 2</figure>)

CSS 
(.box-1 {
  transform: scale(.75);
}
.box-2 {
  transform: scale(1.25);
}
)

 * 2D Translate:   
 (<figure class="box-1">Box 1</figure>
<figure class="box-2">Box 2</figure>
<figure class="box-3">Box 3</figure>
)          
CSS
.box-1 {
  transform: translateX(-10px);
}
.box-2 {
  transform: translateY(25%);
}
.box-3 {
  transform: translate(-10px, 25%);
}

* 2D Skew:
HTML
(<figure class="box-1">Box 1</figure>
<figure class="box-2">Box 2</figure>
<figure class="box-3">Box 3</figure>)


CSS
(.box-1 {
  transform: skewX(5deg);
}
.box-2 {
  transform: skewY(-20deg);
}
.box-3 {
  transform: skew(5deg, -20deg);
}
)

*Combining Transforms*
HTML
(<figure class="box-1">Box 1</figure>
<figure class="box-2">Box 2</figure>
)
CSS
.box-1 {
  transform: rotate(25deg) scale(.75);
}
.box-2 {
  transform: skew(10deg, 20deg) translateX(20px);
}


## TRANSITION
### Transitional Properties
It is important to note, not all properties may be transitioned, only properties that have an identifiable halfway point. Colors, font sizes, and the alike may be transitioned from one value to another as they have recognizable values in-between one another. The display property, for example, may not be transitioned as it does not have any midpoint. A handful of the more popular transitional properties include the following.

- background-color
- background-position
- border-color
- border-width
- border-spacing
- bottom
-clip
- color crop
- font-size
- font-weight
- height
- left
- letter-spacing
- line-height
- margin
- max-height
- max-width
- min-height
- min-width
- opacity
- outline-color
- outline-offset
- outline-width
- padding
- right
- text-indent
- text-shadow
- top
- vertical-alig
- nvisibility
- width
- word-spacing
- z-index
*Transition Timing*:
CSS:
(.box {
  background: #2db34a;
  border-radius: 6px;
  transition-property: background, border-radius;
  transition-duration: .2s, 1s;
  transition-timing-function: linear, ease-in;
}
.box:hover {
  background: #ff7b29;
  border-radius: 50%;
}
)
## 8 SIMPLE CSS3 TRANSITIONS THAT WILL WOW YOUR USERS
1. Fade in
2. Change color
3. Grow & Shrink
4. Rotate elements
5. Square to circle
6. 3D shadow
7. Swing
8. Inset border
