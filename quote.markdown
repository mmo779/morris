---
layout: page
title: Get A Quote
permalink: /quote/
---

<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">

<style>
.intro-header .page-heading h1 {
	font-size: 2.25rem;
	padding: 20px 0;
}

p {
	text-align: center;
	font-family: 'Roboto', sans-serif;
}

.form-container {
	width: 80%;
	margin: 0 auto;
	padding: 1rem;
	border: 1px solid #ccc;
	border-radius: 8px;
	box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

label {
	display: block;
	margin: 1rem 0 0.5rem;
	font-weight: bold;
}

select, textarea, button {
	width: 100%;
	padding: 0.75rem;
	margin-bottom: 1rem;
	font-family: 'Roboto', sans-serif;
	font-size: 1rem;
	border: 1px solid #ccc;
	border-radius: 4px;
	box-shadow: inset 0 1px 3px rgba(0, 0, 0, 0.1);
}

textarea::placeholder {
	font-style: italic;
	color: #888;
}

button {
	background-color: #007bff;
	color: white;
	border: none;
	cursor: pointer;
	transition: background-color 0.3s ease;
}

button:hover {
	background-color: #0056b3;
}
</style>

<div class="form-container">
	<form name="gform" id="gform" action="https://docs.google.com/forms/d/e/1FAIpQLSc9oBfXLmWgiO8M0wQEC9CJITsRdPPbPSdhivENaS4ua2Fv1A/formResponse?" target="hidden_iframe" method="post">
		<label for="service">Select Service:</label>
		<select id="service" name="service" required>
			<option value="">--Please choose an option--</option>
			<option name="entry.219806142" id="entry.219806142" value="custom_pc_build">Custom PC Build</option>
			<option name="entry.219806142" id="entry.219806142" value="tech_repair">Tech Repair</option>
		</select>

		<label for="details">Details:</label>
		<textarea id="entry.101151677" name="entry.101151677" rows="6" required placeholder="Tell us exactly what you're looking for..."></textarea>

		<button type="submit">Get a Quote</button>
		<iframe name="hidden_iframe" id="hidden_iframe" style="display:none;"></iframe>
	</form>
</div>

