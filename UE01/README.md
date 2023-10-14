# WDP3 exercise 01: JavaScript Basics

## Part 1: First step into JavaScript
Write the first JavaScript program and get familiar with Chrome Developer tools(Console, Debugger, Call Function from console, ...).


```
<html>
<body>
    <script>
        function sayHelloWorld() {
            console.log("hello world");
        }

        sayHelloWorld();

    </script>
</body>
</html>

```

## Part 2: Equals vs Equals (== vs ===)

```
1 == "1"
1 === "1"
1 != 1
1 == true
1 === true
false == 0
[] == []
NaN == NaN

null + 1 => 1
undefined + 1 => NaN

undefined == true
undefined == false
```

## Part 3: Implicit type conversion

```
// logcial not operator

!false
!undefined
!!undefined
typeof(undefined)
typeof(!undefined)
typeof(!!undefined)

// string concatenation
"a" + "b"
"a" + true
"a" + 1
"a" + + "b"

// mathematical expression
"5" - 1
"aaa" - 1
"5" * 2
"five" * 2
8 * null // => 0
8 - null // => 8
```

## Part 4: Function Scoping vs Block Scope

```
<html>
<body>
    <script>

        function foo(){

            if(1 === 1){
                var a = "foo";
                let b = "bar";

                console.log(a);
                console.log(b);
            }

            console.log(a);
            console.log(b);
        }

        foo();
    </script>
</body>
</html>
```


## Part 5: Bubblesort (Homework)

Implement the bubblesort algorithm in JavaScript for Numbers

Documentation:
* https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array
* https://en.wikipedia.org/wiki/Bubble_sort

bubblesort.html
```
<html>
<body>
    <script>
       
        function bubblesort(data) {
            // implement function
        }

        let arr = [123, 31, 2, 20, 90, 942, 76, 10];
        
        console.log(arr);
        bubblesort(arr);
        consloe.log(arr);

    </script>
</body>
</html>
```
