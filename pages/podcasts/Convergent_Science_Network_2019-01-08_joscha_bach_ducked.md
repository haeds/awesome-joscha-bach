Unknown 0:04
This is the convergent science network podcast. leading researchers in the domain of neuroscience, brain theory and technology are interviewed by Paul the shore and Tony Prescott.

Unknown 0:22
For sure, for the conversion science network podcast, to get it from colleague, Tony Prescott, and welcome. Joshua was a speaker at the BCD summer school in 2018. Where you give two lectures actually. And in some sense, the old turn around, I think the general question of how we can build an artificial general intelligence. So should this is really, I think, the core concept that your or challenge that you're that you're dealing with, right, so. So what, what's an artificial general intelligence in your mind?

Joscha Bach 0:58
It's a system that has a mind similar to our own and beyond, and suspect that our minds have a particular kind of generality. And, of course, you cannot really know that it's whether we are universal function, approximate errs. But if it turns out that we can build AI, similar advice, that's a strong indication that we are in that class of systems, right. So the whole enterprise is spawned by the question of we are what what is our relationship reality? What's our nature? What is consciousness by things happening to us? What does it mean that something is happening to us, and we realize that psychology has become somewhat unproductive, and philosophy has become even more unproductive as a field because you need to perform experiments that you cannot actually perform in psychology, and that you never performed in philosophy. So we now can build computer models and implement our ideas. And usually our ideas will not work, which will us force us to update our theories in the survey, we can make progress.

Unknown 1:57
So okay, so this is a bit the outlook but but to get there, you saw different stages in which then the search for AI has evolved. And so we go from our, our symbolic AI, there's a sort of version one a first order to an AI that it's more like, the current forms of AI, as we know, where we use different machine learning methods. To actually that can learn functions, right? This was the whole point as far as humans writing them out, we can we can try to learn them. And then we'll jump into into meta learning and meta search, right? So what's the logic of these steps? What's sort of the driving principles that you will see sort of meta search as a tip of the pinnacle,

Joscha Bach 2:45
and there are many ways of looking at this whole issue. I mean, there's a big rift in AI traditionally, between symbolic AI, and everybody else's AI. And before I came to Cambridge, I thought this was because of everybody else, not listening to Marvin Minsky. And after I got to Cambridge and met Marvin Minsky, I felt it was basically the opposite, that Marvin Minsky, who co founded the field with John McCarthy and a few others, realized that in order to understand cognition, we need to teach computers how to think. So we need to build cognitive AI an array. And then he made the decision that this needs to be symbolic. And this was the workhorse, but Minsky was too influential, he started yelling at people that did low level cybernetics, and you will learn him because he thought what they were doing was too simplistic. And then a way he was correct, what they were doing was very simplistic, but it turns out this, the baby can can get to simpler grounding into the kind of operation that our minds are doing. They get started from there, they don't start from symbolic representations, which are so highly abstract that we can only form them after generalizing over our perceptual visitations and operations and so on read these symbolic operations, we get them by making our representation so discreet and low dimensional, that we can apply analytic operators on them doesn't work the other way, or you cannot start with these analytic operators, or at least, this project has not worked out. But what happened is basically the Speak riff because Minsky basically started yelling at people for for doing other things than he did. And this created an area of burn ground around cognitive AI, which was also symbolic AI, and the AI of other people which never bothered to read Piaget anymore. And instead, mostly the neural learning and so on. But what happened in the first half of AI myth, basically, since 1950, until quite recently, was mostly that people thought about, well, when we want to perform the following tasks that requires human intelligence, like playing chess, or parsing natural language. What do we need to do to make that happen? And they came up with a clever algorithm. And then it implemented this algorithm at some point because our computers are very deterministic and scale very well. These algorithms became smarter than people. So I'm born in 1973. There was never point in my life. But I had a chance to play better test than a computer. Let's innovate depressing, right? Even though these algorithms verse so simplistic, that I was able to write an algorithm that would play better chest and myself, right, even though I'm not that good of a programmer, compared to the people that put all this effort in this, but we know that our strategy of playing chess is very different than the ones of the simplistic algorithm, we are able to cope with much more uncertainty in our search space than our program. So we can have much more fuzzy representations that are more perceptual and difficult to grasp what they are about. And to find such ways of navigating very complex, hard to define problem spaces. We cannot enumerate these problems basis directly. But instead, we go to programs that learn how to do this. So this new wave of deep learning is mostly about building systems that learn how to solve a particular kind of problem. And then not general in the sense that we now have systems that can do this for any class of problems. But you basically set up a learning algorithm that learns how to play chess or another learning, learns how to play golf. And we can now use very similar learning algorithms for the same thing. And then this thing's just placed against itself and abstracts over what it sees, and then it outperforms everything humanity has done so far in this particular domain. And the next step might be that you go one step above this, which means we don't write this learning algorithm by hand for this particular task. But we write another algorithm which learns how to find that learning algorithm, which means we go to meta learning, right? And it is tempting to think of our brain not as a learning system, but as a meta learning system, because many domains require very different learning strategies, and we want to conquer them, right. And our brain is, in some sense, a machine that figures out how to learn a new type of thing. And from this perspective, evolution could also be seen as a very slow and unprincipled search for meta learning systems to which we are the first solution that has managed to build computers.

Unknown 7:03
But none, okay, this is fine. Right? Okay, fine. I think that in some sense. I understood the words.

Joscha Bach 7:14
The logic, that gives me hope. But

Unknown 7:16
but but no, no, I could also say, well, that's great, because that's a scheme that just shows that the author of the scheme understands recursion, right? And then you just follow the logic of recursion to say, Ah, so this is another logic I should follow, right? Because there are no one's algorithms Oh, no, it's okay, then I have to cover the space of possible algorithms. But when I have a trick to cover on the space of all algorithms, there might be other spaces we have to go for. So that the process seems to have a meta level, that's actually not so complicated. And indeed, when I was growing up in sort of this transition from symbolic AI, to what the end goal was new AI or M, and what did they AI and artificial life, whatever. That was exactly right. In the dream, we want to use genetic algorithms to find algorithms that can define other algorithms, right? So we're in a loop because this is late 80s. Right. Yeah. So so what should give us any hope that also as a research program, this has any leverage in any traction? Because in some sense, also, when I see the proponents of this approach, going around, or for many years telling me these kinds of stories, there's not necessarily you have this general reflection on on that field. If you don't pose a simple question, okay, but then show me an example that I find impressive, I think we'll miss meals from a scientific perspective. Examples are made a bit poor, right. So so in that sense, for me things like AlphaGo you can see okay, that just means it's not a game that's not interesting, right. So, so why Why should this this program what is logic, actually get us to this promised land? So why should I have any kind of confidence in the track in trajectory that people have already announced for the last 30 years, along which we have not found much represented in the desert?

Joscha Bach 9:11
So you're going over to grumpy AI programmer has gotten bitter on me now, okay. No, I understand, I can relate to

Unknown 9:20
more grumpy scientist who tries to understand the reality he finds himself in. And He does that by trying to get traction on issues like explanation and prediction.

Joscha Bach 9:32
So I'm old enough to remember that we thought for a long time goal is going to be long for long time outside of our reach, because the search space is so fuzzy that we cannot really enumerate it and the situations cannot easily be ordered like chess situation will say my community has gone this is probably very bad and there should be something making up for this if I go down that part of the search tree, and in gold, the all these things are much, much harder to define. So He thought for a long time, this might be out of our reach for maybe even our generation or the foreseeable future. And a system that combines human intelligence with machine intelligence is going to dramatically outperform the whole thing. Now we know if we add human intelligence to this, it's going to get worse, right? There is nothing that a human player right now can add to AlphaGo to make it better. And so I think this is reason to have a slight bit here, but it's a very unprincipled reason. To get to a more principled perspective, I think we need to take a step back and wonder, what is it that a mind is doing right? A mind is some system to make models in the service of regulation for an organism. And to make a model, you need to identify the meaning behind information, but what we get from the world is information, certain patterns, we try to predict other patterns visit, and the meaning of information is its relationship to change and other information. And that is what we call a model. So when you have a blip on your retina, the meaning of that blip is the relationship that you discover to other blips on your retina at the same point, or at different points in time, right. And these models that you can come up with, describe, for instance, the movement of people in a three dimensional space where they exchange ideas and have an economy and all these wonderful things. And they are a simulation generated in your brain to explain and predict the patterns on your retina, you will not be able to do this, for all the patterns, some of them are just going to remain blips because you don't find a relationship. So we call those noise and a lot of noise in our retina, right. So when we try to make sense of our universe, we get a few samples of bits at different points in time, we try to relate them by making these models, this is the task of our mind. So we already know, our mind is a function approximator. And we also roughly know, over how many data our mind is going to approximate you know, how many seconds VR live, we know roughly the frequency at which humans operate, we know the, our surface that basically is our systemic interface to the environment that we operate in, and so on. So we have a rough idea of the ballpark in which we operate. And over which you make models

Unknown 12:06
describing just one side of the elephant, because now you're pulling at the tail. And you say, Okay, we need to compress information, right. That's what we build models with, on the other end, the other side of the of the elephant, we have also the need to generate action, to control physical systems in real time, in the service of regulation, that's fine. But that doesn't necessarily satisfied his whole idea of compression Amala building, because now I have to sort of flip it around and sort of again, decompress into a real world that is that is open. Right? You cannot necessarily capture all of that with the idea of modeling and data compression.

Joscha Bach 12:49
I'm not quite sure In which sense you would ever decompress. And because I don't interact this some decompressed world, I'm interacting this the world of my model that the simulation was a dream generated in my neocortex. This is subjectively the world that inhabit, I'm never going to decompress you back into a part of the evolving state vector of the universe into some weird quantum graph. Instead, I always interact with you as a person that has intentions that has a certain geometry and so on. So I'm always interacting with this data compression model. Yes, but

