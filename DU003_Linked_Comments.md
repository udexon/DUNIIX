# DU003: Comments Linking Comments

The World Wide Web is basically a page linking page (PLP) network. After decades of development, social media comments and actions (SMCA) (likes, upvotes, downvotes, etc.) have perhaps (because no available systematic surveys) surpassed web pages as the most popular media of communications amongst users.

However, as all comments are linked to post and managed by a sole proprietor &mdash; the owner of the web page or app, it has been troublesome and unprofitable to develop a "comments linking comments" (CLC) mechanism similar to "page linking page" (PLP).

We propose the following mechanisms to implement CLC:

1. Graph of Questions (GoQ)
2. Uniform Resource JSON (URJ)

## A. Graph of Questions

Identifying the exact beginning of the modern essay form is obviously beyond the scope of this article. We may just mark it with the mass implementation of modern school system, comprising primary, secondary and tertiary education, although the exact date may still differ widely by countries.

The smallest unit of a modern essay is of course a sentence. An essay is made up of paragraphs. A paragraph is made up of sentences.

As such, a sentence is restricted within the context of its paragraph and the essay itself.

Although the invention of the Uniform Resource Locator (URL) and the Uniform Resource Identifier (URI) may be in principle used to address a sentence (with URI) within any essay (within a web page, addressable by URL), there is no large scale application that makes full use of this feature. 

We propose Graph of Questions as a database of questions, whose answers can be found at a sentence identified by a URI, within any web page, addressable by a URL.

1. Any sentence in a web page can be addressed with a URI.
(See demo: Google Docs, github markdown, or any plain old web page udexon.github.io

2. Anyone, including the author of a document D, may create a question in GoQ, which then has a
URI_Q1, which then maps to a sentence URI_A1 as described in (1).

As such multiple question URI_Q* maybe created to map to one sentence URI_A1.

Further, multiple sets of questions URI_QS* maybe created by anyone (author of document or others)
to map to multiple answers URI_A*.

## B. Applications of Graph of Questions

One very useful applications of Graph of Questions
(GoQ) is the "multithreading" mechanism to sentences within a document.



While there have been questions oriented social networks or websites based on questions, such as Stackoverflow or Quora, they are restricted because the answers given are stored within the same social media.

Fundamentally, this is dues to the design architecture of Centralized User Authentication Scheme (CUAS).

To change this, Duniix has implemented a Decentralized User Authentication Scheme.

Why no one can do comment linking comment (CLC)? Because there has been no open platform for publishing comments. 
Even if there is a CLC (comment linking comment) protocol, there is no commercial incentive to do so --- unless coupled with Duniix DUAS Recommendation Reward. Users may earn a reward …. 
