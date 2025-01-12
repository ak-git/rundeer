<script lang="ts">
    import cyberhealth from './assets/cyberhealth.png'
    import healthreserve from './assets/healthreserve.png'
</script>

<main>
    <section class="hero is-small">
        <div class="hero-head">
            <div class="container box has-text-centered media">
                <div class="media-left">
                    <figure class="image is-48x48">
                        <img src="favicon.svg" alt="Logo"/>
                    </figure>
                </div>
                <div class="media-content">
                    <p class="title">Цифровой тест <nobr>на Здоровье</nobr></p>
                </div>
            </div>
        </div>
        <div class="hero-body">
            <div class="container box has-text-centered columns">
                <div class="column">
                    <article class="panel is-warning">
                        <p class="panel-heading">
                            <a class="tag is-rounded is-large is-hoverable"
                               href="http://www.cyberhealth.ru.s3-website-us-east-1.amazonaws.com">
                                Кибер Здоровье
                            </a>
                        </p>
                        <a href="http://www.cyberhealth.ru.s3-website-us-east-1.amazonaws.com">
                            <figure class="image">
                                <img src="{cyberhealth}" alt="cyberhealth"/>
                            </figure>
                        </a>
                    </article>
                </div>
                <div class="column">
                    <article class="panel is-danger">
                        <p class="panel-heading">
                            <a class="tag is-rounded is-large is-hoverable"
                               href="http://www.healthreserve.ru.s3-website-us-east-1.amazonaws.com">
                                Запас Здоровья
                            </a>
                        </p>
                        <a href="http://www.healthreserve.ru.s3-website-us-east-1.amazonaws.com">
                            <figure class="image is-fullwidth">
                                <img src="{healthreserve}" alt="healthreserve"/>
                            </figure>
                        </a>
                    </article>
                </div>
            </div>
        </div>
        <div class="hero-foot">
            <div class="container box has-text-centered">
                <a class="button is-link is-outlined is-rounded" href="https://www.savostyanov.moscow">
                    savostyanov.moscow
                </a>
            </div>
        </div>
    </section>
</main>
