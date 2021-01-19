## These functions aim to get you into a TDD flow mood 

## TDD is about "divide and conquer" code

Self-dosing the amount of complexity you want to solve ➕ Planning wisely the battles you choose to face

leads to

Less energy spent without slowing down ➕ Well designed code


## How to use these functions

1) `source set_aliases_for_bash_session.sh`
2) use `rwip` when you have set a small goal in a form of a failing test
3) use `gwip` when the small goal is achieved
4) use `fwip` when you want your solution to be easier to read/maintain/change/replace
5) go to 2 until you have delivered business value
6) did this system turn your experience into a more fulfilling one? did you miss your usual approach? why? why not?
7) keep delivering business value

`Even the result is the same, live with enough caring so to consider if multiply 2x2 is better than adding 2+2`

## How to test the functions without cloning/sourcing the files

Copy and paste this text into your console

```function gwip {
        git add -A; git commit -m "🟢🟢🟢🟢 GREEN - $1 - to squash"
}
function rwip {
        git add -A; git commit -m "🔴🔴🔴🔴 RED - $1 - to squash"
}
function fwip {
        git add -A; git commit -m "👍👍👍👍 REFACTOR - $1 - to squash"
}```
