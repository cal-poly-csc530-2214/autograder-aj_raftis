#  Lab 5
AJ Raftis (araftis@calpoly.edu)

First off, sorry this was so late getting checked in. I have no idea if you've graded these yet or not. Sadly, I didn't really get all that much done, despite the time I spent.

I actually wanted to play around more that I had time, intially, but sadly, I wasn't able to get back to this due to other commitments. I actuallys still hope to get back to this a bit. See below for details.

So, that being said, here's what I did:

## The Paper

For starters, I read the paper, of course, and attempted to follow what was going on. I think I did get the gist of things, and I liked the idea. I certainly thinks it's a useful concept, as long as you're willing to deal with the limitations, which mostly seem to be the following:

  1. This isn't going to support particularly complicated programs, so you're not going to be auto evaluating say a B+ tree implementation. In fact, you're probably not going to be evaluating anything much more than one, maybe two functions in size.
  2. It's not going to catch everything. However, it does seem like it can catch quite a bit, so it seems like a good starting point for student assignments. For example, in a large lecture or online class, if you provide reasonable feedback of just half the submissions, that could save a huge amount of time. I could also see where it'd be useful while students were working, because they could submit to a service that would provide near instant, potentially useful feedback.
  3. The language is a little limited, but that seems mostly a factor of the paper, but I can easily see where the language support could be expanded.
  
## What to Do?
  
I was initially thinking that I wanted to build on what I did for Lab 4, and that in reference to point 3 above, I'd write a little Swift program that could convert Swift code into their language. From reading the paper, this certainly seemed doable, but that started the trip down the rabbit hole.
  
So first, I'm thinking, if I'm going to do this, then I want their code, so I went looking for it. That took quite a bit of time, and wasn't really all that fruitful. Mostly I just found references to their paper, but not any actual code.

At that point, I thought, fine, I'll just write my translator, that'd still be useful. And then, another student in the class posted a pointer to the code I had been looking for, so I paused (which became stopped) my initial planning, and jumped to grab the code.

## Getting Sketch

Over all, getting the initial code wasn't too bad. I'm running on a Mac, and checked out sketch-backend, and it built pretty easy. I then ran it with some of the test cases, and it seems like it was working correctly. I poked around this for a while, but I soon realized that I really needed the front end code as well, so I checked that out. I was trying to avoid this due to the apparent Java requirement.

This was a little more of a challenge. I did get it to compile fairly easily, but then I had some issues getting it to install, because I wanted to be able to play around with it a bit. I basically had some compatibility issues, but after playing around and updating some of my MacPorts, I was able to get things installed, into my PATH, and running.

With that, I jumped into the test directory and started to play around with some of their examples. Mostly I just tried a bunch of examples, tweaked a few to see what would happen, but really, nothing too profound.

## Next Steps

So at this point, I was kind of back to where I started, but I'd run out of time. I wanted to get back to my initial attempts at writing a translator for Swift into their small language, but I'd already spent the alloted number of hours, and since I had other things I needed to get done for other classes (and life), I stopped.

I then delayed getting this stuff checked in, because I thought I might get back to it, but that hasn't happened. Then, with Lab 6 and trying to wrap up the quarter, I kept forgetting to check this in, which is totally my bad.

Anyways, I kind of still want to get back to this a bit. While working at Apple, I was on the Xcode team for a number of years, and I was thinking this could potentially be a neat feature for Swift Playgrounds. One of the featuers of Playgrounds is that they're really useful for teaching, and generally, they involve writing fairly simple little code snippets as parts of turtorials, and since they're guided turtorials, I was thinking that something like Sketch could be really useful for potentially for providing feedback to users who don't have the option of a professor to ask for help.

