# BuddyMeterAnswerGrabber
Do your friends send you silly quizzes on https://buddymeter.com about how well you know them? Want to get 10/10 to show them who's boss? This is the tool for you!

## Why I made this
My Friend send me a quiz today, and bet me that I could only get 1 correct. I did it once and got 7 correct, but I was determined to get all of them correct, so I spent a couple minutes writing this code to give me all the answer just so I could get 10/10. As my friend would say: "Cheat!!!! FFS Eric. Are you that fucking sad!?!?"

## Code
```javascript
var answerString = "Answers:\n";
for (var i = 1; i < questionArray.length; i++) {
    answerString += "[" + questionArray[i].answer + "]";
    //Gotta format stuff and things
    if (i % 5 == 0) {
        answerString += "\n";
    }
}
alert(answerString);
```
