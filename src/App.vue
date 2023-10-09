<script setup>
import { ref } from 'vue';

const inputText = ref('hello')
const color = ref('')

</script>
<template>
  <div class=".container-fluid ">
  <div class="p-3 mb-2 bg-black text-white">
    <div class="mx-auto p-2" style="width: 400px; ">
      <div class="border border-primary">
        <div class="border border-primary">
          <div class="p-3 mb-2 bg-secondary text-white">
        <p class="text-center"><h2>List of Contact</h2></p>
 
      
    <select v-model="color" class="form-select" aria-label="Default select example">
      <option selected >------Contact------</option>
        <option value="1">John Lloyd Gentolia</option>
        <option value="2">Mark Rala Jr.</option>
        <option value="3">Lyra Mercado</option>
        <option value="4">Cyrus Jardin Jr.</option>
        <option value="5">Ej-cien Balagoza</option>
        <option value="6">Mylen Javier</option>
        <option value="7">Mikko Martinez</option>
      
    </select>
<hr>

    <p v-if="color == '1'">
    <h5>Contact: 09073943360</h5>
    <h5>Email: lloydgentolia@gmail.com</h5>
    <h5>Age: 23</h5>
    <h5>Gender: Male</h5>
    <h5>Address: M.Roxas,Bulan,Sorsogon</h5>
  
    </p>
    <p v-if="color == '2'">
      <h5>Contact: 09607080901</h5>
    <h5>Email: ralamarkjr@gmail.com</h5>
    <h5>Age: 22</h5>
    <h5>Gender: Male</h5>
    <h5>Address: Beguin,Bulan,Sorsogon</h5>
  </p>
  <p v-if="color == '3'">
    <h5>Contact: 09647045784</h5>
    <h5>Email: lalamercado@gmail.com</h5>
    <h5>Age: 23</h5>
    <h5>Gender: Female</h5>
    <h5>Address: Beguin,Bulan,Sorsogon</h5>
  </p>
  <p v-if="color == '4'">
    <h5>Contact: 09548398549</h5>
    <h5>Email: jardincy215@gmail.com</h5>
    <h5>Age: 27</h5>
    <h5>Gender: Male</h5>
    <h5>Address: San Vicente,Bulan,Sorsogon</h5>
  </p>
  <p v-if="color == '5'">
    <h5>Contact: 09165855935</h5>
    <h5>Email: balagozaejcien@gmail.com</h5>
    <h5>Age: 22</h5>
    <h5>Gender: Female</h5>
    <h5>Address: San Vicente,Bulan,Sorsogon</h5>
  </p>
  <p v-if="color == '6'">
    <h5>Contact: 09307295149</h5>
    <h5>Email: mayeen9413@gmail.com</h5>
    <h5>Age: 23</h5>
    <h5>Gender: Female</h5>
    <h5>Address: Zone 8,Bulan,Sorsogon</h5>
  </p>

  <p v-if="color == '7'">
    <h5>Contact: 09835926903</h5>
    <h5>Email: martinezmikko2001@gmail.com</h5>
    <h5>Age: 22</h5>
    <h5>Gender: Male</h5>
    <h5>Address: Aquino,Bulan,Sorsogon</h5>
  </p>
  <hr>
  </div>
</div>
</div>
</div>
</div>
</div>

</template>