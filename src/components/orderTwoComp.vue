<template>
  <div class="orderTwoComp">
    <h2>** 설문은 다음 순서로 진행됩니다.</h2>
    <p>
      1. 설문이 시작됨과 함께 십자가가 1초 동안 등장합니다. 십자가의 중앙에
      시선을 고정시켜 주십시오.
    </p>
    <br />
    <p>
      2. 하나의 시각자극과 함께 이 자극의 선분을 묻는 질문이 3초간 제시됩니다.
    </p>
    <div>
      예시)<br />
      <img src="@/assets/sample.png" style="width: 100%; height: 100%" />
      <br />
      피험자께서는 제시된 시각자극의 선분을 자세히 보시고 3초 내에 질문에 적합한
      번호를 클릭해주십시오.
    </div>
    <br />
    <p>3. 이러한 과정이 총 16번 반복됩니다.</p>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
export default defineComponent({});
</script>

<style>
.orderTwoComp {
  padding: 1rem;
}
</style>
