---
title: "Why for...of Loop in JavaScript is a Gem"
description: 'for...of cycle in JavaScript iterates over the items of an iterable.'
published: '2020-03-31T12:00Z'
modified: '2020-03-31T12:00Z'
thumbnail: './images/cover-2.png'
slug: javascript-for-of
tags: ['javascript', 'for']
recommended: ['foreach-iterate-array-javascript', 'how-to-iterate-easily-over-object-properties-in-javascript']
type: post
commentsThreadId: javascript-for-of
---

The `for...of` statement (starting ES2015) creates a loop that iterates over array items, and generally any iterable objects.  

The best thing I like about `for...of` is the consize syntax:

```javascript{3-5}
const colors = ['blue', 'red'];

for (const color of colors) {
  console.log(color);
}
// logs 'blue'
// logs 'red'
```

The usability of `for...of` statement is not limited to short syntax to iterate array. 

Even better, `for...of` accepts any iterable. This property leads to a great amount of flexivility to iterate over many object types, including the primitive string.  

## 1. Array items iteration

## 2. Array-like items iteration

## 2. String characters iteration

## 3. Map key/value pairs iteration

## 5. Iterate plain JavaScript objects

## 6. Iterate DOM lists

## 7. Conclusion