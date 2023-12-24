var upperbound = 11
var tries = 1
var triesmax =1
var highscore = 9

function guessMyNumber(n) { 
    
 if (n > upperbound) { 
     (tries=tries+1) 
 return 'Out of bounds! Please try a number between 0 and .' + upperbound 
 } else if ((n== upperbound) &&
(tries<=highscore)){
    highscore = tries
        n = n+2
        x = randInt(n)
        randInt = (randInt+3)
            return 'MISSION PASSED++RESPECT '+ highscore+'tries'}  
 
else if (n === x){
    triesmax = tries
    tries = 0
    n = n+ 9
    return 'MISSION PASSED ' + triesmax+ ' tries'}
 else if (tries>=3){
     tries = 0
     n = n-9
     return 'GAME OVER'
 }
    else (tries = tries+1)
    n = n-9
return 'nope'
}
 function randInt(n) { 
 return Math.floor(Math.random() * (n + 1)) 
 }
alert ("welcom to ours game guess a number between 0 and 11 and be the big winer ")
