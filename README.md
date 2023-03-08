#Test 3 Analysis

### HTML & CSS:

1. What is the difference between HTML elements and HTML tags?

* HTML Tags are for building blocks of HTML page. 
* HTML Elements are components that are used in HTML page.

2. Why is id a tag in HTML?

* The purpose of an id tag is to identify the element when linking, scripting, or styling(CSS).

3. What is an anchor tag?

* Hyperlink, used to link from one page to another.

4. What is a HTML attribute?

* HTML attribute provides additional information about elements. eg. name="value"

5. What is the difference between semantic and non-semantic tags?

* Semantic element clearly describes its meaning to both the browser and the developer. 
* Semantic elements: form, table, article, nav, section, main, footer...etc
* Non-semantic elements: div, span

6. Why should we use IDs?

* To identify the element when linking, scripting, or styling(CSS).

7. What is CSS?

* Cascading Style Sheets for adding style to web documents, decorating web pages. A bad example: [click me](https://manhimyeung.github.io/MyProfile/)

8. What is the CSS box model?

* A box that wraps around every html element, it consists of margins, borders, padding and the content.

9. Where in the HTML document do we link to a CSS file?

```CSS
    <head>
    <link rel="stylesheet" href="styles.css">
    </head>
```

### Web & Mobile Testing

1. What is visual testing?

* Visual testing provides testers evidence that their applications behave correctly across operating systems, devices and browsers.

2. What is meant by responsive design?

* Responsive design is the approach that suggests that design and development should respond to the user's behaviour and envioronment based on screen size, platform and orientation.

3. Why is responsive design important?

* Offers an optimised browsing experience, keeps customers visiting.

4. What is web and device fragmentation?

* Fragmentation is the diversity of browsers, devices, and platform versions in use at any given point in time. 

5. What is cross-browser testing?

* Cross-browser testing is a type of non-functional software testing where applications are checked for support across different browsers and devices.

6. How does web fragmentation relate to web testing?

* Inconsistencies in user experience
* Compatibility issues

7. What is the difference between functional and non-functional web testing?

* Functional testing ensures that the functions and features of the application work properly.
* Non-functional testing examines other aspects of how well the application works.

### Introduction to BDD

1. What is the structure of a Gherkin script?

* Scenario: User wants to login to check balance
* Given: I am on the sign-in page
* When: I enter valid email
* And: I enter valid password
* Then: I should land on customer portal.

2. What is meant by declarative and imperative style?

* In user story, an imperative style describes in detail how the software product has to behave. (eg. include exact credentials)
* A declarative style focuses on specifying the expected result.

3. Explain the BDD development Process.

* Discovery: Define requirements in user stories.
* Forumation: Create Gherkin scripts based on the user stories to guide the devevelopment team building the product and the QA team to test the product.
* Automation: Write test cases and the developer team would improve their code to past all the test cases.

### Test Automation 

1. What is the test automation pyramid?

* The testing pyramid is a framework that can help both developers and QAs create high-quality software. It reduces developers' time to identify if a change they introduced breaks the code. It can also help build a more reliable test suite.

* Unit tests, integration tests, end-to-end tests

2. What is meant by the 70/20/10 split mean in the context of the Test Automation Pyramid?

* 70% Unit tests, 20% Integration tests, 10% End-to-end tests

3. What is Selenium IDE and how can manual testers use it?

* Selenium IDE is an open source test automation tool that can record and playback users' actions on the website. 
* Manual testers can use selenium based on the given gherkin scripts to get values.

4. When should you automate test?

* When you want to run the same test cases across multiple machines at the same time.

5. What is the purpose of the Agile Test Quadrants

* Agile test quadrants are a visual tool for understanding different QA tests. They differentiate between business and technology facing tests, and those that support programming or 'critique' the product. Testing types are sorted into these four categories on a grid.

![ATQ](https://cdn.discordapp.com/attachments/1083147322835349554/1083147340015227032/image.png)

* Q1: Unit and component tests are performed throughout your application's development. They provide feedback to your developers on the quality of their code on an ongoing basis, usually through repeated, automated processes.

* Q2: With a combination of manual and automated tests, these 'business-facing' tests are more customer-focused, but they support your application build as well. These include functional tests, which ensure the product does what it is meant to do.

* Q3: User Acceptance Tests (UAT), usability and exploratory testing all belong in this quadrant. These involve manual testing by experienced QA engineers and end-user testing. Your aim here is to gain feedback and improve the quality of the product, ensuring it is fit for the designed purpose.

* Q4: These are technology-facing performance tests, like load testing and checking the data security of your software application. There are many tools available to automate this type of testing, such as Selenium used alongside JMeter.

6. Which part of the test quadrant do non-functional tests such as performance testing fall under?

* Q4 (Tools)

7. Which part of the test quadrant do unit tests  fall under?

* Q1 (Automated)

8. Which part of the test quadrant do functional tests fall under?

* Q2 (Automated & Manual)

9. Which part of the test quadrant do UAT and Functional Testing fall under?

* Q3 (Manual)

### Usability Testing

1. What is usability?

* Usability refers to how easily a customer can learn and use a product to accomplish a specific goal.

2. What is the difference between usability and user experience?

* Usability refers to how easily a customer can learn and use a product to accomplish a specific goal.
* User experience refers to all aspects of a user’s interaction with and perception of a company’s product, services, or brand.

3. What are the benefits of usability testing?

* Meet user's expectation, improve users' experience, discover hidden issues, ensure the app's functionality matches the requirements.

4. What are the disbenefits of usability testing?

* costly, time consuming, cannot be automated, not suited to AI.

5. Describe the usability testing feedback loop.

Feedback loops are processes where designers use a system’s outputs as inputs to find cause-and-effect relationships within it.

6. What are the 3 most commonly used usability testing methods?

* In-Person: user is observed by a "test conductor" as they use the application.

* Monitored remote: user is observed by a "test conductor" remotely

* Unmonitored remote: user carries out the tasks, the results are reviewed by the "test conductor" afterwards.

7. What are the benefits of each of these testing methods?

* In-person: allows the moderator to note physical, verbal, and emotional responses.

* Monitored remote: less expensive, less time-consuming, more convenient for participants

* Unmonitored remote: same as monitored remote

8. What should testers look out for in regards to web usability?

* clear and sensible flow through the system, header and footer navigation, standardised icons, useful errors and validation messages, suggestions for search results, descriptions or hint text for fields in forms.

### Accessibility Testing

1. What is meant by accessibility?

* The practice of making information, activities, and/or environments sensible, meaningful, and usable for as many people as possible.

2. What type of things do we look out for during accessibility testing?

* Font style and size, colour contrast, visited links, hover effects, alternate text for images, audio and subtitles for videos, language options, keyboard friendliness, zoom in and still work, poorly labelled form fields.

3. What are some examples of accessibility standards?

# Need to rewatch video

4. What are the 4 principles of WCAG? Explain one with an example.

* Perceivable, Operable, Understandable, Robust.

5. What are the 3 levels of WCAG Conformance?

* Level A - covers the most basic web accessibility features
* Level AA - denotes the biggest and most common barriers for disabled users
* Level AAA - tackles the highest level of web accessibility

6. What is the difference between WCAG, WAI-ARIA and ARIA?

# Need to wewatch video
* WCAG - Web Content Assessibility guidelines
* WAI-ARIA - Web Assessibility Initiative - Assessible Rich Internet Application

7. Name some accessibility tools and how they are used.

* Spectrum
* Wave
* ChromeVox
* W3C CSS Validator