# Conjunctions 

## Relationship
<img src="https://raw.githubusercontent.com/Tahsin000/PROLOG-IN-ARTIFICIAL-INTELLIGENCE/main/Introduction%20to%20Prolog/Conjunctions/Assets/Conjunctions.svg" width="720">

## Fact Code
```prolog
emperor(turza, simulation).
emperor(sadhin, html).
emperor(sadhin, css).
emperor(udoy, sleep).
emperor(rajesh, love).
emperor(minhaj, superman).
emperor(turza, css).
emperor(tanu, deeplearning).
emperor(bipro, css).
emperor(munna, html).
emperor(tanvir, poet).
emperor(arif, math).
likes(ismail, dating).
likes(rajesh, dating).
likes(minhaj, photograph).

```

### 1. Who are the emperor of HTML and CSS ?
```prolog
emperor(X,html),emperor(Y,css).
```
### 2. Who are the emperor of HTML or CSS ?
```prolog
emperor(X, html);emperor(X, css).
```
### 3. Who are the emperor of love and like dating ? 
```prolog
emperor(X,love),likes(X, dating).
```
### 4. Show all the characteristics of minhaj ?
```prolog
emperor(minhaj,X);likes(minhaj,X).
```




