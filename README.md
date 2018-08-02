# Pitfalls of the Beginning Mind

## Preface

This is a work in progress, but what I am attempting to construct is what I am calling, "coding philosophy." I believe philosophy is a very appropriate way to describe what I am attempting to instruct on here as what philosophy teaches is a way to think. A way to approach the world. Many nations and languages come with their own philosophy or way of thinking through problems and I want to try and bridge that gap between a western philosophy, and a coding philosophy. To show new people who want to get into coding the pitfalls you will inevitable run into but not many people take the time to explain why you need to think in that way.

## Intro

I attempted to teach myself programming on many occasions and most of it ended up going nowhere or I ended up dropping the class or subject completely after I felt like I hit a wall. To me there was always this sense that learning ot program was a trial by fire. The lessons the instructors try and teach you at the beginning just don’t seem to be applicable to what you want to do. They spend so much time focusing on loops on functions and all you really want to know is how to build that program to track that thing you do for fun. What is typically taught in the beginning of programming feels so far from what you think programming is that often people finish a programing class feeling like they learned nothing. The program spends so much time on how to code they rarely ever seem to talk about why its applicable and why you need to do things in a specific way. They just hope that you can figure out on your own time and through your own experimentation how all these pieces fit together. It takes a very real and very intense sense of curiosity that eventually drives to action.

Now I am in no way going to say I have any knowledge on how to give people this sense of curiosity, but what I do have is a lot of time spent working with students who have beginnings of this curiosity but feel so lost the this strange new world that is computer science and programming that just give up. I am also not going to say that anyone can learn to program, I have worked with enough students to know that this is not the field for everyone, and that is in no way a negative reflection on them. I am not going to ever be an amazing athlete and that is something I have accepted; but I did get lucky enough to be half decent at programming and teaching. So if programming is something you want to learn and you feel like you are missing some fundamental concepts to programming (and trust me, everyone is) then I hope to cover as many of those topics that are just never talked about, but are needed to really succeed. So, let's get into it.

## Curiosity Cured the Cat

I would like to first talk about two mindsets that exist outside of coding and I feel are needed to be successful at literally anything you do. They are, a scientific mind, and a curious mind. Now I did just claim not to be an expert on curiosity, but I did say I didn’t know how to instill that desire into people. But what exactly is this “curiosity skill?” A simple definition I would give to it is this, “A sense of wonder and interest in a given topic that drives you to want to know more about it, or to solve a problem.” A real life example of this is the time that you had an issue with your car. What did you do about it? Did you take it into a shop or did you roll up your sleeves and get your hands dirty? It is this sense of curiosity combined with the determination to solve the problem for yourself that I am talking about.

Now I am not saying that if you take your car into the shop you are a horrible person with no sense of curiosity or determination, because I still take my car into the shop for most problems. But I have spent some time looking into problems that I have fixed on my own. And there is a laundry list of things I intend to look into and one day I will, when I have the time. Programming is this bottomless pit of rabbit holes where each study fest will only lead to more questions, and if you don’t have this inner drive of curiosity for the topic then you will never be able get a personal sense of understanding to the topic.

The kind of mindset I am talking about are the ones who put in the bare minimum into their work. They work from 9-5 and once 5 hits they are done for the day and not another thought about work will enter their mind until 9 the next day. This may seem harsh but that is the cost of excellence. You must develop your desire to figure things out on your own. I can tell when a student is really striving to learn when their questions shift from, “how do i?” to “where can I get information on.” They are taking personal responsibility for their learning, and their approach has become one of mastery instead of passing. When you are no longer concerned with grades or passing the class and your drive is self improvement then in my unprofessional opinion you have the correct focus.

Ok I will get off my high horse and move onto my next point, having a scientific mindset.

## Scientific Mindset

When you start learning to program it is something that feels so foreign and alien to the average person. It's hard to put your finger on what exactly feels so off about it or why it so hard to learn and make improvements on. I would like to talk about the pitfalls and misunderstandings about programing to try and help you bridge the gap from where you are now and where you want to be. You probably wont fully understand all of what this topic is going over the first time but if you reread this I am hoping you can pick up more and more as your understanding continues to grow.

First I want to talk about what Scientific really means. When you hear science, or a science experiment you may initially think about things like the TV show Bill Nye the Science guy. The whole premise of that show is to show you scientific experiments or things that relate to science. I would like to challenge that none of those things are even remotely scientific. To be considered a scientist is someone who makes observations about the world around them, and then performs experiments to test their observations. I left that intentionally vague and broad for a few reasons. You can take a scientific approach to literally any topic. The whole point of being scientific is to learn new things and to fix problems. Before I can really prove or show what I mean by this I want to first talk about what the steps of the scientific method are.

<pre>
1: Make Observe
2: Form a Hypothesis
3: Construct a test to prove hypothesis
4: Run the experiment
5: Analyse the results
6: Form Conclusion
</pre>

I want to break down each one of these steps and how exactly they apply to coding. But to help make the point about how important these steps are to life and problem solving and that they don't just apply to coding I will also talk about how these apply to fixing a car, just to keep with the theme from earlier. Again I want to stress that scientific method is not something just for "scientist" and I would argue it is more of a way of life and a pattern of thinking. By making this your formal practice of problem solving you will have the framework to approach any problem.

### Observation

The first step in the process can come up at any point while you are working. Making an observation can be as easy as noticing, that there is a problem with your project. In the world of cars you might notice or observe that your car make an odd sound while you are driving. By noticing something like that you have unknowingly started the scientific process but a lot of people will stop the process at this point and ignore what could be a greater problem. Or if you choose to engage in your observation you may not have experience at making specific acute observations. We said that your car is making noise, but when is it making noise? does it happen all the time? Only when you turn? only at high speeds? At this point it is going to be to your most benefit for you to hold off moving onto step two until you have done a thorough job making your observations.

In computer speak you the types of observations you could have made is that your code failed after you added in a new feature. But where exactly did it fail? Did it fail on load? when you moved the mouse over an element, or when you clicked something. Did it happen immediately or was there a delay? I will talk more about taking this process slowly in another section but you need to train yourself to notice exactly the order of events that happen. Often I see students perform 10 actions and they are unsure of what caused the issue because they are not asking themselves these kind of questions, or moving methodically through their application and watching the console for errors after every little thing.

You are going to be tempted to start making hypothesis or guesses in this step as it is human nature to simultainisuly make a guess at the cause while you observe. For example you might say when I click this button the function runs and gets the info but won't display the data. Now its possible that this could be an observation but often I will see students click buttons and just assume it runs the function they want. Keep the observation to, when I click this button the desired result is not what I want. To give another car example your horn may not work, so you might say to your self, "the horn wont work because the electrical system is broken." Now im not saying that your initial thought as to why the problem exists are wrong, but often what happens is you will blind yourself to other possibilities. You don't want to loose sight of what the problem you are trying to solve is, (the horn not working) by being fixated on something that may not be the cause of the problem.

To summarize, the observation step should look something like this, "My code is not working as intended. When I click this button it doesn't do the action I expect. It never works, and the error pops up immediately when I click it." It is important not to loose sight of what the problem is, with what you think the problem is caused by, thats the next step.

### Form a Hypothesis

(more to come)

## Programming is a language

It may seem odd at first that we refer to this skill as a “Language,” but that is truly the best way to look at it. You are learning to communicate in an entirely new way, and I mean that very literally. Though reading that can still give the wrong impression of what I mean by saying new ‘language.’ When we learn a new spoken language one of the first things that you need to learn is that you can not translate word for word, instead you must learn to translate meaning for meaning. An example of this is saying ‘Thank you’ in spanish. In spanish you say ‘de nada,’ which literally translates into ‘of nothing.’ Now of nothing has meaning in english but it does not communicate the same thing at all, in fact of nothing really doesn’t mean anything to an english speaker. Instead we must realize that we are translating the idea of gratitude, or of thanks. There are also words in other languages that english really does not have words or concepts for. For example the word ‘Sobremesa‘ is a spanish word that translates to, ‘the conversation that follows a meal.’ Now it’s not hard to translate the word but we have to many words to describe what they have in one word.