Unknown 13:20
decompression what I mean, you interact with me, I'm going to tell you things that you cannot fully predict. Right? I might say wrapped around. Okay, so now there's a decompression sense of the way you interact with the world, the world is open. So the world noggin generates highly variable feedback to you. Yeah, right. So you're compressing the compressed states in the end get mapped to an action that you bring back to the world. Now the world is going to open. Right, so now again, you face a set of possibilities collapse into one decimal you're supposed to write. And then again, you go back into your compression bolt, and you generate your next section. Yeah. So that's more what I meant with the decompression part of it, that your your your action is like this finger in his massive state space that generates Yeah,

Joscha Bach 14:09
but basically, what I do is I try to filter as many invariances from the world as I can, and put them into a model. And everything else is the state of that model in as far as it is relevant, right? So I have a space of relatively few latent variables, just a few million of them right, or a few billion of them in which I operate. And I have a much much larger static set of constraints that captures the loss of perspective and biology and intuitive physics and so on to make the world interpretable. So I can actually regulate my needs in a better way than if raw cannabis, but

Unknown 14:43
you're not necessarily saying anything, that you knock me off my chair, right. This is wrong.

Joscha Bach 14:49
That would surprise me.

Unknown 14:53
But, but this is a very reasonable way, right to summarize what a mind or an embodied mind will do.

Joscha Bach 15:01
Should I apologize for making suggesting a reasonable way? I suspect that we have even converged in many of our perspectives on our intuitions on how to get there. I don't know if our intuitions disagree on how long this is going to take, and what is going to be necessary to get there. But it would be very surprising. If we wouldn't be getting there, even beyond our lifetimes.

Unknown 15:24
I think I can understand where you're coming from in this sort of first, second, third, or the fourth order system. But people have been thinking about this for a long time. And whether it's can be so neat is I mean, it's kind of like a physicist view of how things could possibly be, and you're a psychologist, so it surprises me, you take such a sort of a neat taxonomy of of intelligent systems.

Joscha Bach 15:51
Oh, no, I'm just trying to tell a story that fits into a podcast.

Unknown 15:58
Intelligence is function approximation, this is a huge statement in itself. I mean, that's one of the things is it. It's the ability to act appropriately in real time. And that may not require function approximate. The reason

Joscha Bach 16:12
why I don't do this, why I don't lump this in this regulation is because we observe that there are people that are very bad at acting appropriately, and they might nevertheless be extremely intelligent. So I would distinguish the ability, it from reaching your goals, which we could call smartness, from intelligence is the ability to make models or wisdom, which is the ability to pick the right goals that we find very often when we observe people is that excessive intelligence is often a prosthesis that our brain is using to compensate for the lack of being smart, or being wise.

Unknown 16:50
Yeah. Okay. So we can, we can have this particular definition of intelligence, which maybe captures one aspect of humanity, yes, about minds are doing, whether it works, or whether it can capture general intelligence, you know, in terms of all the different kinds of intelligences that humans have, sort of in a Howard Gardner sense that there might be multiple kinds of intelligence, maybe they're not all function approximation. But then, if we look at what learning is, what learning to learn is what searching for the optimal theory of function discovery is, these aren't necessarily as, as you say, a recursive thing of applying the same idea multiple times to itself, that could be completely different. Oh, I fully agree. And so what we have in the current wave of AI is basically the optimization of inductive learning systems. But you know, we still need deductive systems, we need to discover abductive learning systems which reason beyond the data which no current deep learning system can do. But humans can do. And we don't know how humans do that. And we need to also automate the process of scientific discovery. And we have no idea how to do that either. So

Joscha Bach 18:07
you might be too bold in your statements here. You know, yes, I don't remember when deep learning started. When deep learning came up, basically, everybody around me, including myself, started to make statements about what deep learning cannot do. And time and again, we had to revise our statements about what it can and cannot do. And it's surprising thing to me. Still, it's surprising, because you have these essentially mostly feed forward networks with very limited recurrence, because we cannot train this very well, very few lateral links, because we cannot deal with those very well. And still, at some point, Google threw away everything that computer linguists have done over decades in terms of machine translation and replace the whole thing with an end to end train, but actively damn feed forward network. And there is the thing, you know, if if you think about your neural network, your feed forward network, not as representing a brain something like a neural architecture with all these recurrent connections, but it's a function that correlates adjacent brain states is not quite clear what it cannot do, right. The question is, do we find a sufficiently developed defined loss function and an algorithm that converges quickly enough on a solution to that particular function? So when you want to find an algorithm that discovers truths in, in a particular mathematical domain, for instance, by discovering new serums it's not entirely clear to me that we can prove that our current deep learning approaches cannot get there. No

Unknown 19:40
way. You're going too quickly here because if you take this example of machine translation by Google, right, we have to I think really thing goes about epistemic autonomy of the system. Right? The old the old symbol round and troubling. Why Why could go get away with throwing away a A lot of the traditional methods is they could also capitalize on the collective knowledge of a huge amount of humans, who would just add exceptions and new information that lookup tables they could build. Right? So by virtue of that the system actually worked. So that means epistemic ly, it was not autonomous lessons, it didn't solve the problem of translation, as biological systems as ourselves would perform that, of course, they found a workaround. Yes. We just been really shrewd, if you want and that smart, and the way they capitalized on human knowledge is fantastic, great. No, but it doesn't mean that they really solved the actual challenge. They found a workaround.

Joscha Bach 20:44
Of course, the question is, what is the challenge in terms of providing machine translation? If you

Unknown 20:50
know, we were talking about the mind, right. And your question is,

Joscha Bach 20:53
it's not a mind? I'm not a nobody says, All. Right. So yeah, it keeps surprising me, it keeps surprising me in the sense that I thought, Oh, it does more than I thought it will do selectively simplistic methods, because most of them be discovered in the 1980s already. Yeah.

Unknown 21:08
And I think what I'm saying is, certainly people like me, you know, I had the faith, I thought these systems would be super powerful once we scaled computing, you know, did my PhD in reinforcement learning, you know, it took me a week to train a little bug to move around and avoid obstacles. And now it would take off a minute or less, maybe. So this, you can look at the algorithm and know that it's a super powerful algorithm that given the right, you know, sort of AlphaGo is probably an amazing design of network. And but you can see that reinforcement learning in itself is such a powerful algorithm, given a state space that so easily defined as go in order to be able to do well in that. So the

Joscha Bach 21:55
things where I disagree with you as I do think it's possible, but it's actually very likely that the current class of algorithms is not going to carry us all the way. And if we need to invent new classes, yes. But the thing where we disagree is, I cannot even prove that one. And I haven't seen a proof that they cannot do this. So as long as there is no proof for this, if you don't know that imitation

Unknown 22:20
is yourself, then you're saying that that you don't need to go to

Joscha Bach 22:23
No, I'm just saying that word in uncertainty, or to the negative, where it's not even that one is justified. We don't know that. I think we don't know how far the current approaches can carry us.

Unknown 22:36
Well, it's very difficult to find a proof for for the, the absence of something. So you're asking the impossible.

Joscha Bach 22:42
So no, well, you could say there are certain class of algorithms that you can, in principle, not learn if you could find a proof to show, okay, when Tony says something, we can not just get the thing to discover new theories of is this. This is pretty bold statement. And you could probably formalize this. And then I could ask Tony, what increases your what is the evidence for that claim? Except vague intuition?

Unknown 23:08
Well, no, I think scientific discovery requires interaction with the world. And that's what makes scientific discovery different. You can't just you need to go out there. And you need to make observations. And you don't know a priori what to observe. None of these things neural networks can do at the moment. And people have tried to automate that. And I think you

Unknown 23:29
guys are much too cozy there to get. I don't understand why you guys are not in a state of panic over this challenge of epistemic autonomy. Because this is actually I wrote a few papers in the 90s. Already on that analyzing that talk. Right? that talk was one of the big breakthrough moments in connectionism. Because Oh, wow, we can map words to pronunciation features. And oh, wow, we have emergent vowels and consonants in terms of the pronunciation features. But the thing is, if you analyzed the data, that was the patterns that were presented in that talk already encoded this distinct separation through vowels and consonants. So there was no magic there. That's everything we will how humans have pre coded that data. So that again means it was not epistemic. epistemic ly autonomous, right? And this is the problem. The bumper has gotten all the time, these systems learn fantastically well on human annotated data. Yeah, that's not helping us. So as long as we're not really solving this symbol, grounding problem, we're not making progress. There's one issue. No, I haven't heard an answer for that yet. From from your side of the table. You know, it's a round table, but okay. And secondly, you both seem to be very comfortable with his notion of intelligence. Which which, which worries me because intelligence is actually a very circumspect construct that McCarthy just pulled out of out of his hat in some sense of the 50s. You just give the field a name, because they have computers and computers and who sort of imitates things that you could do like problem solving and then to give it a name. So he goes back to construct to go back to Golden, late 19th century and being there that were actually used to make distinguished to distinguish me classes and races. That's where the essence hasn't had the otology to it. And which was also exemplified, but we now as well, just with my test measures, and even Adrian Owen a few years ago, put humans in the scanner and have to do the Ravens Progressive Matrices test for intelligence, he saw that actually depends on the specific item, you work on different parts of the brain get involved. So there's not even one underlying process, right, so So how can you guys even in this in the search for synthetic mind, we be so comfortable with this notion of intelligence? I think it's leading us astray. It's not helping. And the second thing is, even when it says on that, are you going to solve this epistemic autonomy problem?

