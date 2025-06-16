---
layout: landing
title: Projects
description: "Personal and Team Projects"
image: assets/images/vscode.png
nav-menu: true
---

<!-- Main -->
<div id="main">

<!-- One -->
<section id="one">
	<div class="inner">
		<header class="major">
			<h2>My Projects</h2>
		</header>
		<p>Below are some of the key projects I’ve worked on, showcasing my experience across various technical stacks, along with my contributions to open source and industry-level platforms. For more, feel free to visit my <a href="https://github.com/changminbark" target="_blank">GitHub</a>.</p>
	</div>
</section>

<!-- Two -->
<section id="two" class="spotlights">

	<section>
    	<a href="generic.html" class="image">
    		<img src="{% link assets/images/meta.jpg %}" alt="" data-position="center center" />
    	</a>
    	<div class="content">
    		<div class="inner">
    			<header class="major">
    				<h3>Meta - Production Engineering</h3>
    			</header>
    			<p>I supported the Database as a Service (Enterprise Engineering) team at Meta. I reduced MySQL Clusterset diagnosis time by 70% by creating dashboards and automated alerts based on MySQL Clusterset status. I also implemented a CLI tool in Rust for a quick overview of general Clusterset status, allowing oncall engineers to get a glance into unhealthy clusters, ensuring high availability of the MySQL fleets for core internal operations.</p>
    		</div>
    	</div>
    </section>

    <section>
    	<a href="generic.html" class="image">
    		<img src="{% link assets/images/hangry.jpg %}" alt="" data-position="top center" />
    	</a>
    	<div class="content">
    		<div class="inner">
    			<header class="major">
    				<h3>Hangry Indonesia - Backend Engineering</h3>
    			</header>
    			<p>As a Backend Engineer Intern, I optimized the push (FCM), SMS, and email notification system, improving efficiency by 90%. I also replaced RabbitMQ with a Redis Streams-based message queue, reducing cloud hosting costs by 70%. Additionally, I automated the supply order verification process, reducing time spent by the finance team by 75%. Please contact me if you want to learn more about this project.</p>
    		</div>
    	</div>
    </section>

    <section>
    	<a href="generic.html" class="image">
    		<img src="{% link assets/images/mitappinventor.jpg %}" alt="" data-position="25% 25%" />
    	</a>
    	<div class="content">
    		<div class="inner">
    			<header class="major">
    				<h3>MIT App Inventor (Google Summer of Code)</h3>
    			</header>
    			<p>As an open source developer, I contributed to the integration of the IDraggable interface into Blockly’s multi-select plugin, eliminating the need for monkey patches. I ensured compatibility by cross-testing with 6+ existing plugins and provided detailed documentation to guide future improvements.</p>
    			<ul class="actions">
    				<li><a href="https://github.com/changminbark/workspace-multiselect" class="button">Learn more</a></li>
    			</ul>
    		</div>
    	</div>
    </section>

    <section>
    	<a href="generic.html" class="image">
    		<img src="{% link assets/images/cnn_research.jpg %}" alt="" data-position="25% 25%" />
    	</a>
    	<div class="content">
    		<div class="inner">
    			<header class="major">
    				<h3>Convolutional Neural Networks (CNN) Research</h3>
    			</header>
    			<p>As a machine learning researcher, I developed a CNN using PyTorch to process images, with a focus on optimizing the model with the Adam optimization algorithm. I meticulously tracked parameters and gradients to improve performance, and I also recreated a parallel model in Excel to better understand training dynamics. Please contact me if you want to learn more about this project.</p>
    		</div>
    	</div>
    </section>

</section>

<!-- Personal Projects -->
<section id="personal-projects" class="spotlights">
	<section>
		<a href="generic.html" class="image">
			<img src="{% link assets/images/banteng-ai.jpg %}" alt="" data-position="center center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Banteng-AI (Company-Sentiment-AI)</h3>
				</header>
				<p>This personal project gathers and analyzes news data about specific companies to determine the overall sentiment portrayed in the media using AI and machine learning models. The project consists of two main parts: data collection and sentiment analysis.</p>
				<ul>
					<li><strong>Data Collection:</strong> Initially used web scraping with Puppeteer but later transitioned to News API for a more reliable, legal solution.</li>
					<li><strong>Sentiment Analysis:</strong> Utilizes NLP libraries and machine learning models like SVC, KNearestNeighbors, DecisionTree, and RandomForest to classify the sentiment of news articles as positive, negative, or neutral.</li>
				</ul>
				<p><strong>Technologies Used:</strong> Python (Flask), News API, Pandas, NLP libraries, scikit-learn, VSCode, PyCharm.</p>
				<ul class="actions">
					<li><a href="https://github.com/changminbark/banteng-ai" class="button">Learn more</a></li>
				</ul>
			</div>
		</div>
	</section>

    <section>
    	<a href="generic.html" class="image">
    		<img src="{% link assets/images/tedx-bucknell.jpg %}" alt="" data-position="top center" />
    	</a>
    	<div class="content">
    		<div class="inner">
    			<header class="major">
    				<h3>TEDx Bucknell University Website</h3>
    			</header>
    			<p>A fully dynamic and responsive website for TEDx Bucknell University, built with a team of developers. It features a user-friendly CMS, fully interactive UI/UX design, Google Analytics integration, and security features.</p>
    			<ul>
    				<li><strong>Team Members:</strong> Nolan Lwin, Hung Ngo, Chang Min Bark, Minh Phuong.</li>
    				<li><strong>Technologies Used:</strong> HTML, CSS, JavaScript, React, Node.js, Express.js, MongoDB, Axios, Trello, and Figma.</li>
    			</ul>
    			<ul class="actions">
    				<li><a href="https://github.com/hungngo04/TEDxBucknell2023" class="button">Learn more</a></li>
    			</ul>
    		</div>
    	</div>
    </section>

    <section>
    	<a href="generic.html" class="image">
    		<img src="{% link assets/images/olah.jpg %}" alt="" data-position="25% 25%" />
    	</a>
    	<div class="content">
    		<div class="inner">
    			<header class="major">
    				<h3>Olah: A Social Media Platform for Sports Lovers</h3>
    			</header>
    			<p>A full-stack responsive website that connects sports enthusiasts, allowing them to organize events and compete to rank up. This project, built using the MERN stack, served as an introduction to all aspects of web development.</p>
    			<ul>
    				<li><strong>Technologies Used:</strong> MERN stack (MongoDB, Express, React, Node.js), API calls, middleware tokens, routes, and more.</li>
    			</ul>
    			<ul class="actions">
    				<li><a href="https://github.com/changminbark/Olah" class="button">Learn more</a></li>
    			</ul>
    		</div>
    	</div>
    </section>

</section>

<!-- Three -->
<section id="three">
	<div class="inner">
		<header class="major">
			<h2>Ongoing Research</h2>
		</header>
		<p>I'm currently conducting research with Professor Brian King at Bucknell University on time-series stock price forecasting using deep echo state networks (ESN). This work aims to apply cutting-edge machine learning techniques to predict stock prices based on historical data patterns.</p>
	</div>
</section>

</div>
