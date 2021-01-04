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
    Gelukkig nieuw jaar!!!!
  </p>

 
  <img src="laserop2020.png" alt="Laser op 2020 afbeelding" />
  <footer>Lang leve lasers!</footer>

</main>
