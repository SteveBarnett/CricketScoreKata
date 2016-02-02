---
layout: single
---

# Cricket Score Kata

A game of [cricket](https://en.wikipedia.org/wiki/Cricket) is divided into sections of 6 balls, called **overs**.

When a **no ball** is bowled an extra ball is bowled. When a **wide** is bowled, the batting team scores 1 point.

## Scoring string

Here is a cricket score string showing the results of 5 overs:

```
|* * * w * *|* 1 * 2 * *|* 1w * * 3nb * *|* 1 * 4 * 6|1 w * 1 * 1|
```

In the score string:

|Symbol|Description|
|------|-----------|
|`|`   | divides one over from another|
|`*`   | no runs were scored|
|`w`   | a wicket was taken|
|`1w`  | a wide was bowled|
|`2nb` | a no-ball was bowled, from which 2 runs were scored. An extra ball will be bowled in the over|

Any other number entry states how many runs were scored off a ball.

## Calculations

Given a score string like the example above, write functions that return:

* the average score per over;
* the number of runs scored in the highest scoring over;
* the total score;
* the number of wides bowled;
* the number of no-balls bowled;
* the number of extra balls bowled.
