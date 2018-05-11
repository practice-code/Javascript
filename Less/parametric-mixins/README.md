>Parametric mixins use one or more parameters that extend functionality of LESS by taking arguments and its properties to customize the mixin output when mixed into another block.

`.border(@width; @style; @color) {
    border: @width @style @color;
 }
 
 .myheader {
    .border(2px; dashed; green);
 }`