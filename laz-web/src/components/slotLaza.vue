<template>
    <div class="slotss">
      <slot name="plate-header"></slot>
      <slot name="plate-content"></slot>
    </div>
  </template>
  
  <script>
  export default {
  }
  </script>
  
  <style scoped>
   .slotss {
    
      text-align: left;
      font-size: 10px;
      font-weight: bold;
      background: #ffffff;
      padding: 10px;
      color: #1f1f1f;
      overflow: hidden;
      text-overflow: ellipsis;

    }
   
  </style>