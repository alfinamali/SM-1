<template>
    

<aside class="main-sidebar sidebar-light-primary elevation-4 border-bottom-0">
    <!-- Brand Logo -->
    <a href="#" class="brand-link bg-primary">
        <img :src="'/gambar/us.png'" alt="AdminLTE Logo" class="brand-image img-circle elevation-3" >
        <span class="brand-text font-weight-dark">Kelompok SM-1</span>
    </a>

    <!-- Sidebar -->
    <div class="sidebar">
        <!-- Sidebar user panel (optional) -->
        <div class="user-panel mt-3 pb-3 mb-3 d-flex">
            <div class="image">
                <img :src="'/gambar/su.png'" class="img-circle elevation-2" alt="User Image">
            </div>
            <div class="info">
                <a href="#" class="d-block">WISATA SUMENEP</a>
            </div>
        </div>

        <!-- SidebarSearch Form -->

        <!-- Sidebar Menu -->
        <nav class="mt-2">
            <ul class="nav nav-pills nav-sidebar flex-column" data-widget="treeview" role="menu" data-accordion="false">
                <!-- Add icons to the links using the .nav-icon class with font-awesome or any other icon font library -->
                <li class="nav-item menu-open">
                    <router-link to="home" class="nav-link active">
                        <i class="nav-icon fas fa-home"></i>
                        
                        <p>
                            Dashboard
                        </p>
                    </router-link>
                </li>
                
                <li class="nav-item">
                    <router-link to="data-wisata" class="nav-link">
                        <i class="nav-icon fas fa-atlas"></i>
                        <p>
                            Data Wisata Sumenep
                        </p>
                    </router-link>
                </li>
                <!-- <li class="nav-item">
                <a href="/login" class="nav-link" @click="logout">
                    <i class="nav-icon fas fa-sign-out-alt"></i>
                    <p>
                    Logout
                    </p>
                </a>
                </li> -->
            </ul>
        </nav>
        <!-- /.sidebar-menu -->
    </div>
    <!-- /.sidebar -->
</aside>
</template>

// <script>
// export default {
//   methods: {
//     logout() {
//       axios.post('/logout')
//         .then(response => {
//           // Menghandle respon logout yang sukses
//           console.log(response.data.message);
//           // Redirect ke halaman login
//           window.location.href = '/login';
//         })
//         .catch(error => {
//           // Menghandle error saat logout
//           console.error(error);
//         });
//     }
//   }
// }
// </script>