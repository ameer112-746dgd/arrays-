# arrays-
// Array Methods
// 1. push()
let arr = [1, 2, 3];
arr.push(4);
console.log(arr); // [1, 2, 3, 4]

// 2. pop()
arr.pop();
console.log(arr); // [1, 2]

// 3. shift()
arr.shift();
console.log(arr); // [2, 3]

// 4. unshift()
arr.unshift(0);
console.log(arr); // [0, 2, 3]

// 5. concat()
let arr1 = [1, 2];
let arr2 = [3, 4];
let merged = arr1.concat(arr2);
console.log(merged); // [1, 2, 3, 4]

// 6. slice()
let sliced = arr.slice(1, 3);
console.log(sliced); // [2, 3]

// 7. splice()
arr.splice(1, 2, 'a', 'b');
console.log(arr); // [0, 'a', 'b']

// 8. forEach()
arr.forEach(element => console.log(element));
// 0
// a
// b

// 9. map()
let doubled = arr1.map(x => x * 2);
console.log(doubled); // [2, 4]

// 10. filter()
let filtered = arr2.filter(x => x > 2);
console.log(filtered); // [3, 4]

// String Methods
// 1. charAt()
let str = "Hello";
console.log(str.charAt(1)); // 'e'

// 2. concat()
let str1 = "Hello";
let str2 = "World";
let combined = str1.concat(' ', str2);
console.log(combined); // "Hello World"

// 3. includes()
let str3 = "Hello World";
console.log(str3.includes("World")); // true

// 4. indexOf()
console.log(str3.indexOf("World")); // 6

// 5. toLowerCase()
console.log(str3.toLowerCase()); // "hello world"

// 6. toUpperCase()
console.log(str3.toUpperCase()); // "HELLO WORLD"

// 7. trim()
let str4 = "  Hello World  ";
console.log(str4.trim()); // "Hello World"

// 8. split()
let arr3 = str3.split(' ');
console.log(arr3); // ["Hello", "World"]

// 9. substring()
console.log(str3.substring(0, 5)); // "Hello"

// 10. replace()
let newStr = str3.replace("World", "Everyone");
console.log(newStr); // "Hello Everyone"

// Number Methods
// 1. toFixed()
let num = 123.456;
console.log(num.toFixed(2)); // "123.46"

// 2. toExponential()
let num2 = 123456;
console.log(num2.toExponential(2)); // "1.23e+5"

// 3. toPrecision()
console.log(num.toPrecision(4)); // "123.5"

// 4. valueOf()
let numObj = new Number(123);
console.log(numObj.valueOf()); // 123

// 5. toString()
console.log(num.toString()); // "123.456"

// 6. isNaN()
console.log(Number.isNaN(NaN)); // true
console.log(Number.isNaN(123)); // false

// 7. isFinite()
console.log(Number.isFinite(123)); // true
console.log(Number.isFinite(Infinity)); // false

// 8. parseFloat()
let num3 = Number.parseFloat("123.456");
console.log(num3); // 123.456

// 9. parseInt()
let num4 = Number.parseInt("123.456");
console.log(num4); // 123

// 10. toLocaleString()
let num5 = 123456.789;
console.log(num5.toLocaleString()); // "123,456.789" (in en-US locale)


