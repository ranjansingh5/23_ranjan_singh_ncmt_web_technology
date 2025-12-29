# Chapter-3 WEBSITE STRUCTURE DESIGN
# Group A: Short Questions📌
---
# 1. Define Information Architecture (IA).❓
-> Information Architecture (IA) is the practice of organizing, structuring, and labeling website content so users can easily find information and navigate the website effectively.

---
# 2. What is a “Wireframe”?❓
-> A Wireframe is a basic visual blueprint of a web page that shows the layout, structure, and placement of elements without design details like colors or images.

---
# 3. Explain the concept of “Cognitive Friction” in web design.❓
-> Cognitive Friction refers to the mental effort required by users to understand or use a website. High cognitive friction makes a website confusing, while low cognitive friction makes it easy and smooth to use.

---
# 4. Why should URL slugs use hyphens instead of underscores?❓
-> URL slugs should use hyphens because search engines treat them as word separators, making URLs more readable and SEO-friendly. Underscores join words together and reduce readability.

---
# Group B: Long Questions📌 
# 5. Compare and contrast Hierarchical (Tree) structure and Linear (Sequential) structure. Give an example of when to use each.❓
-> A website’s structure defines how information is organized and how users navigate through it.
* Hierarchical (Tree) Structure
In a Hierarchical structure, information is organized like a tree with a main page at the top and sub-pages branching below it. Users can move from general information to more specific details.
* Characteristics:
- One main homepage with multiple levels of sub-pages
- Easy to scale and organize large amounts of content
- Users have multiple navigation paths
* Example:
An e-commerce website where the homepage leads to categories (Electronics, Clothing), then to sub-categories (Mobiles, Laptops), and finally to product pages.

* Linear (Sequential) Structure
In a Linear structure, pages are arranged in a fixed sequence. Users move step-by-step from one page to the next, usually in one direction.
* Characteristics:
- Simple and straightforward navigation
- Limited user choice
- Best for guided processes
* Example:
An online exam, tutorial, or checkout process where users must complete one step before moving to the next.

---
# 6. Explain the ”Three-Click Rule” and its significance in User Experience (UX) design.❓
-> The Three-Click Rule suggests that users should be able to find any information on a website within three clicks from the homepage.
* Explanation:
- If users take more than three clicks to find content, they may feel confused or frustrated.
- It encourages designers to keep navigation simple and logical.
* Significance in UX Design:
- Improves usability and user satisfaction
- Reduces frustration and bounce rate
- Helps users reach information quickly
- Encourages clear menus and better content organization
Although not a strict rule, it is a useful guideline for creating user-friendly websites.

---
# 7. ”Plan before you do.” Explain how tools like Card Sorting and Flowcharts help in planning a website’s structure.❓
-> Planning tools help designers visualize and organize a website before development begins.
* Card Sorting
Card Sorting is a technique where content topics are written on cards and grouped based on user understanding.
* How it helps:
- Reveals how users expect information to be organized
- Helps create logical menus and categories
- Improves navigation and user experience
* Example:
Users group cards like Admissions, Exams, Results under a single menu called Academics.

---
# Group C: Scenario-Based Questions📌
# 8. You are designing a website for a University. It has hundreds of pages (Admissions, Departments, Alumni, News). Which structural model would you choose? Draw a rough diagram and justify your choice.❓
-> For a university website with hundreds of pages, the most suitable structural model is the Hierarchical (Tree) structure.
* Reason for choosing Hierarchical Structure:
- A university website contains a large amount of information.
- Content naturally falls into categories and subcategories.
- Users (students, faculty, alumni, visitors) look for specific information quickly.
- This structure allows easy scalability when new departments or pages are added.
*Hierarchical Structure (Diagram)
                  Home
                   |
    --------------------------------
    |        |          |          |
Admissions Departments  Alumni     News
    |           |          |         |
 Apply      Science     Events    Notices
 Fees       Arts        Stories   Updates
 Dates      IT

* Justification:
This structure allows users to move from general to specific information in a logical way. It improves navigation, reduces confusion, and makes large websites easier to manage and understand.

---
# 9. A user visits a website but leaves within 10 seconds because they cannot find the navigation menu, which is hidden behind a small icon on a desktop screen. Analyze this design failure using the ”KISS” (Keep It Simple) principle.❓
-> The KISS principle (Keep It Simple) states that a design should be clear, obvious, and easy to use without forcing users to think.
* Analysis of the Design Failure:
- Hiding the navigation menu behind a small icon on a desktop screen adds unnecessary complexity.
- Desktop users expect the menu to be clearly visible, not hidden like on mobile screens.
- The user could not immediately find the navigation, causing confusion.
- Due to this confusion, the user left the website quickly, increasing the bounce rate.
* How this violates the KISS principle:
- The design is not simple or obvious.
- It increases cognitive friction.
- Important elements (navigation) are hidden instead of being visible.

---
# 10. An e-commerce website has a URL structure like www.shop.com/prod?id=55&cat=9. Explain why this is bad for both users and Search Engines (SEO), and propose a better structure using Page Slugs.❓
-> This URL structure is poorly designed for both users and search engines.
* Problems for Users:
- The URL is hard to read and understand.
- Users cannot guess what the page contains.
- It looks technical and untrustworthy.
- Difficult to remember or share.

* Problems for Search Engines (SEO):
- Search engines prefer descriptive URLs.
- Parameters like id=55&cat=9 provide no keyword value.
- Poor readability affects search ranking.
- URLs are not optimized for indexing.

* Why this is bad overall:
- Low user trust
- Poor SEO performance
- Reduced click-through rate

* Better URL Structure Using Page Slugs:
A better, SEO-friendly URL would be:
www.shop.com/electronics/smartphone-samsung-galaxy

* Benefits of Page Slugs:
- Easy for users to understand
- Clearly describes page content
- Includes keywords for SEO
- More professional and trustworthy
- Improves search engine ranking