Joscha Bach 25:50
So, first of all, I don't think that intelligence is such a problematic concept as to think that the notion of being able to make models is a very useful notion to understand what our minds are doing. And it's also clear that this is sometimes domain dependent. So we have certain priors, in which areas we pay attention between means, where we put more resources into learning new models. And this leads to different performance or differences in people's innate differences in talent is probably differences in inattention to some degree, there are certain things that we as organisms are paid for, to pay attention to right paying attention, for instance, to facial expressions, or to the emotional states of others, and so on. And this will create different degrees of resolution our minds most respect to these domains, and bias as an assert a certain way, that there's this other thing, what animates us to do certain things are the needs of the organism that are in implementing some kind of reward function that gives us pleasure and pain, to reward us for doing certain things or punish us for doing other things. And then anticipated pleasure and pain, which make us go into certain areas of the behavior space or via avoid certain areas of the behavior space in advance, and event, lead eventually lead us to generate models about the structure of that behavioral space in the policy space in which we operate. And so if you will ever build a robot that plays soccer, it's not very difficult to make a robot want to go to the ball in some emergent sense, right. And if you have imagined that your robot has many more needs, that it needs to satisfy like, we traveling this battery from time to time, avoiding injuries, and maybe optic or getting repairs from time to time when the inventories have accumulated to such a point that they impair its function. So you could imagine that this thing needs to satisfy a number of needs and achieve some kind of dynamic homeostasis about them. And suddenly, you are have a system with some motivational system that gives relevance to what needs to do. And then when you think about your mind is some general function approximator that has, so to speak a bit of cortical real estate that it can use to model certain domains of its environment with more or less resolution, then what you should be doing as whenever you have a problem that you cannot solve with your existing feedback loops, you need to create secondary tertiary feedback loops, and some point is not enough. So you need to spawn a completely computational model of that domain. So this is probably what our neocortex is doing, it creates a computational model of a domain. So it can regulate this domain, because you cannot regulate what you don't understand that actually is called regulator theory. If you build a regulator, then the structure that it implements needs to be isomorphic, to the system that regulates and the world that we are in is a very complex, three dimensional dynamic, physical world. And then it's overlaid, visit very complex, even more complex social world and economical world, and so on, that are in dynamic interactions with each other. And this is what our cortex in some sense is modeling,

Unknown 28:49
but not and then there's a morphic way out. You do abstract, right ankle press, as you said earlier, yeah.

Joscha Bach 28:55
So isomorphic, to what right, there is a certain number that happens there physically, and we already know that what we perceive as being the world is very, very different from that. So for instance, there is no sound in the world, there are the air molecules, at least been seen from some perspective, right? They're actually also not air molecules. But from some frame of reference, you can describe this stuff as air molecules and their electromagnetic forces between them that give waves of traveling pressure, and then there's some Fourier transform happening in our cochlea that measures the energy of these weights in different frequency ranges. And this gets sent in the neocortex. And now the new cortex does its very best to predict the structure of these patterns is the result, some interesting geometric calculation that our neocortex approximates. And these geometric patterns be interpreted as sound, right? And then they organize the sound into things like phonemes, or into musical patterns and so on.

Unknown 29:52
That's fine, but none of what you said necessitates the use of the word intelligence right, because now you've talked more about the induction ability to build models that have the ability to, to estimate the sources of the of the sensory states that you're exposed to.

Joscha Bach 30:10
I think that before you get to the sources, a lot of other things are happening, this idea that are all the patterns that you perceive go to sources is already a major inference that you're making, right? So you make these inferences, because predictions, right. But what you eventually try to do is you try to predict patterns. And maybe a good metaphor for this is to think of a synthesizer, right synthesizer is have a set arrangement of electronic components that have the property of use, connect them, they go into via oscillations, and produce interesting dynamics. And you have a few knobs that you can use to fiddle until it makes the sound that you want. And imagine you have something like this built from neurons that the brain fiddles at the knobs until it's able to predict the patterns coming in from the cochlea in a few dimensions. And when has done this exhaustively, it moves to the next layer, and then tries to identify the covariance between the knob states between the latent variables that it has discovered, and now uses this to generalize over the previous patterns. And that does this until it's able to fuse the different sensory modalities into a simulation of dynamics three space is moving objects.

Unknown 31:20
It does that in the context of superbly tuned body sort of physical apparatus, which provides all the transducers, which these you know sort of pattern recognizers function approximator, is can work on and already decomposes the world in a way that is well set up in order to be able to make sense of it. So I mean that your notion of function approximation doesn't really cut really stretch to include this aspect of what some people call morphological intelligence.

Joscha Bach 31:51
And totally biased against that. I don't know what and morphological structure

Unknown 31:55
that the, the body makes the challenge of the brain. But I don't like the word telogen. So morphological intelligence, but other people use phrase. But it's certainly true that the body, it makes the challenge for the brain has much simpler, it makes it easier to control walking, because your legs are inverted pendulums. And it makes it easier to do hearing because you're, you're

Joscha Bach 32:17
talking, I've never seen a toddler walking his legs that are absolutely not fine to to walking, your movement of your your geometry of your body is optimized for your adult state. If you're a toddler, it's actually much harder to walk because all the centers of gravity are off and you still managed to do this. In the same sense. You're, you have all these nerves scattered over your skin. If this is not done in a very particular order, your brain is doing the quote current statistics.

Unknown 32:46
Because they're always examples, where just the biomechanics does help you think grasping, right? You just push the center of the hand and grasp. And this is true for any HR. Right? So somebody should push hard enough in the hand it closes like this. So you grasp Trump's just helps you you don't need to plan this.

Joscha Bach 33:06
Oh, yeah, I'm not against the idea that your body is optimizing in the state because it's subject to the same evolutionary constraints. But I wouldn't call this intelligence because your body is not making interesting models. But look,

Unknown 33:19
you and Tony both err on the

Unknown 33:22
side here, because you're saying that, that these models are grounded epistemic ly either false. And I'm saying that what grounds those models is that they interact with the world through a body which is optimized through evolution to do that. So to think about intelligence in this totally abstract way, may not lead you very far. Because the embodiment is critical to the way that human intelligence operates and has evolved. And we may not be able to build this embodies AIS, just by having recursively bootstrapping and learning systems. And people are trying to do that and have been trying to do that for decades. And while I don't see breakthroughs, or imminent breakthroughs, so maybe we need to follow this more biologically grounded approach, which is to say, Let's build embodied AIs. That's that would be my approach, I think, is part of your approach. So

Joscha Bach 34:16
I think it's a super popular approach. People like that approach. Because there's more. But if you

Unknown 34:22
go to, if you go to nips, that's not what they're doing.

Joscha Bach 34:26
Yeah, the stuff that actually works and body mentalism didn't work Historically, it's been a failure. And this new AI stuff came up people have been building lots of robots, like roll Pfeiffer's collaborate a clap Anna Toulon and Zurich. They're very impressive. It's very aesthetic, but it didn't get US intelligence systems. And so I'm of two minds with respect to this. I think that for our human intelligence, there's something that's quite different from what a lot of machine learning is right now doing for instance, when we train a vision system, machine learning, the typical approaches we give it an annotated database was a few million images and asked you to generalize over this. Or we might even give it a non annotated database of video streams and ask you to generalize over this, it's going to figure something out. But it's figuring something out that is slightly different from what we figure out because for instance, it's prone to adversarial examples. So you change a few pixels strategically in the input image. And suddenly, instead of a cat, it sees an ostrich. How is that possible? It's probably because it's mapping this onto a space with a very different structure than the space then that our minds is mapping these things on, which means it gives you similar classification under most circumstances, but not under all circumstances, especially it's not good at dealing with novelty. So if you throw end to end train system, a picture, for instance, of a plane that is crashing into the tarmac, it might recognize Okay, there is a plane and there is a tarmac, and it might figure out oh, there is a plane on the airport. And this is what it's going to tell you, it's going to miss out on the crucial interesting fact that this plane is about to crash, and that thing is going to happen. So how can we do this? And I think it starts in this sense, I agree with this embodiment thesis, we start with our proprioception, when we are born, it's already set up. And we already have made a map of our body surface before we are born. And then we add stuff to that map, we probably add stuff to that local perceptual space. And whenever we see something, we can work based on the assumption, what I'm currently looking at is a window into the same dynamics we space. So everything that I perceptually sense, is a part of the same unified world, right? This is very interesting. So when somebody shows me a picture of a cat, I don't see an isolated set of pixels that allow us to classify, I know, it's a person giving a picture to me of a cat that has been produced by a machine. And at some point was the vendor in different parts of the same reality. This day, I make sense of it. And it's very hard to fake such a universe, right? Just

Unknown 36:57
before we go there, use so I want to challenge you that you are saying, look, a lot of people believe in this sort of embodied view. Mind. I'm explicitly not saying intelligence. And then as then I challenge you said, look, but if you go to nips, no one's doing it and it doesn't work. But the thing is that the people who go to nips, believe work might work for the wrong reasons, because the tools didn't build work, because they rely on massive amounts of human annotated data, which is not the way forward, we know that we'll hit the wall somewhere, right? Well, then you said, Well, look at your throw five rock, the I brought robots to Rule five, just laugh and that one said, no rules work pretty well. Right? And W have to be clear, but doesn't need to work. Right. In our own trajectory. This whole embodied approach has worked extremely well, because we have really explained aspects of the brain. To the extent that we could make testable predictions that were confirmed, to some extent, mills were falsified. So from the perspective of a scientific program, this has been extremely successful to the extent that now we are repairing the brains of stroke patients with it. Right. So it only depends very much on how you define it work. You know, so I think we should be very careful there. And so did we scaled to anything you might want to call Artificial General Intelligence? No, that's that's the future. That's a challenge, right. But I think the situation for embodied models of mind are not that bleak. It just depends what you're looking for. And if you, if you benchmark is what the computer scientists at the big tech tech company is looking for sure, done, we might not be performing really well. But if you're interested in the more scientific program, I think we really have made huge progress, I think, and there is value there. And this might be an alternative approach to these questions, then the more computer engineering and

