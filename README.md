<h1>What is Scope <br>in  JavaScript?</h1>


```
 The scope is the current context of execution in which values and expressions are "visible" or can be referenced.
If a variable or expression is not in the current
scope, it will not be available for use. Scopes can also be layered in a hierarchy, so
that child scopes have access to parent scopes, but not vice versa.
```
 - ## `Global scope:`
The default scope for all code running in script mode.

 - ## `Function scope: `
The scope created with a function.
 - ## ` Block scope:`
This scope restricts the variable that is declared inside a specific block, from access by the outside of the block.



![](https://www.scaler.com/topics/images/scope-in-javascript-thumbnail.webp)


<h1>The scope chain</h1>

``` js
const myName = 'Jonas';

function first(){
    const age= 30;

     if(age >= 30) {
     const decad= 30;
     var millenial = true;
     }

     function second() {
        const job= 'teacher;

        console. log(*$ myName)
     }
     second ();
}

first():
```


<h1>What is Hoisting <br>in  JavaScript?</h1>
--> Hoisting is a JavaScript mechanism where variables and function declarations are moved to the top of their scope before code execution.
<br> <br>
--> Hoisting in JavaScript isa behavior in which a function or a variable can be used before declaration.

![alt text](https://res.cloudinary.com/practicaldev/image/fetch/s--Ceq9cg87--/c_imagga_scale,f_auto,fl_progressive,h_900,q_auto,w_1600/https://thepracticaldev.s3.amazonaws.com/i/kaf11wh85tkhfv1338b4.png)



## H o i s t i n g- Va r i a b l e( v a r )

There'sa temptationt othinkthatallofthecodeyouseei na JavaScript
programi sinterpretedline-by-line,top-downi norder,a stheprogram execute.Whilethatisessentiallytrue,there'sonepartofthatas-assumption thatc a nleadtoincorrectthinkingaboutyourprogram.

```
a = 1;
alert ( ' a = ' + a)
vara;
```

```js
a = 1;
alert ( ' a = ' + a)
vara;
```
