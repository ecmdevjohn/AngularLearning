echo 'hello from Pipeline script in git'
node ('master') {
 echo 'hello from inside master Node'
 stage 'First stage'
 echo 'This is the start of the first stage'
 input 'OK to proceed to second stage?'
 stage 'Second stage'
 echo 'This is the start of the second stage'
}
