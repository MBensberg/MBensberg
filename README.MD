<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta http-equiv="X-UA-Compatible" content="IE=edge">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">

	<title>Michael Bensberg | Data Science Student</title>

	<link rel="icon" href="favicon.ico" type="image/png" />

	<link href="https://fonts.googleapis.com/css?family=Reem+Kufi|Roboto:300" rel="stylesheet">
	<link href="https://use.fontawesome.com/releases/v5.13.1/css/all.css" rel="stylesheet">
	<link rel="stylesheet" href="css/reset.css">
	<link rel="stylesheet" href="css/styles.css">
	<link rel="stylesheet" href="css/themes/indigo-white.css">
	<!-- <link rel="stylesheet" href="css/themes/green-white.css"> -->
	<!-- <link rel="stylesheet" href="css/themes/red-white.css"> -->
	<!-- <link rel="stylesheet" href="css/themes/grey-white.css"> -->
	<!-- <link rel="stylesheet" href="css/themes/white-indigo.css"> -->
	<!-- <link rel="stylesheet" href="css/themes/white-blue.css"> -->
	<!-- <link rel="stylesheet" href="css/themes/white-grey.css"> -->
	<!-- <link rel="stylesheet" href="css/themes/white-red.css"> -->
	<!-- <link rel="stylesheet" href="css/themes/yellow-black.css"> -->
</head>
<body>
	<main>
		<div class="intro">Hello, I'm Michael!</div>
		<div class="tagline">Data Science Student | Coding Beginner | Python Newbie | Lego fan</div>
		<!-- Find your icons from here - https://fontawesome.com/icons?d=gallery&s=brands -->
		<div class="icons-social">
			<a target="_blank" href="https://github.com/MBensberg">
        <i class="fab fa-github" aria-hidden="true" title="Github"></i>
        <span class="sr-only">Github</span>
      </a>
      <a target="_blank" href="https://www.linkedin.com/in/michael-bensberg-244453268/">
        <i class="fab fa-linkedin" aria-hidden="true" title="LinkedIn"></i>
        <span class="sr-only">LinkedIn</span>
      </a>
    </div>
	</main>
</body>
</html>

/* Theme */

main {
	background: #43A047;
	color: #FAFAFA;
}

.icons-social a {
	color: #FAFAFA;
}

.icons-social a svg path{
	fill: #FAFAFA;
}

/* Typography */

html {
	font-family: 'Roboto', sans-serif;
}

@media (min-width: 576px) {
	html {
		font-size: 14px;
	}
}

@media (min-width: 768px) {
	html {
		font-size: 16px;
	}
}

@media (min-width: 992px) {
	html {
		font-size: 18px;
	}
}

@media (min-width: 1200px) {
	html {
		font-size: 20px;
	}
}

.icons-social i {
	font-size: 3em;
}

/* Custom Styles */

main {
	display: flex;
	flex-direction: column;
	min-height: 100vh;
	justify-content: center;
	padding: 0 30px;
	text-align: center;
}

main > .intro {
	font-family: 'Reem Kufi', sans-serif;
	font-size: 3.75em;
	font-weight: 600;
}

main > .tagline {
	font-size: 1.5rem;
	margin: 1.5rem 0;
	font-weight: 100;
}

.icons-social i {
	padding: 10px;
}

.icons-social a {
  text-decoration: none;
}

.devto {
	margin-bottom: -0.20rem;
}

.devto svg {
	margin-bottom: -0.20rem;
	margin-left: 0.675rem;;
	width: 2.65rem;
	height: 2.65rem;
}

/* Minimal CSS Reset */

html {
  box-sizing: border-box;
  font-size: 12px;
}

*, *:before, *:after {
  box-sizing: inherit;
}

body, h1, h2, h3, h4, h5, h6, p, ol, ul {
  margin: 0;
  padding: 0;
  font-weight: normal;
}

ol, ul {
  list-style: none;
}

img {
  max-width: 100%;
  height: auto;
}
