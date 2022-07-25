# Reference

## AnyDice.com
Exploding D6 reference
> function: xpls DS:n {
  S: 0
  if (DS=6) {
    S: 1+[xpls d6]
  }
  if (DS=5) {
    S: S+1
  }
  result: S
}

## Roll20
/roll ?{Base}d6m0=4sd>5 for Base
/roll ?{Resist}d6sd0f<2 for Resistance
/roll ?{Drama}d6!m0=4sd>4f1 for Drama
- Explode on a 6, success 4+ and fail on 1
![[Pasted image 20220723121606.png]]

## Base
> function: bd DS:n {
  B: 0
  if (DS>=5) {
    B: B+1
  }
  result: B
}

## Resistance
> function: rd DS:n {
  R: 0
  if (DS<=2) {
    R: R+1
  }
  result: R
}

## Drama
https://anydice.com/program/2a114
> function: drd DS:n {
  D: 0
  if (DS=1) {
    D: D-1
  }
  if (DS=2) {
    D: D+1
  }
  if (DS=3) {
    D: D+1
  }
  if (DS=4) {
    D: D+1
  }
  if (DS=5) {
    D: D+1
  }
  if (DS=6) {
    D: 1+[drd d6]
  }
  result: D
}
output 1d[drd d6] named "drama"

- 1Dd = ~10% change of 2 successes or more
![[Pasted image 20220723121643.png]]
- 2Dd = ~65% chance of 2 success or more
![[Pasted image 20220723122750.png]]
- 3Dd = ~
![[Pasted image 20220723122730.png]]







## Ideal Drama - not supported in Roll20
![[Pasted image 20220723115601.png]]
- Explodes on 4+, 2-3 = 0, 1 = -1
	- 16% -1
	- 40% 0
	- 20 % 1
	- 10% 2
	- 10% 3+
