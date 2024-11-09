In my [Building a DevOps Team](./blog/building_devops.md) post, I wrote that you should "Remember to look for open source contributions from the potential DevOps engineers; most engineers keep the code they write handy."

I'd like to provide a little more context on what I look for from those open source contributions when reviewing a potential candidate.

Do:
- Ensure the repos you create follow a standard format. Time spent learning where everything is on each repo is time I'm not spending looking at how well you solve problems.  Time is usually the critical resource.
- Follow industry standards/style guidelines for the code you write. Using an [IDE](https://code.visualstudio.com/) is common now, and following the given style(python example: Pylint, PEP 8) makes it easier to read.
- Refactor your non-trivial code at least once to ensure that it provides a good example of what you know. As you create the third similar function to address a slightly different use case, rewrite it to solve the general case. If the language supports it, consider using constructs (e.g., Classes, Modules, Libraries) to encapsulate functionality. When you are working with others or will need to revisit the code in the future, solve the problem in a maintainable way.
- Provide a good README.md which describes the problem, how you solved it, perhaps why you solved it in the given manner, any configuration necessary, and how to expect the solution. If you have future plans for it, add them as well.
- Use comments within the code for describing different components as well as complex sections and non-obvious design choices.
- Provide code you are proud of... not just examples of various patterns.

Don't:
- Focus on the fewest lines for solving a problem. [Code Golf](https://code.golf/) is a fun game, but I usually look at potential code assuming I will have to debug it at 2AM when it fails while the creator is on vacation or has left the company. 
- Add the kitchen sink. As Antoine St. Exupery wrote: "Perfection is achieved, not when there is nothing more to add, but when there is nothing left to take away." 

I probably should add more about User Interface do's and don'ts, but I'd probably just end up rewriting [this guide](https://www.joelonsoftware.com/2001/10/24/user-interface-design-for-programmers/), and it looks like I need to clean up my repos now.