The second hurdle that must be jumped when learning a new language is that the sentence structure may be completely different. In english we structure our ideas in a specific way because that is how we have decided english should be spoken. But in other languages the structure of the sentence may be completely different. This makes speaking in the new language very difficult because not only are you having to worry about what does this word convey in the new language but when should this word be used in a sentence for it to make sense to the listener (come up with examples of this later). After considering this it becomes apparent very quickly that learning to speak a new language requires more than just finding the equivalent word in the new language. You must learn to boil down the idea of what you are trying to convey/communicate and find a whole new sentence structure and the proper words to use. If you were to try and speak japanese using only literal translations it would make no sense to a native Japanese speaker.

When you are practicing your new language skills you are bound to make many mistakes in both pronunciation and grammar, but the saving grace about this is that we can usually rely on the listener to use enough reasoning and mastery of the language and context of the situation to figure out what is attempting to be communicated. If someone came up to you with a very thick accent that made it apparent to you that english was not their first language and they said, “bathroom” you would know exactly what they were really asking, can you show me where the nearest bathroom is. The only way you would be confused at the word is if the accent we so thick you couldn’t even make out the word.

As humans we rely and live off of others ability to infer, guess, use context, and fill in the blanks on the information that wasn’t actually provided. When you really stop and think about it, it is almost like a super power. Within a few words we can pull so much meaning and understanding from our years of life experience. You probably don’t even realize that you do that or that you expect so much from others when you communicate with them. If you think about having a conversation with a child they ask so many questions about everything you say. Without even realizing it they are trying to build a working model of reality that can fill in holes and an understanding about the world they live in. It is from this young age that we start to shortcut our brains. If we had to process every word, one at a time and then put all those words into a sentence, then consider the meaning of the whole, then compare that to the situation that were in conversations would take forever. We spend our entire childhood building these ‘conversation shortcuts,’ and by the time we have reached maturity our ability to communicate and make leaps in meaning is engrained we literally don’t even realize we are doing it, more on that later.

## Phrases Make no sense

Cut to computer programming. Every idea and concept above that we just talked about, forget all of it. Regress your brain back to a 4 year old and re learn how to communicate because this is what it is going to take. A Computer requires communicating with a level of precision and clarity that we as humans have never had to deal with. Yes I mean communicating quite literally here, we are having a conversation with a computer asking it to perform a task or go give us feedback/information but one wrong miss step and we will get nothing but a broken program. This is so frustrating that it drives most new programmers to a level of annoyance and anger they have never known before. You might have thought of yourself as a good communicator and someone who can speak clearly but you probably never considered how much you rely on unspoken or inferred communication, and it is that mind set that will the biggest hurdle to learning to program.

Let’s go over an example to show what I am talking about. Growing up we tell kids to “Not to get into cars with strangers if they offer you candy.” Sound familiar? I want you to think of all the loopholes or situations you didn’t cover that exist with that statement, go ahead, I’ll wait.

First we have loosley explained what a stranger means We hope the kid understand that means anyone you don’t know. But even still think about times when when it ok to get in a car with someone you don’t know, what about police officers? Firefighters? Lets take it even further, lets define the word “know.” To know someone is for you personally to be acquainted with them beforehand. So I may know the person picking up my child but since they don’t know them the kid shouldn’t get in the car with them. Ok also lets define car. Do we just mean sedans? Trucks? Vans? Does getting the the bed of a track count as “getting in?“ What exactly does “get in with” mean. What about specifically “get in with” mean, if they get in at separate times is that ok? What if they offer the kid any other food? What does the kid define as “Candy”. I could literally write a whole novel to explain all the rules and exceptions to that exact situation, but to do so would feel worthless and un necessary. It would go on for hundreds of pages, taking time to define every word and their meaning in that context.

This is what I see as the first major hurdle for when learning to program. Often what we say has no bearing on what we mean. When we say, “do Not get into cars with strangers if they offer you candy” what we really are trying to say is, “I don’t want to lose you and have you get kidnapped. So please don’t be stupid” As you go forward in life you may want to start asking yourself, how would a smart alec kid try and poke holes in my rules. That is literally what we are working with when it comes to computer, an annoying kid who will find every hole in your logic.

