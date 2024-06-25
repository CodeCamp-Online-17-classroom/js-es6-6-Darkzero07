# js-lab-150
### Lab 150 ES6: ฟังก์ชันที่รับค่า ชื่อ นามสกุล และ งานอดิเรก
จงเขียนฟังก์ชันที่รับค่า ชื่อ นามสกุล และ งานอดิเรก ซึ่งงานอดิเรกอาจมี 1 หรือมากกว่า 1 ก็ได้ แล้วคืนค่าเป็น ชื่อ, นามสกุล, งานอดิเรก และจำนวนงานอดิเรก โดยใช้คุณสมบัติของ spread parameter

```JavaScript
const personInfo1 = getInfo('Alice', 'Smith', 'Drawing');
console.log(personInfo1);
// { name: 'Alice', lastName: 'Smith', hobbies: ['Drawing'], numberOfHobbies: 1 }

const personInfo2 = getInfo('Bob', 'Johnson', 'Cooking', 'Fishing', 'Gardening');
console.log(personInfo2);
// { name: 'Bob', lastName: 'Johnson', hobbies: ['Cooking', 'Fishing', 'Gardening'], numberOfHobbies: 3 }

const personInfo3 = getInfo('Eve', 'Brown');
console.log(personInfo3);
// { name: 'Eve', lastName: 'Brown', hobbies: [], numberOfHobbies: 0 }
```
