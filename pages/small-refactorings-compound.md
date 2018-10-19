# Small refactorings compound.

Once you've written some code, be sure to do a self [code review](stop-doing-code-reviews.md).
[Refactor](https://refactoring.com/catalog/) your code.

Or if you're looking at some code that is unexpressive, hard to read, confusing, or simply unfamiliar to you, refactor that code.
Remember, you don't actually have to commit all such code changes.
Sometimes refactoring is good for your own understanding of things.

Make sure the code is expressive, variable names are clear, and you like how it looks.
If you're not sure exactly what to do, start small.
Extract some constants.
[Extract a method](https://refactoring.com/catalog/extractMethod.html) or two.
Introduce an [explaining variable](https://refactoring.com/catalog/extractVariable.html).

You'll identify a bit of your code where something is repeated but doesn't really need to be.
Then you'll see a group of if/else statements that could be simplified and condensed.
Oh look, there's a scenario you hadn't thought of or a bug you didn't notice before. Let's write a test for that.
Then you'll notice that an entire section of your code could be written more clearly using a different mindset.
Then you'll decide you should probably cut back on the cheese sandwiches after midnight, at least on nights you're up late coding.

Before you know it, you've improved your code, your product's quality, your diet, and your ability as a programmer.