Joscha Bach 38:55
I think we should also take care to distinguish the practical work from the industries of AI hype, and NTA hype. These are two variable industries that are PETA number of people to produce AI hype or anti AI hype. And there is actual research work. There's also scientific work. And these are slightly different things. And if you look at nips, it's a very diverse thing. But it's largest Burning Man, but sells out in a quarter of the time by now. And there are a very large number of people that do very constrained vision staff or convolution network things. And there's also many, many other people. And the absolute number of people that wanted to do a science of intelligence under the umbrella of AI was always a pretty small minority. And I think the ratio of people that do this is almost unchanged. So the vast majority of people in AI do engineering. They basically built useful applications for data processing systems at the forefront of what we know about how to do clever data processing, and a small subset a few percent of these people are interested actually how the mind works and dedicate their careers to that question. And just because so many people now do AI doesn't mean that these others are not doing it, it's just, it's the same fraction, the absolute numbers are probably larger than ever in history of AI. And still, it's a small subset. And the absolute number of people that are interested in building models of minds and have very similar ideas to you and me with respect to this, that are at nips are probably still a few 100 to a few 1000. People

Unknown 40:26
know? Sure. I think it's really important distinction, right? Okay. So that we got out of the way.

Unknown 40:33
Onto the second slide.

Unknown 40:37
So, you did emphasize that consciousness has a role to play in reaching this synthetic mind, right? So so what's your definition of consciousness? And what's its function? And why is it such an important ingredient is synthesized mind.

Joscha Bach 40:56
So there are several aspects to consciousness. And when we use this word, we often don't make clear what we mean by it, right? That also doesn't help. It's mostly a thing that we know by pointing and not by agreement about what we mean by its particular functionality. So there is something like alertness, the ability to react to stimuli in real time and so on, then there is the ability to learn and update. And the ability to reason about your behavior and reflect on it, there is the ability to attend to stimuli and high level stimuli that we abstract in your brain into mental simulations, and to remember that you attended to them, and to remember that the second order attention to this, so this reflexive consciousness above this excess consciousness. And then last but not least, there is this phenomenal experience, what it feels like to be in a particular situation, right. So maybe we start with this one, this at the core of what it feels like, if you really meditate very, very deeply, you feel that there is at least this is what appears to me like, its fundamental kind of disagreement with the universe at some level. And whenever you perceive a feature, it has a particular meaning with respect to this kind of disagreement, it gives you a particular kind of relevance is like, zero order consciousness. And then as soon as you start conceptualizing objects, before you think about them in terms of reflexive language and so on, you get something like first order consciousness, there, you see a particular thing and you feel I am perceiving a particular thing. And when you go above this thing, then you are in the conceptual level already, that basically, you now start carrying that thing around. Second order, like in a glass bowl, you see this glow of consciousness was every step, it gets a little bit darker, but it's a symbolic manipulation that you perform, to shift that thing around in your mind and do things visit. And when I give a linguistic report about the whole affair to you, then consciousness is a far distant memory to the processes that produces or it's like a moose something that may linguistic upwards is not actually participating in very much. So there is something like a subjective feeling of being conscious and actuality. And the weird thing is that we probably cannot be conscious in actuality, in the sense that a physical system cannot do that. The brain takes a long time to process stimulate. For instance, when I stub my toe probably takes on the order of 700 milliseconds for that to register in my neocortex in my integrated world model. But I have the impression, not only do I perceive this in real time, but I also act on it in real time. Subjectively, I'm not just experiencing this was a nice time delay that can be filtered away with some editing trick in my mind. But it also had the impression, it is me that acts on that stimulus, which happens right now, right here. And that is not possible because the initiation of that action is going probably to take another second until I'm able to catch myself stumbling, and react to that pain and integrate us all into a cohesive story. Which means the story must be instantiated with hindsight. At least, the physics has corrected we live in a mechanical universe, subjectively, I don't live in a mechanical universe. So how do I What sense can I make of this dualism? Subjectively, I live in other universe in which I can react to me stubbing my toe in real time when I experienced that, right,

Unknown 44:22
yeah, the, the thing is that you do but your conscious self doesn't, but your body does. And so there's the others identification with the conscious conscious self, which is problematic. And your body is reacting as quickly as it can. So

Joscha Bach 44:36
in a way it's react as quickly as it can, but also not in real time.

Unknown 44:40
But the problem is, is that that you're identifying with your subjective consciousness, not with the rest of your body. So yes, you say, I can't respond that fast. Yes, you can. If you identify with your toe, and with the you know, the, the reflex systems in your spine, that's as fast as you can respond. But and then those systems report up to you unconscious stream of consciousness that this has happened. Yeah. But I don't know why that's a problem. I mean, scientifically, we know that that's what must be happening. Exactly, exactly. So I mean,

Joscha Bach 45:10
this is, but this is what gives rise to this confusion that people, including many philosophers have about it. Personally, I don't think it's a problem. Yeah. So there's an answer. Right?

Unknown 45:20
Before you before Joshua was making an assumption, which is not declared. Right, and which is relevant for his argument, because you seem to be saying, there's somebody like behavioral time constants, I hit my toe. And now within a certain timeframe, I will have to respond to that or follow my nose, right? And the tide goes on the process is so short, that it's not reasonable to expect that the system that would support consciousness can operate at the same time constant. That seems to be the argument you're making,

Joscha Bach 45:55
yes. But it's not an assumption. It's something that we have established by measurements, we can put electrodes to somebody's car, and we can see how long it takes until the stimulus arrives there. Right. So we know about

Unknown 46:07
the table now. Yeah. But you didn't declare that before. Okay. That's the argument hinges on that you have two processes one fast and slow, and that they cannot be running, they cannot coalesce. So therefore, the slow conscious process by necessity is the story you tell yourself afterwards.

Joscha Bach 46:27
So no, it's it's even worse. The problem is that yeah, that is conscious process, that thing that I perceive as happening, is happening instantaneously. It's happening, in actuality, it's happening here. And now without any delay. It's not even happening fast. It's happening instantaneously. So how is that possible that I act instantaneously on me stubbing my toe in physics does not permit my neurons to transmit signals instantaneously, but does so in timeframes that I should be able to perceive. Right? Because I can distinguish timeframes that are happening at something like half a second or a third of a second.

Unknown 47:07
Instantaneous. I look at entertainers, can you explain that?

Joscha Bach 47:10
So when I act based on when I act on my perceptions, subjectively, and acting on my perceptions in real time? Really, yeah, I see you moving your head, and I'm reacting subjectively, instantaneously on movement of your head. And, of course, the solution to this is this is a story that's been created after the fact to basically make it possible for me to learn from the past interactions that my nervous system has orchestrated with the physical world.

Unknown 47:41
Well, maybe that's also another tricky bit of subjectivity. I don't experience it like that. Because I, I live according to my own theory, which is real time and subconscious. And because experience is delayed, right, I don't I don't experience stubbing my toe in real time. I don't not at

Joscha Bach 48:01
all. Maybe you're not conscious. That definitely possible.

Unknown 48:05
We can exclude adoption. But it seems

Unknown 48:10
Why are we so surprised the folk psychology is wrong? When and we grew up being

Joscha Bach 48:15
but it's not folk psychology, I'm talking about my subjective experience. That'd be your

Unknown 48:19
subjective experience is folk psychology, because that's what you've been told. As soon as you were able to listen, these were explanations.

Joscha Bach 48:27
Nobody talked to me about consciousness when it was about you to grow up.

Unknown 48:32
They've talked to you about the fact that you could control your toe and that if you stubbed out

Joscha Bach 48:37
my parents mostly stayed out of maybe I learned to work for my tour by myself,

Unknown 48:42
doesn't matter. You may have evolved your own folk psychology. But maybe fortunately, you grew up into a scientist, and then you discovered that it was largely wrong. So now that we've discovered that folk psychology is wrong, we can just put it to one side and not worry about

Joscha Bach 48:56
no. This seems like what I have to explain is the set of phenomena that is subjectively available to me. So the reason that people get confused about consciousness is that they have a particular kind of experience. And that experience seems to conflict with what is scientifically possible, which is why people like to normally get extremely come up with very expensive theories. Right. I mean, epistemologically and ontologically very expensive theories. That is the reason why they're willing to carry that burden is because they're not going to give up on what you saw the rest of the call folk psychology.

Unknown 49:32
Well, I think that's absolutely true, but I think they should. Oh, I agree.

Unknown 49:38
Julio ends up being a pen psychist. Yeah, okay, that depends on who's folk psychology you're buying, but okay. It truly gave up mine. But the thing is, I think you've tried to wiggle yourself out of a chronometer, Joshua, and I would like to remind you of the problem, which is I really believe that I remember that you said Earlier that comes experience of stubbing your toe was a story you told yourself afterwards. In that example Dainius Yes. And then I was trying to help you. But of course thinking I was doing the wrong thing for the right reason, right, though maybe it was all wrong. By saying by just trying to look them up, we are making this fundamental assumption that we have a dual process system that have different time constants.

Joscha Bach 50:24
Oh, no, that's not by, by SE. There is something else going on. Okay. There is this traditional perspective of idealism, right? idealist philosophy basically makes the statement that we don't live in a physical world, but that we live in a dream in a magical, essentially one in which symbolic interactions are possible, instead of just mechanical interactions that need to be performed on some fundamental causally closed physical level, let's say some quantum mechanical level or below that. And in this symbolic universe, certain things are possible that our minds exist. And the dollars perspective says that these two domains this physical domain of objects moving in space, or information flowing in some kind of computational graph of the universe, and this mental domain, where our mental phenomena take place, somehow needs to need to coexist. And what I want to suggest that this is, in some sense, the case, we are literally living in a dream that is dreamt by a mind on a higher plane of existence. And the physical universe is that higher plane of existence and the mind that dreams as is generated by the brain of a primate. So in some sense, these perspectives are complimentary, subjectively, and live in a dream world, the same circuits that produce a dream at night produce a dream during the day to track and predict my sensory data, and the properties of the

Unknown 51:48
ModelBuilder compression.

