<template>
    <h3>
        Welcome to Norsemen Hauling: Your Trusted Junk Removal and Property Cleanup Experts!
    </h3>
    <p>
        At Norsemen Hauling, we are your one-stop solution for all your hauling and property cleanup needs. We
        bring strength, integrity, and a commitment to excellence to every project we undertake. Allow us to
        introduce you to our comprehensive range of services:
    </p>
    <div class="accordion" id="accordionExample">
        <div class="accordion-item">
            <h2 class="accordion-header">
                <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseOne"
                    aria-expanded="false" aria-controls="collapseOne">
                    Junk Removal
                </button>
            </h2>
            <div id="collapseOne" class="accordion-collapse collapse show" data-bs-parent="#accordionExample">
                <div class="accordion-body">
                    Clear out the clutter and reclaim your space. Whether it's old furniture, appliances, or general
                    debris, we are here to haul it away with precision and care.
                </div>
            </div>
        </div>
        <div class="accordion-item">
            <h2 class="accordion-header">
                <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
                    data-bs-target="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
                    House, Estate, Rental & Hoarding Cleanouts
                </button>
            </h2>
            <div id="collapseTwo" class="accordion-collapse collapse" data-bs-parent="#accordionExample">
                <div class="accordion-body">
                    We understand that property cleanouts can be overwhelming. We specialize in efficiently clearing out
                    houses, estates, rental properties, and providing compassionate support for hoarding situations.
                </div>
            </div>
        </div>
        <div class="accordion-item">
            <h2 class="accordion-header">
                <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
                    data-bs-target="#collapseThree" aria-expanded="false" aria-controls="collapseThree">
                    Light Demolition
                </button>
            </h2>
            <div id="collapseThree" class="accordion-collapse collapse" data-bs-parent="#accordionExample">
                <div class="accordion-body">
                    Need to tear down a structure? We handle light demolition projects with precision and expertise, making
                    way for new beginnings.
                </div>
            </div>
        </div>
        <div class="accordion-item">
            <h2 class="accordion-header">
                <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
                    data-bs-target="#collapseFour" aria-expanded="false" aria-controls="collapseFour">
                    Interior Painting
                </button>
            </h2>
            <div id="collapseFour" class="accordion-collapse collapse" data-bs-parent="#accordionExample">
                <div class="accordion-body">
                    Give your space a fresh, vibrant look with our interior painting services. Our meticulous attention to
                    detail ensures flawless results that breathe new life into your home or business.
                </div>
            </div>
        </div>
        <div class="accordion-item">
            <h2 class="accordion-header">
                <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
                    data-bs-target="#collapseFive" aria-expanded="false" aria-controls="collapseFive">
                    Hauling Services
                </button>
            </h2>
            <div id="collapseFive" class="accordion-collapse collapse" data-bs-parent="#accordionExample">
                <div class="accordion-body">
                    From small items to large loads, we have the hauling power to get the job done. We are equipped to
                    handle any hauling challenge, ensuring your items are transported safely and responsibly.
                </div>
            </div>
        </div>
        <div class="accordion-item">
            <h2 class="accordion-header">
                <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
                    data-bs-target="#collapseSix" aria-expanded="false" aria-controls="collapseSix">
                    Storm & Yard Waste Removal
                </button>
            </h2>
            <div id="collapseSix" class="accordion-collapse collapse" data-bs-parent="#accordionExample">
                <div class="accordion-body">
                    When storms strike or yard waste accumulates, count on Norsemen Hauling to swiftly and efficiently
                    clear away debris, restoring your outdoor space to its former glory.
                </div>
            </div>
        </div>
    </div>
    <p>
        With Norsemen Hauling, you can trust that our services are not only top-notch but also rooted in our
        Christian faith and Viking heritage. We approach each project with integrity, compassion, and a commitment
        to delivering results that exceed expectations.
    </p>
    <p>
        Contact Norsemen Hauling today for all your junk removal, property cleanup, and hauling needs.
    </p>
    <a href="tel:+5018646797"><button type="button" class="btn btn-outline-dark btn-lg">Contact us</button></a>
</template>

<style scoped lang="scss">
.accordion-button {
    display: block;
    text-align: center;
}

.accordion-button:not(.collasped) {
    background-color: rgb(57, 57, 57);
    color: white;
}

h3 {
    text-transform: uppercase;
    letter-spacing: .1rem;
    padding: 25px;
    margin: 0;
}

p {
    letter-spacing: .01rem;
    font-size: 20px;
    margin-top: 30px;
    padding: 15px;
}

@media (max-width: 768px) {

    p {
        font-size: 18px;
    }
}
</style>