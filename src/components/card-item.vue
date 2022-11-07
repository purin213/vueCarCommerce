<script setup>
//defineProps()
const model3 = {
    imgUrl: "https://media.istockphoto.com/photos/tesla-model-y-in-austin-texas-at-360-bridge-picture-id1272025387?k=6&m=1272025387&s=612x612&w=0&h=o_W18f-pFNdHsSpdaNejXSS7G8XnWfayhinzZVWhQU8=",
    name: "Model 3",
    maker: "Tesla",
    price: "48,190",
    date: "2020-02-02"
};

const  modelX = {
    imgUrl: "https://media.istockphoto.com/photos/tesla-model-x-travelling-on-the-freeway-in-silicon-valley-picture-id1191552504?k=6&m=1191552504&s=612x612&w=0&h=NWHap01jKkYzC5BT-9gaKYr8phGeO1ZUYHnGPLQ5RUM=",
    name: "Model X",
    maker: "Tesla",
    price: "89,990",
    date: "2017-9-8"
};

const modelS = {
    imgUrl: "https://media.istockphoto.com/photos/tesla-model-s-on-the-highway-picture-id582261244?k=6&m=582261244&s=612x612&w=0&h=LwYAD7oI6Xy9gsRM7OZ10Nsq-ehGsSmLcbPwQEmZBpg=",
    name: "Model S",
    maker: "Tesla",
    price: "82,990",
    date: "2019-5-1"
};

const modelY = {
    imgUrl: "https://media.istockphoto.com/photos/tesla-model-y-in-austin-texas-at-360-bridge-picture-id1272025387?k=6&m=1272025387&s=612x612&w=0&h=o_W18f-pFNdHsSpdaNejXSS7G8XnWfayhinzZVWhQU8=",
    name: "Model Y",
    maker: "Tesla",
    price: "82,990",
    date: "2020-3-2"
};

const cayenne = {
    imgUrl: "https://media.istockphoto.com/photos/porsche-cayenne-picture-id1138819485?k=6&m=1138819485&s=612x612&w=0&h=uSPCZUofVb5ComBHUpH5qZ5QB7B1WWcKFxNzm53W2ME=",
    name: "Cayenne",
    maker: "Porsche",
    price: "67,500",
    date: "2018-1-20"
};

const macan = {
    imgUrl: "https://media.istockphoto.com/photos/porsche-macan-gts-crossover-suv-picture-id508107322?k=6&m=508107322&s=612x612&w=0&h=syLuqvZng-mEbqJblhY3q6wWxcUlaijknWO9ea90CJo=",
    name: "Macan",
    maker: "Porsche",
    price: "52,100",
    date: "2019-8-12"
};

const camry = {
    imgUrl: "https://media.istockphoto.com/photos/toyota-camry-in-motion-picture-id905266220?k=6&m=905266220&s=612x612&w=0&h=8iRQyhjJYVn_ppC6x3LTLGzG0P67NyCvuQqxvO40ryI=",
    name: "Camry",
    maker: "Toyota",
    price: "24,425",
    date: "2015-7-29"
};

const accord = {
    imgUrl: "https://media.istockphoto.com/photos/honda-accord-in-the-city-picture-id649004692?k=6&m=649004692&s=612x612&w=0&h=7WnRBZcLQ6-Y2FrKKVxya3nwJ6U-CLeZUuk-D5RVlu8=",
    name: "Accord",
    maker: "Honda",
    price: "24,800",
    date: "2018-11-2"
};

const civic ={
    imgUrl: "https://media.istockphoto.com/photos/new-honda-civic-front-picture-id458119929?k=6&m=458119929&s=612x612&w=0&h=h8uh7Bqgw2l1Hhg2TmX05VSBnp2cxrjpTBtvPYpKiD4=",
    name: "Civic",
    maker: "Honda",
    price: "20,650",
    date: "2015-5-4"
};

const cx5 = {
    imgUrl: "https://media.istockphoto.com/photos/new-2018-mazda-cx5-red-cx5-suv-car-japanese-car-moving-vehicle-picture-id1069236296?k=6&m=1069236296&s=612x612&w=0&h=CO2YJA51esFD2an-sKkhusVifvwTwhBXR3ebxD6h3Fg=",
    name:"CX-5",
    maker:"Mazda",
    price:"26,940",
    date: "2012-12-3"
};

const GLEcoupe = {
    imgUrl:"https://media.istockphoto.com/photos/mercedesbenz-gle-43-4matic-coupe-picture-id894961460?k=6&m=894961460&s=612x612&w=0&h=aKbMi31eXuJOSVEKlesIzsJlLM6QhUe0k_5V-FJvH0M=",
    name: "GLE Coupe",
    maker: "Mercedez-Benz",
    price:"76,500",
    date:"2020-3-5"
};