Joscha Bach 51:50
So the end, the difficulty that comes up is, which is the reason why people like Tononi are so confused or why strong event somebody mentalism has such an appeal, which basically the there is a different kind of embodiment, which doesn't say, let's use robots, because they're so useful to ground your perception, which I totally agree with, right? If you are a mind, you should be able to beat use your body. That's a useful benchmark. And it's a very good source of data. If you're connected to a physical universe, there's a lot of interesting variants and environments in it, right? And if you have some regulation goals that are maybe give them from an organism that make you interested in in cool stuff, right? So you build interesting models and interesting policies. I agree with that perspective. But there is a deeper perspective, which says, basically, some people get up from their meditation and realize, Oh, my God, this is so awesome. This cannot be explained by a mere computational process. There needs to be something going on that is more than mechanical. And where does this stuff come from? Because my brain is just performing some boring computations, probabilistic excitations, in these glorified fat cells that we use for processing information that we call neurons. Right? So what is that thing and for some people that suggests, oh, maybe it's the touch of the mystical reality substance, maybe physical reality, that's more than computation. And the mind is not something that just happens in the brain. But it's the result of some magical morphic resonance between your body and your environment. By getting in touch with the mystical reality of substance. You have this emergent and possibly extended mind that spreads outside into this universe that you're perceiving. And what you don't realize is that the universe that you're perceiving is not some direct access realist universe, but it's a dream generated inside of your neocortex. It's a simulation. It's a VR.

Unknown 53:38
Sorry, I you you endorsing the idealist perspective.

Joscha Bach 53:41
No, I'm basically saying we should interpret the idealist perspective as something that in some senses to you can perform magic, you can learn how to do to levitate, you can learn how to look into the future. But you do this basically, by editing your memories, by changing the way you produce. Your neocortex produces these models and you pay a price for this because you cannot break the bank because outside that's a mechanical universe.

Unknown 54:06
Because you already declared this earlier, where you say well, we by necessity, we build models, right? And as soon as you start to rely on these models to inform your actions you live in a virtual world it's virtual. So that's and everything else is just a consequence of that

Unknown 54:22
being that that virtual and that's fine. The mind lives in the physical body which is in a physical world yes,

Unknown 54:29
that's the interface so but there's one thing that magic

Joscha Bach 54:33
there's no magic there's no conspiracy it's good to use.

Unknown 54:39
Our which are the mind build models and as a result, you virtualized but now you do you say you add to the physical world yet additional words is the higher plane why why is it necessary? Why is the physical world now? The higher plane why Let's not just rebuild models that are informed by the external world, but we abstract away from it. And those inform our actions. Oh, it's

Joscha Bach 55:09
because the world, the world that I live in, subjectively is VR, right? Similar to Minecraft, it's a computer game generated in my brain, right? And the physical world is the parent universe to this in this sense, it's the higher plane of existence, substrate play, you seem

Unknown 55:24
to suggest that dualism of life because in Tony's because early, you were sympathetic, what is it? What is your mind? And that actually builds a very solid interface with you from the beginning that cannot be decoupled, since it's physically instantiated, so it's an embodied mind is by necessity, always one with the physical world.

Joscha Bach 55:45
No, no, no, you're going to me this is not true. So basically, I think if you would replace your neurons with something that is functionally equivalent, and performs the same computations, you could still be living in the same car. Look,

Unknown 56:01
if I allow you to make all these assumptions clusion might be accepted. But I think these assumptions are extremely strong. And it will, you will not succeed in living up to them till the end of your career.

Joscha Bach 56:13
I know you're just you're not a functionalist, that's all and you maybe I cannot change your mind, I can try. But for the same reason that you can change the CPU on your computer to something that is functionally equivalent, in the sense that it's able to run the same software on it, you can run the same program on your computer, right?

Unknown 56:30
There wasn't the argument? Or does you describe the external world as a parallel universe, right? That's the word you use

Joscha Bach 56:37
No, as a different universe. I didn't say parallel.

Unknown 56:39
Well, it's not separate, it couldn't separate. No, it's,

Joscha Bach 56:43
it's a different frame of reference. So in the same sense, as for instance, the software that runs on your phone does not exist in the same physical universe as the phone itself, because it's a frame of reference that you're using to describe it, which doesn't make sense in that other universe.

Unknown 57:00
I think it's a shortcut you're making, right? Because also all the words you pronounce now, there's other products of this biologically instantiate a Turing machine that you believe you are, right, resonate back to you, as you speak them through the real world, right? Even mobile will hit your skin, human, you just stimulate. So the embodiment is implicitly there. Also SSS as an integral component of these models in which you realize that decoupled, like our nodes are independent from each other. Now,

Joscha Bach 57:34
I remember from reading your paper, that you are basically an identity theorist. Right. And I don't think that's a useful way of conceptualizing that space, because I am not a monkey. And I'm not that body. And the side effect of the regulation is of the monkey, I'm, I'm the result of that mind. And the story that the mind tells itself, there are people

Unknown 57:56
that I project your story.

Unknown 58:03
You're constructing an AI, why not construct an item that identifies with the physical self, as much as with the mental side.

Joscha Bach 58:09
Because this identification doesn't hold I realized that I'm when I think about what this physical system is that it really don't get behind it, I have difficulty to identify with a subset of the evolution of the state vector of the universe. Because this is not what I perceive myself to be. What I perceive myself to be, is very similar to a character and a novel that is told in a very rich, perceptual language. And this character in this novel is something that the brain uses to tell itself its own story in a way. But it's not the story of a brain, or it's not the story of a primate or an organism or a bunch of cells or a bunch of particles. It's something else entirely, right? Because the thing is, a brain is a physical system, it cannot feel anything, it cannot experience anything, neurons can't experience anything. But it would be very useful for the brain to know what it would be like, if it was somebody who could experience something, the what the brain is doing, it creates this VR of a world. And then business we are it creates a person a simulacrum of a person. And that does seem to that the monochrome that is halfway to assimilation. Yes. So basically, as an author of that cream that we're in, that's the system, set of processes that generate your VR, and that create your personal self, your model of what you think you are. And then it does things to that model, DEC expectations and the result of past actions, and then witnesses the reactions of that simulation and uses it for learning

Unknown 59:40
that you're identifying with this thing, which which is flickering on and off. Because this simulation itself isn't going on all the time. Most of the time you're operating in the real world, your body's just doing things.

Joscha Bach 59:53
So the good thing is my brain gives that thing access to the language to enter and here I am and talk to you

Joscha Bach 1:00:00
If you don't have to, it's totally up to me to know, but

Unknown 1:00:12
this is partially partially all reasonable, because because it still fits the same model building story only Now you say, look, but there's other sources of information relate to them what itself COVID chose to build models. But though you have a problem, because you indeed actually explicitly declared that there is something observing the model, right? So so you have this problem? No. Okay, what's your job? What's, how does the observer work? Who cares about you? And why do you do the observer at all,

Joscha Bach 1:00:49
there isn't not an observer in the center or something, looking at it, what is there is a system that takes parameters from that simulation and uses it for learning. So there's a loss function that is generated by producing a virtual character with certain intrinsic tendencies behavioral tendencies. So it's a model of my own internal regulation. And when something happens to me in my virtual simulated world, like my simulated love interest, my partner, decides to desert me because of something that might happen to my mental simulation, then, my brain, in some sense, observes what happens to that character, which doesn't mean it's laying back and watch that movie. It just takes a few kilometers from that thing and uses it for learning. Right?

Unknown 1:01:33
So we'll play that scenario into working memory, and then you're going to experience Yes, scenario.

Joscha Bach 1:01:38
Yes. So it's basically it's simulation simulated world that that syncs to that particular thing, because it's very high level compression of the state vector of the universe in the available data at my systemic interface to say, Okay, you have a partner, and that partner has left you, what do you feel about this?

Unknown 1:01:53
Sure. But it doesn't matter when it's hard to measure or not, right? So, so just yet you have you have a self model. Right? Then you have a model of the world, right? And these, these two models are interact with each other. Yeah. Because now the self model could say, Okay, let's push some parameters in the world model, to create some scenario that will affect me, let's see what kind of states that would give rise to. So it's like a coupling of two models.

Joscha Bach 1:02:19
So you can do this to some extent, right, you can imagine what it would be like if you would get a lot of chocolate in an hour from now, right? And you can evaluate your own reaction to this. But if you're working correctly, you're not allowed to believe that this is going to happen without evidence that it's going to happen, right? Because otherwise you become delusional, which means you are not free to choose the environment that you want to live in. It's very paradoxical thing. Because objectively, you might suffer because the world simulation that you're in does horrible things to you. And you might wish that not to happen, it's actually your brain at that level that does these things to you. And you could go and reprogram that brain to give you paradise. But of course, it might mean that this organism dies, because the model does not give very good predictions. And yet, I think that most of what these Buddhist techniques of fixing your conflict with environment are doing is to reprogram that simulation to get your brain to like you better to like that person better to do nice things, do

Unknown 1:03:19
Buddhist shots, a very simple trick to do that. Because just say you so whole conflict, you don't want anything, you stop wanting stuff. So turned out all your drive systems. And the world is great.

Joscha Bach 1:03:29
There's more than one Buddhist tradition, of course. And once you describe this, this will trump. So this Utrecht tradition is as Catholic, you basically get rid of your needs by stopping to satisfy them. And at some point, this thing realizes I don't need to satisfy them, and then don't look forward to this. So they don't create any discrepancy between target and vote current value anymore, you forget the other thing and you become free. And that's the tantric tradition, which does the opposite, which says basically embrace this maximally, and satisfy all your needs. Except that they're there and explore them and eat your shadow, integrate this all into a thing that actually really works for you.

Unknown 1:04:07
So can I ask the question, so in since I, I've been in Barcelona, I've been having vivid dreams. Now, do you want to share it? I can tell you more later. But when I wake up in the morning, I, I experienced the world in a different way than they experienced my model of the world. In my dream of my model, the world seems very vivid and very real when I'm dreaming it. But then I wake up in the real world. And this is if that is a model of the world that I'm living in now. It's different in some interesting and important qualitative ways from my dream world. So mean, whereas Would you recognize it the distinction there that, that the waking world that I'm in is somehow closer to to maybe this physical world that that that your say you're permanently separated from? So I think You can and certainly the, we've talked a lot about the mind building models, but we, you know, we can also talk about the well being, it's

