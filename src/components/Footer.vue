<template>
  <div class="footer-container container">
    <!-- div con logo -->
    <div class="logo-container">
      <img src="../assets/logo.png" alt="" />
    </div>

    <div class="menu-container">
      <ul>
        <li>titolo</li>
        <li><a href="#">Il pastificio</a></li>
        <li><a href="#">Il pastificio</a></li>
        <li><a href="#">Il pastificio</a></li>
        <li><a href="#">Il pastificio</a></li>
        <li><a href="#">Il pastificio</a></li>
        <li><a href="#">Il pastificio</a></li>
      </ul>

      <ul>
        <li>titolo</li>
        <li><a href="#">Il pastificio</a></li>
        <li><a href="#">Il pastificio</a></li>
        <li><a href="#">Il pastificio</a></li>
        <li><a href="#">Il pastificio</a></li>
        <li><a href="#">Il pastificio</a></li>
        <li><a href="#">Il pastificio</a></li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style lang="scss" scoped>
.footer-container {
  display: flex;

  .logo-container {
    width: 40%;

    img {
      width: 200px;
    }
  }
  .menu-container {
    flex-grow: 1;
    display: flex;

    ul {
      width: 50%;
      li {
          font-size: 12px;

          &:first-child{
              font-size: 18px;
              font-weight: bold;
          }
          a{
              color: #333;
              text-decoration: none;
              &:hover{
                  text-decoration: underline;
              }
          }
      }
    }
  }
}
</style>