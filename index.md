---
title: Home
layout: home
---

# RGBoard Docs 🔴🟢🔵
RGBoard is a system comprised of parts in different disciplines.
To replicate this project, some fundamentals in different areas must be
understood to create derivations out of the provided instructions. The
documentation provided serves as a guide to help create RGBoards from scratch.
## Fundamentals Prerequisites
This is a great project for those that love tinkering and are not afraid of doing
a little bit of everything. Let's start with the fundamentals to get started
in building RGBoards.
### Engineering graphics 📐✏️
A lot of people outside of mechanical engineering think this class is a waste of
time, but is one of the most important engineering classes and one
of the most classical forms of engineering. Truth is, to build something, you're going to have to
measure and sketch various iterations til you get your desired end result. Don't panic,
you don't need to know how to create complex objects, it all depends on what kind of board
you want to assemble, but in most cases, you will be building a frame. All you need to know is how
to draw measured lines, do your corners and measure where to put your holes so you can bolt your frame
to the panels.
### Electrical engineering ⚡
RGBoard needs power relative to its size and the correct GPIO wiring. You don't need to be an electrical engineer,
but you need to understand that if each of your panel draws 3.8A, and you have 2 panels, then you need at minimum, a
10A power supply.
### Raspberry Pi 4 Model B and Unix/Linux Operating Systems 💻
RGBoard is basically a Raspberry Pi project and this is where you will
be spending most of your time. Raspberry Pi's will usually run on an Operating System built on Debian
running on top of the very much popular Linux kernel. You need to understand how to use this type of
Operating System. If all you have ever used is Windows, you have quite a journey. If you have a Mac,
you're halfway there.
### Python and Flask 🐍
The back-end of RGBoard is built with Flask, a web server interface for handling client requests,
and written in Python. Python is a relatively easy language to code in thanks to how much is able to
abstract with its very popular and well documented libraries. You will be handling user request, authenticating
them cryptographically with JSON Web Tokens, and making sure they have their respective CRUD permissions.
### Web frameworks 🌐
RGBoards front-end is built using a selected set of tools out of the rabbit hole that is web development. We use the React with JavaScript,
Tailwind CSS to have quick styling options, and Vite to build the whole thing in a bundle that can be served with NGINX. You can make your
own front-end if you desire or even turn RGBoard into a mobile app. In the front-end is where most people can apply their flavor.
### Relational databases 🗃️
In RGBoard, we use SQLite to store data due to it being so easy to interface with Python. You need to know concepts of
Relational Databases like set theory, tables, and SQL queries and transactions. 