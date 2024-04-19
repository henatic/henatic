![](./profile-3d-contrib/profile-night-green.svg)
<!-- Original GIF for profile
<div align="center">
  <img src="https://media4.giphy.com/media/dxn6fRlTIShoeBr69N/giphy.gif?cid=ecf05e47e387wrkdtx6drx3ssrv7w2yulhtnv7jy1ndlwoa1&rid=giphy.gif&ct=g"/> 
</div>
-->
<div id="badges" align="center">
    <a href="https://www.linkedin.com/in/henry-morgan-938485227">
        <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
    </a>
    <a href="https://www.freecodecamp.org/henatic">
        <img src="https://img.shields.io/badge/freeCodeCamp-2a2b40?style=for-the-badge&logo=freeCodeCamp&logoColor=white" alt="freeCodeCamp Badge"/>
    </a>
</div>
<h1>About Me! 🧠</h1>
<p>My name is Henry Morgan (not to be confused with Captain Morgan 🏴‍☠️).<br>I enjoy coding and learning to code in multiple areas of study in Computer Science.  I continue coding practice by using <a href="https://www.freecodecamp.org/">freeCodeCamp</a> and <a href="https://leetcode.com">LeetCode</a>! 💻</p>
<p>I am a motivated problem solver and strong communicator looking to prove how knowledgeable and value, and I look for opportunity to advance and expand my current skillset.  If I get the opportunity to do so, I'd also like to earn a Masters degree in Computer Science and/or Software Engineering.</p>
<h2>Work 🕴️</h2>
<h3>Nylex.net, Inc.: September 2022 - Present</h3>
<p>Currently, I work for <a href="https://www.nylex.net/">Nylex.net</a> as an Automation Technician.  My job is to work on projects for clients and the company using software engineering practices.  My most noteable project during this position is the Project/Promo Initiation (See Projects section for more info).</p>
<h3>Little Caesars: August 2017 - December 2017</h3>
<p>First job was making pizza pizza during my first semester in college.</p>
<h2>Education 👨‍🎓</h2>
<h3>California State Polytechnic University, Humboldt (Cal Poly Humboldt): 2020 - 2022</h3>
<p>I'm a Computer Science graduate with honors from California State Polytechnic University, Humboldt (formerly known as Humboldt State University).</p>
<p>I have been awarded the Computer Science Outstanding Student of the Year 2021-2022, from the Cal Poly Humboldt Department of Computer Science.</p>
<h3>College of the Redwoods: 2017 - 2020</h3>
<p>I attended College of the Redwoods to complete all the prerequisites I can take before transferring my way to a university.  In the process, I earned an associates degree in Liberal Arts: Science Exploration.</p>
<h2>Projects 👨‍💻</h2>
<h3><a href="https://github.com/Nylex-net/PPI-Build2">Project/Promo Initiation (PPI)</a></h3>
<p>One of the main reasons why I was hired at Nylex.net was because they needed help from someone to program an initiation system for the company SHN.  SHN is an engineering consultant company based in Eureka, California, and they needed an internal form to initiate new projects and promos by doing the following:</p>
<ol>
  <li>Have the user enter PPI info into a multi-page web form.</li>
  <li>View their inputted information.</li>
  <li>Send to a server to manage the data.</li>
  <li>Insert the data into a Projects database to be used for searching, modifying, and updating information.</li>
  <li>Create the necessary directories within a shared drive to host project information.</li>
  <li>Apply Windows Protections to the folders that require it.</li>
  <li>Create a PDF to summarize all of the user's submitted information.</li>
  <li>Grab emails from admins and the selected individuals from the user's submission, and send them all a notice.</li>
</ol>
<p>I created 5 different forms in total that follows the above scheme.  A few of the forms also include searching directories to find cooresponding project folders and files to manage.</p>
<p>Some of the tools I used for this project were Node.js, express, npm, JavaScript, HTML, Azure, and CSS.  Overall, this project ended up being very JavaScript heavy.  Over time, I continuously made improvements to the system based on the company's suggestions.  For every improvement I made, I'm glad about how well it turns out.<br>The PPI is still currently in use today.  For security reasons, I'm keeping the original repository for this project private within Nylex's GitHub organization.  However, I'm currently working on an updated and improved version <a href="https://github.com/Nylex-net/PPI-Build2">here</a>.</p>
<h3><a href="https://github.com/Nylex-net/website">Nylex.net's Company Website</a></h3>
<p>To replace Nylex.net's current website, I was tasked to customize a new one to look more modern. But rather than using a CMS, web designer, or writing primarily in traditional website languages (i.e. HTML, CSS, and Javascript), I chose Python's Django framework. For me, the creation of this project was the most complex because of my choice of tools that all need to work together.  These tools include the following:</p>
<ul>
  <li>Django (Python application framework)</li>
  <li>PostgreSQL</li>
  <li>Nginx</li>
  <li>Certbot</li>
  <li>Docker</li>
  <li>Kubernetes</li>
