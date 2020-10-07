<template>
  <div>
    <!-- NAVBAR -->
    <nav class="navbar navbar-dark bg-primary justify-content-between flex-nowrap flex-row">
      <div class="container">
        <router-link to="/" class="nav navbar-brand float-left">MEVN Stack Example</router-link>
        <ul class="nav navbar-nav flex-row float-right">
          <li class="nav-item">
            <router-link class="btn btn-primary nav-link pr-3" to="/">Create Student</router-link>
          </li>
          <li>
            <router-link class="btn btn-success nav-link" to="/view">View Student</router-link>
          </li>
        </ul>
      </div>
    </nav>

    <div class="container mt-5">
      <router-view></router-view>
    </div>
  </div>
</template>