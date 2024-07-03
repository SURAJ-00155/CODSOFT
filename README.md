<!DOCTYPE html>
<html lang="en">

<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Portfolio Web Design</title>
	<link rel="preconnect" href="https://fonts.googleapis.com">
	<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
	<link href="https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300..800;1,300..800&display=swap"
		rel="stylesheet">
	<link rel="stylesheet" href="./styles.css">
	<script src="./scripts.js"></script>
	<link rel="icon" href="../imgs/logo.png">
</head>

<body>
	<header>
		<a href="#" class="logo-holder">
			<div class="logo">< SR ></div>
			<div class="logo-text">SURAJ RATHI</div>
		</a>
		<nav>
			<ul id="menu">
				<li>
					<a href="#">Home</a>
				</li>
				<li>
					<a href="#skills">Skills</a>
				</li>
				<li>
					<a href="#projects">Projects</a>
				</li>
				<li>
					<a href="#" class="button">Contact Me</a>
				</li>
			</ul>
			<a href="#" class="mobile-toggle" onClick="toggleMobileMenu();">
				<svg class="w-6 h-6 text-gray-800 dark:text-white" aria-hidden="true" xmlns="http://www.w3.org/2000/svg"
					width="24" height="24" fill="none" viewBox="0 0 24 24">
					<path stroke="currentColor" stroke-linecap="round" stroke-width="2" d="M5 7h14M5 12h14M5 17h10" />
				</svg>
			</a>
		</nav>
	</header>
	<main>
		<section class="hero container">
			<div class="hero-blue">
				<div>
					<h1><small>Hi I'm</small>
						Suraj Rathi
					</h1>
					<p>
						A Full stack web Developer from India.Currently pursuing B.Tech Degree in <b>The Technological
                            Institute of Textile and Sciences,Bhiwani</b>.
                        <span>I am interested in AI topics That's why I also add things like chatgpt into My Projects
                            these Days . </span>
					</p>
					<div class="call-to-action">
						<a href="#" class="button black">
							View Resume
						</a>
						<a href="mailto:hello@adriantwarog.com" class="button white">
							Contact Me
						</a>
					</div>
					<div class="social-links">
						<a href="#">
							<img src="./imgs/github.png" alt="GitHub" width="60" />
						</a>
						<a href="#">
							<img src="./imgs/linkedin.png" alt="LinkedIn" width="60" />
						</a>
					</div>
				</div>
			</div>
			<div class="hero-yellow">
				<img src="../imgs/asdf.jpg" alt="SURAJ" width="100%" />
			</div>
		</section>
		<section class="logos container">
			<div class="marquee">
				<div class="track">
					<img src="./imgs/html.png" alt="HTML" width="128" />
					<img src="./imgs/css.png" alt="CSS" width="128" />
					<img src="./imgs/javascript.png" alt="JS" width="128" />
					<img src="./imgs/react.png" width="128" alt="React" />
					<img src="./imgs/nextjs.png" width="128" alt="Next JS" />
					<img src="./imgs/python.png" width="128" alt="Python" />

					<img src="./imgs/vscode.png" width="128" alt="VS Code" />
					
					<img src="./imgs/html.png" alt="HTML" width="128" />
					<img src="./imgs/css.png" alt="CSS" width="128" />
					<img src="./imgs/javascript.png" alt="JS" width="128" />
					
					<img src="./imgs/react.png" width="128" alt="React" />
					<img src="./imgs/nextjs.png" width="128" alt="Next JS" />
					<img src="./imgs/python.png" width="128" alt="Python" />
					<img src="./imgs/vscode.png" width="128" alt="VS Code" />
					
				</div>
			</div>
		</section>
		<section id="skills" class="skills container">
			<h2>
				<small>About Me</small>
				Skills
			</h2>
			<div class="holder-blue">
				<div class="left-column">
					<h3>Frontend</h3>
					<ul>
						<li>HTML</li>
						<li>CSS</li>
						<li>JavaScript</li>
						<li>React</li>
						<li>Angular</li>
						<li>Vue</li>
					</ul>
					<h3>Backend</h3>
					<ul>
						<li>Node.js</li>
						<li>Express.js</li>
						<!-- <li></li>
						<li></li> -->
						
						
						
					</ul>
					<h3>Databse :</h3>
					<ul>
						<li>MongoDB</li>
						<!-- <li></li>
						<li></li> -->
					</ul>
					<h3>Extra Technical Skills</h3>
					<ul>
						<li>Visual Studio Code</li>
						<!-- <li></li>
						<li></li> -->
						
					</ul>
				</div>
				<div class="right-column">
					<h3>A bit about me</h3>
					<p>
						As a passionate and driven individual pursuing B.Tech (Computer Engineering) , I am eager to apply my knowledge in web development  through a challenging internship. My academic background has provided me with a solid foundation in programming languages like Python ,C language 
 and C++ through various minor projects ,Web development tool such as HTML CSS, JavaScript, React,   
 ExpressJS, NodeJS ,MongoDB .
