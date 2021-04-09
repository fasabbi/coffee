<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link
      href="https://unpkg.com/tailwindcss@^1.0/dist/tailwind.min.css"
      rel="stylesheet"
    />
    <title>coffee shop</title>
    <style>
      section {
        margin-top: -110px;
      }
    </style>
  </head>
  <body>
    <header class="text-gray-500 bg-gray-900 body-font">
      <div
        class="container mx-auto flex flex-wrap p-5 flex-col md:flex-row items-center"
      >
        <a
          class="flex title-font font-medium items-center text-white mb-4 md:mb-0"
        >
          <!-- <svg xmlns="https://www.freepik.com/free-vector/coffee-shop-badge-vintage-style_1389344.htm#page=1&query=coffee%20logo&position=25" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-10 h-10 text-white p-2 bg-blue-500 rounded-full" viewBox="0 0 24 24">
              <path d="M12 2L2 7l10 5 10-5-10-5zM2 17l10 5 10-5M2 12l10 5 10-5"></path>
            </svg>  -->
          <img src="freeLogo.jpeg" alt="" style="width: 50px; height: 50px" />
          <span class="ml-3 text-xl">Coffee Spice</span>
        </a>
        <nav
          class="md:ml-auto md:mr-auto flex flex-wrap items-center text-base justify-center"
        >
          <a class="mr-5 hover:text-white">Home</a>
          <a class="mr-5 hover:text-white">About</a>
          <a class="mr-5 hover:text-white">Gallery</a>
          <a class="mr-5 hover:text-white">Contact</a>
        </nav>
        <button
          class="inline-flex items-center bg-red-800 border-0 py-1 px-3 focus:outline-none hover:bg-gray-700 rounded text-base mt-4 md:mt-0"
        >
          Subscription
          <svg
            fill="none"
            stroke="currentColor"
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            class="w-4 h-4 ml-1"
            viewBox="0 0 24 24"
          >
            <path d="M5 12h14M12 5l7 7-7 7"></path>
          </svg>
        </button>
      </div>
    </header>

    

    <section class="text-gray-500 bg-gray-900 body-font">
      <div
        class="container mx-auto flex px-5 py-24 md:flex-row flex-col items-center"
      >
        <div class="lg:max-w-lg lg:w-full md:w-1/2 w-5/6 md:mb-0 mb-10">
          <img
            class="object-cover object-center rounded"
            alt="hero"
            src="cf2.jpg"
            style="width: 500px; height: 600px"
          />
        </div>

        <!--https://source.unsplash.com/1600x900/?nature,water-->

        <div
          class="lg:flex-grow md:w-1/2 lg:pl-24 md:pl-16 flex flex-col md:items-start md:text-left items-center text-center"
        >
          <h1
            class="title-font sm:text-4xl text-3xl mb-4 font-medium text-white"
          >
            Moroccan Coffee With Six Fragrant Spices Recipe
          </h1>
          <p class="mb-8 leading-relaxed">
            Copper mug try-hard pitchfork pour-over freegan heirloom neutra air
            plant cold-pressed tacos poke beard tote bag. Heirloom echo park
            mlkshk tote bag selvage hot chicken authentic tumeric truffaut
            hexagon try-hard chambray.
          </p>
          <div class="flex justify-center">
            <button
              class="inline-flex text-white bg-green-500 border-0 py-2 px-6 focus:outline-none hover:bg-indigo-600 rounded text-lg"
            >
              Add to cart
            </button>
            <button
              class="ml-4 inline-flex text-blue-400 bg-gray-800 border-0 py-2 px-6 focus:outline-none hover:bg-gray-700 hover:text-white rounded text-lg"
            >
              Buy Now
            </button>
          </div>
        </div>
      </div>
    </section>

    <section class="text-gray-500 bg-gray-900 body-font">
        <div class="container px-5 py-24 mx-auto">
          <div class="xl:w-1/2 lg:w-3/4 w-full mx-auto text-center">
            <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="inline-block w-8 h-8 text-gray-700 mb-8" viewBox="0 0 975.036 975.036">
              <path d="M925.036 57.197h-304c-27.6 0-50 22.4-50 50v304c0 27.601 22.4 50 50 50h145.5c-1.9 79.601-20.4 143.3-55.4 191.2-27.6 37.8-69.399 69.1-125.3 93.8-25.7 11.3-36.8 41.7-24.8 67.101l36 76c11.6 24.399 40.3 35.1 65.1 24.399 66.2-28.6 122.101-64.8 167.7-108.8 55.601-53.7 93.7-114.3 114.3-181.9 20.601-67.6 30.9-159.8 30.9-276.8v-239c0-27.599-22.401-50-50-50zM106.036 913.497c65.4-28.5 121-64.699 166.9-108.6 56.1-53.7 94.4-114.1 115-181.2 20.6-67.1 30.899-159.6 30.899-277.5v-239c0-27.6-22.399-50-50-50h-304c-27.6 0-50 22.4-50 50v304c0 27.601 22.4 50 50 50h145.5c-1.9 79.601-20.4 143.3-55.4 191.2-27.6 37.8-69.4 69.1-125.3 93.8-25.7 11.3-36.8 41.7-24.8 67.101l35.9 75.8c11.601 24.399 40.501 35.2 65.301 24.399z"></path>
            </svg>
            <p class="leading-relaxed text-lg">Our business is built entirely on the foundation of “Helping People Succeed in Specialty Coffee”. In short, this is what we do. We sell spice and help people open coffee shops, and help people who own coffee shops run them to be more efficient and profitable. This is our niche. 

                If you’re in the beginning phases of opening a coffee shop, or already own one and are looking for ways to improve it – you are our target audience. We exist solely to help YOU.
                
                It’s what our company has been doing for over 30 years, and what we have done for thousands of coffee shops worldwide in that time span. .</p>
            <span class="inline-block h-1 w-10 rounded bg-red-500 mt-8 mb-6"></span>
            <h2 class="text-white font-medium title-font tracking-wider text-sm">HOLDEN CAULFIELD</h2>
            <p class="text-gray-600">Manager</p>
          </div>
        </div>
      </section>

    <section class="text-gray-500 bg-gray-900 body-font">
        <div class="container px-5 py-24 mx-auto">
          <div class="flex flex-wrap -m-4">
            <div class="lg:w-1/4 md:w-1/2 p-4 w-full">
              <a class="block relative h-48 rounded overflow-hidden">
                <img alt="ecommerce" class="object-cover object-center w-full h-full block" src="cf3.jpg">
              </a>
              <div class="mt-4">
                <h3 class="text-gray-500 text-xs tracking-widest title-font mb-1">CATEGORY</h3>
                <h2 class="text-white title-font text-lg font-medium">Black</h2>
                <p class="mt-1">$16.00</p>
              </div>
            </div>
            <div class="lg:w-1/4 md:w-1/2 p-4 w-full">
              <a class="block relative h-48 rounded overflow-hidden">
                <img alt="ecommerce" class="object-cover object-center w-full h-full block" src="cf4.jpg">
              </a>
              <div class="mt-4">
                <h3 class="text-gray-500 text-xs tracking-widest title-font mb-1">CATEGORY</h3>
                <h2 class="text-white title-font text-lg font-medium">Latte</h2>
                <p class="mt-1">$21.15</p>
              </div>
            </div>
            <div class="lg:w-1/4 md:w-1/2 p-4 w-full">
              <a class="block relative h-48 rounded overflow-hidden">
                <img alt="ecommerce" class="object-cover object-center w-full h-full block" src="cf5.jpg">
              </a>
              <div class="mt-4">
                <h3 class="text-gray-500 text-xs tracking-widest title-font mb-1">CATEGORY</h3>
                <h2 class="text-white title-font text-lg font-medium">Cappuccino</h2>
                <p class="mt-1">$12.00</p>
              </div>
            </div>
            <div class="lg:w-1/4 md:w-1/2 p-4 w-full">
              <a class="block relative h-48 rounded overflow-hidden">
                <img alt="ecommerce" class="object-cover object-center w-full h-full block" src="cf6.jpg">
              </a>
              <div class="mt-4">
                <h3 class="text-gray-500 text-xs tracking-widest title-font mb-1">CATEGORY</h3>
                <h2 class="text-white title-font text-lg font-medium">The 400 Blows</h2>
                <p class="mt-1">$18.40</p>
              </div>
            </div>
                       
            
            
            </div>
          </div>
        </div>
      </section>


      <section class="text-gray-500 bg-gray-900 body-font relative">
        <div class="container px-5 py-24 mx-auto flex sm:flex-no-wrap flex-wrap">
          <div class="lg:w-2/3 md:w-1/2 bg-gray-900 rounded-lg overflow-hidden sm:mr-10 p-10 flex items-end justify-start relative">
            <iframe title="map" class="absolute inset-0" style="filter: grayscale(1) contrast(1.2) opacity(0.16);" marginheight="0" marginwidth="0" scrolling="no" src="https://maps.google.com/maps?width=100%&height=600&hl=en&q=%C4%B0zmir+(My%20Business%20Name)&ie=UTF8&t=&z=14&iwloc=B&output=embed" width="100%" height="100%" frameborder="0"></iframe>
            <div class="bg-gray-900 relative flex flex-wrap py-6">
              <div class="lg:w-1/2 px-6">
                <h2 class="title-font font-medium text-white tracking-widest text-sm">ADDRESS</h2>
                <p class="leading-relaxed">Photo booth tattooed prism, portland taiyaki hoodie neutra typewriter</p>
              </div>
              <div class="lg:w-1/2 px-6 mt-4 lg:mt-0">
                <h2 class="title-font font-medium text-white tracking-widest text-sm">EMAIL</h2>
                <a class="text-red-500 leading-relaxed">example@email.com</a>
                <h2 class="title-font font-medium text-white tracking-widest text-sm mt-4">PHONE</h2>
                <p class="leading-relaxed">123-456-7890</p>
              </div>
            </div>
          </div>
          <div class="lg:w-1/3 md:w-1/2 flex flex-col md:ml-auto w-full md:py-8 mt-8 md:mt-0">
            <h2 class="text-white text-lg mb-1 font-medium title-font">Feedback</h2>
            <p class="leading-relaxed mb-5 text-gray-600">Post-ironic portland shabby chic echo park, banjo fashion axe</p>
            <input class="bg-gray-800 rounded border border-gray-700 focus:outline-none focus:border-red-500 text-base text-white px-4 py-2 mb-4" placeholder="Name" type="text">
            <input class="bg-gray-800 rounded border border-gray-700 focus:outline-none focus:border-red-500 text-base text-white px-4 py-2 mb-4" placeholder="Email" type="email">
            <textarea class="bg-gray-800 rounded border border-gray-700 focus:outline-none h-32 focus:border-red-500 text-base text-white px-4 py-2 mb-4 resize-none" placeholder="Message"></textarea>
            <button class="text-white bg-red-500 border-0 py-2 px-6 focus:outline-none hover:bg-red-600 rounded text-lg">Submit</button>
            <p class="text-xs text-gray-500 mt-3">Chicharrones blog helvetica normcore iceland tousled brook viral artisan.</p>
          </div>
        </div>
      </section>
  </body>
</html>
