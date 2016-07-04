---
layout: default
title:  "Learning by example"
description: "Learing by example"
date:   2016-07-02 12:50:00
categories: ruby
---

# Learning by example

Learning by example is one of efficente way to adopte knowledge. Problem you encounter is how to find a good example. When I think about ruby I could not find better example then rack.

Ruby is famous for Rails framework, and most of the time it is not ruby it is Ruby On Rails. I found it very intresting, even though Rails is the most famouse, everthing is build on top of rack. 

Rack is accepted and used by Rails and all alternatives. It is well known that ruby developers are very sensitive about code they write. Rigorous roules and coding standard have to be met to fulfill that ideal of code standard. And rack is the one.

That been said I would say rack is the best example you can find for ruby.

Friend of mine point to me excelent way to see how rack is builded. Idea is called git walk. It is a simple script which allows you to move throught git commits.

A simple instructions would be:

- First step is clone rack source from github (https://github.com/rack/rack).
- Second steo is to find init commit hash. You can find it yourself or just use it. 'git rev-parse --verify HEAD' or '2cb9430fce32da2f2dbccf9de97ab691351c1408'
- Third would be to do 'git checkout 2cb9430fce32da2f2dbccf9de97ab691351c1408' and set rack project on the begining of time.
- Forth would be to get a script which allows moving forward and back. I put gist https://gist.github.com/denza/376400382d334d41e20cb71ffdc3ab3d for persevation purpose.
- Other steps are moving forward in the future and inspect changes the team has made in your favorite editor. 

