    Question 1: WEBSITE CREATION
A Header section: This section includes my name, which is GIFT KAPESA, and my current status as a student of Information Communication University.
An About Me section: A short summary of my background, interests, and experience in technology and web development.
A Skills section:A categorized list of my technical skills and soft skills, such as basics of HTML and Git/GitHub.
An Education section listing that I am studying Interactive Web Development, Electronics for Computing and other modules as part of my degree program.
Projects: Presenting my work, such as this HTML portfolio.
Contact: I include my professional email and GitHub profile for opportunities to connect with me.

Question 2: HTML Elements 
1. which 5 elements did you find most challenging to implement and why?
. <nav> and <a> (internal links): setting up the navigation was a bit trickly because i had to ensure the id attributes in the sections (like id="about") matched the href in the links exactly (like href="#about") for the "jump" effect to work.
. <address>: i had to learn that this isn't just for physical street addresses; it is the semantic way to wrap contact info like email and github links.
.<abbbr>: getting the syntax right for the title attribute so that a tooltip appears when someone hovers over "ICU" took a couple of tries.
.<time>: using the datetime attribute was new to me. i had to make sure the machine-readable date format (yyyy_mm_dd)was correct even though the text says "february 2026."
.<img>: managing the file path for the image (making sure the filename matched the code exactly) was a challenge at first to ensure the picture actually displayed.

2.how did you use semantic elements (like <section>, <article>, <header>, <footer>) to structure your content?
I used these elements to give the page a logical "map" so that it's easy for both humans and machine to read:
.<header> and <footer>: i used these to "bookend" the site-the header introduces me, and the footer contains the copyright.
.<section>: i used these to divide the page into clear chapters (about, skills, education, etc.). each section acts as a container for a specific topic.
.<article>:vi used this inside the Education and project sections. it's perfect for content that can stand alone, like a specific degree project description.

3.which element was most useful for organizing your layout and why?
the <main> element was the most useful for organization. by wrapping all my core sections inside <main>, it clearly separated my actual portfolio content from the repeated parts of the site like the navigation and footer.
it acted as the "parent" cointer that kept the whole body of the website organized and centered.

QUESTION 3: which attribute helped improve user experience the most and why?
the target="_blank" attribute helped the most.
By using this on my GitHub link, it ensures that when a user clicks it, my profile opens in a new tab. this keeps my portfolio website open in the original tab, preventing the user from accidentally leaving my site while they explore my work.

QUESTION 4: DEVELOPMENT PROCESS 
1.How did you plan your website structure before coding?
i started by wireframing the layout on paper. I decided which sections were most important for a student portfolio (about, educaion, projects) and mapped out a hierarchy using a "top-down" approach. i planned to use a navigation bar at the top for easy access and main container to hold the core content. i also list the specific information i wanted to include, such as my course list at ICU, to ensure ichose the right HTML element(like <ul>for courses) before i began typing.

2. what was youur approach to testing and debugging your HTML?
my approach was iterative. i used the following steps;
. live previewing: after writng each section, i opened the file in the web browser (like chrome or edge) to see if the structure looked correct.
.Link verification: i clicked everly link in the<nav> and the <address> sections to ensure the href attributes were pointing to the correct IDs and external URLs.
.Validation: i checked for common mistakes like unclosed tags (e.g., making sure every <li> had a </li>) and ensured attributes were wrapped in quotation marks.
.Developer tools: i used the "inspect" tool in the browser to check the DOM tree and ensure elements were nesting exactly where i intended.

3.what challenges did you face and how did you overcome them?
one major challenges was managing the image path. initially, my image wouldnt load because i had a typo in the filename. i overcame this by double-checking the file extension (.JPG vs .JPG) and ensuring the image was in the same folder as my index.html file.
another challenge was semantic accuracy. i initially struggled with when to use <article> versus <section>. i overcome this by researching the documentation, learning that <article> is for independent content (like a specific project) while <section> is for grouping related content (like the "about" area). this helped me make the code more professional.

Question 5: Git and GitHub implementation 
1.what git commands did you use during development?
during the development of my portfolio, used the following core Git commands:
.git init: to initialize my local reposistory.
.git add . :to stage my html file and image for a commit.
git commit -m "message" : to save snapshots of my progrss.
. git remote add origin : to link my local project to my GitHub repository.
.git push -u origin main : to upload my code to GitHub.

2how many commits did you make and what was your commit message strategy?
i made approximatelty 5 to 7 commits. my strategy was to commit after every major milestone to keep the history organized. for example:
.feat: initia project structure.
.feat: added education and skills sections.
.fix: corrected image path and contact links.
. docs: finalized readme with assignment answers.

3.why is version control important for web development project?
version control is essential because it acts as a "safety net." if i make a mistake that breaks my layout, i can easily revert to a previous working version. it also allows me to track exactly what changes were made and when, which is vital when collaborating with other developers or managing large, complex websites.

QUESTION 6: code quality and best practices
1.how did you ensure your HTML was valid and error-free?
 I ensured my code quality by using two main methods:
 .W3C validator: I ran my code through the offical HTML validator to check for missing closing tags or nesting errors.
 .manual cross-browser testing: I opened the file in different browsers (like chrome ) to ensure the semantic structure remained consistent and the images loaded correctly.

 2.what best practices did you follow for writting clean, readable code?
indentation: I used consistent spacing to show the nesting of elements (like <li> inside <ul>).
.comments: I added hidden notes in the code to label where sections began and ended.
.semantic naming: I used meaningful IDs (like id="contact") rather than generic names, making the code easier for another developer to understand.

3.how would you improve your website if you had more time?
if i had more time, i would:
.Add more projects: I would include a "Gallery" or "portfolo" grid with screenshots of other assignments.
.Accessibility: I would add more aria-labels and ensure the color contrast meets high accessibility standards for users with visual impairments.