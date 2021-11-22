<template>
  <div>
    <html lang="en">
      <head>
        <meta charset="UTF-8" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        <title>Burguers & Shakes</title>
        <link
          rel="shortcut icon"
          href="/public/images/food.png"
          type="image/x-icon"
        />
        <link rel="stylesheet" href="/public/css/styles.css" />
      </head>

      <body>
        <!-- Header -->
        <header class="header bg-red-600 md:grid-rows-2 md:grid-cols-5">
          <div class="row-span-2">
            <img
              class="h-13 w-13"
              src="public/images/logo-food-2x.png"
              alt="Logo del sitio"
            />
          </div>
          <div class="text-5xl text-right pr-5 md:hidden" @click="open = true">
            &equiv;
          </div>
        </header>

        <!-- Main -->
        <main>
          <div
            class="h-56 md:h-80 bg-no-repeat bg-cover bg-center mb-8"
            style="
              background-image: url('https://images.unsplash.com/photo-1576433477363-1a2a80cf9f60?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1950&q=80');
            "
          >
            <div
              class="
                text-white
                font-semibold
                flex flex-col
                justify-center
                items-center
                md:items-center
                h-56
                md:h-80
                bg-gray-700 bg-opacity-25
              "
            >
              <h1 class="text-5xl md:text-6xl">Burguer & Shakes</h1>
              <h2 class="text-4xl md:text-5xl">Welcome</h2>
            </div>
            <!-- <h2 class="text-5xl font-thin leading-loose ">Bienvenidos</h2> -->
          </div>

          <div class="container md:mx-auto md:flex">
            <!-- Card -->
            <div
              class="
                card-container
                md:flex md:items-center md:bg-white md:shadow-xl
              "
            >
              <div>
                <img
                  class="rounded-lg md:rounded-r-none"
                  src="https://images.unsplash.com/photo-1550950158-d0d960dff51b?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=500&h=500&q=60 "
                  alt="Hamburguesa "
                />
              </div>
              <div
                class="
                  card-content
                  md:w-full md:shadow-none md:p-2 md:bg-transparent md:pt-5
                "
              >
                <h2 class="card-title md:text-lg">Classic Burger</h2>
                <p class="text-gray-700 leading-snug">
                  Carne 100% de res, queso, lechuga, jitomate, salsa especial y
                  pan con ajonjolí.
                </p>
                <div class="text-sm font-semibold text-gray-700 mt-2">
                  75.00 SR
                </div>
                <div class="card-footer md:flex-col">
                  <div>
                    <span class="text-yellow-600"
                      >&starf;&starf;&starf;&starf;&star;</span
                    >
                    <span class="text-gray-700">| 36 reseñas</span>
                  </div>
                  <div class="md:mt-4">
                    <span class="btn-ordenar">pick-up</span>
                  </div>
                </div>
              </div>
            </div>

            <!-- Card -->
            <div
              class="
                card-container
                md:flex md:items-center md:bg-white md:shadow-xl
              "
            >
              <div>
                <img
                  class="rounded-lg md:rounded-r-none"
                  src="https://images.unsplash.com/photo-1585703900468-13c7a978ad86?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=500&h=500&q=80 "
                  alt="Alitas"
                />
              </div>
              <div
                class="
                  card-content
                  md:shadow-none md:p-2 md:bg-transparent md:pt-5
                "
              >
                <h2 class="card-title md:text-lg">Wings</h2>
                <p class="text-gray-700 leading-snug">
                  Orden de 10 alitas de pollo fritas con salsa a tu elección.
                  <br />
                  Tamarindo | BBQ | Cajún
                </p>
                <div class="text-sm font-semibold text-gray-700 mt-2">
                  81.90 SR
                </div>
                <div class="card-footer md:flex-col">
                  <div>
                    <span class="text-yellow-600"
                      >&starf;&starf;&starf;&starf;&starf;</span
                    >
                    <span class="text-gray-700">| 41 reseñas</span>
                  </div>
                  <div class="md:mt-4">
                    <span class="btn-ordenar">pick-up</span>
                  </div>
                </div>
              </div>
            </div>
          </div>

          <div class="container md:mx-auto md:flex">
            <!-- Card -->
            <div
              class="
                card-container
                md:flex md:items-center md:bg-white md:shadow-xl
              "
            >
              <div>
                <img
                  class="rounded-lg md:rounded-r-none"
                  src="https://images.unsplash.com/photo-1572490122747-3968b75cc699?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=500&h=500&q=80 "
                  alt="Malteada de Oreo"
                />
              </div>
              <div
                class="
                  card-content
                  md:w-full md:shadow-none md:p-2 md:bg-transparent md:pt-5
                "
              >
                <h2 class="card-title md:text-lg">Milkshake Oreo</h2>
                <p class="text-gray-700 leading-snug">
                  Malteada de galletas oreo con leche de tu elección, decorada
                  con galletas y crema batida.
                </p>
                <div class="text-sm font-semibold text-gray-700 mt-2">
                  55.00 SR
                </div>
                <div class="card-footer md:flex-col">
                  <div>
                    <span class="text-yellow-600"
                      >&starf;&starf;&starf;&starf;&starf;</span
                    >
                    <span class="text-gray-700">| 36 reseñas</span>
                  </div>
                  <div class="md:mt-4">
                    <span class="btn-ordenar">pick-up</span>
                  </div>
                </div>
              </div>
            </div>

            <!-- Card -->
            <div
              class="
                card-container
                md:flex md:items-center md:bg-white md:shadow-xl
              "
            >
              <div>
                <img
                  class="rounded-lg md:rounded-r-none"
                  src="https://images.unsplash.com/photo-1541592106381-b31e9677c0e5?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=500&h=500&q=80 "
                  alt="Papas a la francesa"
                />
              </div>
              <div
                class="
                  card-content
                  md:w-full md:shadow-none md:p-2 md:bg-transparent md:pt-5
                "
              >
                <h2 class="card-title md:text-lg">Fries</h2>
                <p class="text-gray-700 leading-snug">
                  Orden de papas a la francesa con nuestro sasonador especial.
                </p>
                <div class="text-sm font-semibold text-gray-700 mt-2">
                  40.00 SR
                </div>
                <div class="card-footer md:flex-col">
                  <div>
                    <span class="text-yellow-600"
                      >&starf;&starf;&starf;&star;&star;</span
                    >
                    <span class="text-gray-700">| 41 reseñas</span>
                  </div>
                  <div class="md:mt-4">
                    <span class="btn-ordenar">pick-up</span>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </main>

        <!-- Forms -->
        <div
          class="
            container
            md:w-1/2
            mt-10
            md:mx-auto md:shadow-lg
            p-10
            md:rounded-lg
          "
        >
          <h1 class="mb-5 text-3xl leading-loose uppercase text-center">
            Contact us
          </h1>

          <div>
            <label id="name " for="name ">Name</label>
            <input
              class="form-control"
              type="text"
              name="name"
              placeholder="John Doe "
            />
          </div>
          <div class="mt-4">
            <label id="email " for="email ">Email</label>
            <input
              class="form-control"
              type="text "
              name="email "
              placeholder="john.doe@mail.com "
            />
          </div>
          <div class="mt-4">
            <label id="comentarios " for="comentarios ">Tell us</label>
            <textarea
              class="form-control"
              name="comentarios "
              cols="30 "
              max-rows="5 "
              placeholder="Hello, I... "
            ></textarea>
          </div>
          <div class="mt-4">
            <button class="btn">Send us</button>
          </div>
        </div>

        <!-- Footer -->
        <footer class="mt-8 pt-2 w-full bg-primary">
          <div>
            <div class="mt-4 ml-8 md:flex md:justify-center">
              <div class="cursor-pointer">
                <span class="hover:bg-yellow-500 p-1 mr-20"
                  >شركة الموجة الدائمة التجارية</span
                >
              </div>
              <div class="cursor-pointer">
                <span class="hover:bg-yellow-500 p-1 mr-20">@kutlet</span>
              </div>
              <div class="cursor-pointer">
                <span class="hover:bg-yellow-500 p-1">CR:1010665116</span>
              </div>
            </div>

            <div
              class="
                py-4
                mr-8
                text-right
                md:text-left md:flex md:justify-center
              "
            >
              <div>
                <span class="hidden md:inline">· </span>
                <a class="hover:bg-yellow-500 p-1" href="# "
                  >Address: 7350 خالد بن الوليد - حي الحمراء وحدة رقم 212 4518 -
                  13216 الرياض</a
                >
                <span class="hidden md:inline"> ·</span>
              </div>
              <div>
                <a class="hover:bg-yellow-500 p-1" href="# "
                  >Phone: +966550433132</a
                >
                <a class="hover:bg-yellow-500 p-1" href="# "
                  > Almojah Aldaimah Trading Company </a
                >

                <span class="hidden md:inline"> ·</span>
              </div>
              <div>
                <a class="hover:bg-yellow-500 p-1" href="# "
                  >Contact: social@kutlet.co</a
                >
                <span class="hidden md:inline"> ·</span>
              </div>
              <div>
                <span class="hidden md:inline"> ·</span>
              </div>
            </div>
          </div>
        </footer>
      </body>
    </html>
  </div>
</template>

<script>
export default {}
</script>