Joscha Bach 1:05:06
closer in the sense of the ideally, it's predictive of the patterns on your systemic interface. So, at night, you're dissociated from your sensory input, yeah. Which means that your dreams spin freely, and you have no way to invalidate your hypothesis of the world state that you're in. Also, Dream Central, relax your priors, which means your model has more degrees of freedom than it would have

Unknown 1:05:29
us back to grounding. So when I'm awake, when I'm not daydreaming, I'm in a grounded state where I can't believe arbitrary things or, you know, sort of imagine, or see cockroaches climbing off the walls, which I did the other night. I can't do that, because they're just not there. And so the world is grounding me in this awake state? Yes. So this makes me closer to the physical world than I would be if I was entirely living in a mental simulation.

Joscha Bach 1:05:57
Do you think it's a very useful category to say closer? I mean, how close are you to quantum mechanics,

Unknown 1:06:04
but I can believe in with some confidence that my perceptions in, in my everyday state, reflect something about the physical world. So it's not that I'm trapped in my mind, you know,

Unknown 1:06:18
let's not mistake the physical worlds for quantum mechanics are two very different things. No,

Joscha Bach 1:06:23
abandoned mechanics isn't probably not an ontological theory. It's a particular kind of formal theory that allows you to describe

Unknown 1:06:29
the state of Israel, it's not what

Joscha Bach 1:06:31
I wanted to say it's the world is more vivid than quantum mechanics, the physical world is probably some computational system that progresses from state to state in a particular way. And we are an emergent pattern in this, it's physical.

Unknown 1:06:45
Nevertheless, there are things that can't happen in my waking life. Unless they're her Lunesta, unless they're truthless nations. Yes, I mean, very much constrained what I can perceive by the physical world, the idea that even at

Joscha Bach 1:06:58
only hallucinating things that are matching other patterns on your retina, which has predictive values for failure for the parents on your retina. But the things that you're hallucinating are not actually like the things happening on your retina, or there's things that give rise to what happens on your retina, there

Unknown 1:07:13
are interfaces, so I mean, they they are interfaces so that physical events can affect my mind and impact on my mind, you might

Unknown 1:07:19
you might, you might come to interpolation between states of the retina, that as such has never occurred, why not? I don't see the problem. You're very literal in that sense. And then the other the other problem I have. One of the many problems I have, with the one that we'll share with you now, is that you agree with this idea of the embodied your mind, the machine view of mind. But I think we disagree very deeply what machine means was, I think I would even accuse you of only thinking about the machine in terms of a Turing machine. And that's why I think also the word computation is so central for you in the way you describe these phenomena? Well, again, I wouldn't see the Turing machine as just a thought experiment, as in the very ideal, kind of, yeah, it's very too powerful.

Joscha Bach 1:08:12
We need to find it

Unknown 1:08:14
physically doesn't exist. At best, it's approximated. It's so I agree that I know infinity tapes. Exactly. So therefore, it's only a metaphorical machine. Well, I want to talk about flesh advancements in bond machines have really physical existence have an ontology? So So isn't there? Isn't there a bias in a sense an analysis? If we if you implicitly defined define machine as Turing machine? Wouldn't it be more useful? To just consider scenarios where we're less tied to a notion of computation? Say the universe is computation? No, that's the way you can describe it. Okay,

Joscha Bach 1:08:49
let's try to disassemble this. Okay, so, first of all, a machine is not part of the territory, it's part of your map, right? It's a certain part of the language that are used to describe the world. And what I mean by this particular concept in my language is a system that I can describe as a state space, and a transition function that correlates these spaces in deterministic or probabilistic ways. And what's characteristic, usually about machine descriptions that the machine is able to exactly revisit earlier states, so at least conceptually, should be able to do that. So it's a particular

Unknown 1:09:24
already that is problematic. Yes, it is.

Joscha Bach 1:09:26
But this is not our point of contention here. So the important thing is, machine is part of the language that are used to make sense of the world. And mathematics is the set of all languages, right? It's the domain of all possible languages. And then there is a set in which you can make proofs which are the languages that you can formalize a particular way. So you get very interested in those. And most of what we do in mathematics is these formal languages. And it turns out that in these languages, I can specify things that cannot work like paradoxes things or that are conflicting with themselves. Like the set of all sets that don't contain themselves, this cannot be implemented. And for something to exist, it probably needs to be implementable, which means it needs to be realizable in a way that it can produce certain functions that they can perform certain things, right, that it can go from state to state and give rise to states at my interface to my environment. But I cannot know what that is that's in because I only get discern the differences. And even this, I don't know exactly. If I really get the discernible differences that I think I get right. So I had to make very conditional models. And it turns out that mathematics allows me to reason about these conditional models, if I have evidence that my mind is cohesive enough to afford this reasoning, and the good news is, the theory that my mind is cohesive enough to perform mathematics gives very good predictions. It's a very nice theory. So I can do some mathematics that miners can start bootstrapping certain things. And one of the first things I discover that mathematics is covered very late, is that there is a part of mathematics that doesn't have contradictions. And this is constructive mathematics. And the modern name for this is computation. So everything that happens is a computation cannot have a contradiction, your computer can never be in an invalid state, right. And the traditional definitions of computation, which use infinite tapes, and other things don't fully realize that implication. So this gives rise to the girdle problem and the halting problem, and so on, which are features of language specifications that introduce infinity and timelessness, and so on. But in computation, these things disappear. Now, in computation, a few things are different from classical mathematics. For instance, pi is suddenly not a number anymore, it's a function. And it's a function that you cannot actually compute, because nobody knows the last digit of pi. In order to compute the last digit of pi, you would need an infinite amount of energy to produce these computations if you happen to live in a reversible universe like ours, but you need energy to delete bits, right? So you will never know the last digit of pi, if you live in a universe that you can mathematically deduce, to be probably in, right. So we're not talking about reality. As such, what you're talking about is mathematical models of hypothetical worlds. And then we try to discover the class of mathematical models that can explain our observations, and subjectively, if you live in members of that class, but we don't live in the low level members of that class, because our brain is not sufficiently detailed, to simulate them.

Unknown 1:12:32
But is is that you do live in a subset of the class because your mathematical languages and the statement of mathematics is only true for for closed worlds. If the boundary conditions are defined as, as life forms, the power of life is that we act against the second law of thermodynamics is open systems. So there might be aspects of the systems that you cannot capture with a set of mathematical languages that you know advance.

Joscha Bach 1:13:00
I'm not part of that religion, I think that

Unknown 1:13:07
still, you must, you must convince me or I'm trying so you should explain. That's it, you should explain why we believe that this specific language of computation would be susceptible for giving us any kind of traction to deliveries, open systems that we call life.

Joscha Bach 1:13:26
I don't think that life is about open systems, the meaning of life on Earth is the hydrogenation of carbon dioxide, that roughly speaking, life is

Unknown 1:13:37
so meaning. Something that is not

Joscha Bach 1:13:44
only in the sense that people are asking for the meaning of life, right? Of course, there is no meaning, but in the sense that people are asking for the meaning of life, what is it their

Unknown 1:13:53
meaning of life? I was saying your computational language might not be appropriate to understand life, including consciousness and everything in between.

Joscha Bach 1:14:01
Okay, I'm trying to to show you why I think that is the case, of course. Okay. So what life is about itself at some point in 1650? We didn't know what was life in the same sense, as people in 1950, didn't really know what was intelligence, you could point at it, but you didn't know what it structurally functionally was. So in the same way, as I would say, today, and you might disagree that intelligence is the ability to make models, I would say today, most biologists would say this life is cells. A cell is a molecular machine that is able to extract Nick entropy from a very wide range of environments. And it has something built into it that is almost literally a Turing machine, you have this DNA tape is a readwrite head. And this thing implements an operating system on SR which allows the cell to become part of a cellular automaton to

Unknown 1:14:48
create an organism. states of the tech dread, it's actually really good. It's reading it,

Joscha Bach 1:14:53
but it can also write a few things and some of it it also writes in methylation. So we have this epigenome. It's a flash drive. Yes, but They're even neurons seem to be breaking their DNA in particular ways to write something about. But largely, of course, it's around mostly reading from this. And when we also write state, but we do this in additional parts in that cell. So with methylation and changing the layout of the genome, there are basically a few bytes that we can write. And what this can do is it basically measures its state, which is a chemical configuration, based on processes that happen inside of the cell, and processes that chemicals diffuse over the cellular membrane from the environment of the cell, which might also contain other cells. And based on this, the cell is going to go into a new state. And then the process of this is either regulate something or a differentiate itself and another cell, which will behave differently when confronted with the same set of possible states, or it might go into apoptosis, or it might divide itself. So your cell combines an entropy extractor is a state machine differentiation mechanisms that allow them to participate in evolution, and self replicator, in the absence of any of these components, your cell is not going to work, once you have these components, which are incredibly complicated, and probably require an enormous amount of rolls of the cosmic dice, maybe in the same order of magnitude as their available planetary surfaces in a sufficiently isotropic region of the universe, right. And that you won't have that thing like if you have this evolution of things that go up and what life can do. But other damped chemical processes cannot not do, it can produce controlled reactions, right? You are in competition with dumb combustion processes and redox reaction on this planet. And when they start, you usually cannot outperform them, when there's a fire we lose against the fire, the fire is so efficient in closing, like entropy gradients. But there are some things that you can do like we can do photosynthesis, if you are a cell, so you need to add a little bit of energy to harvest more energy in the end. And what happened initially was that the cells, some of them discovered, after a while a way to turn energy from the sun into their own structure by taking carbon dioxide from the atmosphere and changing it into their organic molecules and putting oxygen into the atmosphere. And that did this for a while. And we're successful in this. And from the geological perspective, this was the major oxygenation event, a major event where suddenly you had a lot of free oxygen in the atmosphere,

