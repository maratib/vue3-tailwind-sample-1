<template>
  <div>
    <!-- Form Starts -->
    <form action="" class="bg-white w-full p-5 space-y-5">
      <div class="flex space-x-10">
        <div class="flex flex-col space-y-1 w-full">
          <label for="">Rut Clientie</label>
          <input
            type="number"
            placeholder="111111131"
            class="bg-[#402828] bg-opacity-[15%] border-2 border-[#ADADAD] p-3 rounded-sm placeholder:text-[#455257]"
          />
        </div>
        <div class="flex flex-col space-y-1 w-full">
          <label for="">N* Cotizacion WEB</label>
          <input
            type="number"
            placeholder="80972"
            class="bg-[#402828] bg-opacity-[15%] border-2 border-[#ADADAD] p-3 rounded-sm placeholder:text-[#455257]"
          />
        </div>
      </div>
      <div class="flex space-x-10">
        <div class="flex flex-col space-y-1 w-full">
          <label for="">Nombre</label>
          <input
            type="text"
            placeholder="Jorge"
            class="bg-[#402828] bg-opacity-[15%] border-2 border-[#ADADAD] p-3 rounded-sm placeholder:text-[#455257]"
          />
        </div>
        <div class="flex flex-col space-y-1 w-full">
          <label for="">Version</label>
          <input
            type="number"
            placeholder="ACCENT RB 5DR 1.4 6M/TGL 2AB ABSAC "
            class="bg-[#402828] bg-opacity-[15%] border-2 border-[#ADADAD] p-3 rounded-sm placeholder:text-[#455257]"
          />
        </div>
      </div>
      <div class="flex space-x-10">
        <div class="flex space-x-4 w-full">
          <div>
            <label for="">Applelido paterno</label>
            <input
              type="number"
              placeholder="$"
              class="bg-[#402828] bg-opacity-[15%] mt-1 border-2 border-[#ADADAD] p-3 rounded-sm placeholder:text-[#455257] w-full"
            />
          </div>
          <div>
            <label for="">Appleido materno</label>
            <input
              type="text"
              class="bg-[#402828] bg-opacity-[15%] mt-1 border-2 border-[#ADADAD] p-3 rounded-sm placeholder:text-[#455257] w-full"
            />
          </div>
        </div>
        <div class="flex flex-col space-y-1 w-full">
          <label for="">Punto de Venta</label>
          <input
            type="text"
            placeholder="Mapu -Gildemiestar Autos"
            class="bg-[#402828] bg-opacity-[15%] border-2 border-[#ADADAD] p-3 rounded-sm placeholder:text-[#455257]"
          />
        </div>
      </div>
      <div class="flex space-x-10">
        <div class="flex flex-col space-y-1 w-full">
          <label for="">Telefono</label>
          <input
            type="number"
            placeholder="978078911"
            class="bg-[#402828] bg-opacity-[15%] border-2 border-[#ADADAD] p-3 rounded-sm placeholder:text-[#455257]"
          />
        </div>
        <div class="flex flex-col space-y-1 w-full">
          <label for="">Observacion</label>
          <input
            type="number"
            class="bg-[#402828] bg-opacity-[15%] border-2 border-[#ADADAD] p-3 rounded-sm placeholder:text-[#455257]"
          />
        </div>
      </div>
      <div class="flex space-x-7 w-full">
        <div class="w-full">
          <label for="">Email</label>
          <input
            type="text"
            placeholder="jsantibanez@openpartner.cl"
            class="bg-[#402828] bg-opacity-[15%] mt-1 w-full border-2 border-[#ADADAD] p-3 rounded-sm placeholder:text-[#455257] w-full"
          />
        </div>
        <div class="w-full">
          <label for="">Communa</label>
          <input
            type="text"
            placeholder="lasCondes"
            class="bg-[#402828] bg-opacity-[15%] mt-1 border-2 border-[#ADADAD] p-3 rounded-sm w-full placeholder:text-[#455257] w-full"
          />
        </div>
        <div class="w-full">
          <label for="">Direccion</label>
          <input
            type="text"
            placeholder="San Sebastian 2807"
            class="bg-[#402828] bg-opacity-[15%] mt-1 border-2 border-[#ADADAD] p-3 rounded-sm w-full placeholder:text-[#455257]"
          />
        </div>
      </div>
      <div>
        <label for="">Commentarion de clientie</label>
        <textarea
          name=""
          id=""
          cols="30"
          rows="5"
          class="bg-[#402828] bg-opacity-[15%] mt-1 w-full border-2 border-[#ADADAD] p-2 rounded-sm placeholder:text-[#455257]"
        ></textarea>
      </div>
    </form>
    <!-- Form Ends -->
    <!-- Bottom Buttons Starts-->
    <div
      class="w-full h-16 bg-[#455257] mt-10 flex justify-evenly items-center"
    >
      <button
        class="bg-tranparent border-0 outline-none focus:outline-none text-white"
      >
        Enviar Email
      </button>
      <button
        class="bg-tranparent border-0 outline-none focus:outline-none text-white"
      >
        Detalle
      </button>
      <button
        class="bg-tranparent border-0 outline-none focus:outline-none text-white"
      >
        Tipificar
      </button>
    </div>
    <!-- Bottom Buttons Ends-->
  </div>
</template>
