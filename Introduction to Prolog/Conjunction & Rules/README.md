# Conjunction & Rules

## Fact Code
```prolog
sells(mila,egg).
sells(joni,apple).
sells(john, bread).
buys(niloy,egg).
buys(tony,bread).

```

### 1. Mila sells anything that niloy buys ?
* Using Conjunction 
```prolog
sells(mila, X), buys(niloy, X).
```
* Using Rules 
    * Fact Code
    ```prolog
      mila_sells(X):-buys(niloy,X).
    ```
    * Main Code:
    ```prolog
      mila_sells (X).
    ```
          
### 2. Tony buys from anyone who sells bread ?
* Using Conjunction
```prolog
buys( tony, bread), sells( X, bread).
``` 
* Using Rules
    * Fact Code
    ```prolog
      tony_buys(X):-sells(X,bread).
    ```
    * Main Code
    ```prolog
      tony_buys(X).
    ```



