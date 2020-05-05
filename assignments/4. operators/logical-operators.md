# Logical Operator

1. 🥇What's the output of the following, write the output next to the code as comment.

* [ ] Logical AND operation

```js
true  && true; //true
true  && false; //false
false && true;// false
false && false; //false
"foo" && "bar"; //"bar"
"bar" && "foo"; //"foo"
"foo" && ""; //""
""    && "foo"; //""
" "   && "John" && "" && false //""
false && "Hey" && undefined //false
"undefined" && false && 42 //false
```

* [ ] Logical OR operation
```js
true  || true; //true
true  || false; //true
false || true; //true
false || false; //false
"foo" || "bar"; //"foo"
"bar" || "foo"; //"bar"
"foo" || ""; //"foo"
""    || "foo"; "foo"
" "   || "John" || "" || false //" "
false || "Hey" || undefined //"Hey"
"undefined" || false || 42 //"undefined"
```

2. 🥈You have two variables i.e `isGuestOneVeg` and  `isGuestTwoVeg` according to the value using logical && and || opeartor do the following.

* [ ] If both are veg "Only offer up vegan dishes."
* [ ] At least one veg  "Make sure to offer up some vegan options."
* [ ] Else, "Offer up anything on the menu"
```js
let isGuestOneVeg = false;
let isGuestTwoVeg = false;
// Your code goes here
let menu
if(isGuestOneVeg && isGuestTwoVeg) {
    menu = 'only offer up Vegan dishes';
} else if(isGuestOneVeg || isGuestTwoVeg) {
    menu = "Make sure to offer up some vegan options.";
}else{
    menu = 'offer up anything on the menu';
}
alert(menu)
```


3. 🎖Using the variable `temperature` and logical operators do the following
* [ ] If temperature is less then 32 alert "It is freezing outside"
* [ ] If the temperature is greater then 110 alert "It is hot outside"
* [ ] else 'Go for it. It is pretty nice out'
```js
let temperature = 4;
// Your code goes here
if(temperature < 32){
    alert('It is freezing outside')
}else if(temperature > 110){
    alert('It is hot outside')
}else{
    alert('Go for it. It is pretty nice out')
}
```

4. 🎖 Output of this and the reason behind the output.
```js
alert( alert(1) || 2 || alert(3) );
// Ans. First 1 and then 2
//Reason: alert doesnot return any value. OR, while operating, goes from left to right.
// So, first alert(1) is operated which gives value '1'. So, '1' is displayed. But, it doesnot return any value or we can say it returns "undefined" which is falsey value. Therefore, OR moves on to its next operator to check if it's truthy.
// '2' is truthy value. So, search of OR stops and it shoews "2" as final output.
```