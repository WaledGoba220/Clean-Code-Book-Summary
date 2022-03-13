# Clean-Code-Book-Summary
Clean Code Book Summary, clean code is attributed to software engineer Robert Cecil Martin, who used it in his book Clean Code: Refactoring, Patterns, Testing and Techniques for Clean Code to refer to clean code . However, its principles are much older and do not come from the field of programming. We explain what the clean code consists of , what its advantages are and how to develop it..
Clean code: what is it?
The code clean is not a strict set of rules, but a set of principles that help produce intuitive and easy to modify code. In this context, intuitive means that any professional developer can understand it immediately. An easily adaptable code has the following characteristics:

The sequence of execution of the entire program follows a logic and it has a simple structure .
The relationship between the different parts of the code is clearly visible .
The task or function of each class, function, method, and variable is understandable at first glance .
A code is considered easy to modify when it is flexible and extensible, which also helps to correct any errors it may have. Therefore, the clean code is very easy to maintain and has the following properties:

Classes and methods are reduced and, if possible, have a single clear task.
Classes and methods are predictable , work as expected, and are publicly accessible via well-documented APIs (interfaces).
The code has been  unit tested .
The advantages of this type of programming are obvious: the clean code becomes independent of the developer who created it . In principle, any programmer can work with it, which avoids problems such as those associated with legacy code. The maintenance of the software is also simplified , because the bugs are easier to find and fix.

8 Reasons Why Clean Code Matters
1. Clearness
It’s easy to forget that each line of code software developers write is likely to be read many times by humans during its lifetime. These humans are usually co-workers. They’re busy fixing bugs and adding features. Therefore each developer should take care of the code and make it as clean and clear as possible. Developers are like authors, great authors are known for writing books that tell a clear, compelling story. They use chapters, headings, and paragraphs to clearly organize their thoughts and painlessly guide their reader. Developers work in a very similar system, but use namespaces, classes, and methods instead of words.

2. Best Practices
In recent years, software best practices like unit testing, TDD, CI, etc. have been growing very fast in terms of adoption. These practices elevate code quality and maintainability. Implementing clean code principles is a foundational skill that pays off especially well when it’s time to refactor code or bring code under testing. Clean code makes it easier to read and test. If you think of it as part of a house, clean code is the foundation.

3. Logic Behind the Code
If someone asks you about your code quality, you should provide a rational justification. If you’ve never methodically considered the quality of your coding style, there’s likely plenty of opportunity for improvement. Those who write clean code have concrete activities, patterns, and techniques they use to keep their code clean. 

4. Maintenance
Writing code is relatively easy, reading is hard. This is why so many developers prefer to rewrite rather than do the hard work of reading and comprehending existing code. By writing code that is readable, you are optimizing for the 90% of the time we are reading code, rather than the 10% of the time you are writing it. This is a significantly more cost-effective strategy than the alternative strategy of writing code as quickly as possible without concern for the readability of the code. Also, it makes it almost impossible to say, “Oh, this code is not mine, it is Juan’s.” With clean code you won’t need to blame others for the poor quality of the code, clean code is a standard, a foundation for everyone to work on. So, at the end of the day, by creating code that is maintainable, you are optimizing the majority of your time and the cost of maintaining code.

5. Easy to Test
By building clean code, automated testing of that code is encouraged. By automated testing, I mean Test-Driven Development - which is the most effective way to improve the quality of code, improve the long-term velocity of a team, and reduce the number of software defects. All of these factors contribute heavily to the overall ROI of the software.

6. Simplicity
Keep your code as simple and readable as possible. Don’t over-complicate problems, which is a common issue among software developers. By keeping it simple, you can produce higher quality code, solve problems faster ,and work better in groups.

At Apiumhub, we love the KISS principle (keep it simple, stupid), as well as the DRY principle, which means don’t repeat yourself. It allows software developers to avoid duplication and allows them to produce much cleaner code compared to the programmer who uses unnecessary repetition. 

And don’t add extra features because you might need them in the future. Never do that. It’s a useless waste of time and money. And it’s actually harmful. When you over complicate the code by adding extra features, you are making the code harder to read, understand, maintain, and test. By doing this, you’re creating bugs in your code. And you don’t know the future, and nine out of ten times your assumption will be wrong. Even if you were right that a feature would be necessary later, it might only be needed two years from now, and by then, you might have found a better way to do it. Focus on MVP.

7. Consistency
Imagine you go to a shop and there is no consistency over how the items are placed in the area. It would be hard to find the products you are searching for. Indentation in the code is much like the arrangement that you need in a supermarket. When your code is indented, it becomes more readable and easier to find what you’re looking for. Especially when you pay attention to the names of the items. Having a proper naming convention is extremely important in code for future edits. Having irrelevant or contradicting names for your pages, variables, functions or arrays will only create trouble for you in the future. Therefore, naming elements on the basis of what they are is a common rule helps a lot. It creates consistency and makes it easier to come back and work on the project at a later time.

Actually, this leads us to the next step for clean code – creating a common language, or a “ubiquitous language,” if you follow the ideas of Domain Driven Design. It seems obvious, but unfortunately, many developers skip this part. So, once again, I would like to repeat that the wording of code is very important because you want your variable names, class names, and package names to make sense no matter who is looking at the code.

8. Cost Savings
By doing clean code, you gain all those advantages listed above, and all of them lead to cost savings.

As a conclusion, I would like to say that you shouldn't be afraid to defend your project and your code. Build quality, working software and take as much time as you need. 

Many managers defend the schedule and requirements with passion, but that’s their job. It’s your job to defend your clean code with equal passion! It helps to increase the overall value, and reduce the overall cost, of both creating and maintaining software. It does this by focusing on creating reader-centric code that is simple, readable, understandable, testable, and maintainable.

If you are interested in knowing more about clean code, I recommend you to read these 2 books, written by Robert C. Martin:
