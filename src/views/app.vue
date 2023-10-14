

<!-- <script src="/src/scripts/controller.js"></script>
<script src="/src/scripts/controllers/edit-controller.js"></script>
<script src="/src/scripts/controllers/view-controller.js"></script>
<script type="module" src="/src/scripts/graph.js"></script> -->

import controller from '/src/scripts/controller.js';
import controller from '/src/scripts/edit-controller.js';
import controller from '/src/scripts/view-controller.js';
import controller from '/src/scripts/graph.js';

<template>
  
<p>testing canvas</p>
<div id="interactive-graph"></div>
</template>

<style>
  :root {
    --bg-blue: #4666E5;
    --toggle-height: 20px;
    --toggle-width: 35px;
  }
  #interactive-graph {
    border: 3px solid black;
    border-radius: 10px;
    margin: 0 auto;
    top: 5%;
    width: 500px;
    height: 500px;
    overflow: hidden;
  }
</style>