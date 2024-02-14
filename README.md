# JS Bites

+ [String Reversal](#string-reversal---beginner-free)

***

## *String Reversal - Beginner (Free)*
<!-- Wednesday, 14th Feb 2024 -->

This challenge will test your skills in string manipulation.

🎯 You need to create a function that takes a string and returns it reversed.

Here's the starter function:

```js
function reverseString(str) {

}
```

🎯 Your task is to write code that reverses the string str and returns it.

> *Notes:  
> 📌 Ensure the reversed string is returned.  
> 📌 Try reversing different strings to test your function.*

### *Solution:*

```js
function reverseString(str) {
  return str.split("").reverse().join("")
}
```
#### *Donde*:

#### 🔥 `.split()`
+ **Divide** un *string en un array* mediante una *separación*.  
`str.split(separator [, limit])`
***
#### 🔥 `.reverse()`
- **Invierte** el orden de los *elementos* de un *array*.  
`arr.reverse()`
***
#### 🔥 `.join()`
+ **Une todos los elementos** de un *array* en un *string* y devuelve dicho *string*.  
`arr.join(separtor)`