<template>
<aside class="menu">
  <p class="menu-label">
    General
  </p>
  <ul class="menu-list">
    <!-- TODO -->
    <li>
      <router-link exact to="/">
        <span class="icon is-small">
          <i class="fa fa-tachometer"></i>
        </span> Dashboard
      </router-link>
    </li>
    <li><a>Customers</a></li>
  </ul>
  <p class="menu-label">
    Administration
  </p>
  <ul class="menu-list">
    <li>
      <a>
        <span class="icon is-small">
          <i class="fa fa-cog"></i>
        </span> Settings
      </a>
    </li>
    <li>
      <a>
        <span class="icon is-small">
          <i class="fa fa-users"></i>
        </span> Manage Your Team</a>
      <ul>
        <li><router-link to="/users">Members</router-link></li>
        <li><a>Plugins</a></li>
        <li><router-link to="/users/add">Add a member</router-link></li>
      </ul>
    </li>
    <li>
      <router-link to="/posts">
        <span class="icon is-small">
          <i class="fa fa-table"></i>
        </span> Posts
      </router-link>
    </li>
    <li><a>Payments</a></li>
    <li><a>Transfers</a></li>
  </ul>
  <p class="menu-label">
    Transactions
  </p>
  <ul class="menu-list">
    <li><a>Payments</a></li>
    <li><router-link to="/form">Form</router-link></li>
    <li><router-link to="/tiles">Tiles</router-link></li>
  </ul>
</aside>
</template>
