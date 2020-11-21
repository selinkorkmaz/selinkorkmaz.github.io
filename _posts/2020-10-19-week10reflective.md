---
layout: post
title: What is Aleatory Poetry?
categories:
- Reflective posts
---
According to Dr. Pilsch, aleatory poetry is the process of using chance to generate text. For example, a poet can take an existing piece of their writing and submit it to chance operations (a method of generating poetry independent of the author's will). This can be done by deleting every third word, cutting up the text and putting the pieces together in a random sequence, or what I did change certain words and replace them with synonyms. 
<br/>

After coming up with a random story, I thought it would be easier to change certain words and replace them with synonyms. Here is what I did: 
* **Thomas**: Tom & Tommy
* **Cleverer**: more intelligent, brighter, smarter, gifted, talented 
* **Little**: small, mini, tiny
* **Creatures**: critters & living things 
* **Kill**: murder, assassinate, destroy, eliminate 
* **Sitting**: stationed & seated 
* **Sweetmeats**: sweets & enjoyments 
* **Death**: end, demise, passing, expiration 

I could've gone about this by creating two different introductions and two different endings (introduction A, introduction B, ending A, ending B), which would make four separate storylines. So each time you hit generate - a different story appeared. 
<br/>

After completing my story, it was time to figure out how to implement it on GitHub and for it to generate properly. First, I started creating a new "tracery" layout that made a new page for the post. My "origin" displayed my whole story from start to end. Then, I included "grammar" which are `#Thomas#`, `#Cleverer#`, `#Little#`, `#Creatures#`, `#Kill#`, `#Sitting#`, `#Sweetmeats#`, `#Death#`. Whenever I run my bot, Tracery will check that the grammar has a key named `Thomas` (which it does) and return the contents of that key (which is Tom & Tommy). Tracery would also check the rest of the seven keys I also have.
