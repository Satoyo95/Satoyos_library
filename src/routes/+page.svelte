<script lang="ts">
	import Banner from "$lib/assets/library.png"
	import { ThemeSupa } from '@supabase/auth-ui-shared'

	export let data
</script>

<svelte:head>
	<title>Satoyo's Library</title>
</svelte:head>

<div class="flex column justify-start align-center">
	<h1>Satoyo's Library</h1>
  <div class="col-6 form-widget">
		<img src={Banner} alt="Library Banner" />
	</div>
  <br />
  <h2>Welcome to the Library</h2>
  <div class="flex column justify-start">
    <p>
      Hello, welcome to my "Library". Below will be all the books that I have read, am currently reading or have dropped. There will be a second list below for books I plan to read. I wanted to get all of  them together for personal tracking but thought I would share it with anyone who wants to find something new to read or discuss anything that I have read.
    </p>
    <p>
      I love reading. While I grew up on western books I have read light novels and web novels predominantly for the past 10 years or so. I have lived most of my life in the fiction section of written word and hope to add more non-fiction to my library.
    </p>
    <p>
      I hope to share what I have enjoyed with others while receiving more recommendations on what other people enjoy. I understand my library is heavily skewed to certain genres and I really hope to expand that.
    </p>
    <p>
      Please feel free to recommend anything you like whether western/eastern or anything in between.
    </p>
  </div>
  <h2>*Disclaimer*</h2>
  <div class="flex column justify-start">
    <p>
      I will continue to update this list as I read new books or remember books that I have not kept track of reading in the past.  Lots of reviews will be placeholders until I can re-read the books and have an updated, accurate and honest opinion.
    </p>
    <p>
      None of this content is my own. All Links lead to where I have personally read the books. I will try to find links to support the original Authors and Translators. If you have the information please share with me.
    </p>
  </div>
</div>