# Telescoping string reverse

We have an input with id="text-input" and div with id="text-span-holder",
what we need to implement is as the user types in the input
for each character typed we create a <code>span</code> inside <code>#text-span-holder</code>div
 with decreasing font size starting with 45 and decreasing by 1px.

Example:-
User types "Hello" inside input.
Inside <code>#text-span-holder</code
<span>H</span>  // fontSize:45px
<span>e</span>  // fontSize:44px
<span>l</span>  // fontSize:43px
<span>l</span>  // fontSize:42px
<span>o</span>  // fontSize:41px

Use keys for span and id of format <code>char-${index}</code> for span.