## Error Handling

Another issue we encounter is the issue of context and “Error Handling” in a conversation. Let me give a few examples to illustrate what I mean. If we were standing in a room full of people and I were to ask “what is his name?” you would ask a clarifying questions “who?” From there I would clarify what I mean by “his” and you would be able to repeat the original question to yourself and give an appropriate answer and then we could continue our conversation without a problem. This is a perfect example of “Error Handling” while talking, but it can be done on the fly and not stop the conversation. You are so accustomed to this idea of on the fly clarification you don’t even realize how amazing of a tool it really is.
If I were to ask a computer the same question the conversation would a little like this.

<pre>Me: what is his name?
Computer: his?
Me: *points to guy* yeah him.
Computer: what about him?
Me: That guy, whats his name…
Computer: what guy?
Me: *points* THAT GUY! What is his name!?
Computer: Jerry</pre>

This may seem like an over exaggeration but it really isn’t. The issue that we ran into is that it wasn’t until the last statement that I did both, clarify who the subject of the question was and ask the question at the same time. The problem we have here is that the computer has no memory of past questions and needs needs us to be explicit all at the same time. Without all necessary info at the time to the inquiry it is seen as invalid and then it promptly forgets the question was even asked. Computers are are typically devoid of context or if it has a system of context build in it usually does not line up with what you think the context should be. In programming we often have to explicitly set the context so the program knows what values or variables we are trying to reference.

If you are not accustomed to this kind of blunt response it can feel jarring as the “conversation” just abruptly ended with a program failing error, and if you are not accustomed to reading errors it can feel like the computer is giving you no indication of what went wrong, or some weird cryptic response if you do read the error. It is 100% on you to recognize that your statement or question is unclear and needs clarifying, but identifying why your statement was poor can be hard. As a human we can get a correction in grammar and an answer at the same time. You have probably had the situation where you misspoke or used a wrong name and the person you are talking to will use the context of the situation and go off what you mean, not what you are saying. They may even correct you quickly, or ask for clarification like, “you mean Jill right? She is over there.”

The computer however will give you no such leeway, no clarification, and no on the fly correction. In computer programming we refer to the grammar of programming as syntax, and with improper syntax no communication can be had, unlike with humans where we can get the gist of what is being said.

## Variable names and values

To make things even more difficult there is a huge disconnect between the definition of the words on the screen are and their values, or what they represent. That statement was a confusing and vague so let's dig into what is meant. If I create a variable called age, we as a human we have such a connection to the meaning and definition of what age means it can be near impossible to see that word as anything else. There is however no promise or assurance that the variable age even holds a number inside of it. As the computer understands it, it is just a random assortment of characters that has no meaning. New programmers often make this assumption and association, often without even realizing it, that the letters ‘a’ ‘g’ and ‘e’ being arranged in that order is something that has meaning to the computer, but it does not. By giving something a name it is only natural for us to assume that the value inside of the variable matches what the name is but that is nowhere near the truth.

Having the value inside the variable line up with the definition is only true if we are consistent as a programer and make it make it that way. The computer does not care what we call anything, it is going to execute our instructions exactly as instructed, even if the instructions don’t make “sense”. Computers are devoid of “sense” so it falls to us to decide what “sense” means. On top of all that we have so much pre-existing biases towards words and the meaning associated to them that we have a hard time reading and understanding ‘age’ as anything other than the definition. To the computer the variable ‘age’ is literally just a random collection of characters and the order of them has no meaning and it won’t check your value against the name of the variable to see if it ‘makes sense’. That connection is only meaningful to the programmer. Learning to mentally disconnect that the words we see have no bearing on the value tied the variable name we choose to use. Age could just as easily store a paragraph of text, or a list of all the countries capitals in europe.

So then why give variables names that mean anything? Why not just slap the keyboard every time we make a variable and just use the random assortment of characters that come out. Because it is necessary to name them. But wait I hear you yelling at me through the pages, didn’t you literally just spend the last page saying the names are meaningless. Yes, I did. But the necessity is not for the computer, it is for the programmer. We write code the way we do not for the computer, but for ourselves and the other programers who will read our code. With that understanding then you will start to realize that we are literally having a conversation with 4 people all at the same time, one: the computer, two: our current self, three: our future self, four: other programmers.

