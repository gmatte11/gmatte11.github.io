---
layout: post
title: Back from CppCon 2020
---

This year I had the opportunity to assist the CppCon live from my computer chair. 

## 2020

The CppCon organization team did a tour de force by reorienting the conference via the Remo platform supported by Youtube video streams. The Remo platform can be flawed, but it was a functional abstraction of a normal conference floor with rooms for talks, a "Hallway Track" room for conversation with up to 8 people around virtual tables, and even an Expo Hall for sponsors... that I didn't take time to visit.

During a presentation, attendees could discuss and silently applaud in the room/track's General Chat and ask questions that could be upvoted by other attendees à la Stack Overflow.

## Presentations

One of the advantages of the Youtube streams is that I could watch multiple talks at the same time without having to physically walk between rooms. I could listen to one (or two sometimes) and mute the others. By watching the slides, if something picked my interest, I could unmute the other talk and if needed rewind to listen to the interesting bits I missed.

I would like to highlight some of the talks that you will be able to watch on your own on Youtube as some of them already began to become available.

1. `Building an intuition for composition` by Sy Brand

    This is a great introduction to some of the C++20 features such as ranges and coroutines and gives a great overview of the new C++20 idiomatic to use and _mix_ algorithms.
    Plus some overview of what might come in future C++ releases.

2. `Retiring the Singleton pattern: concrete suggestions for what to use instead` by Peter Muldoon

    Singletons are simple to write, especially in game projects, as they are quick to write and offer global access to a resource.
    This video explains why the pattern can create creeping issues in the quality of the code we write (non-testability, hidden dependencies).
    It also offers solutions to improve the pattern while keeping the global accessibility offered by the pattern.

3. `Pipes: How plumbing can make your C++ code more expressive` by Jonathan Boccara

    This video takes the ranges' design and offers an alternative less general but more efficient design. 
    By going in-depth in this alternative library it helps the viewer to do parallels on how ranges work.

4.  `C++20 string formatting library: an overview and use with custom types` by Marc Gregoire

    A pet peeve of mine; I would love to evolve my debug code from printf formatting to fmtlib or std::format in a near future. 
    The talk is a 30-minutes course on how to use the format syntax and how to expand it.

5. `Some things C++ does right` and `The surprising costs of void() (and other Not-Quite-Innocuous evils)` by Patrice Roy

    Both talks by Patrice were formatted similarly, so I put them both here. 
    The first focus on some C++ language foundations that differs from other languages that we (sometimes) need to be remembered about. 
    The other one gives some examples of bad programming practices that we may have been taught to use but isn't as inoffensive as we might think.

## Takeaways

As it was a C++ Standard release year, a lot of the talks' subjects focused on the newest C++20 features. I might be biased, but I find there was less focus on the evolution of the language than other years.

As it was my first CppCon, I was really impressed to meet some of the most vocal members of the C++ community and I was also pleased to discuss with other attendees from all around the world.