Unknown 1:17:21
there was a danger, or just agreeing with each other. So Paul said that animals are machines that can physically exist, you're saying that animals are computational entities, but you're defining those in a particular way, such that there can be ones that can exist. So we're largely agreeing. Yeah. So

Joscha Bach 1:17:41
they happen to singularity at this point, that at some point, some cells decided to combine together and form organisms, which made them participate in the multi level selection. And they mostly became carnivores, they started eating other cells.

Unknown 1:17:57
Because the challenge was a somewhat different one. Right?

Joscha Bach 1:18:01
Oh, I'm giving you a computational description. And I'm trying to explain to you at some point by life is not an open system.

Unknown 1:18:06
You don't give me a competition description, because you already admitted that the state machine of the cell is not a Turing machine. It might be sort of No,

Joscha Bach 1:18:13
it's just a finite state machine. It doesn't have to infinite tape, it's less than a Turing machine. Right, exactly. It's not more. The point is, it's ultimate, something different. functional language

Unknown 1:18:22
might give you leverage in describing certain processes. I gave you that another product, which you seem to give us some ontological status. That was my concern. Right? I mean, I think

Joscha Bach 1:18:32
you cannot discuss ontology, what we can discuss is epistemology and metaphysics we can

Unknown 1:18:38
because you seem to give it some exclusive, some exclusive descriptive power, that I want to question a bit more. And that's why I always was challenged you and this notion is your notion of machine, a Turing machine, right, because maybe for thinking about all that, we were talking about mind synthesizing mind and consciousness, there might be properties to that, that go beyond what we can capture easily from this computational perspective,

Joscha Bach 1:19:03
it's basically in the limit, it becomes a Turing machine. If you give it unlimited computational resources, then

Unknown 1:19:12
it's also in a sort of open system, energies flowing across its boundaries, otherwise it would die. So this is just another way of describing what it's doing. So maybe there is a conflict here. But I think in some ways that it reflects your view of the mind as being pure computation and sort of sitting inside this body, which in this physical world with which it could never have any direct contact, because it's in it's purely in the virtual virtual sphere. Whereas I think, Paul, myself have more of a view that the these are really, in the end the same thing. The physical world generates the virtual mind.

Joscha Bach 1:19:55
Oh, basically, what I would say there are, in some sense, the same thing, but they're described what they do. Different language. So basically the language in which you describe mental events, and in which you experience mental events is a language that is different from the language that we use to describe physics. So mental events don't exist in the physical realm. And it's also not all physical events exist on all languages of the physical realm, for instance, retinas doesn't exist at the level of molecules. He doesn't exist. Molecule mental

Unknown 1:20:25
events, like memory states are physical events, right? So this, you know, there's an identity relation. You will know examples of that, right? From where you could go the physiology of play cells or something like this, right? So much more to say, look, fine, you have a computation language and Turing machines are fantastic, Alan Turing is really great. No,

Joscha Bach 1:20:45
no, no, I'm not convinced of this. That is an important distinction, there might be something going on here is not true. So it could be that there are certain, for instance, that I have memories of conscious states that the physical system has actually never been in. From my perspective, this is a conscious state that I inhabited, because I had a memory of having had this in the content, and the focus of my attention, but you might be able to show that my physical system actually was never there. So from my perspective, I have a language that describes something that's subjectively totally valid, they experience that as being valid. But this has got its place in the physical universe,

Unknown 1:21:23
because Because none of your memories ever took place at all reconstructions of, you know, of things and how you would like to think they have no, I

Joscha Bach 1:21:34
think what you're doing in order to sacrifice or to say, if your identity theory, you basically come up with this, there is a notion of folk psychology to invalidate my actual experience.

Unknown 1:21:46
I'm saying that none of you know, my experience

Joscha Bach 1:21:47
is not identical to what happens physically, it has its separate something.

Unknown 1:21:53
The nature of Mallory, because I

Joscha Bach 1:21:55
have experiences that are not consistent with my understanding of physics.

Unknown 1:22:00
That's a very introspective argument. Yes. So basically,

Joscha Bach 1:22:03
I caught myself editing my own memories, and I've had mystical experiences that are probably the result of my brain messing up its own memories, or editing them.

Unknown 1:22:13
And then it's a necessary part of being a physical machine, that you can't go back in the past and relive that experience. All you can do is reconstructed, which is what memory is, and it's always going to be different from the actual,

Joscha Bach 1:22:26
but how do you know that ever experienced that thing?

Unknown 1:22:29
No, would you jump? Yes.

Joscha Bach 1:22:31
So actually recorded it based on the timing, I know that most of the things that I experience cannot physically take place in the way that I experienced them.

Unknown 1:22:43
And that's all fine. So what's the portability of memory?

Joscha Bach 1:22:46
Now, it's just not just the fallibility of memories of

Unknown 1:22:48
creative, it's constructive. you compress you build models, right? So okay, big deal. No problem.

Joscha Bach 1:22:53
It's basically it's no, no, it's something else there is the distinction between a novel and the book. If you look at the book, and you open it, you see characters in it, which are actually does colored parts of the actual categories. Right, right. Yeah, there is no story in that book, except from the perspective of mine who reads it. So and a similar thing happens to me, I don't exist expect from the perspective of mine who generates me, and my own perspective will reflect on what I think I am. And that thing is distinct from this thing. So there is no identity at some level between the novel and the book. He could say there's one because the novel doesn't have a being that is distinct from the from the book and the reader. But that

Unknown 1:23:35
metaphor breaks down. Because your mind is not the story that's in the book. It's a bad metaphor, because the book always assumes there's a reader. So now immediately, you have your wanderlust problem. You don't want to have his Democritus broken if you want to have a scientific theory. So it's, I like the metaphor to give a just the gist of this idea of the promo of natural categories. Fine.

Joscha Bach 1:24:01
That was the idea of that metaphor. So you see that it's such an accepted Yes,

Unknown 1:24:05
you cannot push it too far. And say therefore, also the story I tell myself about who I am me there's a story

Joscha Bach 1:24:14
that you're going to fire in an attempt to save identity theory. No, I don't think it's very elegant. I don't think it works. Well. You should

Unknown 1:24:22
functionalism and

Joscha Bach 1:24:24
you don't have a discrete

Unknown 1:24:26
weakened, strong functionalism you can be in a weekly functionalist and say that you can have mental states in things rather than brains. But there's a lot of constraints around what those sorts of things can be. And, you know, I think that's probably where I would be I don't know if Paul is an identity theorist. I think he probably is at least weekly functionalist because he wants to build robots that can have mental states. So, but then we can discuss what those constraints might be. And I think we're making some progress on that. Whereas you're quite strong functionalist. So you think you could check your mind, maybe you could put it into some very different kinds of computer, and it will still be your mind. Whereas, for me, maybe for Paul, it's instantiated by brain, it's very hard to imagine how it could be instantiated, and other any other kind of device. But I'm still a functionalist, because, you know, in theory, at least, it might be possible. So

Joscha Bach 1:25:24
to take a small step back from this thing, when we describe reality, be not aim for a single narrative, right? What we aim for is the map of all possible theories that could explain the observations to a degree that you can discover them. And then we want to assign confidences in that theory, space, right? To our best knowledge, and meta confidences on why we assign the confidences if we can, right, so this is some some of the process that we're doing. When you have a disagreement, you should be able to understand the perspective of the other one, too, in such a way that we could state it in ways that the other would agree that we stated this correctly. And then you should be able to exchange arguments about the different confidences, right. So for instance, there are people that are a body mentalist in the sense that I think that the mind must be the result of some resonance between body and environment. And brains are only incidentally, present in that whole thing, which is a very strong thing. But there, I've met a number of philosophers that are in that camp. And then there are people which are strong idealist in the sense that I think there is no physical system behind that room. There's nothing that computes God's mind, and I live in God's mind. And this is the lowest level of the thing that exists there, right. And then we have different ideas that for instance, there's some computational irreducibility going on in the brain, that leads to mechanisms that are so intricate, that they produce the mind in a way that cannot be functionally abstracted in something that has fewer moving parts than the brain. And then that's disagreement about how many moving parts we need, right? And this is now starts to get interesting, because now we get in the domain of things that we can possibly empirically test, right? So at this point, you can start maybe identifying interesting disagreements. So I am not okay cannot know whether it's possible to reduce brain into functional units, for instance, at the level of cortical columns before somebody has done this, right. So it's only a hunch that I'm having, and my hunch is currently, then we can probably run a person in less than a terabyte of, of computer memory, if we had the right kinds of algorithms, which be a demand probably don't come from just an upper bound based on the amount of data that you collect in your lifetime, a number of concepts that you can form, the number of computations that a new one can make per second, functional organization and aquatic columns, the kissing number of the cortical columns, and so on, which basically gives you the address space of this

Unknown 1:27:58
versus a guesstimate. Yes, it's all yesterday.

Joscha Bach 1:28:01
It's all a ballpark figure. And when I was at MIT and taught a class about the future of AI, I asked the students in their class to come up with their own estimate. But they think so we before we had discussions about different ways of making that estimate. And the estimates range between something like 200 gigabytes on the low end, and several exabytes on the high end, depending on what people thought the level of granularity is, and the majority clustered around the low end. But of course, this doesn't mean that we know that this is the true answer, right? We will only know about if and when we succeed in doing this, and then we must look at arguments that are not driven by our intuitions or human vanity, because we are that's a special species that cannot be possibly explained by a damn computer.

Unknown 1:28:48
depends a lot on the physical machine in which you're instantiating. Yeah,

Unknown 1:28:53
that's right. And there's not a thing of a memory that, as we discussed, right, from the model building, it explodes the models to be regenerative and constructive. That's why you can imagine stuff you never experienced. So. So that means it's more about that, what are the parameters of these models? Right? And how can you store those. But to store a model might be more than just storing just flat bits, right? It's also relations now and functions that I have to have to store consistent function so might be gone. Let's read the question on the safe side, as I probably read, we can we can make this theory space, we can start to compare it see where the disagreements are. But I think at the bottom of it, the fundamental challenge of any theory is to explain and to make testable predictions, and to control stuff. These are the three criteria for theory, right? So with respect to your theory See, we just discussed 5% of it by now but okay, we can do a follow up podcast,

