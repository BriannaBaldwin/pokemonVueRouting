<template>
    <div class="card card--electric
    has-text-weight-bold
    has-text-white">
        <div class="card-image">
            <div class="card-image-container">
                <img src="../../../static/jolteon.png"/>
            </div>
        </div>
        <div class="card-content has-text-centered">
            <div class="main">
                <div class="title has-text-white">Jolteon</div>
                <div class="hp">hp 65</div>
            </div>
            <div class="stats columns is-mobile">
                <div class="column">⚡<br />
                  <span class="tag is-warning">Type</span>
                </div>
                <div class="column center-column">54.0 lbs<br>
                    <span class="tag is-warning">Weight</span>
                </div>
                <div class="column">0.8 m <br>
                  <span class="tag is-warning">Height</span>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "PikachuCard",
};
</script>
