<template>
  <div class="px-10 shadow-sm">
    <div class="navbar bg-base-100">
      <div class="flex-1">
        <div class="flex items-center gap-6">
          <div class="flex gap-3">
            <svg class="text-base-200" fill="none" viewBox="0 0 48 48" width="35" height="35" xmlns="http://www.w3.org/2000/svg">
              <path
                d="M42.4379 44C42.4379 44 36.0744 33.9038 41.1692 24C46.8624 12.9336 42.2078 4 42.2078 4L7.01134 4C7.01134 4 11.6577 12.932 5.96912 23.9969C0.876273 33.9029 7.27094 44 7.27094 44L42.4379 44Z"
                fill="currentColor"></path>
            </svg>
            <a class="bg-base-100 border-0 text-2xl font-bold">ScreenTale</a>
          </div>
          <a href=""><div class="font-semibold hover:text-base-200 transition">Movies</div></a>
          <a href=""><div class="font-semibold hover:text-base-200 transition">Series</div></a>
          <a href=""><div class="font-semibold hover:text-base-200 transition">Anime</div></a>
          <a href=""><div class="font-semibold hover:text-base-200 transition">My List</div></a>
        </div>
      </div>
      <div class="flex gap-2">
        <div>
          <!-- <img src="`~public/img/svg/lol.svg" alt="" /> -->
          <input type="text" placeholder="Search titles" class="w-96 bg-primary h-full rounded-3xl px-3" />
        </div>
        <div class="dropdown dropdown-end">
          <div tabindex="0" role="button" class="btn btn-ghost btn-circle avatar">
            <div class="w-10 rounded-full">
              <img :src="'img/me.png'" alt="" />
            </div>
          </div>
          <ul tabindex="-1" class="menu menu-sm dropdown-content bg-base-100 rounded-box z-1 mt-3 w-52 p-2 shadow">
            <li>
              <a class="justify-between">
                Profile
                <span class="badge">New</span>
              </a>
            </li>
            <li><a>Settings</a></li>
            <li><a>Logout</a></li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts"></script>
