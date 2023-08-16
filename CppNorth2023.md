# **CPPNorth2023**

## July 16-19 2023

It's my second year at CppNorth! Woohoo!! The organizers are great, the venue is great and most importantly, the attendance is great! Such a diverse group of people that all love programming, it's so easy to start a conversation!

Let's go!

## Travel

I chose to go by car, because last year I missed the ending keynote because I had to take my flight back home. This time I wanted to participate in everything, watch everything, and talk to everyone! (almost done!)

I'm travelling from Montréal, so it's a 550KM drive that took 7 hours because the highway 401 got closed to clear out an accident. I'm a speaker this year, so I had the chance to practice my presentation while driving. It took almost the full length of the trip to try to remember it, and practice 'punch lines', I think it was a great exercise. Having the slides in front of us to practice is much different than doing it in our head, and I think it really helped me be more natural in transitions.

Once arrived, I parked the car just beside the venue, got to shower, and then on to the welcome reception!
Got my badge, saluted a couple of people I remembered from last year, and just generally was sooooo excited! The place is packed with C++ legends and great speakers! (Kate Gregory, Ben Deane, Matt Godbolt, Timur Doumler, Jessica Karr, all of them!) Everyone was very easy to talk to and the conversations were a great insight at what we would live for the next 3 days....
![IMG_3213](https://github.com/joblobob/conferences/assets/5419436/ed54a77d-7779-4fd7-9347-f87ffdfb871b)

I find a group of people to get to the 'real' talks.... the after hours meal and beers of course! Conor Hoekstra is a local and helped us find a comfy and quiet place, that our presence quickly made much more lively, hehe. It was very nice to talk to a very diverse group of programmers. We talked about what learned during the day, and of course, I started to spoil some animations and topics from my own talk that is scheduled for Tuesday after the Keynote, oh oh ! More on that soon....

I love the city (because of last year's CppNorth) so I walked to the water front to sit and relax before going to bed. The city lights are great at night!

## Day 1

And so it begins!!!
![IMG_3214](https://github.com/joblobob/conferences/assets/5419436/82aaca0f-9807-4ef3-b261-b50b31b5b3de)

The included breakfast is a welcomed addition by everyone since we can chat a little before going onto the opening keynote! 

Mike Daum gets on stage and starts with the appropriate opening speech, then sets the bar high for Kate Gregory but she absolutely nailed it once again! 

The opening keynote **Steps to Wisdom for C++ Developers** was all about sharing her HUGE experience with us. This is going to be an instant bookmark once it's on Youtube! I loved the segment on 'taking notes' to become the 'expert' and be able to settle arguments using our notes. Also shifting left for people, asking them if they are alright ('Are you ok?'), I was already tired and it really helped understand the mindset behind some code.
Before we can even realize it, the keynote is over and is going to have to be re-watched a couple of times :-)

After a quick coffee break, I stayed in the 'Vanity Fair' room for **Building Interfaces That Are Hard to Use Incorrectly** by Andreas Weis. Very good intro into hardening interfaces, making good use of scoped enums, structs, designated initializers to prevent the misuse of an interface at compile time, great! As always, never use bool or an arbitrary number for a parameter!!

Then it's time for a quick lunch provided by the conference, woohoo!! This gives us more time to talk and meet new people! C++ passionates like me are aplenty here!!

Then hard decisions time! Miro Knejp and Amir Kirsh are on at the same time as one of my favorite speakers... Ben Deane! His **Calendrical C++: std::chrono, History, Mathematics and the Computus** was just perfect on the amount of usable content (std::chrono uses and practicalities) and funny factoids about calculating the date of Easter! So fun! I asked him afterwards if his coding style (auto function return type with trailing named type) was used for alignment or just personal styling preference? (Yeah, I ask weird questions sometimes but I read so much code that I like to know the reasoning behind everyone's tastes, hehe)

And then... some talk by Victor Ciura, his **And Then() Some(T)** take on more functional programming with std::optional<> and better readability. I use this pattern all the time, but I liked his use of a function to hide to 'box opening' in the optional, a great idea that I immediately take away, haha! Although I prefer the 'pipes' notation, I see how it's easier for readability to have the .or_else() notation for error handling, a most common problem for new hires!

Ending the day with **C++ and Safety** by Timur Doumler couldn't have been better. The overview of the 'safety' situation and impressions from the 'industry' gave a nice common ground for the rest of the conference. I heard a lot of people talk about safety in a more logical way afterwards. Timur scored big with a reasonable and mature approach to the compromises we have to do to get safe code. Myths were debunked and steps towards safer coding standards were shown.

After the talks, the conference wasn't over! I was invited to the speaker's dinner! A chance to talk about programming and C++ with the leaders of their fields, the cream of the crop! But after some very good food, I realized that we're all alike, only humans doing our best in this ocean of code chaos. I was happy to hear that 'they' were also intimidated by features like co_routines, and that most of them hadn't used Modules yet. Nor MDSpan! Conor told me that he had never seen anyone as excited about Modules as I am, great! Wait and see until I talk about MDSpan then... they are going to be everywhere in my presentation! 

After the dinner, I got to walk around and sit close to the fountain in a park really close to the hotel, the weather was super nice, which let me sink in my thoughts for rehearsing some parts of my talk...

## Day 2

I had a hard time finding sleep yesterday, I kept thinking about my intro, and my outtro. I woke up very early, and started to remove 2 slides because I thought I would run out of time... I also re-re-re-checked the animations because some of them didn't want to behave yesterday... Pfff..... calm down! I went down for breakfast and a coffee, just one! Because otherwise I'll run around the for the entire talk :-P

But before we start...

Ben Deane's keynote **Optimizing for Change** was super nice, and although I'll have to re-watch it because my mind was sometimes projecting itself in the very near future, I could relate to the parts when he was talking about the *good* kind of laziness, testing is not easy, let's make it as easy to contribute to as possible, and that part about not overthinking for change, but acknowledge that change will in fact come. 

Great pacing, time flew, and it's now already time to prepare for mine! Grabbed some water, plugged in the laptop, got to chat a bit, got micced and....

![IMG_3217](https://github.com/joblobob/conferences/assets/5419436/52180d5b-2904-41e7-98f9-21e35ab5972c)

People started to show up... (Matt Godbolt and Ben Deane front row for me!!! Thanks a lot!!!)

![IMG_3220](https://github.com/joblobob/conferences/assets/5419436/f60d97ac-5540-416b-8f50-3e0cb52680e8)

One more shot for posterity, yes, I was reallllly there!! Doing this!!!

![IMG_3221](https://github.com/joblobob/conferences/assets/5419436/d49d4499-48b3-4e7a-b35b-4be9de8094de)

And off we go!!! **Do you like physics simulations aaaannnd C++? Me too!**

![intro-for-github-trip-report4](https://github.com/joblobob/conferences/assets/5419436/ceadca7f-5593-4ec4-ac1e-639ff7a781dd)

And now we conclude!!! (yeah, the quality looks horrible, I had to compress it a lot for the web!)

![outtro-for-github-trip-report2](https://github.com/joblobob/conferences/assets/5419436/bc7c6d08-1e31-4ac0-acb2-3ca5effb98fa)


That was a blast!! I managed to make the attendance make **'the wave'** to explain the way the fluid's grid and particles are used. The audience was on fire! (might have been the speaker also, hehe)

If you want to learn how to use **Modules, Ranges, MDSpan, parallel execution, format, consteval** aaaaaannnnnnd also see some cool fluid animations along the way, go check this on Youtube! I created this talk to be able to learn the exciting new features of C++23 and at the same time learn about fluid simulations! I always understand features and learn much faster when I can *see* the effects of my changes right away. I never thought that I would be learning so much while creating this presentation! I would have been happy learning and using only modules, but instead, the sum of all the features that I learned changed my way of thinking, structuring and writing code. The data is always the key... If you don't understand the data, you don't understand the problem!

If you want to see to code, go ahead! https://github.com/joblobob/fluid

If you want to see the code commit by commits, bo ahead! https://github.com/joblobob/ray


I also had a lot of good feedback! :-D

One good point is Richard Powell told me that I should have shown an overview of the code at the end, like I did at the beginning to get a better feel for the changes to modules, you are absolutely right, thanks Richard! Also that I could've used Qt's multimedia module for sound generation, hehe, yup! ;-)

Being on the stage of an international C++ conference has always been a dream of mine, now I hope I'll inspire others to share their passion! 

So.... no time for realizing too much what just happened, we're getting lunch at the St-Lawrence market! What a nice place to discover! I missed it last year, how could I! 

Back in time for Conor Hoekstra's **Composition Intuition** talk! A quick but thorough overview (?) of APL, BQN, array languages and combinators. I didn't know much about those languages, and even though they feel quite far from my field, I like the logic behind them. *It's all another level of abstraction*, lovely.

After a little break, **Typical C++, But Why?** by Björn Fahller picked my curiosity. I liked the config struct pattern, now I have a word to describe what I was doing without realizing it! Björn is the author of a strong type library, but he showed us how to prevent errors in our code, with better types, explicit conversions, enum classes and spaceship operator, great stuff! Thank you!

Last talk of the day! I was so excited for my friend Thamara Andrade that was doing her first talk in a C++ conference, like me! I met her during the online editions of CppCon and was delighted to see her coming in Canada for the first time! Her talk was about **Object Lifetime: From Start to Finish**. A *simple* subject at first glance, but immensely deep when looking at the details. I learned a lot about temporary object's lifetime! There are so many corner cases, like how the lifetime extension works and in which situation you will not get the extension you want. Thank you Thamara for coming in Canada, I hope to see you again in person next year!

**Lightning Talks!** There we many great moments during the lightning talks as always, Tony Van Eerd was hosting them with his usual jokes and quotes. I particularly liked Jessica Kerr's and Miro Knejp ones, I think they are going to be instant classics once on YouTube. Also there were volunteers doing lighting talks, how cool! I had so many ideas, but so little time to prepare something, that I decided to do a 'Making of...' of my talk on particles simulation. I was the last speaker, like last year, but I'm not sure I have done enough to explain the kind of work I did. I didn't have any slides, and just showed the ppt structure, the way I did the videos, and where I cheated with *not*-real-time animations :-P 

Anyway, off to get food and talk about C++ over a nice beer in a super chill *terrasse* in Toronto!

## Day 3

Last day of the conference :_(

But not the least, we are having a lot of great content today so let's start! We are treated with a surprise! Bloomberg joins as a Gold sponsor! We're going to have another CppNorth next year, wooooohooooo!!!

**I can write the code. But getting something done is another matter.** Jessica Kerr nailed it! There were so many gems in there, it's the talk that I took the most notes of! She shoed us a couple of examples where getting things done is not just about writing the code. Socializing the change is much more important. I learned about symmathesy (hehe) and open telemetry. Ok here are some notes: 'symmathesy! a learning system' - 'Run new and old and compare' - 'Shadow deploy, but not for everything, mostly critical paths' - 'Free customers for tests, don't bother power users!' - 'Socializing change!' - 'Hack weeks!' - 'Problem definition > problem solving' - 'User expectations!'
A really good subject, that is well aligned with any workplace, I will absolutely show that video to our management and dev teams!

A tool I really should use more is Matt Godbolt's eponymous website. **What’s New in Compiler Explorer?** revealed even more cool features that are really useful. It's fun to see how the project got started, a simple 2 second loop to rebuild a simple function and display the output. Everything about this presentation was great! Go see this!!

Another time for a run to the St-Lawrence market, but this time I grab a burrito to eat at the park close by. I'm so lucky to be here at the same time as a singer! She played a couple of ballades and serenades for the park, how cool is Toronto!
![IMG_3232](https://github.com/joblobob/conferences/assets/5419436/fba8adf7-8bf5-400c-8daa-7e702608e028)


Last talks before the ending keynote, so I go to see **C++ Feature Coroutines, Beginner Friendly** by Andreas Fertig. And wow! I absolutely recommend it to anyone that wants to understand the coroutine's ecosystem! It was a 90 min talk so there was plenty of time to understand each of his examples, and I can finally say that I feel like I do get coroutines! (like Neo, *-I learned Kung-fu!*) co_await gets the input, co_yield calls yield_value() and co_return ends the coroutine, simple! Lambdas can be coroutine! cool! I feel like a lot of eventful data processing will be written using coroutine! I know I'll do now! Thanks Andreas!

It's with a feeling of fulfillment that I go to the ending keynote by Timur Doumler, **Contracts, Testing, and the Pursuit of Well Defined Behaviour**. Contracts seem to be a big feature of C++26, and we get a good overview of what pre conditions and post conditions can do, while also showing different proposed syntax. The future looks bright!

But as soon as it's over, I see most people hanging around. Everyone's talking about their plans for the rest of the week, the things we learned, our highlights. I turn over to **Mike Daum** and **Kate Gregory** to thank them, I tell them that I feel like a better programmer then I was 3 days ago, and I haven't touched a single line of code. Hugs were given, hands were shaken but I didn't want to leave. A lot of people didn't want to leave. I try to find everyone I've met to tell them a few last words before having to pack up....

## Post Conference

Fortunately, a group of enthusiasts gather up in the hotel bar for one last time. We quickly fill up all the space in the bar, and we use all the remaining chairs.
![IMG_3238](https://github.com/joblobob/conferences/assets/5419436/f8ab70ea-fa14-4b26-b541-b66d65c64a38)
![IMG_3239](https://github.com/joblobob/conferences/assets/5419436/75e7eb08-cd4a-48ee-91c4-ff59d688b771)

I sit close to Tony Van Eerd, Amund Desmarais, Alex Dathskovsky, Timur Doumler, Andreas Weis, Conor Hoekstra, Ben Deane, and I feel privileged. It feels like an old group of friends, all talking on subjects they are passionate about. A lot of laughs, smiles and insights. I had some of my stuff with me so I even took notes while we were talking about interview questions, hehe!

Mike told us that there was a big neighbour meeting in the area, so I wanted to see that to let some of the traffic pass before I head back home.
![IMG_3240](https://github.com/joblobob/conferences/assets/5419436/664e050d-fb68-4bd2-b713-130e22d1ce11) 
![IMG_3241](https://github.com/joblobob/conferences/assets/5419436/d08f699d-2fb6-4b8f-9279-07b2e8032551)

Even if I didn't find him there, I felt his presence. He's such a good, profound, caring person. He made all of us so comfortable and welcomed that I felt that the gathering in this park, was in fact exactly like Him. A group of diverse people, all coming together to share, and care, for the singular goal of having a better community. Wow, Thank you. I know that there is a big team with him, so we cannot end this without citing the full board of the special people organizing the CppNorth. **KATE GREGORY, MIKE DAUM, JASON WALTER, DIANA OJEDA ARISTIZABAL, NATALIA LEIBENZON, AMUND DESMARAIS, CHRIS RYAN, KAREN KRUEGER, GAELAN MCMILLAN**, YES YOU DESERVE THE ALL CAPS!

With the last sights of Toronto's traffic behind me, I started to reflect on what had just happened to me. 
7 months ago I started to re-write a JS tutorial to learn C++23 stuff and fluid simulations. Fast forward hundreds of hours of long nights committed to the task, fighting powerpoint and searching for the best way to communicate it, I did *it*. I wanted people to learn while having fun, mission accomplished! One of the volunteers told me that she liked it so much, it made her think about doing fluid simulations too, but most importantly, I inspired her. This is the most rewarding feeling and filled me with joy for the whole drive back to Montréal. 

The content was outstanding, of course, but the real difference with other conferences is the people. **C**aring**P**assionate**P**eople North, is what it should be called. I've heard numerous times this week by other attendees that the setup is perfect to share and talk to everyone, the food is awesome, the venue is classy, the city is great and the content, well, indescribable because you have to be there to understand. The amount of time in-between talks let's us sink in the new information we've just learned, while asking others about their own view of the subject. The balance between the content vs the agenda was perfect. It is mind-blowing, the amount of time, money and efforts that have been put for organizing such a conference, but also the surprises that kept on going for the organizers, but managed to make it feel easy to manage. 

That's when tears of joy started to fill my eyes. I couldn't stop smiling, shouting, and laughing for a good 2 hours. I felt so proud of myself for my first talk, but also for all of the super-cool things I just learned and most importantly all of the awesome people I just met. I've met my programming heroes, legends in the field, and they were all so easy to speak with, always happy to answer my weird questions. This is the kind of event that will grow on me. 

But then the tears of joy got replaced by genuine tears of sadness. I realized that it's going to be a long year before we can do this again. I'm going to miss everything and everyone. I know I can add them to linkedIn or stuff like that, but it's never the same as a real conversation. 

This engaging community changed me forever. Thank you CppNorth!
