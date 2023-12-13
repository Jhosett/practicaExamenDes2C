<script setup>
import { ref } from 'vue';


let indice = ref(0)

let restaurante= ref([
    {
      desayuno: ['Arepa de Huevo', 'Empanada', 'Patacon'],
      almuerzo: ['Mondongo', 'Bandeja Paisa', 'Changua'],
      cena: ['Hamburguesa', 'Salchipapa', 'Hot-Dog']
          },
  {
  desayuno: ['Arepa con huevo', 'Pan con queso', 'Croissant'],
  almuerzo:['Meesi', 'Antonio', 'xd'],
  cena:['uwu', 'onixan', 'quehacesxd']
},
{
  desayuno:['tamal', 'buñuelos', 'natilla'],
  almuerzo:['Hamburguesa', 'Salchipapa', 'Hot-Dog'],
  cena: ['pechuga', 'carne', 'lomo']
},
{
  desayuno: ['yuca', 'chicharron', 'pasta'],
  almuerzo: ['lechona', 'salchichon', 'tamal'],
  cena:['papa', 'xd', 'uwu']
},
{
  desayuno:['suero', 'queso', 'mantequilla'],
  almuerzo: ['chorizo', 'fritanga', 'pescado'],
  cena: ['xd', 'xd', 'xd'],
},
{
  desayuno: ['manzana', 'pera', 'mandarina'],
  almuerzo: ['morcilla', 'arroz', 'pasta'],
  cena: ['no hay cenas']
}])


</script>

<template>
  <div class="mx-[20%] my-5">
    <p class="text-blue-500 border-b-2 border-blue-500 text-center text-3xl font-semibold mb-8">RESTAURANTE UNIVERSITARIO</p>
    <div>
      <div class="w-[30%]">
        <div class="bg-gray-200 mb-2 p-1">
          <p class="ml-2">Lunes</p>
        </div>
        <div class="bg-gray-200 mb-2 p-1">
          <p class="ml-2">Martes</p>
        </div>
        <div class="bg-gray-200 mb-2 p-1">
          <p class="ml-2">Miercoles</p>
        </div>
        <div class="bg-gray-200 mb-2 p-1">
          <p class="ml-2">Jueves</p>
        </div>
        <div class="bg-gray-200 mb-2 p-1">
          <p class="ml-2">Viernes</p>
        </div>
        <div class="bg-gray-200 mb-2 p-1">
          <p class="ml-2">Sábado</p>
        </div>
      </div>
      <div class="w-[70%] bg-teal-200">
        <div>
          <p>Desayuno</p>
          <p>Almuerzo</p>
          <p>Cena</p>
        </div>
        <div>
          <ul v-for="">
            <li>

            </li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>
