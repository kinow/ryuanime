<template>
  <div class="bg-indigo-900 text-purple-lighter md:w-1/6 pb-6 hidden md:block">
      <div class="text-white mb-2 mt-3 px-4 flex justify-between">
        <div class="flex-auto">
          <h1 class="font-semibold text-xl leading-tight mb-1 truncate">Ryuanime</h1>
          <div class="flex items-center mb-6">
              <span class="bg-green-600 rounded-full block w-2 h-2 mr-2"></span>
              <span class="text-white opacity-50 text-sm"> ライウアニミー</span>
          </div>
        </div>
        <div>
          <svg class="h-6 w-6 fill-current text-white opacity-25" viewBox="0 0 20 20">
            <path d="M14 8a4 4 0 1 0-8 0v7h8V8zM8.027 2.332A6.003 6.003 0 0 0 4 8v6l-3 2v1h18v-1l-3-2V8a6.003 6.003 0 0 0-4.027-5.668 2 2 0 1 0-3.945 0zM12 18a2 2 0 1 1-4 0h4z" fill-rule="evenodd" />
          </svg>
        </div>
       </div>
       <div class="mb-8">
          <div class="px-4 mb-2 text-white flex justify-between items-center">
              <div class="opacity-75">♝ Discover</div>
              <div>
                  <svg class="fill-current h-4 w-4 opacity-50" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20">
                      <path d="M11 9h4v2h-4v4H9v-4H5V9h4V5h2v4zm-1 11a10 10 0 1 1 0-20 10 10 0 0 1 0 20zm0-2a8 8 0 1 0 0-16 8 8 0 0 0 0 16z" />
                  </svg>
              </div>
          </div>

           <!-- ROUTER LINK [to latest], this is the home page -->
          <router-link to="/"><div class="bg-teal-dark py-1 px-4 text-white">ヅ Latest</div></router-link>
          <router-link to="/SearchAnime"><div class="bg-teal-dark py-1 px-4 text-white">ヅ Search</div></router-link>

       </div>
       <div class="mb-8">
          <div class="px-4 mb-2 text-white flex justify-between items-center">
            <div class="opacity-75">♝ Anime by </div>
            <div>
                <svg class="fill-current h-4 w-4 opacity-50" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20">
                    <path d="M11 9h4v2h-4v4H9v-4H5V9h4V5h2v4zm-1 11a10 10 0 1 1 0-20 10 10 0 0 1 0 20zm0-2a8 8 0 1 0 0-16 8 8 0 0 0 0 16z" />
                </svg>
            </div>
          </div>
           <div class="flex items-center mb-3 px-4">
               <span class="bg-green rounded-full block w-2 h-2 mr-2"></span>
               <router-link to="/AnimesByLetter"><span class="text-white opacity-75">ლ Alphabet</span></router-link>
           </div>
           <div class="flex items-center mb-3 px-4">
               <span class="bg-green rounded-full block w-2 h-2 mr-2"></span>
               <router-link to="/AnimesByGender"><span class="text-white opacity-75">ლ Genres</span></router-link>
           </div>
       </div>
       <div class="mb-8">
          <div class="px-4 mb-2 text-white flex justify-between items-center">
            <div class="opacity-75">♝ By Type </div>
            <div>
                <svg class="fill-current h-4 w-4 opacity-50" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20">
                    <path d="M11 9h4v2h-4v4H9v-4H5V9h4V5h2v4zm-1 11a10 10 0 1 1 0-20 10 10 0 0 1 0 20zm0-2a8 8 0 1 0 0-16 8 8 0 0 0 0 16z" />
                </svg>
            </div>
          </div>
           <div class="flex items-center mb-3 px-4">
               <span class="bg-green rounded-full block w-2 h-2 mr-2"></span>
               <router-link to="/Movies"><span class="text-white opacity-75">シ Movies</span></router-link>
           </div>
           <div class="flex items-center mb-3 px-4">
               <span class="bg-green rounded-full block w-2 h-2 mr-2"></span>
               <router-link to="/Ovas"><span class="text-white opacity-75">シ Ovas</span></router-link>
           </div>
       </div>
  </div>
</template>


