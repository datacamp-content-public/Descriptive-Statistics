---
title: test challenges
description: >-
  undefined


---
## Another test

```yaml
type: NormalExercise

xp: 

key: 8eb71c7a4c
```

Correlation calculation

`@instructions`
Calculate the correlation between x and y

`@hint`


`@pre_exercise_code`
```{}
# randomly generate x and y
  n <- 12
  x <- runif(n)
  y <- runif(n)
# print x, y
	x; y
```

`@solution`
```{}
cor(x, y)
```
`@sct`
```{}
success_msg('Yeah !!')
```




