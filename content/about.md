---
title: "About"
date: "2023-09-14"
aliases:
 - "about-us"
 - "about-hugo"
 - "contact"
author:
  name: "Eibriel"
---

Compicactus is a **game about learning a visual constructed language to chat with a cute AI**. Have a date, build memories, share moments and have fun!

* [Wishlist on Steam](https://store.steampowered.com/app/2278200/Compicactus/)

### AI usage

For this game an ontology was used, with a hierarchy of concepts (for example object->person->human), and a database of instances of those objects (for example the Player is a human).

This allowed for some generalizations, for example expecting that all Persons has a favorite color.

This was inspired in the work on [Ontological Semantics](https://mitpress.mit.edu/books/ontological-semantics). The system also uses an utility function to select the answers, given a set of goals, see [Versu](https://if50.substack.com/p/2013-a-family-supper).

Source code available at [GitHub](https://github.com/Eibriel/Compicactus).