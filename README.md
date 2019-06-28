# Loops Exit Ticket

## Instructions for lab submission

1. Fork the assignment repo
1. Clone your Fork to your machine
1. Complete the lab
1. Push your changes to your Fork
1. Submit a Pull Request back to the assignment repo
1. Paste a link to of your Fork on Canvas and submit

## Question 1

What will the code below print?

```swift
var myNum = 8

for number in 4..<8{
    if number == 7 {
        break
    } else {
        myNum += number
    }
}

print(myNum)
```
It will print 23 it will count up to 6 because it breaks at 7 so add 4+5+6+8=23
***
## Question 2

Which of the following loops will print out all the numbers between 1 and 100, inclusive?  Select all that apply.

Answer: B & C

B)
```swift
for j in 1...100 {
    print(j)
}
```

C)
```swift
for k in 1..<1000 where k < 101 {
    print(k)
}
```


***
## Question 3

How many times will the code below print **"Nesting!"** ?

```swift
for _ in 1...10{
    for _ in 1...10{
        print("Nesting!")
    }
}
```
it will print it 100 times 10*10 because everytime outerloop prints the innerloop will print also

***
## Question 4

Which of the loops below will run forever? Select all that apply.


Answer: A & D

a)
```swift
var q = 0

while q%2 != 1 {
    print("Hello Problem Two!")
    q += 2
}
```

d)
```swift
var t = 0

while t == t{
    print("Ahoy-hoy!")
    t += 1
}
```

***