Unknown 1:29:54
or lecture one, I think, exactly. It's like one

Joscha Bach 1:29:59
or two now right?

Unknown 1:30:03
What's the prediction? What's the most convincing prediction that you have the theory? Which has been validated, right? And what has to be the most fundamental aspect of mine that you think you've explained?

Joscha Bach 1:30:17
So, that's a difficult thing to say for me. There, I've answered many questions that I had. And this was mostly conception and analysis. So for instance, when I started to go into the field of AI, I didn't know how it's possible that a system can have an emotion. And what does it mean to be in an emotional state, because they're sort of an emotional state is something like a parameter within the system, what does make this parameter special, what makes an emotion different from a number, or from a scalar, or from a bunch of scalars, right. And at some point, I discovered that way to make sense of this is that emotion is a modulation of cognition. So you have parameters that ask themselves not emotions, like arousal, and valence, and focus, and the securing rate, which starts with you, you focus your attention, inwards, outwards, and so on. And these together put you into a particular kind of configuration. And this configuration means that your cognition is going to work differently, you will perceive the world as differently, you will perceive yourself as differently if you have a self concept. And these changes is what we actually mean by emotion. So basically, I realized, yes, this is explained sufficiently, what I meant is this notion of emotion, so I could before it point at a certain phenomenon. And now this language allows me to perform a conception analysis that makes it possible for me to understand, oh, this is actually how emotion is probably implemented in an organism as a set of modulators that configure the cognition of that organism, depending on the environmental and internal circumstances, right. So it makes sense. It's not a predictive theory. It's an integrative model. And I've done this for a lot of things to for the predictive things, you can say, okay, we can come up with a machine learning algorithm that, for instance, identifies a cost function, you should think that the value of a cognition is proportionate to the increase in expected reward if you perform it minus the utility cost of not doing something else, these computational units, right? So if you implement this principle, and you will have lots of computational agents, do they perform useful modeling of useful computations in a given domain? This is an experiment that you can test. And many things in machine learning are in that area. But they're not theories of how the mind works. There are theories on how to implement a learning system. And when you look at reinforcement learning, for instance, many of the breakthroughs that we had there were the result of such considerations, right. So in that sense, AI has made many interesting predictions and useful theories. But without being able to build a thing that works like us, we will not know whether our models are actually models of the mind, or of something else that only performs certain functions that are very much like

Unknown 1:33:04
the slide that I put up on day one was said we can have an analytical approach, static approach, the synthetic approach can give rise to an existence. And the way I would look at what you're doing, you're following a synthetic approach, which is inspired by biology, but it's not so limited. And you're looking to build existence proofs of your ideas that do things which animals and humans do, we might call them intelligent. And that's how you validate your theories. Yeah,

Joscha Bach 1:33:37
yeah, I think that's fair. And the problem is, if I would use an analytic approach, I would have to produce theories which have an enormous amount of free variables. And that would be very prone to overfitting of my models. It's very hard to make predictive models, there's very many free variables when you analytically look at the brain. So, UK, for instance, this example of is making a model of the connectome of C. elegans, right. So we know that's C 109 neurons. And we have mapped out the connectome. Unfortunately, we haven't really mapped out which of the neurons are excitatory, or inhibitory, previously hadn't really gotten to a model to the level of the individual vesicles. There. So the search space is still very large. And if we map this out correctly, I think it's a good guess to say that this thing is probably going to behave somewhat C. elegans like this, that would be very surprising if it doesn't, very interesting. But there are good reasons by right now, models are not really good enough for this, at least as far as I know, I haven't looked in that space in the last year or so. And don't know if they're new publications that have cracked the problem. But you probably would have heard about it right. So it's also possible that the connectome of C. elegans is computational irreducible, which means it doesn't compress. It's possible that we don't find a description of what C elegans is doing. This quarter than the full connectome, right. So we would still expect that the thing, that's what, what C. elegans is doing. But we cannot say anything beyond this, except it's a function, which has 309 moving parts and complex interaction between those parts, right, which means our minds are not very well equipped to do a further analysis on that model. But also, this is a very bold thing. And we probably can compress it a little bit and make, identify some patterns in this and make sense of this on a higher level description. Right. So this is what we would expect. But for me, the main prediction that I'm making right now is that at some point, humanity will build machines burning the current computational paradigms, which means building finite state machines that process information that are able to perform similar intellectual feats as we do if global warming doesn't kill us before that. That's basically my prediction. It's it will be testable in some sense.

Unknown 1:35:56
But on a bit longer timescale.

Joscha Bach 1:35:59
Yeah, we don't know that. So there's a question saying, Daddy, do you think that computers will ever be intelligent? Yes, before I die a little bit before that.

Unknown 1:36:11
So before we hit the finish line, we might look at, we might try to tour so many aspects of the mind how we can model minds how we can think about it those from historical perspective. And those new have been really working very, very deeply and thinking very deeply about about these challenges. So if we'd like to follow in your approach to cracking this, this hard nut, what can be Joshua's law?

Joscha Bach 1:36:46
It's a very interesting question. What would be my light in the sense what? What strategy should I be using to get to results or strategy? Should

Unknown 1:36:54
anyone use recommend much autonomy doing tomorrow? Be doing the stuff that they're doing? needs direction. law,

Joscha Bach 1:37:10
it really depends. I mean, from a career perspective, very different.

Unknown 1:37:18
Principle t shirt. There's too many words.

Joscha Bach 1:37:29
So I think at some level, you should be aware that your your arm story that your mind tells itself. And when you make a model of the world, you do this by identifying relationships between information. The most important rule there is that you have to understand that the meaning of information, its relationship to change and other information. And when you try to evaluate your model, the first rule for that is that the weight of your confidence should equal the strength of the evidence to support it. There are no valid belief without priors, you basically need to track all of your priors until you form a ring until you know the rules of your reasoning until you know the basic axioms that go into your mathematical languages. And then you try to see if you can find a model that matches the data that matches the patterns that you get and has predictive value. And once you've done this, you try to see if there are other rings if there are other self contained systems that have the same power and the law. So the law is in some sense, follow the evidence. Try to make models that track the priors, always follow your priors and resolve them until you believe stops being a verb. Because that system is now self contained and no longer has a relationship to you. Once you understand a way to define arithmetic, that definition of arithmetic becomes independent of

Unknown 1:38:52
your right priors until your circular Yes until

Joscha Bach 1:38:55
basically you get to a mathematically closed system. Every mathematically closed system, in some sense is a tautology. Mathematics is a set of tautologies

Unknown 1:39:04
so it used to be a solipsist

Joscha Bach 1:39:07
No way, I don't even exist I cannot be a solipsist. Thinks days is pretty successfully constructed my own existence. Don't take that away from

Unknown 1:39:20
me. Saying Russell said in that clip, focus on the facts, what you want to get to the truth. But

Joscha Bach 1:39:29
in some sense, I realized that Tony and Paul and me are characters in a dream that is driven by a higher mind on a higher plane of existence. And the best explanation for that thing is that it was created in the brain of a primate and in the course of an evolutionary trajectory right. So this seems to be a theory that gives good predictions seems to be sound. David Smith compatible this all the solid scientific results and getting

Unknown 1:39:56
and going to our Lord Oh, no, no Oops, we

Joscha Bach 1:40:00
didn't know the basic law is I think still this what Francis Bacon discovered the first law of epistemology, the date of the confidence must equal the strength of the evidence. And I think from this follows everything else if you if you take this thing, because you can take this and check all the alternatives, once you have this hypothesis that you should be

Unknown 1:40:18
doing this law is Megan's Law. Evidence as well,

Joscha Bach 1:40:22
I cannot claim originality, I'm not a very original mind. Okay, not that smarter than so

Unknown 1:40:26
the last question. Tony, Tony Wolf, will chase you up four years from now, you might be in San Francisco by then. Or somewhere else, we don't know you are still at Cambridge, I don't know what your what you're up to. Sure will be great place. But Tony's going to check whether you were you succeeded in falsifying or verifying a specific hypothesis that you're going to share with us today. So what what's the most urgent hypothesis that you would like to see really fully tested in this four year timeframe with respect to your theory of mind? prediction.

Joscha Bach 1:41:10
So one of the things that I find very interesting right now is whether the purpose of consciousness is attention based learning. So there is seems to be a problem, our brains are not differentiable. They are not easily decomposed in the succession of layers that are which we can pipe a loss function with the chain rule. So something else needs to be going on. Right. And I suspect what's going on, there is among a few other things that are not seeing right now an attention based learning algorithm. And that might work by capturing the current binding state the current latent variables that define your party partial configuration of your brain, and the change that you're making to this configuration with respect to a particular goal and the expected outcome, and triggering conditions that tell you when you have a possibility to evaluate whether a change was successful. And then you commit this to an index, and conscious attention might be the ability to make index memories. And then you go into the future, you busy appearance of a few other world states decompose this binding state to do other things. And then at some point, the result manifests in the world, you re instantiate this original binding state and based on the outcome of your change, you will reinforce the change or you undo it. And this could be an learning algorithm. That sounds a little bit awkward, because we need to do so many steps. But eventually we need to touch on a few other things that are current machine learning are working store. And what I would like to see is if this kind of algorithm actually works, and produces useful results, and if we see a new family of learning algorithms that implement this or similar principles.

Unknown 1:42:45
Okay, very good, Vishal. Both Thank you very much for this conversation.

Unknown 1:42:49
Thank you. So CSN podcast was produced by the convergent science network, biometrics and biohybrid systems project funded by the European sevens research framework program. For more interviews, recorded lectures, or upcoming conferences in the field of bioinformatics and bio hybrid systems, go to CSN network, dot Thank you for listening
