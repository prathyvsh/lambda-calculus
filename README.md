# Lambda Calculus
Guide to understand the Lambda Calculus

Lambda Calculus is a term usually tossed around in the programming circles supposedly providing the undergirding for functional programming, but I find very rarely understood for what it is in it's original flavour. I undertook this quest to find out what it finally is about and here are my findings.

## Motivation
While it was comforting to remain in the shadows of the giants and take the computer stack for granted, half a decade hacking on the system and constantly consuming articles from people active in the community, you develop this notion that most of the technology that we take for granted has reached this point of iteration after going through considerable amounts of constraints, not all of which are immutable or geared for the welfare of a daily programmer. Some are well thought out, many are historical accidents, and a great many micro-decisions that manifests at the day to day level are just utter chaos resulting from decisions with rationale as weak as "if its not broken, dont fix it, and ramp up the complexity to 11". After realizing that I was in the breads and circuses business of pop culture computing, I thought of looking elsewhere and thats when I figured the answer could lie beneath the historical layers. A lot of great many works in the past inspired me and I continued to look further where in I found out that one needs to have a good understanding of an entire system inorder to figure out why/how/what is happening at any one particular level. So in that sense, this document is a thorough look at the language level of a functional programming language that is commonly used as the lingua franca to translate the electrical  communicate with the computer system.

# Elements of Lambda Calculus
The essential primitives of Lambda Calculus are three things:

## Variables
Variables store an abstraction built up of functions.
## Functions
## Application

# Using the primitives
The primitives can be put together to compose expressions which can be evaluated to produce a result. The evaluation proceeds by continuously applying the functions until a resultant value is produced.

# A network traversal metaphor of computation
The trinity of variables acting as names, functions, and application can be thought of as a memory network (DAG) which is continuously traversed to obtain a sequence of values in the end. So evaluation is a continuous graph traversal built up of values which can be stored as variables. These values form a network by composing functions together. These functions act are a mapping between values which can be realized by passing the appropriate argument. The process by which it is realized is called an application. Thus variables when passed to functions on application is how Lambda Calculus performs computation.

# Essential Operations
## Alpha Conversion
## Beta Reduction
## Eta Reduction

# Trivia
While the untyped variant of Lambda Calculus is thought of as a canonical model that can carry out any conceivable computation, not all variants of Lambda Calculus is so. This property of being able to complete any computation is termed as **Turing Completeness** and the typed variant of Lambda Calculus is not Turing Complete.
