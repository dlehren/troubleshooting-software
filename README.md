# Troubleshooting Software
A book about troubleshooting software issues.

## Definition
A software bug is an error, flaw, failure or fault in a computer program or system that causes it to produce an incorrect or unexpected result, or to behave in unintended ways. source https://en.wikipedia.org/wiki/Software_bug

Software by nature is going to have bugs in it, the first step is comming to terms with it, its normal and the only way to not have bugs is to stop shipping software (no software == no bugs).

## Bug vs Feature 

Im using github to write this document and im not the best at spelling and grammer, it would be realy helpfull if spell check worked but it does not. is that a bug? no. would it be helpfull? yes. but its more of a feature request.

A bug gets reported to a developer and he replies that its not a bug, its a feature and goes on to explain why the software works in a certain way. the issue is that user was using the software and something bothered them so much that thay went ahead and contacted you its probibly worth understanding what the expectation was and it might indeed be a bug.

bugs will not go away by themself and will keep on happening, and its importent that if you notice something not working as expected to take a note of it to have it fixed in the future.

## finding a bug has a few steps.

### The somthing is off feeling
  when using or developing a software application and you notice that somthing is strange, stop for a secound and think then ask yourself is there a problem here? for example I use google maps to commute to work and i noticed that when entering a difrent state there is a small pop up on the buttom saying welecome to new jersey and then it goes away, I noticed that after a update to maps the pop up was not going away and the bar on the buttom with the ETA was being blocked, at first i didnt think its a issue and i would try clicking on it to get rid of the pop up but after a few times i realized that somthing is off and i would pay extra attention every time it happond and then i went ahead and reported it and a while later it was fixed.

### agreeing that its a bug
  it is posible that there is a mistake in almost anything and comming to terms with it is one of the first steps of being able to address the problem. the better software is built the less it should happon but as people its always posible to make a mistake or sometimes we just did not think of that use case or we did not fully get the users needs. for example i signed up for a credit card and when i got approved online the website said i could create a username and passward to access my account befor i actually get the cards in the mail, while i was signing up somthing on the banks website went wrong and i was not able to log into the account. after spending a lot of time with them on the phone they said that it will get fixed ones i get the actual cards in the mail and using the card number would help, after i got the cards the same issue was still happoning and only after another half hour on the phone with the bank the online account was fixed. the moral of the story is that even now the bank still probibly has this issue due to not be willing to agree that something is wrong and it being a edge case that does not happon often.
  
### documenting
  after the past steps its importent to take a note of the issue and send feedback or look into getting it fixed if its a product you are involved in. alot of times when i find somthing looking off when developing software im not looking for bugs at that time and im just trying to get some other work done but if i just let it go there is a chance ill lose the clarty of the problem and when exatly its happoning. 

### replicating 
  documenting issues and passing them on to other people to fix is a lot more efficient when it includes the steps to take to couse the issue to happon. try figuring out exactly when its happoning, and try to cause it to happen again to confirm. somtimes this step is not posible for you if you dont have acesss to the system or its caused by things you cant simulate or trigger.
  
## Avoiding bugs

### after developing a new feature try using it
  after making a code change dont expect it to work just becouse it makes logical sense, run the new code at least one time to make sure there are no obvious issues, it could be syntex error or system related.
  
  





