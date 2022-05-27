## Spin the Pots (Hughes and Ensor, 2005)

Link to current version: [spinThePots](https://intr-eeg.github.io/spinThePots/)

```
The Spin the Pots task was developed to assess working memory and inhibition 
in young children. The child was shown eight distinct "pots" which are set up 
on a Lazy Susan tray, and then invited to help the researcher place attractive 
stickers in six of the eight pots. The tray was then covered with a cloth and 
spun. Following this, the cloth was removed and the child choose a pot with 
the aim of finding all six stickers without error. Each choice was recorded 
and the child congratulated/encouraged before moving on to the next trial. 
Fixed spatial cues could not be used due to the rotation of the cups. Children 
were allowed a maximum of 16 trials and the task ended when all six stickers 
had been found. The task was scored as 16 minus the number of errors.
```

### Data Dictionary

Variable                        | Description
:------------------------------ | :--------------------------------------------
trial\_num                      | trial number
sticker1                        | location of sticker 1
sticker2                        | location of sticker 2
sticker3                        | location of sticker 3
sticker4                        | location of sticker 4
sticker5                        | location of sticker 5
sticker6                        | location of sticker 6
number\_of\_clicks              | number of clicks within trial
time\_to\_first\_click          | time to first click from start of trial (seconds)
time\_to\_last\_click           | time to last click from start of trial (seconds)
pot\_chosen                     | pot chosen in trial
sticker\_in\_chosen\_pot        | name of sticker within pot, if any
trial\_outcome                  | 'correct' or 'wrong'
current\_working\_memory\_score | working memory score as at end of current trial
current\_preservation\_score    | preservation score as at end of current trial
trial\_mouse.x                  | x coordinates of clicks
trial\_mouse.y                  | y coordinates of clicks
trial\_mouse.leftButton         | left button clicks (1) or not (0)
trial\_mouse.midButton          | middle button clicks (1) or not (0)
trial\_mouse.rightButton        | right button clicks (1) or not (0)
trial\_mouse.time               | click times (seconds)
trial\_mouse.clicked\_name      | names of objects clicked on

