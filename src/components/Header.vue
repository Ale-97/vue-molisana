<template>
  <div class="header-full">
    <div class="logo-container">
      <img src="../assets/logo.png" alt="" />
    </div>

    <nav>
      <ul>
        <li>Home</li>
        <li>Prodotti</li>
        <li>Chi Siamo</li>
        <li>Contatti</li>
      </ul>
    </nav>
  </div>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style lang="scss" scoped>
.header-full {
  .logo-container {
    text-align: center;

    img {
      width: 200px;
    }
  }

  nav {
    ul {
      display: flex;
      list-style: none;
      justify-content: center;
      font-size: 14px;
      font-weight: bold;

      li {
        margin: 5px 0;
        height: 50px;
        line-height: 50px;
        padding: 0 10px;
        cursor: pointer;

        &:hover{
            background: #cee;
        }
      }
    }
  }
}
</style>