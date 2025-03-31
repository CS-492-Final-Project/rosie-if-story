<script lang="ts">

</script>
  <div class="container">
	  <div class="credits">
		A game by: Simran Thind, Adam Koziorz, Misha Melnyk, Sophie Liu
	  </div>

	  <div class="game-container">
		<iframe
			src="/CS492-Rosie-IF.html"
			title="Twine Game"
			class="game-iframe"
		></iframe>
	  </div>
	
	  <div class="text-field">
		<h1>Why make this game?</h1>
		As part of our CS492 final group project at the University of Waterloo, we were asked to explore a
		social issue concerning AI, and we took interest in the increasing prominence of AI within the realm
		of dating. We ultimately wanted to explore the implications that using an AI dating assistant might have on
		authenticity, social connectedness, and privacy. Our team has strengths with art, as well as an
		interest with writing and games, so we felt like an interactive fiction game would be a perfect
		medium for doing so.

		<h1>Does something like Rosie exist?</h1>
		While there is currently nothing like Rosie which helps with dating in real-time undetectably,
		many dating services - both existing and new - are already rushing to integrate AI capabilities
		into their products. The most notable type are profile curators, where AI can help redesign
		entire profiles to maximize chances of dating success. Furthermore, more people are consulting LLMs
		like ChatGPT for dating advice, which if acted upon, could be risky. It is our belief that the
		scope of AI integration with dating services will continue to increase as more and more companies
		seek to ride the AI hype train and promote "novel" solutions for profit, likely at the
		expense of its users.

		<h1>Where can I learn more?</h1>
		There was a lot of background research conducted for this project, but to keep things short, here
		are some readings we would recommend the most:

		<ul>
			<li><a href="https://doi.org/10.1086/730709">How AI Constrains the Human Experience</a></li>
			<li><a href="https://www.wiley.com/en-us/Algorithmic+Intimacy%3A+The+Digital+Revolution+in+Personal+Relationships-p-9781509549825">Algorithmic Intimacy: The Digital Revolution in Personal Relationships</a></li>
			<li><a href="https://www.cbc.ca/news/canada/artificial-intelligence-relationships-1.7148866">From AI dating to flirt coaches: How AI is changing dating, for better or worse</a></li>
		</ul>

		We would probably recommend above all, however, to evaluate your relationship with AI and ask yourself:
		has AI really helped me grow as a person? Does it make me more capable of relationships?
	  </div>
  </div>
  
  <style>
	.container {
	  display: flex;
	  justify-content: center;
	  align-items: center;
	  flex-direction: column;
	  gap: 4rem;
	}

	.credits {
		font-family: Roboto, san-serif;
		font-size: 20px;
	}

	.game-container {
	  display: flex;
	  justify-content: center;
	}
  
	.game-iframe {
		width: 90rem;
		height: 55rem;
		border: none;
		padding: 32px;
	}

	.text-field {
		width: 60rem;
		font-family: Roboto, Helvetica, Arial, sans-serif;
		font-size: 22px;
		font-style: normal;
		font-weight: 300;
		letter-spacing: normal;
		line-height: 32px;
		text-transform: none;
		color: #000000;
		padding: 32px 0px;
	}

	.text-field h1 {
		font-family: Montserrat, san-serif;
		font-size: 42px;
		font-weight: 600;
		line-height: 52px;
		text-align: left;
		padding: 64px 0px 24px 0px;
	}

	.text-field ul {
		padding: 16px 20px;
	}

	.text-field li {
		list-style-type: disc;
	}


  </style>