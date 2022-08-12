# Rules in Prolog 

## Relationship
<img src="https://raw.githubusercontent.com/Tahsin000/PROLOG-IN-ARTIFICIAL-INTELLIGENCE/main/Introduction%20to%20Prolog/Rules/Assets/Relationship.svg" width="820px">

## Fact Code
```prolog
father(shohidul, satcho).
father(jamal,shohidul).
father(rahman,jamal).
father(someone,rahman).

```

### 1. Is Jamal the grandfather of satcho ?
* Fact Code:
  ```prolog
  % grandfather(jamal,satcho):-father(jamal, shohidul), (shohidul,satcho).
  grandfather(X,Y):-father(X,shohidul),father(shohidul, Y).
  ```
* Answer:
  ```prolog
  grandfather(jamal,satcho).
  ```

### 2. What is the name of Sathco's grandfather ?
* Fact Code:
  ```prolog
  grandfather(X,Y):-father(X,shohidul),father(shohidul, Y).
  ```
* Answer:
  ```prolog
  grandfather(X,Y).
  ```