const CLA = {
    imgUrl:"https://media.istockphoto.com/photos/mercedes-benz-cla-picture-id472122163?k=6&m=472122163&s=612x612&w=0&h=IIRhsoWfMXXy6b_aTMtSA2dgSTPK4pSD-_M5vh8OY6M=",
    name:"CLA",
    maker:"Mercedez-Benz",
    price:"37,850",
    date:"2019-7-9"
};

const GLA250={
    imgUrl:"https://media.istockphoto.com/photos/mercedesbenz-gla-2020-test-drive-day-picture-id1297389811?k=6&m=1297389811&s=612x612&w=0&h=NOPBUppwL9aFKKoha3phbhpHUw6hYSdsW5NlFejp4RU=",
    name:"GLA250",
    maker:"Mercedez-Benz",
    price:"37,280",
    date:"2017-6-2"
};

const rx350 = {
    imgUrl:"https://media.istockphoto.com/photos/hybrid-suv-lexus-nx-on-the-road-picture-id657915058?k=6&m=657915058&s=612x612&w=0&h=DGCgfv-pBE75oOUktrX_WpGSadnEmRcm5iPfa49BOQw=",
    name:"RX 350",
    maker: "Lexus",
    price:"45,175",
    date:"2015-2-1"
};

const nx300 ={
    imgUrl:"https://media.istockphoto.com/photos/lexus-nx-200t-car-picture-id480681192?k=6&m=480681192&s=612x612&w=0&h=Ne9_r4aioLH_jpiK41fHpTr-ADdKsHcFMOOPXT9DGp8=",
    name:"NX 300",
    maker:"Lexus",
    price:"37510",
    date:"2018-10-12"
};

const urus={
    imgUrl:"https://media.istockphoto.com/photos/lamborghini-urus-picture-id1184360237?k=6&m=1184360237&s=612x612&w=0&h=cDC3bjJCG9fZC8VpJnuoK73du-hKLnij-14eKHxuLyA=",
    name:"Urus",
    maker:"Lamborghini",
    price:"218,000",
    date:"2021-9-16"
};

const aventador={
    imgUrl:"https://media.istockphoto.com/photos/lamborghini-aventador-lp-7504-superveloce-picture-id1083962000?k=6&m=1083962000&s=612x612&w=0&h=VBYRfp0408ZHqDTdJ69pIJP7z_zhj2T7z8OB-28adSU=",
    name:"Aventador",
    maker:"Lamborghini",
    price:"393,695",
    date:"2020-10-11"
};

const A3 ={
    imgUrl:"https://media.istockphoto.com/photos/audi-a3-sportback-on-a-street-picture-id1255388367?k=6&m=1255388367&s=612x612&w=0&h=nh2TLu9W-68-3_PgN1-0qkXYaw4mfFZviKY1sY_fjJ8=",
    name:"A3",
    maker:"Audi",
    price:"33,500",
    date:"2019-6-8"
};

const x3 = {
    imgUrl:"https://media.istockphoto.com/photos/-picture-id1206921084?k=6&m=1206921084&s=612x612&w=0&h=o8ETeAQHAuzOerMorNWxPnDpyhSyrxiy6vvIQ8TLd4Y=",
    name:"X3",
    maker:"BMW",
    price:"43,000",
    date:"2018-4-11"
};

const twoSeries ={
    imgUrl:"https://media.istockphoto.com/photos/coupe-competition-picture-id1187329409?k=6&m=1187329409&s=612x612&w=0&h=qDHLX8yA8WVGmEwFU8k56z72uobZfcGkHH14zzpLPc4=",
    name:"2 Series",
    maker:"BMW",
    price:"37,500",
    date:"2019-2-15"
};

const carList = [model3, modelY, modelS, modelX, camry, accord, civic, cx5, cayenne, macan, GLEcoupe, CLA, GLA250, rx350, nx300, urus, aventador, A3, x3, twoSeries];

function createCarCard(carObj){
    let res = document.createAttribute("div");
    res.innerHTML = `
    <div class="card m-2" style="width: 18rem;">
        <div class="card-body">
            <img src="${carObj.imgUrl}" class="card-img-top" alt="...">
            <h5 class="card-title pt-2">${carObj.name}</h5>
            <p class="card-text">Maker: ${carObj.maker}</p>
            <p class="card-text">Price: $${carObj.price}</p>
            <p class="card-text">Date: ${carObj.date}</p>
        </div>
    `;
    return res;
}

</script>
<template>
    <div v-for="car in carList">
        {{ createCarCard(car) }}
    </div>
</template>