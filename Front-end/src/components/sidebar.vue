

<template>
<nav
class="bg-gradient-to-r from-orange-500 via-orange-400 to-orange-600 h-screen fixed top-0 left-0 min-w-[260px] py-6 px-4 font-[sans-serif] flex flex-col overflow-auto" >
<ul class="space-y-3 mt-8">
  <li>
    <a href="/user"
      class="text-gray-700 hover:text-white text-sm flex items-center hover:bg-orange-950 bg-orange-300 rounded px-4 py-3 transition-all">
      <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="w-[18px] h-[18px] mr-4"
        viewBox="0 0 24 24">
        <path
          d="M18 2c2.206 0 4 1.794 4 4v12c0 2.206-1.794 4-4 4H6c-2.206 0-4-1.794-4-4V6c0-2.206 1.794-4 4-4zm0-2H6a6 6 0 0 0-6 6v12a6 6 0 0 0 6 6h12a6 6 0 0 0 6-6V6a6 6 0 0 0-6-6z"
          data-original="#000000" />
        <path d="M12 18a1 1 0 0 1-1-1V7a1 1 0 0 1 2 0v10a1 1 0 0 1-1 1z" data-original="#000000" />
        <path d="M6 12a1 1 0 0 1 1-1h10a1 1 0 0 1 0 2H7a1 1 0 0 1-1-1z" data-original="#000000" />
      </svg>
      <span>New Progress</span>
    </a>
  </li>
  <li>
    <router-link to="/myProgress"
      class="text-gray-700 hover:text-white text-sm flex items-center hover:bg-orange-950 bg-orange-300 rounded px-4 py-3 transition-all">
      <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="w-[18px] h-[18px] mr-4"
                viewBox="0 0 512.003 512.003">
                <path
                  d="M475.244 264.501a15.592 15.592 0 0 1 0-16.998l18.698-28.74c17.032-26.178 5.556-61.348-23.554-72.491l-32.02-12.26a15.596 15.596 0 0 1-9.992-13.754l-1.765-34.24c-1.608-31.184-31.563-52.902-61.667-44.802l-33.109 8.902a15.598 15.598 0 0 1-16.167-5.254l-21.555-26.665c-19.631-24.284-56.625-24.245-76.223 0l-21.556 26.666a15.597 15.597 0 0 1-16.167 5.254l-33.111-8.902c-30.163-8.112-60.063 13.678-61.667 44.802l-1.765 34.24a15.598 15.598 0 0 1-9.992 13.753l-32.018 12.26c-29.171 11.166-40.555 46.365-23.556 72.492l18.699 28.739a15.596 15.596 0 0 1 0 16.998L18.061 293.24c-17.034 26.181-5.554 61.352 23.554 72.492l32.02 12.26a15.598 15.598 0 0 1 9.992 13.754l1.765 34.24c1.608 31.19 31.568 52.899 61.667 44.802l33.109-8.902a15.602 15.602 0 0 1 16.168 5.254l21.555 26.664c19.635 24.291 56.628 24.241 76.223 0l21.555-26.664a15.607 15.607 0 0 1 16.167-5.254l33.111 8.902c30.155 8.115 60.062-13.674 61.667-44.802l1.765-34.24a15.598 15.598 0 0 1 9.992-13.753l32.018-12.26c29.169-11.166 40.554-46.364 23.557-72.493l-18.702-28.739zm-16.806 70.02-32.02 12.26c-18.089 6.926-30.421 23.9-31.418 43.243l-1.765 34.24c-.511 9.921-10.036 16.821-19.612 14.249l-33.111-8.902c-18.705-5.032-38.661 1.455-50.836 16.518l-21.553 26.664c-6.245 7.725-18.009 7.709-24.242 0l-21.553-26.664c-9.438-11.676-23.55-18.198-38.132-18.198-4.229 0-8.499.548-12.706 1.68l-33.111 8.902c-9.596 2.576-19.1-4.348-19.612-14.249l-1.765-34.24c-.997-19.343-13.33-36.318-31.418-43.243l-32.02-12.261c-9.277-3.552-12.896-14.744-7.49-23.053l18.698-28.739c10.563-16.236 10.563-37.218 0-53.452l-18.698-28.739c-5.418-8.326-1.768-19.509 7.491-23.054l32.02-12.26c18.089-6.926 30.421-23.9 31.418-43.243l1.765-34.24c.511-9.921 10.036-16.821 19.612-14.249l33.111 8.902c18.705 5.031 38.66-1.455 50.836-16.518l21.555-26.665c6.245-7.724 18.01-7.708 24.241 0l21.555 26.666c12.178 15.063 32.129 21.549 50.836 16.517l33.111-8.902c9.595-2.577 19.1 4.348 19.612 14.249L395 121.98c.997 19.343 13.33 36.318 31.418 43.243l32.021 12.261c9.276 3.55 12.895 14.744 7.49 23.053l-18.697 28.738c-10.565 16.235-10.565 37.217-.001 53.453l18.698 28.738c5.416 8.328 1.768 19.51-7.491 23.055z"
                  data-original="#000000" />
                <path
                  d="M339.485 170.845c-6.525-6.525-17.106-6.525-23.632 0L159.887 326.811c-6.525 6.525-6.525 17.106.001 23.632 3.263 3.263 7.54 4.895 11.816 4.895s8.554-1.632 11.816-4.895l155.966-155.967c6.526-6.524 6.526-17.105-.001-23.631zm-151.071-4.895c-18.429 0-33.421 14.993-33.421 33.421 0 18.429 14.994 33.421 33.421 33.421 18.429 0 33.421-14.993 33.421-33.421.001-18.428-14.992-33.421-33.421-33.421zm122.545 122.545c-18.429 0-33.421 14.993-33.421 33.421 0 18.429 14.993 33.421 33.421 33.421s33.421-14.993 33.421-33.421c.001-18.428-14.992-33.421-33.421-33.421z"
                  data-original="#000000" />
              </svg>
      <span>My Progress</span>
    </router-link>
  </li> 
  <li>
    <router-link to="/History"
      class="text-gray-700 hover:text-white text-sm flex items-center hover:bg-orange-950 bg-orange-300 rounded px-4 py-3 transition-all">
      <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="w-[22px] h-[22px] mr-4"
        viewBox="0 0 24 24">
        <path d="M12 8v5h5v-2h-3V8z"></path>
        <path
          d="M21.292 8.497a8.957 8.957 0 0 0-1.928-2.862 9.004 9.004 0 0 0-4.55-2.452 9.09 9.09 0 0 0-3.626 0 8.965 8.965 0 0 0-4.552 2.453 9.048 9.048 0 0 0-1.928 2.86A8.963 8.963 0 0 0 4 12l.001.025H2L5 16l3-3.975H6.001L6 12a6.957 6.957 0 0 1 1.195-3.913 7.066 7.066 0 0 1 1.891-1.892 7.034 7.034 0 0 1 2.503-1.054 7.003 7.003 0 0 1 8.269 5.445 7.117 7.117 0 0 1 0 2.824 6.936 6.936 0 0 1-1.054 2.503c-.25.371-.537.72-.854 1.036a7.058 7.058 0 0 1-2.225 1.501 6.98 6.98 0 0 1-1.313.408 7.117 7.117 0 0 1-2.823 0 6.957 6.957 0 0 1-2.501-1.053 7.066 7.066 0 0 1-1.037-.855l-1.414 1.414A8.985 8.985 0 0 0 13 21a9.05 9.05 0 0 0 3.503-.707 9.009 9.009 0 0 0 3.959-3.26A8.968 8.968 0 0 0 22 12a8.928 8.928 0 0 0-.708-3.503z">
        </path>
      </svg>
      <span>History</span>
    </router-link>
  </li>
