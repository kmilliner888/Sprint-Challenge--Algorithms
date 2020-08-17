#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(log n)- It isn't constant time because the size of the input will affect the runtime, but it is still slow


b) O(1) - Constant time because no matter what n is, the run time is unaffected


c) O(n)- bunnies and runtime will grow at the same rate

## Exercise II

## If egg dropped from n-story >= floor-f: egg == broken

## If egg dropped from n-story < floor-f: egg == not-broken

def buildingdrop(n, f):
    egg = 0
    if n == 0:
        return
    elif n >= f:
        return egg =- 1
    else:
        return egg =+1

