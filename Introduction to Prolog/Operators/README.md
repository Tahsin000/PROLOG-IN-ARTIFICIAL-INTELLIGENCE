# Operators


## Fact Code
```prolog
go:-write('enter any number: '),read(Num1),nl, write('enter any number: '),read(Num2),nl,mul(Num1,Num2).

mul(Num1,Num2):-
	Result is Num1*Num2,write(Result).

```

### 1. Multiply the two values?
```prolog
go.
```
