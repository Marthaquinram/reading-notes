#  CSS Transforms, Transitions, and Animations
####  CSS Transforms

- Transform property comes in two different settings, two-dimensional and three-dimensional. they each come with their own individual properties and values. ex:
div {
  - webkit-transform: scale(1.5);
     - moz-transform: scale(1.5);
       - o-transform: scale(1.5);
          - transform: scale(1.5); }
- 2D Transforms - Two-dimensional transforms work on the x and y axes, known as horizontal and vertical axes. 
- 3D - Three-dimensional transforms work on both the x and y axes, as well as the z axis. 
- 2D rotate -The rotate value provides the ability to rotate an element from 0 to 360 degrees. HTML - < figure class="box-1">Box 1< /figure>
< figure class="box-2">Box 2< /figure>. CSS .box-1 {
  transform: rotate(20deg);
}
.box-2 {
  transform: rotate(-55deg);
}

- 2D scale - "Using the scale value within the transform property allows you to change the appeared size of an element. The default scale value is 1, therefore any value between .99 and .01 makes an element appear smaller while any value greater than or equal to 1.01 makes an element appear larger. HTML - < figure class="box-1">Box 1< /figure>
< figure class="box-2">Box 2< /figure>. CSS - .box-1 {
  transform: scale(.75);
}
.box-2 {
  transform: scale(1.25);
}
- 2D Skew - The last transform value in the group, skew, is used to distort elements on the horizontal axis, vertical axis, or both.

- 3D Rotate - With three-dimensional transforms we can rotate an element around any axes. To do so, we use three new transform values, including rotateX, rotateY, and rotateZ. CSS - .box-1 {
  transform: perspective(200px) rotateX(45deg);
}
.box-2 {
  transform: perspective(200px) rotateY(45deg);
}
.box-3 {
  transform: perspective(200px) rotateZ(45deg);
}
- 3D Scale - By using the scaleZ three-dimensional transform elements may be scaled on the z axis. CSS - .box-1 {
  transform: perspective(200px) scaleZ(1.75) rotateX(45deg);
}
.box-2 {
  transform: perspective(200px) scaleZ(.25) rotateX(45deg);
}



### CSS Transitions & Animations
- for a transition to take place, an element must have a change in state, and different styles must be identified for each state.The easiest way for determining styles for different states is by using the :hover, :focus, :active, and :target pseudo-classes.
- theres Four transition related properties total 
  - transition-property
  - transition-duration
  - transition-timing-function
  - transition-delay
  - not all are required to build a transition.
- Ex: .box {
  background: #2db34a;
  transition-property: background;
  transition-duration: 1s;
  transition-timing-function: linear;
}
.box:hover {
  background: #ff7b29;
}
- Transition Duration - "The duration in which a transition takes place is set using the transition-duration property. The value of this property can be set using general timing values, including seconds (s) and milliseconds (ms). These timing values may also come in fractional measurements, .2s for example." (https://learn.shayhowe.com/advanced-html-css/transitions-animations/)
- Transition Timing - The transition-timing-function property is used to set the speed in which a transition will move. 
-  A few of the more popular keyword values for the transition-timing-function property include linear, ease-in, ease-out, and ease-in-out.


### 8 simple CSS3 transitions that will wow your users
- Fade In - effects are coded in two steps: first, you set the initial state; next, you set the change, for example on hover:(set class for div to fade):.fade
{
        opacity:0.5;
}
.fade:hover
{
        opacity:1;
}

- change color - animating the change of color. (set div class to color):
.color:hover
{
        background:#53a7ea;
}
- "Grow & Shrink:Set your div’s class to “grow” and then add this code to your style block: .grow:hover
{
        -webkit-transform: scale(1.3);
        -ms-transform: scale(1.3);
        transform: scale(1.3);
}" 
- to shrink animation ".shrink:hover
{
        -webkit-transform: scale(0.8);
        -ms-transform: scale(0.8);
        transform: scale(0.8);"
}
- Rotate elements - div the class “rotate” .rotate:hover
{
        -webkit-transform: rotateZ(-30deg);
        -ms-transform: rotateZ(-30deg);
        transform: rotateZ(-30deg);
}
- Square to circle - transition the border-radius property. Give your div the class “circle”:.circle:hover
{
        border-radius:50%;
}
- 3D shadow - This effect is achieved by adding a box shadow, and then moving the element on the x axis using the transform and translate properties so that it appears to grow out of the screen. - div the class “threed”
.threed:hover
{
        box-shadow:
                1px 1px #53a7ea,
                2px 2px #53a7ea,
                3px 3px #53a7ea;
        -webkit-transform: translateX(-3px);
        transform: translateX(-3px);
}
- Swing- can create complex animations using @keyframes, animation and animation-iteration.due to implementation issues, we need to use @-webkit-keyframes as well as @keyframes. 
- Inset border - a button with  not background and a heavy border. div the class “border” .border:hover
{
        box-shadow: inset 0 0 0 25px #53a7ea;
}


## Things I want to know more about
- I want to get better at CSS, really understand what each thing does and when to use it.
