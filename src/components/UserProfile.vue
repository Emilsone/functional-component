<template>
  <section>
    <div>
      <h1 :class="$style.heading">Employee Profile</h1>
    </div>
    <div :class="$style.display">
      <div :class="$style.card">
        <img src="../assets/avatar-1.png" alt="Avatar" :class="$style.img" />
        <div :class="$style.container">
          <h3 :class="$style.name">Jesse Michael</h3>
          <p>Project Manager</p>
          <p>jessemichael56@gmail.com</p>
          <span :class="$style.action">
            <a href="mailto:" :class="$style.message">&#9993; Message</a>
            <a href="mailto:" :class="$style.call">&#9743; Call</a>
            <a href="mailto:" :class="$style.follow">+ Follow</a>
          </span>
        </div>
      </div>

      <div :class="$style.card">
        <img src="../assets/avatar-2.png" alt="Avatar" :class="$style.img" />
        <div :class="$style.container">
          <h3 :class="$style.name">John Michael</h3>
          <p>Head of Marketing</p>
          <p>jessemichael56@gmail.com</p>
          <span :class="$style.action">
            <a href="mailto:" :class="$style.message">&#9993; Message</a>
            <a href="mailto:" :class="$style.call">&#9743; Call</a>
            <a href="mailto:" :class="$style.follow">+ Follow</a>
          </span>
        </div>
      </div>
      <div :class="$style.card">
        <img src="../assets/avatar-3.png" alt="Avatar" :class="$style.img" />
        <div :class="$style.container">
          <h3 :class="$style.name">Gabriel Luke</h3>
          <p>CTO</p>
          <p>gabluke@gmail.com</p>
          <span :class="$style.action">
            <a href="mailto:" :class="$style.message">&#9993; Message</a>
            <a href="mailto:" :class="$style.call">&#9743; Call</a>
            <a href="mailto:" :class="$style.follow">+ Follow</a>
          </span>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "UserProfile",
};
</script>

<style module>
.display {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
  grid-gap: 0.6rem;
  place-items: center;
}
.card {
  box-shadow: 0 5px 9px 0 rgba(0, 0, 0, 0.4);
  width: 80%;
}

.container {
  padding: 10px 16px;
}

.heading {
  font-size: 50px;
  font-weight: 900;
  text-align: center;
}

.img {
  width: 20%;
  border-radius: 10px;
  margin-left: 7px;
  margin-top: 7px;
}
.action {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.message {
  background-color: #2563eb;
  color: #2563eb;
  padding: 9px;
  text-decoration: none;
  margin: 5px 0px;
  background: rgba(59, 130, 246, 0.1);
  border-radius: 16px;
}
.call {
  background-color: #ca8a04;
  color: #ca8a04;
  padding: 9px;
  text-decoration: none;
  margin: 5px 0px;
  border-radius: 16px;
  background: rgba(234, 179, 8, 0.1);
}
.follow {
  background-color: #16a34a;
  color: #16a34a;
  padding: 10px;
  text-decoration: none;
  margin: 5px 0px;
  background: rgba(34, 197, 94, 0.1);
  border-radius: 16px;
}
</style>