It may seem odd at first glance to include ourselves on that list twice but any programmer who has ever gone back to an old project knows that that code can be as foreign to them as someone’ elses code. A fun anecdote to illustrate my point is this programming joke, “When I wrote this code only god and I knew what it did. Now only god knows.” There is a phrase that pops up in programming called, “mind mapping” and it happens when the programmer is quickly making variable names that don’t communicate what the value should be. Examples of this is naming variables things like, ‘x’ or ‘value’ or ‘things’. The problem with naming variables this way is that it is extremely unclear what you are attempting to do in your given code block. If you are having a hard time following your code now, then there is no way in hell you will be able to quickly decipher it after a weekend.

You are also writing code in such a way to communicate with other programmers. There is another anecdote is, “Write your code with the assumption that the next guy to maintain it an ax murder who knows where you live.” This may seem like an over exaggeration but it can be one of the most frustrating experiences trying to reason about someone else's code if the names of things don’t make any sense. In this situation you are literally trying to enter into the mind of other human and trying to reason about their problem solving approach. Really at the end of the day a big reason we have “coding best practices” is to make our code readable to other programmers.

We are literally making our own language with new definitions for every word as write our code, in my program people can be one thing, but in another way it can be completely different.

Every word we see in a program must learn to be looked at with skepticism because we can never be absolutely certain that the words we see are relate to the value tied to the name of the variable. So we have this dissonance that the names of things are both widely important and meaningless at the same time. Most of the reasons why we write programs the way we do has nothing to do the way a computer thinks or works, but it does have meaning for the other programmers  who will read and try in interpret meaning from your code. So we are trying to simultaneously communicate to two different people or ‘Beings” at the same time, one a human, and the other a computer; and both will interpret your code differently. A human sees meaning in the code, we do this because it means we can get this end result, the computer make no such connection and it lifelessly follows the instructions one step at a time with no concept of what came before and what will come next or the meaning it provides the user. There is this dissonance between the words we the programmers choose to represent meaning and the computers total ignorance what the what the words mean, because it doesn’t even have the concept of words, only a collection of characters.

## "Small" errors

Students continue to feel this dissonance widening because it demands and is required that everything be spelt perfectly or suffer the consequences of instant failure. This is demoralizing to a new programmer because we are fighting some deeply carved habits and shortcuts our brain has made over the years (often without even realizing we made those short cuts!) We have learned to read whole words, not read a collection of individual letters and sound it out and remember the meaning. We have amazing pattern recognition and the ability to fill in the blanks, so if two letters are swapped in a word, the human brain has trained itself to quickly read over the word and ignore “small” issues so that we can continue and not get hung up. The computer has no such filter, if the word is “spelt wrong” then it is wrong and does not exist. Notice I put “spelt wrong” in quotes above, this implies the computer has an understanding of the idea of “close to” or even the concept of “spelling.” For us there is a small difference between “animal” and “anamal”, however the computer has no such mechanism and there is no connection between those two and are 100% different in every way. You must learn to destroy your brain’s autocomplete functionality by learning to read “letter by letter” not “word by word” because as the words have no meaning the computer, they have values associated to the variable name. Because of this if you are going to keep any sense of sanity when learning to program you have to learn to remove the phrase, “small error” from your phraseology. “Small errors” paint this mental picture that you can’t even do the simple things like spelling or typing, skill you should have mastered in grade school.These errors are causing such a “Big deal” that you must be bad at coding. That is so far from reality and is a response founded in emotion, not logic. In the cold hard word of computers if you ask is x is equal to y, there is no, “its not but its close”, you will get either a no or yes. There are no shades of grey, only 0 or 1, is and is not.. You must not look at problems in your code with the lense of a human gauging it by size, that can only do one thing, make you feel inadequate or that you are a fraud. I can promise you  even senior programmers make these “small errors,” the only difference between them and you, is they have mastered reading “letter by letter” and have practiced reading the error messages.

