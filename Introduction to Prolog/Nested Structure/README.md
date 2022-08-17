# Nested Structure


## Fact Code
```prolog
has(joe,car(ford,3,5000)).
has(joe,car,(opel,2,6000)).
has(mick,car,(toyta,5,1000)).
has(mick,car,(ford,2,2000)).


```

### 1. What kind of ford does mick have?
```prolog
has(mick,car,(ford,Age,Price)).
```
### 2. show the car name and price info ( condition price is less than 5000 )

* Using Conjunction
```prolog
has(_,car,(Car,_,Price)),Price < 5000.
``` 



