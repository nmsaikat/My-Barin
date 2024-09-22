
## ``CSS এ পাঁচ ধরনের সিলেক্টর হয়ে থাকে``
1. CSS element Selector
2. CSS id Selector
3. CSS class Selector
4. CSS Universal Selector
5. CSS Grouping Selector
---

## The CSS element Selector
- আমরা কোন ``HTML Tags`` কে টার্গেট করে ``CSS`` লিখলে সেটাকে ``HTML Element Selector`` বলে থাকে। 

```css
p {
  text-align: center;
  color: red;
}
```
---

## The CSS id Selector
- ``HTML File`` এর মধ্যে আমরা স্পেসিফিক কোন কিছুকে ``Style`` করতে হলে আমরা ``ID Selector`` ব্যবহার করে ``Style`` করতে পারি। 
- ``HTML File asame id`` একবারের বেশি ব্যবহার করা যায় না। আমরা চাইলে ``different id`` ব্যবহার করতে পারি ``HTML`` এর মধ্যে

```css
#para1 {
  text-align: center;
  color: red;
}
```
---

## The CSS class Selector
- ``HTML`` এর মধ্যে আমরা স্পেসিফিক কোন কিছুকে ``Style`` করতে হলে আমরা ``Class Selector`` ব্যবহার করতে পারি আর ``Class Selector`` একই জায়গায় একের অধিক ব্যবহার করা যায়। 

```css
.center {
  text-align: center;
  color: red;
}
```
---

## The CSS Universal Selector
- ``CSS Universal Selector`` কাজ হল কোন ``Class`` বা কোন ``ID`` বা কোন ``Element`` এর সাথে কাজ করে না এটা হচ্ছে পুরা ``Web Page`` এর জন্য ``Globally`` কাজ করে। 

```css
* {
  text-align: center;
  color: blue;
}
```
---

## The CSS Grouping Selector
-  ``CSS Grouping Selector`` এর কাজ হল অনেকগুলো ``Class`` অনেকগুলো ``Element`` কে একসাথে করে ``same style Apply`` করতে পারা। 

```css
h1, h2, p {
  text-align: center;
  color: red;
}
```