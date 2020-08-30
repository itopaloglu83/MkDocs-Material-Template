# MkDocs Material Template

> This information is an extract from [The documentation system](https://documentation.divio.com) website.

The documentation needs to include and be structured around its **four different functions**: 

* tutorials,
* how-to guides, 
* technical reference, and 
* explanation.

|               | Tutorials                          | How-To Guides                        | References                       | Explanation                           |
| :------------ | :--------------------------------- | :----------------------------------- | :------------------------------- | :------------------------------------ |
| *oriented to* | learning                           | a goal                               | information                      | understanding                         |
| *must*        | allow the newcomer to get started  | show how to solve a specific problem | describe the machinery           | explain                               |
| *its form*    | a lesson                           | a series of steps                    | dry description                  | discursive explanation                |
| *analogy*     | teaching a small child how to cook | a recipe in a cookery book           | a reference encyclopedia article | an article on culinary social history |

Each of them requires a **distinct mode of writing**. And documentation needs to be explicitly structured around them, and they all must be kept separate and distinct from each other. This division makes it obvious to **both author and reader** what material, and what kind of material, goes where.

## Tutorials

Tutorials are *lessons* that take the reader by the hand through a series of steps to complete a project of some kind. They are what your project needs in order to show a beginner that they can achieve something with it.

They are wholly **learning-oriented**, and specifically, they are oriented towards *learning how* rather than *learning that*.

**You are the teacher**, and you are **responsible** for what the student will do. Under **your** instruction, the student will execute a series of actions to achieve some **end**.

The end and the actions are up to you, but deciding what they should be can be hard work. The end has to be *meaningful*, but also *achievable* for a complete beginner.

The important thing is that having done the tutorial, the learner is in a position to make sense of the rest of the documentation, and the software itself.

Most software projects have really bad - or non-existent - tutorials. Tutorials are what will turn your learners into users. **A bad or missing tutorial will prevent your project from acquiring new users.**

Of the sections describing the four kinds of documentation, this is by far the longest - that's because tutorials are the most misunderstood and most difficult to do well. The best way of teaching is to have a teacher present, interacting with the student. That's rarely possible, and our written tutorials will be at best a far-from-perfect substitute. That's all the more reason to pay special attention to them.

Tutorials need to be useful for the beginner, easy to follow, meaningful and extremely robust, and kept up-to-date. You might well find that writing and maintaining your tutorials can occupy as much time and energy as the the other three parts put together.

## How-To Guides

How-to guides take the reader through the steps required to solve a real-world problem.

They are recipes, directions to achieve a specific end - for example: *how to create a web form*; *how to plot a three-dimensional data-set*; *how to enable LDAP authentication*.

They are wholly **goal-oriented**.

**How-to guides are wholly distinct from tutorials** and must not be confused with them:

* A tutorial is what you decide a beginner needs to know.
* A how-to guide is an answer to a question that only a user with some experience could even formulate.

In a how-to guide, you can assume some knowledge and understanding. You can assume that the user already knows how to do basic things and use basic tools.

Unlike tutorials, how-to guides in software documentation tend to be done fairly well. They’re also fun and easy to write.

## References

Reference guides are *technical descriptions of the machinery* and how to operate it.

Reference guides have one job only: to describe. They are code-determined, because ultimately that's what they describe: key classes, functions, APIs, and so they should list things like functions, fields, attributes and methods, and set out how to use them.

Reference material is **information-oriented**.

By all means technical reference can contain examples to illustrate usage, but it should not attempt to explain basic concepts, or how to achieve common tasks.

Reference material should be **austere and to the point**.

Note that description **does** include basic description of how to use the machinery - how to instantiate a particular class, or invoke a certain method, for example, or precautions that must be taken when passing something to a function. However this is simply part of its function as technical reference, and emphatically **not** to be confused with a how-to guide - *describing correct usage of software* (technical reference) is not the same as *showing how to use it to achieve a certain end* (how-to documentation).

For some developers, reference guides are the only kind of documentation they can imagine. They already understand their software, they know how to use it. All they can imagine that other people might need is technical information about it.

Reference material tends to be written well. It can even - to some extent - be generated automatically, but this is never sufficient on its own.

## Explanation

Explanation, or discussions, *clarify and illuminate a particular topic*. They broaden the documentation’s coverage of a topic.

They are **understanding-oriented**.

Explanations can equally well be described as *discussions*; they are discursive in nature. They are a chance for the documentation to relax and step back from the software, taking a wider view, illuminating it from a higher level or even from different perspectives. You might imagine a discussion document being read at leisure, rather than over the code.

This section of documentation is rarely explicitly created, and instead, snippets of explanation are scattered amongst other sections. Sometimes, the section exists, but has a name such as *Background* or *Other notes* or *Key topics* - these names are not always useful.

Discussions are less easy to create than it might seem - things that are straightforward to explain when you have the starting-point of someone’s question are less easy when you have a blank page and have to write down something about it.

A topic isn’t defined by a specific task you want to achieve, like a how-to guide, or what you want the user to learn, like a tutorial. It’s not defined by a piece of the machinery, like reference material. It’s defined by what **you** think is a reasonable area to try to cover at one time, so the division of topics for discussion can sometimes be a little arbitrary.
