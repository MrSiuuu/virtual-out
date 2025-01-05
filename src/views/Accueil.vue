<template>
<div class="p-8">
  <h2 class="text-2xl font-bold text-center mb-6">Catégories</h2>
  <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-6 gap-6">
    <div class="bg-white shadow-md rounded-lg overflow-hidden transform transition duration-300 hover:shadow-lg hover:scale-105">
      <a href="/restaurants" class="block">
        <img src="https://toohotel.com/wp-content/uploads/2022/09/TOO_restaurant_Panoramique_vue_Paris_Seine_Tour_Eiffel_2.jpg" alt="Restaurants" class="w-full h-32 object-cover transition-transform duration-300 hover:scale-110">
        <div class="p-4 text-center">
          <span class="text-blue-600 font-semibold hover:underline">Restaurants</span>
        </div>
      </a>
    </div>
    <div class="bg-white shadow-md rounded-lg overflow-hidden transform transition duration-300 hover:shadow-lg hover:scale-105">
      <a href="bars" class="block">
        <img src="https://i.pinimg.com/originals/ac/4e/28/ac4e28af117cfc201c65fcc1d3851b83.jpg" alt="Bars" class="w-full h-32 object-cover transition-transform duration-300 hover:scale-110">
        <div class="p-4 text-center">
          <span class="text-blue-600 font-semibold hover:underline">Bars</span>
        </div>
      </a>
    </div>
    <div class="bg-white shadow-md rounded-lg overflow-hidden transform transition duration-300 hover:shadow-lg hover:scale-105">
      <a href="sallesdejeux" class="block">
        <img src="https://www.sybelles.ski/wp-content/uploads/2023/09/Hero-Salle-de-jeux.webp" alt="Salles de jeux" class="w-full h-32 object-cover transition-transform duration-300 hover:scale-110">
        <div class="p-4 text-center">
          <span class="text-blue-600 font-semibold hover:underline">Salles de jeux</span>
        </div>
      </a>
    </div>
    <div class="bg-white shadow-md rounded-lg overflow-hidden transform transition duration-300 hover:shadow-lg hover:scale-105">
      <a href="attractions" class="block">
        <img src="https://expatexperiment.com/wp-content/uploads/2016/09/CALG6427-1024x683.jpg" alt="Attractions touristiques" class="w-full h-32 object-cover transition-transform duration-300 hover:scale-110">
        <div class="p-4 text-center">
          <span class="text-blue-600 font-semibold hover:underline">Attractions touristiques</span>
        </div>
      </a>
    </div>
    <div class="bg-white shadow-md rounded-lg overflow-hidden transform transition duration-300 hover:shadow-lg hover:scale-105">
      <a href="evenement" class="block">
        <img src="https://les-seminaires.eu/wp-content/uploads/2019/04/organisation-evenement-entreprise-735x400.png" alt="Événements" class="w-full h-32 object-cover transition-transform duration-300 hover:scale-110">
        <div class="p-4 text-center">
          <span class="text-blue-600 font-semibold hover:underline">Événements</span>
        </div>
      </a>
    </div>
    <div class="bg-white shadow-md rounded-lg overflow-hidden transform transition duration-300 hover:shadow-lg hover:scale-105">
      <a href="magasins" class="block">
        <img src="https://media.lesechos.com/api/v1/images/view/5c0693628fe56f5a7d327c6b/1280x720/ech22287092-1.jpg" alt="Magasins" class="w-full h-32 object-cover transition-transform duration-300 hover:scale-110">
        <div class="p-4 text-center">
          <span class="text-blue-600 font-semibold hover:underline">Magasins</span>
        </div>
      </a>
    </div>
  </div>
</div>


</template>

<script>
export default {
  name: "Accueil",
};
</script>