</ul>
<p>My choice of approaching this project was to make the website an application that is editable through Django's built-in admin portal. Most of the web pages use the same consistent template for all of its web pages, and the individual page content is grabbed from the PostgreSQL database by using the slug name in the URL.  It uses Bootstrap 5.0 for the majority of its stylization and user interactions. Individual page content can be edited from the admin portal, and Django renders the template tags in the HTML files to fill the page content.</p>
<p>Next, I decided to introduce Docker containers to host the application. For this to work, I followed the example <a href="https://londonappdeveloper.com/deploying-django-with-docker-compose/">here</a>, which uses Docker Compose to create multiple containers. For this application to work, I needed a proxy server (Nginx) to help preload media and external files to render each page. I also created a certbot container for the website to use HTTPS.</p>
<p>Finally, I decided to introduce Kubernetes to learn how I can host these containers in an enterprise environment. The reason I wanted to use Kubernetes is to keep the website accessible during times of high web traffic and to manage software deployments.</p>
<p>You can find the repository for this project <a href="https://github.com/Nylex-net/website">here</a>.</p>
<h3><a href="https://github.com/SeanFxyz/assembler_exemplar">Senior Capstone Project</a></h3>
<p>For the senior capstone project, I grouped up with three fellow classmates to build a puzzle game about the basics of computer chips.  Our inspiration was from the classwork we'd done in our Computer Architecture class.  In that class, we used logic chips to build more complex chips using a selection of inputs and outputs.  The goal for each project in that class was to connect chips together in a way that every selection of inputs leads to the correct set of outputs.  Our game is called <strong>Assembler Exemplar</strong>.<br>Our GitHub repository is located <a href="https://github.com/SeanFxyz/assembler_exemplar">here</a>.</p>
<h3>Other Projects</h3>
<p>Some more projects I'm proud of include the following:</p>
<ul>
  <li>Portfolio.</li>
  <li>Recreated the typical operating system layers using C++.</li>
  <li>Using C# to interact with M-Files (a document management system) to build interactive objects.</li>
  <li>Built executable programs using Python.</li>
  <li>Wrote PowerShell scripts to manage the Windows operating system and devices.</li>
  <li>Custom built a database system for memes.</li>
  <li>Docker containers demonstrating examples of cybersecurity attacks written in the C language.</li>
  <li>A custom database built using <a href"https://www.airtable.com/">Airtable</a> for a local elderly support agency.</li>
