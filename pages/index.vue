<template>
  <div>
    <div id="header" class="bg-[url('/hero-bg.jpg')] px-20">
      <div id="menu" class="grid grid-cols-2 py-5">
        <div id="menu-left">
          <img src="logo.png" class="w-[150px]" alt="" />
        </div>

        <div id="menu-right">
          <ul class="grid grid-cols-4 text-lg font-oswald text-white uppercase pt-5">
            <li>About Us</li>
            <li>Our Menu</li>
            <li>Locations</li>
            <li>Contacts</li>
          </ul>
        </div>
      </div>

      <div class="grid grid-cols-2 text-center">
        <img src="hero-burger.png" class="pr-10 mt-10" alt="" />
        <div>
          <h1 class="text-8xl text-white text-centre font-lilita uppercase">
            Classic Burger
          </h1>
          <h2 class="text-6xl text-white text-center font-lilita uppercase mt-5 mb-5">
            With Onion
          </h2>
          <p class="text-white font-roboto font-light text-center pb-6">
            Our signature burger now comes with onion and cheese. You can customize it to
            your likings. Freshly made to order, all in a Brioche style bun.
          </p>
        </div>
      </div>
    </div>
    <div id="section-1" class="text-center bg-[url('/three-burgers')] pb-60 bg-cover">
      <h1 class="text-6xl uppercase font-oswald text-center pt-20 px-24">
        The burger tastes better when you eat it with family
      </h1>
      <p class="font-light text-gray-500 text-center text-lg py-6 px-28">
        Spend quality time with your family and eat an affordable, nutritious and
        delicious meal together. Not all burgers are fast foods. All our burgers are
        handmade to orders for you and your family members to enjoy.
      </p>
      <button class="font-oswald uppercase bg-red-500 text-white py-3 px-8">
        Explore Full Menu
      </button>
    </div>

    <div id="section-2" class="grid grid-cols-3 bg-yellow-500 text-center px-20 pt-5">
      <div>
        <img src="star.jpg" class="w-[100px] mx-auto" alt="" />
        <h3 class="font-oswald uppercase mt-5 ml-5">Original Recipes</h3>
        <p class="font-light mb-5 ml-5">
          We use our secret recioes with only the best ingredients to make our burgers.
          Starting from patties, sauces, and even buns.
        </p>
      </div>
      <div>
        <img src="cake.png" class="w-[100px] mx-auto" alt="" />
        <h3 class="font-oswald uppercase mt-5 ml-5">Quality Food</h3>
        <p class="font-light mb-5 ml-5">
          We purchase our ingredients from the best suppliers daily, to ensure the
          freshest quality of our burgers.
        </p>
      </div>
      <div>
        <img src="delivery.png" class="w-[100px] mx-auto" alt="" />
        <h3 class="font-oswald uppercase mt-5 ml-5">Fastest Delivery</h3>
        <p class="font-light mb-5 ml-5">
          Burgers are best served while it's hot. We deliver to your door with our speedy
          partners from the nearest outlet.
        </p>
      </div>
    </div>

    <div id="section-3" class="text-center">
      <h2 class="text-6xl font-oswald text-red-500 uppercase font-medium pt-20 px-20">
        Our Crazy Burgers
      </h2>
      <p class="text-gray-500 font-light text-xl my-10">
        Whether you are looking for the classics, our specialities, or just wraps, salads,
        and fries. We have it all. We always have something that rewards your tastebud.
      </p>

      <div class="grid grid-cols-2 px-40 gap-5">
        <div id="left-item-column">
          <Item
            image="crispy-chicken.jpg"
            title="Crispy Chicken"
            description="Chicken
          breast, chili sauce, tomatoes, pickles,
          coleslaw"
            price="11.99"
          />
          <Item
            image="baa-baa.jpg"
            title="Baa-Baa Black Sheep"
            description="American cheese, tomato relish,
            avocado, juicy lamb patty"
            price="15.75"
          />
        </div>
        <div id="right-item-column">
          <Item
            image="ultimate-bacon.jpg"
            title="Ultimate Bacon"
            description="House beef
          patty, cheddar cheese, smokey bacon, onion, mustard"
            price="14.99"
          />
          <Item
            image="double-burger.jpg"
            title="Double Burger"
            description="2 beef patties,cheddar cheese,
            mustard, pickles, tomatoes"
            price="15.35"
          />
        </div>
      </div>
    </div>
  </div>
</template>
