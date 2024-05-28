<template>
  <div class="home mt-4 py-5">
    <h1 class="display-2 mt-4 py-5">
      <b>
        ({{ count }})
      </b>
    </h1>
    <h1 class="display-1">E-Tasbih</h1>
    <p>Tasbih Dalam Genggaman</p>
    
    <button class="mt-2 py-3 mx-2 btn btn-outline-success" @click="incrementCount">
      Count
    </button>
    
   
    <button class="mt-2 py-3 mx-2 btn btn-outline-primary" @click="resetCount">
      Reset
    </button>

    
  </div>
</template>

<script>
export default {
  data() {
    return {
      count: 0,
    };
  },
  methods: {
    incrementCount() {
      this.count += 1;
    },
    resetCount() {
      this.count = 0;
    },
  },
};
</script>
