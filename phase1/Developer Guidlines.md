# Developer Guidlines
Coding Guidelines for Developers

This living document provides useful advice for software developers who either create or contribute to the system. The recommendations cover:
1- Documentation and coding practices
2- References to codes of conduct
3- How tasks are carried out and how developers interact with each other and users

Code of Conduct
Each of these points is designed to help the technical team collaborate effectively with the executive team in making decisions and guiding the project toward success.
If you occasionally write code or work outside the Anaqati development team, you should read the entire document at least once, but there's no expectation that you'll remember every detail.
If you're part of the Anaqati development team, these guidelines are essential reading.

Developer Interactions
All team members must adhere to the community guidelines and documentation. Developers should communicate with one another via email or MS Teams.
These are guidelines rather than fixed rules. We believe that they will help optimize our workflow, enhance teamwork, and benefit both individual developers and the products we create together.
Anaqati system developers are happy to assist with any questions regarding the contents of this document.
Remember, the goal of these guidelines is to improve everything we create so we can proudly say, "I was part of that!" We should not lose momentum by trying to follow these guidelines too rigidly. If you feel they're slowing progress too much, we should review them. They are not set in stone.

Code Formatting
Each line should contain only one command.
Code blocks should be separated by a two-line margin.

Code Scope
Use default constructors for classes that only have default constructor values.
Use the "final" keyword unless it's for constants.

Additional Code Information:
Variable names should be descriptive and relevant to their purpose.
Every group or block of code should have a short comment explaining what it does.

Further Considerations When Writing Code
Writing Secure Software
While it may not always be the most exciting part of programming, it's crucial to consider the security risks associated with a project to avoid costly fixes and damage to your reputation. Security risk assessments should start early and continue throughout the project.

The security risks will differ from project to project, but general guidelines include:
Educate yourself on the security risks tied to various project components.
Don't rely solely on out-of-the-box software or default settings, such as open-source libraries, AWS services, etc. These may contain malicious software, and default configurations typically prioritize ease of use over security.

What Programming Language Should I Use?
There are no strict rules about which programming languages Anaqati software should use. However, keep in mind that any software you build will need to be maintained by you and your colleagues (now and in the future), so we want to avoid unmaintainable code. Right now, we are using HTML, CSS, and JavaScript, and we are open to changes that will improve the project.

Code Comments
Code should be commented to explain why it does what it does. Ideally, what it does should be clear from the code itself. If the code is unclear or can't be easily simplified, comments are necessary. A good comment will clarify the purpose.

Readability
Use consistent indentation.
Make good use of horizontal whitespace (code blocks/paragraphs). There is no need to compress code into as few lines as possible.
Try to avoid long lines of code (over 75-80 characters) whenever possible.

Feature Requests
We welcome new feature requests. Before submitting, please take a moment to assess whether your idea aligns with the scope and goals of the project. It is your responsibility to make a strong case for the feature to the project maintainers. Be sure to include as much relevant information and context as possible.

Pull Requests
Quality contributions include good pull requests for patches, improvements, new features, etc. However, please keep the scope of your pull request focused and avoid irrelevant commits.

Before starting a significant pull request, it's recommended to ask a maintainer if the scope of the changes is reasonable for merging into the project. Otherwise, you risk wasting time on something not aligned with the project's goals.
Please include a description of your intent when creating a pull request. By default, we request that you pull from the master branch.

Bug Reports:
Key points to consider:

Title: Keep it short and clear. Explain what the bug is in detail.
Summary: Include when, where, and how the bug occurred if the title isn’t enough.
Visual evidence: A screenshot or video can help the developer understand the issue quickly.
Expected vs. Actual results: Keep it concise.
Reproducible steps: List the steps that led to the bug.
Environment: Include details like browser, operating system, screen size, and zoom level.
Console log: Identify the source of the issue.
Source URL: Help the developer find the issue faster.
Severity/Priority: Indicate how critical the bug is and how soon it should be addressed.
Reporter name, assignee, due date, and customer/user interaction

Keep in mind that adding irrelevant or unclear information will make it harder to identify the issue. Avoid submitting duplicates. Once you have all the necessary information, compile it into a report and email it to anaqati.476@gmail.com.
