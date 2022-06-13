# Programs -
## 1. Average of array nums in Javascript?
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <script>
        function avg(){
            let sum = 0;
            let arry = [1,2,3];
            for (let i = 0; i < arry.length; i++) {
                sum+= arry[i];
                
            }
            document.write(`the average is ${sum/arry.length}`);
        }
        avg();
     </script>
</body>
</html>
```

## 2. Swap two numbers by reference?
```
<!DOCTYPE html>
<html>
<body>
<h1> Swap Two Numbers</h1>

<script>
var num1 = 10;
var num2 = 20;
var temp = 0;

document.write("<br>Before Swap, num1 = " +num1+" num2 = "+num2);
temp = num1;
num1 = num2;
num2 = temp;
document.write("<br>After Swap, num1 = " +num1+" num2 = "+num2);
</script>
</body>
</html>
```

## 3. Print the fibonacci sequence?
```
<!DOCTYPE html>
<html>
<body>
<h1>JS Swap Two Numbers</h1>

<script>
function fibonacci( N){
    let t1 =0;
    let t2 = 1;
    let nextTerm ;
    for(let i =0;i<N;++i){
        document.write(` ${t1 }`);
        nextTerm =t1+t2;
        t1 = t2;
        t2 = nextTerm;
    }
}
fibonacci(5);
</script>
</body>
</html>
```

## 4. Sort an array by both ascending and descending order?
```
<!DOCTYPE html>
<html>
<body>

<h2>JavaScript Arrays</h2>

<p>The Array.sort() method sorts the elements of an array.</p>

<p id="p1"></p>

<script>
const ascending = [40, 100, 1, 5, 25, 10];
ascending.sort(function(a, b){return a-b});
document.getElementById("p1").innerHTML = "ascending order :"+ascending;
</script>

<p id="p2"></p>

<script>
const descending = [40, 100, 1, 5, 25, 10];
descending.sort(function(a, b){return b-a});
document.getElementById("p2").innerHTML ="descending order :"+ descending;
</script> 
</body>
</html>
```

## 5. Show a variable value in an HTML webpage using DOM?
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title></title>
  </head>
  
  <body>
   
    <script>
     let name = "Nathan";
      document.write(name); 
      </script>
    <P> value has shown!</P>

  </body>
</html>
```