</ul>
<h2>Programming Languages and Tools</h2>
<div>
  <img src="https://github.com/devicons/devicon/blob/master/icons/java/java-original-wordmark.svg" title="Java" alt="Java" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/c/c-original.svg" title="C" alt="C" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/cplusplus/cplusplus-original.svg" title="C++" alt="C++" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/csharp/csharp-original.svg" title="C#" alt="C#" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/swift/swift-original.svg" title="Swift" alt="Swift" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/python/python-original-wordmark.svg" title="Python" alt="Python" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/django/django-plain-wordmark.svg" title="Django" alt="Django" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/flask/flask-original-wordmark.svg" title="Flask" alt="Flask" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/json/json-original.svg" title="JSON" alt="JSON" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/xml/xml-original.svg" title="XML" alt="XML" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/html5/html5-original.svg" title="HTML5" alt="HTML" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/css3/css3-plain-wordmark.svg"  title="CSS3" alt="CSS" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/javascript/javascript-original.svg" title="JavaScript" alt="JavaScript" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/typescript/typescript-original.svg" title="TypeScript" alt="TypeScript" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/jquery/jquery-original-wordmark.svg" title="jQuery" alt="jQuery" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/php/php-original.svg" title="PHP" alt="PHP" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/markdown/markdown-original.svg" title="Markdown" alt="Markdown" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/react/react-original-wordmark.svg" title="React" alt="React" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/bootstrap/bootstrap-original-wordmark.svg" title="Bootstrap" alt="Bootstrap" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/nodejs/nodejs-original.svg" title="Node.js" alt="Node.js" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/nodewebkit/nodewebkit-plain-wordmark.svg" title="Nodewebkit" alt="Nodewebkit" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/npm/npm-original-wordmark.svg" title="NPM" alt="NPM" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/express/express-original.svg" title="Express" alt="Express " width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/powershell/powershell-original.svg" title="PowerShell" alt="PowerShell" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/yaml/yaml-original.svg" title="YAML" alt="YAML" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/dot-net/dot-net-original-wordmark.svg" title=".NET" alt=".NET" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/xamarin/xamarin-original.svg" title="Xamarin" alt="Xamarin" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/azure/azure-original.svg" title="Azure" alt="Azure" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/microsoftsqlserver/microsoftsqlserver-plain-wordmark.svg" title="MSSQL" alt="MSSQL" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/mysql/mysql-original-wordmark.svg" title="MySQL"  alt="MySQL" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/mongodb/mongodb-original-wordmark.svg" title="MongoDB" alt="MongoDB" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/postgresql/postgresql-original-wordmark.svg" title="PostgreSQL" alt="PostgreSQL" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/wordpress/wordpress-original.svg" title="WordPress" alt="WordPress" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/amazonwebservices/amazonwebservices-plain-wordmark.svg" title="AWS" alt="AWS" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/git/git-original-wordmark.svg" title="Git" alt="Git" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/github/github-original-wordmark.svg" title="GitHub"  alt="GitHub" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/githubactions/githubactions-original.svg" title="GitHub Actions"  alt="GitHub Actions" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/githubcodespaces/githubcodespaces-original.svg" title="GitHub Codespaces"  alt="GitHub Codespaces" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/godot/godot-original-wordmark.svg" title="Godot" alt="Godot" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/android/android-original-wordmark.svg" title="Android" alt="Android" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/nuget/nuget-original.svg" title="Nuget" alt="Nuget" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/oracle/oracle-original.svg" title="Oracle" alt="Oracle" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/putty/putty-original.svg" title="PuTTY" alt="PuTTY" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/ssh/ssh-original-wordmark.svg" title="SSH" alt="SSH" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/apache/apache-line-wordmark.svg" title="Apache" alt="Apache" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/ubuntu/ubuntu-plain-wordmark.svg" title="Ubuntu" alt="Ubuntu" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/debian/debian-original-wordmark.svg" title="Debian" alt="Debian" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/docker/docker-original-wordmark.svg" title="Docker" alt="Docker" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/nginx/nginx-original.svg" title="Nginx" alt="Nginx" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/kubernetes/kubernetes-plain-wordmark.svg" title="Kubernetes" alt="Kubernetes" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/unix/unix-original.svg" title="Unix" alt="Unix" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/linux/linux-original.svg" title="Linux" alt="Linux" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/visualstudio/visualstudio-plain.svg" title="Visual Studio" alt="Visual Studio" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/vscode/vscode-original.svg" title="Visual Studio Code" alt="Visual Studio Code" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/windows8/windows8-original.svg" title="Windows 8" alt="Windows 8" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/windows11/windows11-original.svg" title="Windows 11" alt="Windows 11" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/apple/apple-original.svg" title="Apple" alt="Apple" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/chrome/chrome-original-wordmark.svg" title="Chrome" alt="Chrome" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/google/google-original.svg" title="Google" alt="Google" width="40" height="40"/>&nbsp;
</div>
<h2>Hobbies 🎮</h2>
<ul>
  <li>Play video games (My favorite series is The Legend of Zelda). 👾</li>
  <li>Take walks on my freetime.🚶‍♂️</li>
  <li>Traveling (both in real life and through Google Maps). 🗺️</li>
  <li>Watch various videos on YouTube. 🟥</li>
  <li>Watch Anime. 🗼</li>
  <li>Learn Japanese using Duolingo. 🎌</li>
  <li>Dank Memes. 🤤</li>
</ul>
<h2>Community Involvement 🌲</h2>
<ul>
  <li>Boy Scouts of America</li>
  <ul>
    <li>Highest Rank before leaving was Star Scout.</li>
    <li>Volunteer work for my local community.</li>
    <li>Exciting trips along the west coast.</li>
  </ul>
  <li>Clubs:</li>
  <ul>
    <li>Computer Science Club</li>
    <li>Key Club</li>
    <li>Drama Club</li>
  </ul>
</ul>
<!---
henatic/henatic is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