</ul>
<hr class="my-8 border-gray-600" />
<ul class="space-y-3">
    <li>
        <router-link to="/logout" class="w-64">
          <a href="javascript:void(0)" @click="logout" class="text-white text-sm flex items-center hover:bg-orange-950 bg-orange-900 rounded px-4 py-3 transition-all">
            <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="w-[18px] h-[18px] mr-4"
          viewBox="0 0 6.35 6.35">
          <path
            d="M3.172.53a.265.266 0 0 0-.262.268v2.127a.265.266 0 0 0 .53 0V.798A.265.266 0 0 0 3.172.53zm1.544.532a.265.266 0 0 0-.026 0 .265.266 0 0 0-.147.47c.459.391.749.973.749 1.626 0 1.18-.944 2.131-2.116 2.131A2.12 2.12 0 0 1 1.06 3.16c0-.65.286-1.228.74-1.62a.265.266 0 1 0-.344-.404A2.667 2.667 0 0 0 .53 3.158a2.66 2.66 0 0 0 2.647 2.663 2.657 2.657 0 0 0 2.645-2.663c0-.812-.363-1.542-.936-2.03a.265.266 0 0 0-.17-.066z"
            data-original="#000000" />
        </svg>
            <span>Logout</span>
          </a>
        </router-link>
      </li>
    </ul>
  </nav>
</template>

<script>
import axios from 'axios';
import { useRouter } from 'vue-router';

export default {
  name: "SideBar",
  methods: {
    async logout() {
      try {
        await axios.post("http://127.0.0.1:8000/api/auth/logout", {
          headers: {
            Authorization: `Bearer ${localStorage.getItem('token')}`
          }
        });
        localStorage.removeItem('token');
        const router = useRouter();
        router.push({ name: 'login' });
      } catch (error) {
        console.error('Error logging out:', error);
      }
    }
  },
};
</script>