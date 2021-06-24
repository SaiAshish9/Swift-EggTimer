# Selection Statements

```
if a==1{}else {}

switch a {case 1 to 2: print(1)  case 2 to 4: print(2) default : print (9) 
switch a {case 1: print(1)  case 2: print(2) default : print (9) }
```

# Ranges

```
a...b closed range a<=  <=b
a..<b left open range a<= <b
...b  one sided range <b



case 81...100
case 41..<81:
case ...40

["a":1,"b":2]
```

# Definning & Unwrapping optionals

 ```
 var a:String = nil X
 var a:String? = nil
 a="a"
 a = nil
 print(a!) X
 if a!=nil {
  print(a!)
 }
 ```
 
 # Timer
 
 ```
 timer = Timer()
 timer.invalidate()
 Timer.ScheduledTimer(timeInterval:1.0,target:self,userInfo:nil,repeats:true,selector:#selects(updateTimer))
 ```
 
