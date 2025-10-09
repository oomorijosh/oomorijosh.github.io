---
layout: essay
type: essay
title: "Smart Questions"
# All dates must be YYYY-MM-DD format!
date: 2025-09-10
published: true
labels:
  - Technical Essay
  - Stack Overflow
  - Software Engineering (ICS 311)
---

<!-- A lot of md format is like Obsidian note taking -->

## What Constitutes a Smart or Dumb Question?

When thinking about what makes a question smart, it can actually be easier to start with the opposite: **What is a dumb question?** While many people like to say, “There are no dumb questions,” that’s not entirely true. Some questions may come across as uninformed or thoughtless, depending on the context.

A question might seem “dumb” if it’s:

- **Off-topic**<br />
  - *e.g., in a physics class: “Do aliens exist?”*

- **Not specific enough**<br />
  - *e.g., “Is this good?” — What is “this” referring to? What kind of feedback are you looking for?*

- **Easily searchable**<br />
  - *e.g., asking your parents, “What’s the temperature tomorrow?”*

- **Already answered**<br />
  - *e.g., after a presentation clearly stating the deadline: “Wait, what’s the deadline?”*

**Context is key.** The time, place, and audience all affect how a question is received.  
For example, asking, “What was his name again?” after meeting someone is usually fine. But asking that same question at a funeral might not be appropriate.

---

## Smart vs. Dumb Questions in Software Engineering

In Software Engineering, forums like Stack Overflow are vital for asking questions when facing technical challenges. These platforms connect you with experienced developers who can offer insight, alternative perspectives, or quick fixes.

However, a smart question:

- Shows that you’ve already made an effort
- Provides context and code samples
- Clearly states what you’re trying to achieve

In contrast, dumb questions often:

- Are easily Googleable
- Lack specificity
- Look like homework questions with no attempt shown
- Spam multiple threads, wasting other users’ time

---

### Dumb Question Examples (from Stack Overflow)

<br />

#### 1. Java main function won't compile with a method in it

> *I am using Netbeans to learn basic Java stuff right now, and I have looked around and I cannot figure out what is wrong with this. I am unable to make any kind of method in the "main" function because it does not compile. I get an error saying <br /><br /> `error: illegal start of expression: public String method(int a){`


```java
public class JavaApplication3 {
    public static void main(String[] args) {
        public String method(int a){
            return "a";
        }
    }
}
```

This question is considered “dumb” because:
- Spelling Mistakes
- It's easily searchable
- It reflects a lack of prior effort or understanding

[Source](https://stackoverflow.com/questions/44013965/java-main-function-wont-compile-with-a-method-in-it)

<br />

#### 2. removing multiple occurences of alphabets in a word

> *“I want to remove multiple occurrences of a character using a single array. Say the word entered is "APPLE" then the output should be "APLE". Similarly for "Soccer" it should be "Socer" <br /><br /> Please help."*

This question is problematic because:

* It lacks punctuation and clarity
* Shows no attempt at solving the problem
* Sounds like a homework question, expecting others to do the work

[Source](https://stackoverflow.com/questions/25910593/removing-multiple-occurences-of-alphabets-in-a-word)

---

### Smart Question Example

#### What is the `-->` operator in C/C++?

> *After reading Hidden Features and [Dark Corners of C++/STL](https://groups.google.com/access-error?continue=https://groups.google.com/g/comp.lang.c%2B%2B.moderated/c/-/m/IN1YDXhz8TMJ?pli%3D1) on comp.lang.c++.moderated, I was completely surprised that the following snippet compiled and worked in both Visual Studio 2008 and G++ 4.4. I would assume this is also valid C since it works in GCC as well. <br /> <br /> Here's the code:*

```c
int x = 10;
while (x --> 0) {
    printf("%d ", x);
}
```
> *Output:*
```
9 8 7 6 5 4 3 2 1 0
```
> *Where is this defined in the standard, and where has it come from?*

This is a **smart question** because:

- The user gives clear context and code
- They reference specific compilers
- The behavior is non-obvious and not easily Googleable
- The question opens the door for a deep, meaningful discussion

[Source](https://stackoverflow.com/questions/1642028/what-is-the-operator-in-c-c)

---

## Conclusion

Whether a question is considered smart or dumb depends largely on context. For example, asking Google “How do I get input from a user in Java?” is perfectly fine; sometimes we just need a refresher. However, posting that same question on a professional forum without showing any effort makes it seem lazy or thoughtless.

If you're unsure how to phrase a good technical question, a great resource is Eric Steven Raymond’s essay:
  ["How to Ask Questions the Smart Way"](http://www.catb.org/esr/faqs/smart-questions.html)

Taking a few extra minutes to research, clarify, and phrase your question well can make all the difference in getting helpful answers and bringing on healthy discussion.
