---
layout: page
title: Get A Quote
permalink: /quote/
---

<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">

<style>
.intro-header .page-heading h1 {
	font-size: 2.25rem;
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
}

label {
	display: block;
	margin: 1rem 0 0.5rem;
	font-weight: bold;
}

select, textarea, button {
	width: 100%;
	padding: 0.5rem;
	margin-bottom: 1rem;
	font-family: 'Roboto', sans-serif;
	font-size: 1rem;
	border: 1px solid #ccc;
	border-radius: 4px;
}

button {
	background-color: #007bff;
	color: white;
	border: none;
	cursor: pointer;
}

button:hover {
	background-color: #0056b3;
}
</style>

<div class="form-container">
	<form action="your_form_processing_script" method="post">
		<label for="service">Select Service:</label>
		<select id="service" name="service" required>
			<option value="">--Please choose an option--</option>
			<option value="custom_pc_build">Custom PC Build</option>
			<option value="tech_repair">Tech Repair</option>
		</select>

		<label for="details">Details:</label>
		<textarea id="details" name="details" rows="6" required placeholder="Please describe in detail what you need..."></textarea>

		<button type="submit">Get a Quote</button>
	</form>
</div>
