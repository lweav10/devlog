---
title: Testing Screen
publish: true
---

This is a testing screen so i can see how various markdown elements appear on the browser.

# h1
## h2
### h3
#### h4
##### h5
###### h6

## Number list

1. First item
3. Second item
2. Third Item
5. number 5
5. number 5 again

## Bullet list

- a
- b
- c
    - sub c

## Code

This is a single line of code: `string name = Console.ReadLine();`

### Multilines
```C#
static void Main(){
    string language = "CSharp";
    int number = 37;
    Console.WriteLine("Multi");
    Console.WriteLine("Line");
    Console.WriteLine("C#");
    //Prints Multi Line C# (each word on new line)
}
```

```python
print("Hello, World")
print("This is in python")
a,b = 2,4

print(a+b) #returns 6
```

## Equations

Single line $a^2 + b^2 = c^2$

### Multilines

$$
x = \frac{-b \pm \sqrt{b^2-4ac}}{2a}
$$
$$
f'(a) = \lim_{h \to 0} \frac{f(x+h)-f(x)}{h}
$$

## Table

|h1|h2|h3|h4|
|-|-|-|-|
|This is the first cell of the first row of the table; It is very long|Cell 2 short|The next cell is empty||
|1|2|3|4|

> Callouts

>[!info] Info
>This might be an info block

>[!error] Error
>This might be an error block

>[!example]- How to print to console
> `Console.WriteLine("Your text here");`