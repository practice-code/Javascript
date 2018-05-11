>Parameters can be separated using commas or semicolon. Using the comma symbol, you can interpret it as mixin parameters separator or css list separator. If you use semicolon inside mixin, then it separates the arguments by semicolons and CSS lists will be having all the commas

- If you have two arguments, then the arguments will contain commas separated list. For instance, .class1(1, 2, 3; sometext, other thing)
- You can use dummy semicolon with comma separated list like .class1(1, 2, 3;).
- If there are three arguments, the arguments will include only numbers such as .class1(1, 2, 3).
- There is comma separated default value. For instance .class1(@color: gray, green;)`

**syntax:**

`.mixin_name(@var_name1; @var_name2:some) {
    //code here
 }`