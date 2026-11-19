# 2035 Project

we took a pic on voyager 1's one light-day and tlock-encrypted it until [1 Nov 2035](https://x.com/NSFVoyager2/status/2123053906062152079), when voyager 2 reaches the same distance.

using [drand timelock encryption](https://docs.drand.love/docs/timelock-encryption/).

### unlock in nov 2035

```sh
tle -d -o identity.txt identity.tlock
age -d -i identity.txt -o photo.jpg photo.age
```

### a note on quantum computers


> *we cannot guarantee that quantum computers won't crack the encryption sooner.*
> *if that happens, congratulations! you have officially beaten voyager 2 to the destination.*
>
> *humanity, 2026.*

### if drand dies

the age key is split with shamir secret sharing. if the drand network is gone before 2035, we're able to reconstruct the pic and lock it another way.
