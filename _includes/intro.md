*Schedule:* Wednesdays 9-10AM at Johnson Pavilion 209

*Format:*

* Function/library of the week

  FotW presenter will tell us about any useful function or library and give a brief example on how to use it. Bonus points for running an example live! Maximum 10-15 minutes.

* Code review

  Code presenter will send out a code selection on Monday by lab
  meeting time. The ideal body of code for a review session is 100
  lines long, with clear start and end points. You do not need to be
  the author of 100% of the code. It should be from a project that you
  are working on currently.

*Presenters list:* Kyle, Aubrey, Erik, Ceylan, Chunyu, Scott, John, and Chris. Others, please email Kyle if you would like to present.

*Rules:* No slides allowed! Please do not waste time making a presentation. Let's just look at the code and talk.

*For presenters:* In your email, include a link to a Git or SVN repository where the code lives (code can be attached to the email if needed). In the email, also describe the motivation for this segment of code, your goals for writing the software, and the expected input/output.

*For reviewers:* Please read the code before the review meeting. See checklist below for some things to consider.

*For everyone:* I will do my best to foster a positive and motivating environment where we work together to learn from each other and improve our craft. Please talk to me or Rick privately if you feel like this is ever not the case.

*Checklist for code review:*

* Tests: Does the code have any tests? If not, are examples of input/output provided?
* Functions: Are functions/methods taking the right type of arguments? Does the function return one type of result? Are functions and methods able to be easily tested?
* Null/empty values: Will the code work if Null values are passed? If functions can return Null, will this work with the rest of the code?
* Idioms: Is code idiomatic where possible?
* Safety: Are tasks completed in the safest way possible? Will some valid inputs cause errors?
* Comments: Are tricky spots commented? Do comments describe intent?
* Documentation: Is there any documentation of functions? Is a README file included? What level of documentation makes sense at the current stage of development?
* Version control: How can commit messages be improved?
* Design (SUPER IMPORTANT): Are functions, classes, and modules well organized? Are functions or methods able to be easily tested? Could we do more to decrease coupling between functions, or to increase separation of concerns? Are we taking advantage of polymorphism when using objects?
* Examples of good practice: Do you notice particularly good habits in the code, which might be useful on other projects?