To tie this back to the the cover or layer analogy the shell is the words we choose to give meaning to the values, but the computer looks only at the lifeless values behind the names we choose and makes no meaningful connection between the two. There is the mind of the computer that is lifeless and cold,  and our mind that is full of feeling, bias and connection. I often hear students say things like, “it should know,” or “why doesn’t it know” and the problem is those biases literally can’t exist in programming. Perhaps the most damning mindset that carries over to programming is “this should work!” That phrase is filled with so much emotion and ends up not being founded in reality at all. A computer will only follow your instructions so if you are convinced that it should work, the real problem that you have run into is that you lack the communication skills/tools to talk with the computer and establish common ground. We often come to students who are struggling with their code and are at their wits end and I come over and see there hasn’t been any attempt to clarify their communication. Instead what they try is continually rephrasing the question or instructions without a thought of “how can I check how the computer interprets this?” So you must fill both the role of question asker and the clarifier at the same time. All you know is your communication failed so it falls to you to also clarify your own question, often without a real understanding of why your communication was poor. We have lots of tools to clarify our communication but the approach to doing so is so new that it is more rare than common for people to even attempt to truly clarify, often because they are stuck in the mindset of assumptions.

## Good Communication

A good communicator knows that if you are to have a real dialogue with someone who’s opinions that differ from their own the primary goal is to clarify definitions. Both will use the same word but neither of them have the same meaning. If this is not remedied early in the conversation then there is no way to make progress as they are actually both talking about completely different things, both without even realizing it. We run into the same issue when programming without using tools like console.log, this is essentially our way to saying, “I think X means this, what do you think it means?” The only difference here is that we don’t get to negotiate on the definition, you are always wrong, and the computer is always right. And you are forced into changing your definition to match the computers, always. If the computer says the value is not what you expect then it is your responsibility to change the value behind the variable to match what you expect it to be. Coding is the infinite loop of going through that process every few minutes and sometime every few seconds. You must constantly be asking the computer, not yourself, what does this actually mean? This ties back perfectly to the idea talked about above where we say the name of the value has no bearing on what the value actually is in reality. You must learn to always questions the assumptions you are making about the code, and even more challenging is to realize that you are even making assumptions about your code, or “the way you are communicating”

On the subject of assumptions another concept that is hard to wrap the brain around is learning to watch ourselves and the way we interact with the computer, or in other words, to make observations. Every single click you make needs to be observed and remembered. I have often seen students looking through some data that has a lot of nested data inside of it to navigate it requires multiple clicks to get to the data they want. The question I pose them is, “what is the immediate information we are working with?” and they will then click 3 times to that data they want, and then give that answer. They completely ignore that they even used the mouse to navigate through the data and are so focused on what they want,  instead of what they have. This is common and I am not trying to condemn anyone for this but I want to make the point that the average person also has not learned what it means to watch closely and observe their actions and results. They act with no concept of all the actions they performed and which of the many actions actually caused error, and because they don’t see what they did as 4  separate actions it becomes hard to isolate what is happening. Back on the subject of the “size” of an action gives the action more weight or meaning than others, and if an action is sufficiently “small” then it can have no bearing. “All I did was click those buttons!” There is this sub context that because I do so many clicks all day and the action is so commonplace how can you expect me to watch everything after every single click? The annoyance and frustration of this is even further compounded that the new student often does not even know what, “paying attention” or “observing” even looks like. There is so much new information being throw with so much new phrasing it feels impossible to get usable information or meaning from it.

### Additional topics to flush out

To learn coding it is a minimum requirement that a foundation of observation is in place but is never taught or addressed.

Yes, no and mu.

Gumption(motivation) Traps

When would I need to use this? Answer, “when you need to use it”

Science is about experimentation, not “tricks”

Moving a value into a function can suddenly change its name

how do I make (fill in the blank)?

Idea of “resolving data”
 - what is tims first kids name?

what does thorough look like?

consumer vs dev mindset

### Maybe out of scope topics

How do servers work and what is a protocole.

‘A’ !== ‘a’
Obj1 !== obj2
Ob1 === Obj1	‘