Proficient in leveraging advanced AI tools to optimize and enhance workflow efficiency.

					</p>
					<p>
						My key strengths lie in problem-solving, quickly adapting to new technologies, teamwork, Smart work . I am particularly fascinated by Web development. I am currently seeking opportunities to intern as a Web developer Intern where I can contribute my skills and learn from seasoned professionals.

I am always eager to discuss technology, software development trends, and innovative projects. Please feel free to connect with me for networking, mentorship, or potential opportunities. Let’s collaborate and grow together!

					</p>
				</div>
			</div>
		</section>
		<section class="work-experience container">
			<h2>
				<small>Recent</small>
				Work Experience
			</h2>
			<div class="jobs">
				<article>
					<figure>
						<div>
							<img src="./imgs/1.jpg" alt="Workplace 1 - YouTube Creator" width="100%" />
							<figcaption>
								workplace-First Internship
							</figcaption>
						</div>
					</figure>
					<h3>Web Developer Intern</h3>
					<div>2024-current</div>
					<p> create website and deploy it in this organisation</p>
				</article>
				<article>
					<figure>
						<div>
							<img src="./imgs/3.jpg" alt="Workplace 1 - YouTube Creator" width="100%" />
							<figcaption>
								workplace-Second Internship
							</figcaption>
						</div>
					</figure>
					<h3>Web Developer Intern</h3>
					<div>2024-current</div>
					<p> create website and deploy it in this organisation</p>
				</article>

			</div>
		</section>
		<section id="projects" class="bento container">
			<h2>
				<small>
					Previous
				</small>
				Completed Projects
			</h2>
			<div class="bento-grid">
				<a href="#" class="bento-item">
					<img src="./imgs/4.jpg" alt="BGCCI" width="100%" />
				</a>
				<a href="#" class="bento-item">
					<img src="./imgs/5.jpg" alt="Churhview" width="100%" />
				</a>
				<a href="#" class="bento-item">
					<img src="./imgs/6.jpg" alt="Harley" width="100%" />
				</a>
				
			</div>
		</section>
	</main>

	<div class="footerContainer">
        <div class="socialIcons">
            <a href="#"><img src="" alt="Gmail"></a>
            <a href="#"><img src="#" alt="Whatsapp"></a>
			<a href="#"><img src="#" alt="Phone/Mobile"></a>
			<a href="#"><img src="#" alt="LinkedIn"></a>
			<a href="#"><img src="#" alt="Twitter"></a>
			<a href="#"><img src="#" alt="Instagram"></a>
		
            
            
            
        </div>
       
        
    </div>
    <div class="footerBottom">
        <p>Copyright &copy;2024; Designed by<span class="designer">SURAJ</span></p>
    </div>
</footer>
</body>

</html>
