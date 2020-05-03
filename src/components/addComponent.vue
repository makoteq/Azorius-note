<template>
  <b-col class="h-100 leftCol">
    <div class="innerCon">
      <p class="title">Hey You! note something:)</p>
      <textarea
        placeholder="K: Hello there!
G: General Kenobi..."
        rows="10"
        maxlength="1000"
      />
      <input placeholder="Password" type="text" />
      <button class="submit">Submit</button>
    </div>
  </b-col>
</template>

<script>
export default {
  name: "addComponent",
  data() {
    return {
      active: false
    };
  }
};
</script>

<style lang="scss" scoped>
.leftCol {
  width: 100%;
  margin: 0;
  padding: 0;
  min-height: 60vh;
  border-radius: 0 10px 0 0;
}
.innerCon {
  display: flex;
  flex-direction: column;
  padding: 0 50px;
  justify-content: center;
  align-items: center;
  width: 90%;
  height: 100%;
  margin: 0 auto;
}
input,
textarea {
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

.submit {
  border-radius: 20px;
  border: none;
  outline: none;
  font-size: 12px;
  font-weight: bold;
  padding: 15px 45px;
  margin: 14px;
  letter-spacing: 1px;
  text-transform: uppercase;
  cursor: pointer;
  transition: transform 80ms ease-in;
  box-shadow: -5px -5px 10px #fff, 5px 5px 8px #babebc;
  &:active {
    box-shadow: inset 1px 1px 2px #babebc, inset -1px -1px 2px #fff;
  }
}
.title {
  font-weight: bold;
  color: black;
  font-size: 1.8em;
  margin: 10px;
}
</style>
