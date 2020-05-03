<template>
  <b-col class="h-100 rightCol">
    <div class="innerCon">
      <p style="color:white" class="title">
        Or redeem your code!
      </p>
      <input placeholder="ID" type="text" />
      <button class="submit2">Gimme my notes!</button>
    </div>
  </b-col>
</template>

<script>
export default {
  name: "getNotesComponent"
};
</script>

<style lang="scss" scoped>
.rightCol {
  background-color: #ff4b2b;
  width: 100%;
  margin: 0;
  padding: 0;
  min-height: 60vh;
  border-radius: 0 0 10px 0;
}
input {
  background-color: #f3f3f3;
  border: none;
  line-height: 1.5;
  font-weight: 600;
  padding: 10px;
  border-radius: 5px;
  margin: 10px;
  transition: all 0.4s;
  &:focus {
    outline: 0;
  }
}
.submit2 {
  border-radius: 5px;
  border: none;
  font-weight: bold;
  outline: none;
  font-size: 12px;
  color: black;
  font-weight: bold;
  padding: 10px 15px;
  margin: 14px;
  letter-spacing: 1px;
  text-transform: uppercase;
  cursor: pointer;
}
</style>
