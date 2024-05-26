---
title: About
layout: page
---

<!-- This code directly applies the border-radius, display, and margin styles inline to the image tag. -->
![Profile Image]({% if site.external-image %}{{ site.picture }}{% else %}{{ site.url }}/{{ site.picture }}{% endif %}){: style="border-radius: 50%; display: block; margin: 0 auto;"}

<!-- ![Profile Image]({% if site.external-image %}{{ site.picture }}{% else %}{{ site.url }}/{{ site.picture }}{% endif %}) -->

<p>Hello, my name is Roberto, I am a Mecatronics Engineer, I made a Masters in Banking and FInaicla Markets.</p>

<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>

<h2>Skills</h2>

<style>
    .skill-list ul {
        list-style: none; /* Remove default bullet points */
    }

    .skill-list ul > li::before {
        content: "•"; /* Use a custom bullet point, like a solid circle */
        color: #5eff00; /* Set the color to green */
        display: inline-block;
        width: 1em; /* Adjust size as needed */
        margin-left: -1em; /* Adjust spacing as needed */
    }

    .skill-list ul > li > ul > li::before {
        content: "•"; /* Use a custom bullet point, like a solid circle */
        color: red; /* Set the color to red */
        display: inline-block;
        width: 1em; /* Adjust size as needed */
        margin-left: -1em; /* Adjust spacing as needed */
    }
</style>

<section class="skill-list">
	<ul>
		<li>HTML
		<li>CSS
		<li>Git
		<li>Excel/Google Sheets
		<li>SAP ERP
		<li>Python:
			<ul>
				<li>Data:
					<ul>
						<li>Fundamentals</li>
						<li>Pandas</li>
						<li>NumPy</li>
					</ul>
				</li>
			</ul>
		</li>
		</li>
		</li>
		</li>
		</li>
    </ul>
				<!-- <li>Data Visualization:
					<ul>
						<li>Matplotlib</li>
						<li>Seaborn</li>
					</ul>
				</li>
				<li>Data Mining:
					<ul>
						<li>Text Mining</li>
						<li>Data cleaning</li>
					</ul>
				</li>
				<li>Database:
					<ul>
						<li>Spark</li>
						<li>SQL</li>
					</ul>
				</li>
			</ul>
		</li>
		<li>SQL, Non SQL:
			<ul>
				<li>MySQL</li>
				<li>MongoDB</li>
				<li>Snowflake</li>
			</ul>
		</li>
		<li>BI Software:
			<ul>
				<li>Power BI</li>
				<li>MicroStrategy</li>
				<li>Google Locker</li>
			</ul>
		</li>
	</ul> -->
</section>
<h2>Projects</h2>

<ul>
    <li><a href="https://github.com/">Lorem Lorem</a></li>
    <li><a href="https://github.com/">Ipsum Dolor</a></li>
    <li><a href="https://github.com/">Dolor Lorem</a></li>
</ul>
