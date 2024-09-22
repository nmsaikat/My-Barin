#### There are three ways to insert CSS in HTML documents
1. Inline CSS
2. Internal CSS
3. External CSS

#### Rules for using inline CSS
- আমরা ``HTML`` ট্যাগের মধ্যে ``Style`` অ্যাট্রিবিউটের মাধ্যমে জে ``CSS`` গুলো ব্যবহার করে থাকি সেগুলোকেই ``inline CSS`` বলে। 
```html
<!DOCTYPE html>
<html>
<head>
</head>
<body>

<h1 style="color:blue;">A Blue Heading</h1>

</body>
</html>
```

#### Rules for using internal CSS
- আমরা ``HTML Document`` মধ্যে ``<head></head>`` ট্যাগের ভিতরে ``<style></style>`` ট্যাগের মাধ্যমে যে ``CSS`` গুলো ব্যবহার করে থাকি সেটাকে বলা হয় ``internal CSS``
```html
<!DOCTYPE html>
<html>
<head>
<style>
h1   {color: blue;}
p    {color: red;}
</style>
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
```

#### Rules for using external CSS
- আমরা আলাদা করে ``CSS`` ফাইল তৈরি করে, ``HTML Document`` সাথে ``link Tag`` এর মাধ্যমে ``link`` করে ব্যবহার করে থাকি সেটাকে ``External CSS`` বলে। 
```html
<!DOCTYPE html>  
<html>  
<head>  
<link rel="stylesheet" href="mystyle.css">  
</head>  
<body>  
  
<h1>This is a heading</h1>  
<p>This is a paragraph.</p>  
  
</body>  
</html>
```