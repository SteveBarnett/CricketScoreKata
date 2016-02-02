# Cricket Score Kata

A cricket game is divided into 6 ball sections which is called an over.
When a 'no ball' is bowled an extra ball is bowled.
When a wide is bowled the score is allocated to the team and not against a specific player.

Parse a basic cricket score string in a format like this:

`
|* * * w * *|* 1 * 2 * *|* 1w * * 3nb * *|* 1 * 4 * 6|1 w * 1 * 1|
`

In the score string:

|Symbol| Description|
|-----|----------|
|`|`  |  divides one over from another|
|`*`  | means a ball was bowled by no run scored|
|`w`  |  a wicket was taken|
|`1w`  | 1 wide was bowled|
|`2nb` | a no-ball was bowled of which 2 runs was scored and extra ball wil be bowled in that over|
| | any other number entry states how many runs was scored of a ball|

Given a score string like above, write functions that can calculate:

* the average score per over
* return the number of runs scored in the most profitable over
* the total score
* the number of wides balled
* the number of no balls bowled
* the number of extras bowled.
