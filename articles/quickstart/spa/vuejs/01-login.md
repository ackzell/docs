---
title: Login
description: This tutorial demonstrates how to add user login to your application with Auth0
budicon: 448
---

<%= include('../../../_includes/_package', {
  org: 'auth0-samples',
  repo: 'auth0-vue-samples',
  path: '01-Login',
  requirements: [
    'Vue 2.0'
  ]
}) %>

<%= include('../_includes/_getting_started', { library: 'Vue.js', callback: 'http://localhost:3000/callback' }) %>

<%= include('_includes/_centralized_login') %>
