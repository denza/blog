---
layout: default
title:  "Learning by example"
description: "Learing by example"
date:   2016-07-02 12:50:00
categories: ruby
---

# Learning by example

Learning by example is one of efficient ways to adopte knowledge. The problem you encounter is how to find a good example. When I think about ruby I could not find a better example then rack.

Ruby is famous for Rails framework, and most of the time it is not ruby it is Ruby On Rails. I found it very interesting, even though Rails is the most famous, everything is built on top of rack. 

Rack is accepted and used by Rails and all alternatives. It is well known that ruby developers are very sensitive about code they write. Rigorous rules and coding standard have to be met to fulfill that ideal of code standard. And rack is the one.

That being said I would say rack is the best example you can find for ruby.

Friend of mine pointed to me excellent way to see how rack is built. The idea is called git walk. It is a simple script which allows you to move through git commits.

A simple instructions would be:

- First step is clone rack source from github (https://github.com/rack/rack).
- Second step is to find init commit hash. You can find it yourself or just use it. 'git rev-parse --verify HEAD' or '2cb9430fce32da2f2dbccf9de97ab691351c1408'
- Third would be to do 'git checkout 2cb9430fce32da2f2dbccf9de97ab691351c1408' and set rack project at the begining of time.
- Forth would be to get a script which allows moving forward and back. I put gist https://gist.github.com/denza/376400382d334d41e20cb71ffdc3ab3d for preservation purpose.
- Other steps are move forward in the future and inspect changes the team has made in your favorite editor. 

