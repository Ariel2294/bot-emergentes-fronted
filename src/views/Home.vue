<template>
  <div id="main-wrapper">
    <!-- ============================================================== -->
    <!-- Topbar header - style you can find in pages.scss -->
    <!-- ============================================================== -->
    <header class="topbar">
      <nav class="navbar top-navbar navbar-expand-md navbar-light">
        <!-- ============================================================== -->
        <!-- Logo -->
        <!-- ============================================================== -->
        <div class="navbar-header">
          <a class="navbar-brand" href="javascript:void(0)">
            <!-- Logo icon -->
            <b>
              <!--You can put here icon as well // <i class="wi wi-sunset"></i> //-->
              <!-- Dark Logo icon -->
              <img src="@/assets/images/logo-icon.png" alt="homepage" class="dark-logo" />
              <!-- Light Logo icon -->
              <img src="@/assets/images/logo-light-icon.png" alt="homepage" class="light-logo" />
            </b>
            <!--End Logo icon -->
            <!-- Logo text -->
            <span>
              <!-- dark Logo text -->
              <img src="@/assets/images/logo-text.png" alt="homepage" class="dark-logo" />
              <!-- Light Logo text -->
              <img src="@/assets/images/logo-light-text.png" class="light-logo" alt="homepage" />
            </span>
          </a>
        </div>
        <!-- ============================================================== -->
        <!-- End Logo -->
        <!-- ============================================================== -->
        <div class="navbar-collapse">
          <!-- ============================================================== -->
          <!-- toggle and nav items -->
          <!-- ============================================================== -->
          <ul class="navbar-nav mr-auto mt-md-0">
            <!-- This is  -->
            <li class="nav-item">
              <a
                class="nav-link nav-toggler hidden-md-up text-muted waves-effect waves-dark"
                href="javascript:void(0)"
              >
                <i class="mdi mdi-menu"></i>
              </a>
            </li>
            <li class="nav-item m-l-10">
              <a
                class="nav-link sidebartoggler hidden-sm-down text-muted waves-effect waves-dark"
                href="javascript:void(0)"
              >
                <i class="ti-menu"></i>
              </a>
            </li>
          </ul>
          <!-- ============================================================== -->
          <!-- User profile and search -->
          <!-- ============================================================== -->
        </div>
      </nav>
    </header>
    <!-- ============================================================== -->
    <!-- End Topbar header -->
    <!-- ============================================================== -->
    <!-- ============================================================== -->
    <!-- Left Sidebar - style you can find in sidebar.scss  -->
    <!-- ============================================================== -->
    <aside class="left-sidebar">
      <!-- Sidebar scroll-->
      <div class="scroll-sidebar">
        <!-- User profile -->
        <div class="user-profile">
          <!-- User profile image -->
          <div class="profile-img">
            <img src="@/assets/images/users/profile.png" alt="user" />
            <!-- this is blinking heartbit-->
            <div class="notify setpos">
              <span class="heartbit"></span>
              <span class="point"></span>
            </div>
          </div>
          <!-- User profile text-->
          <div class="profile-text">
            <h5>Chat Bot</h5>
            <a href="javascript:void(0)" class="dropdown-toggle u-dropdown">
              <i class="mdi mdi-settings"></i>
            </a>
            <a href="javascript:void(0)" class data-toggle="tooltip" title="Email">
              <i class="mdi mdi-gmail"></i>
            </a>
            <a href="javascript:void(0)" class data-toggle="tooltip" title="Logout">
              <i class="mdi mdi-power"></i>
            </a>

            <div class="dropdown-menu animated flipInY">
              <!-- text-->
              <a href="#" class="dropdown-item">
                <i class="ti-user"></i> My Profile
              </a>
              <!-- text-->
              <a href="#" class="dropdown-item">
                <i class="ti-wallet"></i> My Balance
              </a>
              <!-- text-->
              <a href="#" class="dropdown-item">
                <i class="ti-email"></i> Inbox
              </a>
              <!-- text-->
              <div class="dropdown-divider"></div>
              <!-- text-->
              <a href="#" class="dropdown-item">
                <i class="ti-settings"></i> Account Setting
              </a>
              <!-- text-->
              <div class="dropdown-divider"></div>
              <!-- text-->
              <a href="login.html" class="dropdown-item">
                <i class="fa fa-power-off"></i> Logout
              </a>
              <!-- text-->
            </div>
          </div>
        </div>
        <!-- End User profile text-->
        <!-- Sidebar navigation-->
        <nav class="sidebar-nav">
          <ul id="sidebarnav">
            <li class="nav-devider"></li>
          </ul>
        </nav>
        <!-- End Sidebar navigation -->
      </div>
      <!-- End Sidebar scroll-->
    </aside>
    <!-- ============================================================== -->
    <!-- End Left Sidebar - style you can find in sidebar.scss  -->
    <!-- ============================================================== -->
    <!-- ============================================================== -->
    <!-- Page wrapper  -->
    <!-- ============================================================== -->
    <div class="page-wrapper">
      <!-- ============================================================== -->
      <!-- Bread crumb and right sidebar toggle -->
      <!-- ============================================================== -->
      <div class="row page-titles">
        <div class="col-md-5 align-self-center">
          <h3 class="text-themecolor">Tecnologías emergentes</h3>
        </div>

        <div class></div>
      </div>
      <!-- ============================================================== -->
      <!-- End Bread crumb and right sidebar toggle -->
      <!-- ============================================================== -->
      <!-- ============================================================== -->
      <!-- Container fluid  -->
      <!-- ============================================================== -->
      <div class="container-fluid">
        <!-- ============================================================== -->
        <!-- Start Page Content -->
        <!-- ============================================================== -->
        <div class="row">
          <div class="col-12">
            <div class="card m-b-0">
              <!-- .chat-row -->
              <div class="chat-main-box">
                <!-- .chat-left-panel -->
                <div class="chat-left-aside">
                  <div class="open-panel">
                    <i class="ti-angle-right"></i>
                  </div>
                  <div class="chat-left-inner">
                    <div class="chat-main-header">
                      <div class="p-20 b-b">
                        <h3 class="box-title">INTEGRANTES</h3>
                      </div>
                    </div>
                    <ul class="chatonline style-none">
                      <li>
                        <a href="javascript:void(0)">
                          <span>
                            OSMIN ARIEL LÓPEZ CLAROS
                            <span class="text-success font-18">SMISO87316</span>
                          </span>
                        </a>
                      </li>
                      <li>
                        <a href="javascript:void(0)">
                          <span>
                            BRENDA ELIZABETH GÓMEZ RIVERA
                            <span
                              class="text-success font-18"
                            >SMIS090816</span>
                          </span>
                        </a>
                      </li>
                      <li>
                        <a href="javascript:void(0)">
                          <span>
                            KAREN AURORA BONILLA RAMOS
                            <span class="text-success font-18">SMIS090816</span>
                          </span>
                        </a>
                      </li>
                    </ul>
                  </div>
                </div>
                <!-- .chat-left-panel -->
                <!-- .chat-right-panel -->
                <div class="chat-right-aside top">
                  <div class="chat-main-header">
                    <div class="p-20 b-b">
                      <h3 class="box-title">Chat Message</h3>
                    </div>
                  </div>
                  <div class="chat-rbox" style="top:150px">
                    <ul class="chat-list p-20">
                      <div v-if="mensajes.length===0" class="text-center">
                        <h1>NO HAY MENSAJE</h1>
                      </div>

                      <div v-for="(mensaje, index) in mensajes" :key="index">
                        <li v-if="mensaje.tipo===1">
                          <div class="chat-img">
                            <img src="@/assets/images/users/1.jpg" alt="user" />
                          </div>
                          <div class="chat-content">
                            <h5>BOT EMERGENTES</h5>
                            <div class="box bg-light-info">{{mensaje.mensaje}}</div>
                          </div>
                          <div class="chat-time">{{mensaje.hora}}</div>
                        </li>

                        <li v-if="mensaje.tipo===2" class="reverse">
                          <div class="chat-content">
                            <h5>USUARIO</h5>
                            <div class="box bg-light-inverse">{{mensaje.mensaje}}</div>
                          </div>
                          <div class="chat-img">
                            <img src="@/assets/images/users/5.jpg" alt="user" />
                          </div>
                          <div class="chat-time">{{mensaje.hora}}</div>
                        </li>
                      </div>
                    </ul>
                  </div>
                  <div class="card-body b-t">
                    <div class="row">
                      <div class="col-8">
                        <textarea
                          v-model="texto"
                          placeholder="Escriba su mensaje aquí..."
                          class="form-control b-0"
                          ref="caja"
                        ></textarea>
                      </div>
                      <div class="col-4 text-right">
                        <button
                          @click="sendMensaje"
                          type="button"
                          class="btn btn-info btn-circle btn-lg"
                        >
                          <i class="fa fa-paper-plane-o"></i>
                        </button>
                      </div>
                    </div>
                  </div>
                </div>
                <!-- .chat-right-panel -->
              </div>
              <!-- /.chat-row -->
            </div>
          </div>
        </div>
        <!-- ============================================================== -->
        <!-- End PAge Content -->
        <!-- ============================================================== -->
        <!-- ============================================================== -->
        <!-- Right sidebar -->
        <!-- ============================================================== -->
        <!-- .right-sidebar -->

        <!-- ============================================================== -->
        <!-- End Right sidebar -->
        <!-- ============================================================== -->
      </div>
      <!-- ============================================================== -->
      <!-- End Container fluid  -->
      <!-- ============================================================== -->
      <!-- ============================================================== -->
      <!-- footer -->
      <!-- ============================================================== -->
      <footer class="footer">© 2020 UGB</footer>
      <!-- ============================================================== -->
      <!-- End footer -->
      <!-- ============================================================== -->
    </div>
    <!-- ============================================================== -->
    <!-- End Page wrapper  -->
    <!-- ============================================================== -->
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home",

  data() {
    return {
      mensajes: [],
      texto: "",
    };
  },
  methods: {
    getMensajes() {
      this.axios.get(`${process.env.VUE_APP_API}mensajes`).then((result) => {
        this.mensajes = result.data;
      });
    },
    sendMensaje() {
      const data = {
        mensaje: this.texto,
      };
      if (this.texto !== "") {
        this.axios
          .post(`${process.env.VUE_APP_API}enviar`, data)
          .then((result) => {
            if (result.status === 201) {
              this.texto = "";
              this.getMensajes();
              this.$refs.caja.focus();
            }
          });
      } else {
        alert("Debe escribir un mensaje");
      }
    },
  },

  beforeMount() {
    this.getMensajes();
  },
  mounted() {
    this.$refs.caja.focus();
  },
};
</script>
