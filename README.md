# ArrayInJSNotes
从网上找了一些自己不知道到东西，先记到这里，说不定什么时候我就写博客了


`新建数组
/*方法一*/
var a = new Array(1,2);
/*方法二*/
var b = [1,2];
/*方法三（ES6新增）*/
var c = Array.of(1,2,3);
`
今天看到
https://segmentfault.com/a/1190000006136799
当参数只有一个数的时候。
var myArray = new Array(5); // 此时是新建了数组 preallocate how many elements will be required。 5是length
ES6 这个新增的方法of
var c = Array.of(1);   // 直接就是element 的array。1 是element.

