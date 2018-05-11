>You can change the behavior of mixin by passing parameters to it.

**syntax:**

`.mixin(@a; @color) { ... }
 
 .line {
    .mixin(@color-new; #888);
 }`
 
 ###another one
 
 
 `.mixin(dark; @color) {
     color: darken(@color, 15%);
  }
  
  .mixin(light; @color) {
     color: lighten(@color, 15%);
  }
  
  @color-new: dark;
  
  .line {
     .mixin(@color-new; #FF0000);
  }`