# links
Links are the defining feature of the web because they allow you to move from one web page to another — enabling the very idea of browsing or surfing.

**Type Links:** Links are created using element (a). Users can click anything between the open (a) and the closing (/a) mark. You specify the page you want to link to using the href attribute.

**Linking to Other Sites:** Links are created using element (a) which has a property called href. The href attribute value is the page you want people to go to when they click the link.

**Link to other pages on the same site:** (a) When you link to other pages within the same site, you do not need to specify the domain name in the URL. You can use an abbreviation known as Relative URL

**Directory structure:** On large websites, it is a good idea to organize your code by placing the pages for each different section of the site in a new folder. Folders on a website are sometimes referred to as directories

### Email Links:
**mailto:** To create a link that starts the user's email program and addresses an email to a specific email address, you can use item (a). However, this time the value of the href attribute starts with mailto: and is followed by the email address you want to send the email to.

### Opening Links in a New Window:
Target: If you want to open a link in a new window, you can use the target attribute in the opening tag (a). The value of this attribute must be _blank

Links are created using the (a) element. Element (a) uses the href attribute to indicate the page you are linking to. If you are linking to a page within your site, it is better to use relative links rather than qualified URLs. You can create links to open email programs with an email address in the To field. You can use the id attribute to target elements within the linkable page

# Layout
### Key Concepts in Positioning Elements
* Building Blocks: CSS treats each HTML element as if it were in its own box. This square will either be a block-level square or an inline square.
* Block level items: start on a new line
* Inline elements: flow between surrounding text

* Containing Elements: If one block-level element sits inside another block-level element then the outer box is known as the containing or parent element.

**Control the position of elements:** CSS contains the following positioning systems that allow you to control the layout of the page: normal flow, relative position, and absolute position. You can specify the GPS using the location property in CSS. You can also float items using the float feature.

**CSS Frameworks:** CSS frameworks aim to make your life easier by providing code for common tasks, such as creating layout grids, design models, creating print-friendly versions of pages, etc. You can include CSS framework code in your projects instead of writing CSS from scratch.

Dives are often used as containing elements to group page sections together. Browsers render pages in the normal flow unless you specify a relative, absolute, or fixed position. Float moves content to the left or right of the page and can be used to create multi-column layouts. (Floating elements require a specific width.) Pages can be either fixed width or fluid (extendable) layouts. Designers keep pages 960-1000px wide, and indicate what the site is about within the top 600px (to prove it fits without scrolling). Grids help create professional and flexible designs. CSS Frameworks provide rules for common tasks. You can include multiple CSS files on one page

# FUNCTION
**Functions:** Allows you to group a series of statements together to perform a specific task. If different parts of the script repeat the same task, you can reuse the function (instead of repeating the same set of statements).

 Browsers require very detailed instructions on what we want them to do. Therefore, complex scripts can run for hundreds (even thousands) of lines. Programmers use functions, methods, and objects to organize their code, and this chapter is divided into three sections that introduce

 ANONYMOUS FUNCTIONS & FUNCTION EXPRESSIONS: expressions produce a value. Can be used where values are expected. If a function is placed where the browser expects to see an expression (for example, as an argument to a function), it is treated as an expression.

 **Scope:** The location where you declare a variable will affect where it can be used in your code. If you define it within a function, it can only be used within that function. This is known as variable scope.

 **How memory and variables work:** Global variables use more memory. Your browser should remember it for as long as the web page you're using is loaded. Local variables are only remembered for the period of time the function is being executed.

 # 6 Reasons for Pair Programming:
  the software engineering practices that have proven to dramatically improve the quality of code developers produce:
1. Iterative loops 
2. Code reviews
3. Fast feedback
4. Error checking  
5. linting.
**pair programming:** is the practice of two developers sharing a single workstation to interactively tackle a coding task together.
### How does pair programming work?
While there are many different styles, pair programming usually involves two roles: driver and navigator. The driver is the programmer who writes and is the only one who has his hand on the keyboard. By dealing with the "mechanisms" of encoding, the driver manages the text editor, file swapping, version control, and of course writing. Navigator uses their words to guide the driver but does not provide any direct computer input. Navigator thinks about the big picture, what comes next, and how an algorithm can be turned into code, while looking for typos or errors. Navigator may also use its computer as a second screen to search for solutions and documentation, but no code should be written.
### Why pair program?
Pair programming touches on all four skills: developers explain out loud what the code should do, listen to others’ guidance, read code that others have written, and write code themselves.
1. Greater efficiency
A common misconception is that pair programming takes much longer and is less efficient. In fact, when two people focus on the same code base, it is easy to spot errors while making it.
2. Engaged collaboration
When two programmers focus on the same code, the experience is more engaging and both programmers are more focused than if they were working alone. It's hard to procrastinate or get off track when someone else is relying on you to get work done. Opening your Facebook timeline is less attractive when someone else is looking at your screen.
3. Learning from fellow students
Everyone has a different approach to problem solving; Working with a teammate can expose developers to technologies they wouldn't have thought of otherwise. If one developer has a unique approach to solving a particular problem, pair programming exposes the other developer to a new solution.
4. Social skills
Pair programming is great for improving social skills. When working with someone who has a different coding style, communication is key. This can become more difficult when programmers have two different personalities. Pair programming not only improves programming skills, but it can also help programmers develop their interpersonal skills. When just holding the keyboard and taking charge isn't an option, mastering finding the right words is a skill in itself.
5. Job interview readiness
A common step in many interview processes involves pair programming between the current employee and the applicant, either in person or through a shared screen. They will perform exercises together, such as code challenges, building a project or feature, or debugging an existing code base. By doing this, companies can get a better feel for how the applicant fits in with the team and their style of collaboration.
6. Work environment readiness
Many companies that use pair programming expect to train new employees from CS degree programs on how they can work to actually deliver a product. Code Fellows who are familiar with how the pairing works can start working in a new job, with one less hurdle to overcome.