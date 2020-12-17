<script>
	export let name;
</script>

<main>
	<h1>{name}</h1>
  <p>Iedereen heeft al niet zo'n best jaar, en dan ook nog eens geen vuurwerk...</p>
  <br/>

  <h2>Een oproep aan alle theaterzalen, discotheken, DJ's en enthousiastelingen!</h2>
  <p class="main-text">Organiseer een buitenlichtshow op 31 december 2020, om voor eens en altijd 2020 de rug toe te keren.</p>
  
  <img src="laserop2020.png" alt="Laser op 2020 afbeelding"/>

</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}
  .main-text {
    margin: 1em 0 2em 0;
  }
	h1 {
		color: #111;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>
