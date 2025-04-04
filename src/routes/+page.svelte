<script lang="ts">
</script>

<div class="credits items-center justify-center text-center pb-8">
	A game by: <a href="https://simranthind.me/" target="_blank">Simran Thind</a>, <a href="https://adamkoziorz.github.io" target="_blank">Adam Koziorz</a>, Misha
	Melnyk, Sophie Liu
</div>

<div class="flex justify-center">
	<div class="relative w-[90rem] aspect-[16/9]">
	  <iframe src="/CS492-Rosie-IF.html" title="Twine Game" class="absolute top-0 left-0 w-full h-full border-none p-8"></iframe>
	</div>
  </div>
  

<div class="flex w-full items-center justify-center">
	<div class="text-section flex-column w-[60rem] items-center justify-center p-1 text-black">
		<div>
			<h1>Why make this game?</h1>
			<div class="text-paragraph">
				<p> As part of our <a href="https://student.cs.uwaterloo.ca/~cs492/" target="_blank">CS492: The Social Implications of Computing</a> final group project at the University of Waterloo, we were asked to explore a social issue concerning AI, and we took interest in the increasing prominence and risks of AI within the realm of dating. More specifically, we wanted to explore the implications that using an AI dating assistant might have on authenticity, social connectedness, and privacy. Our team has strengths with art, as well as a shared interest in writing and games, so we felt like an interactive fiction game would be a perfect medium for accomplishing this.</p>
				<br>
				<p> We found through our research that AI, particularly Large Language Models (LLMs), function in ways that often reduce the depth of romantic connections when utilized for dating. By labeling people, making predictions based on aggregated data that reflects societal biases, and optimizing predefined metrics, they can make relationships feel less authentic and serendipitous. The usage of LLMs can encourage people to make stereotypical judgements, further compromising the potential for meaningful connection. Our game illustrates these findings by placing players in various dating situations with Rosie, an LLM embedded in AR glasses, present.</p>
			</div>
		</div>
		<div>
			<h1>Does something like Rosie exist?</h1>
			<div class="text-paragraph">
				<p>There is currently nothing like Rosie which helps with dating in real-time undetectably through AR. However, many companies are already rushing to integrate AI capabilities into their dating services, riding the AI hype train for profit, and likely doing so at the expense of its users.</p>
				<br>
				<p>With the rise of online dating, first impressions matter more than ever. Companies like YourMove AI know this and are already providing AI services to help redesign entire profiles and provide suggestions for what to text date interests with the goal of maximizing dating success. This is not too different to what Rosie does, albeit it does so through a different medium. We already have the LLM technology, and once AR advances further, Rosie will become much more feasible to implement.</p>
			</div>
		</div>
		<div>
			<h1>Where can I learn more?</h1>
			<div class="text-paragraph">
			There was a lot of background research conducted for this project, but to keep things short, here
			are some readings we would recommend the most:

			<ul>
				<li>
					<a href="https://doi.org/10.1086/730709" target="_blank"
						>How AI Constrains the Human Experience</a
					>
				</li>
				<li>
					<a
						href="https://www.wiley.com/en-us/Algorithmic+Intimacy%3A+The+Digital+Revolution+in+Personal+Relationships-p-9781509549825"
						target="_blank"
						>Algorithmic Intimacy: The Digital Revolution in Personal Relationships</a
					>
				</li>
				<li>
					<a
						href="https://www.cbc.ca/news/canada/artificial-intelligence-relationships-1.7148866"
						target="_blank"
						>From AI dating to flirt coaches: How AI is changing dating, for better or worse</a
					>
				</li>
			</ul>
			Above all, however, we would encourage you to introspect on your relationship with AI. Do you feel as though you are surrendering your own innate capacities to act, think, and feel when using AI? Without them, we risk losing the most valuable components of human connection. We believe through introspection, people can properly internalize the risks that LLMs pose. It is our hope that the game serves as a starting point for that reflection.
		</div>
		</div>
	</div>
</div>

<style>
	.credits {
		font-family: Roboto, san-serif;
		font-size: 20px;
	}
	.text-section {
		font-family: Roboto, Helvetica, Arial, sans-serif;
		font-size: 22px;
		font-style: normal;
		font-weight: 300;
		letter-spacing: normal;
		line-height: 32px;
		text-transform: none;
		color: var(--color-text);
	}

	.text-section p {
		font-family: Roboto, Helvetica, Arial, sans-serif;
		font-size: 22px;
		font-style: normal;
		font-weight: 300;
		letter-spacing: normal;
		line-height: 32px;
		text-transform: none;
		color: var(--color-text);
	}
	.text-section h1 {
		font-family: Montserrat, san-serif;
		font-size: 42px;
		font-weight: 600;
		line-height: 52px;
		text-align: left;
		padding: 64px 0px 24px 0px;
	}

	.text-section ul {
		padding: 16px 20px;
	}

	.text-section li {
		list-style-type: disc;
	}
		
	.text-paragraph {
		position: relative;
		padding-left: 20px; /* Space for vertical line */
		margin-left: 0; /* Ensures alignment with header */
	}

	.text-paragraph::before {
		content: "";
		position: absolute;
		left: 0;
		top: 0;
		height: 100%;
		width: 3px;
		background-color: #e95372;
	}

</style>
