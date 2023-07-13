<template>
    <h3 class="top-title">About Us</h3>
    <img src="../../images/FamShot.jpg" alt="" class="about-img-mobile">
    <div class="aboutImg">
        <div class="caption">
            <span class="heading">About Us</span>
        </div>
    </div>
    <div class="content">
        <section class="top-sect">
            <p>
                When you choose Norsemen Hauling, you're not just hiring a typical junk removal service—you're
                joining our Viking family. We take pride in our personalized approach, treating each customer like
                a valued member of our tribe. With a smile and a handshake, we deliver the old-fashioned way,
                honoring the timeless values of respect and trust.
            </p>
            <p>
                Our expert team is equipped to handle any hauling challenge you may face. We tackle our work with
                the strength and determination of Viking warriors. Rest assured, we treat your belongings with the
                utmost care, ensuring safe and responsible disposal or donation, in line with our Christian
                principles.
            </p>
        </section>
        <h3 class="title">Meet the viking</h3>
        <section>
            <p>
                Our founder, Rick, drawing inspiration from his Viking ancestry, established Norsemen Hauling with a
                mission to lend a helping hand to our valued friends and neighbors, ensuring completion of their
                essential projects with professionalism. With a genuine smile and a firm handshake, Rick and our
                dedicated team embrace the timeless values of the past, delivering unparalleled service the
                old-fashioned way.
            </p>
        </section>
        <h3 class="title">Meet the Shield-maidens</h3>
        <section>
            <p>
                Wanda and Brook, a formidable mother and daughter duo, exemplify an unwavering commitment and
                remarkable diligence in their roles. Although they operate primarily behind the scenes, their
                contributions and achievements transcend expectations. These remarkable individuals embody the
                spirit of Shield-maidens, renowned for their unwavering dedication and indomitable strength in their
                field. As adept soldiers in the Viking tradition, they faithfully serve as loyal disciples of
                Christ, epitomizing qualities of loyalty and devotion.
            </p>
        </section>
        <h3 class="title">Meet the viking's son</h3>
        <section>
            <p>
                In Proverbs 22:6, it says, "Train up a child in the way he should go, and when he is old he will
                not depart from it." At Norsemen, we believe in teaching the next generation the importance of hard
                work because God holds us to higher standards. As the son of the Viking, Noah is learning
                the invaluable teachings of the virtues of setting a positive precedent, practicing humility,
                and prioritizing service to others over self-interest.
            </p>
        </section>
    </div>
</template>

<style scoped>
.about-img-mobile {
    display: none;
}

.aboutImg {
    background-image: url('../../images/FamShot.jpg');
    background-attachment: fixed;
    background-position: center center;
    background-repeat: no-repeat;
    background-size: cover;
    min-height: 100vh;
    width: 100%;
}

.top-title {
    display: none;
}

.caption {
    position: absolute;
    top: 50%;
    left: 0;
    width: 100%;
    text-align: center;
}

.heading {
    background-color: rgba(255, 255, 255, 0.5);
    font-size: 5rem;
    -webkit-backdrop-filter: blur(2em);
    backdrop-filter: blur(2em);
    border-radius: 25px;
    padding: 4rem 6rem;
    box-shadow: 0px 0px 20px 1.5px rgba(0, 0, 0, 0.5);
}

.content {
    margin-top: 30px;
}

.title {
    text-transform: uppercase;
    letter-spacing: .2rem;
    text-align: center;
    padding: 10px;
}

section {
    padding: 20px 55px;
    letter-spacing: .1rem;
}

@media (max-width: 768px) {
    .about-img-mobile {
        display: flex;
        align-items: center;
        justify-content: center;
        width: 100%;
    }

    .aboutImg {
        display: none;
    }

    .top-title {
        display: block;
        text-transform: uppercase;
        letter-spacing: .2rem;
        text-align: center;
        padding: 20px;
    }

    .heading {
        display: none;
    }
}
</style>