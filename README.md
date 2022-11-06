<h2> About</h2>

I'm a frontend developer . I really like to share knowledge and experience to help others become better or deal with career or tech problems. I'm happy to communicate and meet new people, so feel free to reach out to me.

- 💻 I’m currently looking forward to find a job
- 📚 I’m passionate in working as a web develope
- 🌱 I’m currently diving deeper into web and frameworks performance
- 💬 Ask me about web-development, React and career-related topic

<a href="https://app.daily.dev/DavidMphande"><img src="https://api.daily.dev/devcards/80028a53da454fe691bd9d99b9c42781.png?r=kws" width="400" alt="david mphande's Dev Card"/></a>

<h2>🛠️ Languages and Tools</h2>
<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=html,css,javascript,photoshop,illustrator" />
  </a>
</p>

### <h2>💬 Let's connect</h2>

Feel free to contact me on these social networks.

[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kirillkurko/)


<!DOCTYPE html>
<html lang="en">
<head>
	<script>
		* {
	padding: 0;
	margin: 0;
	box-sizing: border-box;
}

body {
	background: #222;
	height: 100vh;
	display: grid;
	place-items: center;
	font-family: consolas;
}

.our-skills {
	padding: 15px;
	width: 500px;
	border-radius: 10px;
	box-shadow: 5px 5px 10px rgba(0, 0, 0, 0.4),
		inset 5px 5px 10px rgba(255, 255, 255, 0.08),
		inset -5px -5px 10px rgba(0, 0, 0, 0.4),
		-5px -5px 10px rgba(255, 255, 255, 0.08);
}

.our-skills .skill {
	margin: 40px 10px;
}

.skill p {
	margin-bottom: 10px;
	color: #fff;
	font-size: 22px;
}

.skill .progress-line {
	position: relative;
	width: 100%;
	height: 8px;
	background: rgba(255, 255, 255, 0.05);
	border-radius: 8px;
}

.skill .progress-line::before {
	position: absolute;
	content: "";
	height: 15px;
	width: 15px;
	top: 50%;
	left: 0;
	transform: translateY(-50%);
	background: var(--bg);
	border-radius: 50%;
	box-shadow: 0 0 5px var(--bg), 0 0 10px var(--bg);
	z-index: 1;
	animation: circle-animate 2s forwards ease-out;
	opacity: 0;
}

@keyframes circle-animate {
	25% {
		left: 0;
		opacity: 1;
	}
	100% {
		opacity: 1;
		left: calc(var(--wd) - 8px);
	}
}

.skill .progress-line span {
	position: relative;
	display: block;
	height: 100%;
	width: 0;
	background: var(--bg);
	border-radius: 8px;
	box-shadow: 0 0 5px var(--bg);
	animation: span-animate 2s forwards ease-out;
}

@keyframes span-animate {
	25% {
		width: 0;
	}
	100% {
		width: var(--wd);
	}
}

.skill .progress-line span::before {
	position: absolute;
	content: "";
	width: 0;
	height: 0;
	border: 7px solid transparent;
	border-top-color: var(--bg);
	top: -9px;
	right: -6px;
	opacity: 0;
	animation: hint 0.2s forwards 2.2s;
}

.skill .progress-line span::after {
	position: absolute;
	content: var(--tx);
	color: #222;
	top: -30px;
	right: -16px;
	background: var(--bg);
	padding: 3px 6px;
	font-size: 14px;
	font-weight: bold;
	border-radius: 4px;
	box-shadow: 0 0 5px var(--bg);
	opacity: 0;
	animation: hint 0.2s forwards 2.2s;
}

@keyframes hint {
	to {
		transform: translateY(-5px);
		opacity: 1;
	}
}

/* YouTube icon */
#ytb {
	position: absolute;
	height: 70px;
	width: 70px;
	top: calc(50% - 35px);
	left: 10px;
	text-align: center;
	line-height: 70px;
	border: 2px solid transparent;
	color: #ff1717;
	font-size: 30px;
	transition: 0.2s;
}

#ytb:hover {
	border-radius: 50%;
	border-color: #ff1717;
	box-shadow: 0 0 10px #ff4040;
}

	</script>
</head>
	
<body>
<div class="our-skills">
	<div class="skill">
		<p>Html</p>
		<div class="progress-line" style="
                    --bg: #ff981a;
                    --wd: 65%;
                    --tx: '65%'">
			<span></span>
		</div>
	</div>
	<div class="skill">
		<p>CSS</p>
		<div class="progress-line" style="
                    --bg: #3bd8ff;
                    --wd: 88%;
                    --tx: '88%'">
			<span></span>
		</div>
	</div>
	<div class="skill">
		<p>JavaScript</p>
		<div class="progress-line" style="
                    --bg: #fff458;
                    --wd: 79%;
                    --tx: '79%'">
			<span></span>
		</div>
	</div>
</div>
<a href="https://www.youtube.com/c/ShortCode" target="_blank" id="ytb"> <i class="fab fa-youtube"></i> </a>
	
	</body>
</html>
