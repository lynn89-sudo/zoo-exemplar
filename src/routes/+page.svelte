<script>
    import "$lib/styles.css";

    let facts = [
        "Ducks are omnivores — they eat plants, insects, worms, snails, and even small fish.",
        "Ducks have webbed feet, which act like paddles, making them excellent swimmers.",
        "Ducks can sleep with one eye open — half their brain stays awake to watch for predators.",
        "Ducks are omnivores — they eat plants, insects, worms, snails, and even small fish.",
        "Ducklings can swim and feed themselves within hours after hatching!"
    ];
    let fact = $state(0);
    let factText = $derived(facts[fact]);
</script>
<style>
    #factContainer {
        margin: 0 auto;
        width: 60%;
        padding: 20px;
        border: 2px solid #4CAF50;
        border-radius: 10px;
        background-color: #d5fac3;

        button {
            font-family: Montserrat;
            background-color: rgb(4, 56, 4);
            color: white;
            padding: 10px;
            border-radius: 20px;
            margin-left: 10px;
        }
        button:hover {
            background-color: rgb(29, 65, 29);
            cursor: pointer;
        }
    }
</style>
<br>
<h1>DUCKS</h1>
<br>
<div id="factContainer">
    <h4>{factText}</h4>
    <h3><button>Previous</button><button>Next</button></h3>
</div>




