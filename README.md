**QUESTION 2**

1\. Five Most Challenging Elements and Why



<a> (Anchor Tag): Managing relative file paths (index.html, about.html, professional.html) consistently across navigation menus required precise naming to avoid broken links.  

&#x20;   



<section>: Planning logical boundaries for page content without relying on generic wrapper tags required thoughtful content grouping.  

&#x20;   



<ul> \& <li> (Unordered List and List Items): Formatting structured list items inside section containers required clean indentation to ensure readable markup.  

&#x20;  



<header>: Integrating nested typographic tags (<i>, <b>) alongside structural navigation links (<p>, <a>) inside a single block required careful syntax balancing.  

&#x20;   



<meta>: Configuring proper document metadata (charset="UTF-8", name="viewport") required strict adherence to standards for proper mobile rendering.  

&#x20;   



2\. Use of Semantic Elements



&#x20;   <header>: Encloses the primary site heading (<h1>) and horizontal navigation bar across all pages.  

&#x20;   



&#x20;   <section>: Groups thematic page content into distinct blocks using specific IDs (id="home", id="about", id="professional").  

&#x20;   



&#x20;   <footer>: Anchors the bottom of each page to hold standardized copyright metadata.  

&#x20;   



3\. Most Useful Element for Layout Organization



The <section> element was the most useful for layout organization. It cleanly separates unique page body content from repetitive global structural components like <header> and <footer>. By wrapping page topics in dedicated <section> blocks with unique id attributes, the site layout remains modular, easy to navigate, and semantically clear for screen readers and search engines.  





**QUESTION 3**

1\. Three Essential Attributes for Functionalityhref: Used in <a> anchor elements to define page destinations (index.html, about.html, professional.html), enabling internal site navigation.  charset: Declared inside <meta charset="UTF-8"> to set standardized character encoding, ensuring correct browser rendering of text characters.  id: Applied to <header> and <section> tags (id="top", id="home", id="about", id="professional") to uniquely identify structural DOM containers on each page.  



2\. Difference in id and class Implementationid Attribute: Used exclusively to uniquely mark single structural containers per page (e.g., <header id="top">, <section id="about">), maintaining unique identity per document.  class Attribute: Was not utilized in this specific HTML codebase, as there were no recurring element groups requiring shared class-based CSS styling or JavaScript selection. 



3\. Attribute Most Improving User ExperienceThe title attribute provided the most direct UX enhancement. Added to the navigation link tags (title="Go to Home", title="Go to About", title="Go to Professional Life"), it delivers native desktop hover tooltips that explicitly clarify link intent and destination before a user clicks.  



**QUESTION 4**



1\. Site Planning Strategy



Three-Page Structure: I split the site into index.html, about.html, and professional.html to keep things organized. The index serves as the main overview, the about page covers general background, and the professional page highlights tech skills and contact info.



Shared Header \& Footer: To give the site a consistent feel, every page shares the same top navigation (<header id="top">) and a standard copyright footer (<footer>).



Organized Content: I grouped page-specific content inside dedicated <section> tags (using IDs like #home, #about, and #professional) to keep the HTML clean and readable.



2\. Testing \& Debugging



Browser Checks: I tested the site across different desktop browsers to make sure text rendered correctly and layout alignment stayed intact. Link Audits: I clicked through every relative link between index.html, about.html, and professional.html to guarantee smooth navigation without any dead ends.



HTML Cleanup: I reviewed the code to fix any tag nesting and closing issues, ensuring tags like <i><b> inside <h1 align="center"> were closed in the exact reverse order they opened.



**QUESTION 5**

1\. Git Commands Used



&#x20;   git init: Initialized the local repository right inside the project folder.



&#x20;   git status: Kept tabs on untracked, modified, or staged files before pushing anything through.



&#x20;   git add <file> / git add .: Staged specific HTML/CSS tweaks (or all changes at once) for the next snapshot.



&#x20;   git commit -m "message": Saved clean snapshots of staged code along with clear, summary messages.



&#x20;   git remote add origin <URL>: Linked the local repository to the remote GitHub repo.



&#x20;   git push -u origin main: Uploaded local commits to GitHub and set the default upstream tracking branch.



&#x20;   git log --oneline: Ran quick checks on the commit history to verify milestones and confirm accurate tracking.



2\. Commit Count \& Strategy



Total Commits: 12 commits across the project build.



Commit Strategy: Followed an incremental, milestone-driven workflow. Instead of making one massive commit at the end, code was saved in small, logical chunks after completing individual tasks (like setting up page layouts, verifying link paths, or building out global headers and footers).



Prefix System: Applied standard structural tags to keep the commit log readable:



&#x20;       init: repo initialization and baseline file setup



&#x20;       feat: building core markup for the index, about, and professional pages



&#x20;       refactor: standardizing global header and footer elements across all pages



&#x20;       fix: resolving HTML tag nesting errors and fixing relative file paths



3\. Why Version Control Matters in Web Development



Safety Net \& Easy Rollbacks: If a rogue CSS rule or broken JavaScript breaks the entire layout, version control lets you instantly revert to the last working build without losing progress.



Granular Tracking: A line-by-line history of changes makes bug hunting straightforward—you can pinpoint the exact commit where something broke.



Seamless Collaboration: Multiple developers can build separate features on independent branches simultaneously without stepping on each other's code or corrupting the main codebase.



Offsite Backup \& Deployment: Pushing code to platforms like GitHub protects against local hardware failure and integrates directly with modern hosting platforms for fast deployment.





**QUESTION 6**

1\. Ensuring Valid and Error-Free HTML



Editor Linting: Used built-in editor linting in VS Code to flag syntax mistakes and missing closing tags in real-time as the structure was being built.



Browser DOM Inspection: Checked the page source and inspected the DOM tree in the browser to verify that the element hierarchy rendered as expected and that relative file links (href and src) pointed to the right files without broken paths.



Manual Code Walkthrough: Read through the raw markup line by line to double-check that every opening tag had a matching closing tag and that headings followed a logical <h1> to <h6> order.



2\. Best Practices for Clean, Readable Code



Semantic HTML Markup: Relyed on proper structural tags (<header>, <nav>, <main>, <section>, <article>, <footer>) rather than relying purely on generic block tags or unformatted text.



Consistent Indentation \& Formatting: Maintained uniform 2-space indentation throughout every document so parent-child element relationships are easy to read at a glance.



Lowercase Syntax \& Quoted Attributes: Kept all HTML tags, attributes, and file names strictly in lowercase, and wrapped every attribute value in quotation marks (href="about.html").



Section Comments: Placed concise HTML comments (<!-- Navigation Bar -->, <!-- Main Content Area -->) to clearly separate major document sections.



Clean Project Directory: Kept all page files neatly organized at the root level using simple, descriptive file names (index.html, about.html, contact.html).



3\. Future Improvements with More Time



Introduce CSS for Styling: Add external Cascading Style Sheets to introduce proper visual layouts, custom typography, color themes, and responsive design for mobile screens.



Incorporate JavaScript: Add client-side scripting to create dynamic elements like interactive form verification, collapsible menus, or media sliders.



Expand HTML Content \& Media: Add structured tables, interactive forms, embedded audio/video elements, and extra sub-pages to build out a more complete site structure.



Enhance Accessibility: Integrate full ARIA (Accessible Rich Internet Applications) attributes and landmark roles so screen readers can easily navigate the raw markup.

