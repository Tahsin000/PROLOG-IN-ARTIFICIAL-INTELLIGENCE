# Facts, Query, Variable in Prolog

## RELATIONSHIP
<img src="https://raw.githubusercontent.com/Tahsin000/PROLOG-IN-ARTIFICIAL-INTELLIGENCE/main/Introduction%20to%20Prolog/Facts%2C%20Query%2C%20Variable%20in%20Prolog/Assets/relationship.svg" width="560">

## 1. Check whether the following statements are true or false through prolog query ? 
#### A ) Paul is joe’s father 
```prolog
fatherOf(paul,joe).
```
#### B) Jane is mary’s mother 
```prolog
motherOf(jane,mary).
```
#### C) Mary is male
```prolog
male(mary).
```
#### D) Paul is male
```prolog
male(paul).
```

## 2. Find out the following people:
#### A ) Joe’s children
```prolog
fatherOf(joe, Children).
```

#### B ) Jane’s children 
```prolog
motherOf(jane, Children).
```
#### C ) Male family members
```prolog
male(Male).
```
#### D ) Female family members
```prolog
female(Female).
```
