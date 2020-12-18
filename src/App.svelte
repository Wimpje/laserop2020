<script>
  export let name;
</script>

<style>
  main {
    text-align: center;
    padding: 1em;
    margin: 0 auto;
  }
  .main-text {
    margin: 1em 0 2em 0;
  }
  h1 {
    color: #111;
    text-transform: uppercase;
    font-size: 12vw;
    font-weight: 100;
    margin: 0.1em 0;
  }

  img {
    width: 100%;
    max-width: 640px;
  }
  footer {
    font-size: 0.9em;
  }

  @media (min-width: 640px) {
    main {
      max-width: none;
    }
  }
</style>

<main>
  <h1>{name}</h1>
  <p>
    Iedereen heeft al niet zo'n best jaar, en dan ook nog eens geen vuurwerk...
  </p>

  <h2>Geen vuurwerkshow maar een lichtshow!</h2>
  <div class="main-text">
    <p>
      Een oproep aan een alle theaters, discotheken, DJ's, evenement
      organisaties en enthousiastelingen!
    </p>
    <p>
      Zet op 31 december je lampen, lasers en rookmachines voor je raam, of op
      je dak, en organiseer een buitenlichtshow!
    </p>
    <p>
      Dan hebben we toch nog iets moois om naar te kijken, en kunnen we 2020 op
      een leuke manier de rug toekeren.
    </p>

  </div>

  <img src="laserop2020.png" alt="Laser op 2020 afbeelding" />
  <footer>Pas natuurlijk wel op dat je niemand in de weg zit met je lichten ;-) - En zorg ervoor dat er geen menigten ontstaan; het moet wel veilig zijn!</footer>

</main>
