<template lang="">
  <div>
    <div class="container-2">
      <footer class="footer-div">
        <div class="text-content">
          <p class="text-div">© Jobkhuzi.com</p>
        </div>
        <div class="course-container">
            <a href="">About</a>
            <a href="">course</a>
            <a href="">Our course</a>
            <a href="">Job</a>
        </div>
      </footer>
    </div>
  </div>
</template>
<script>
export default {
  name: 'NavbarComponents',

}
</script>
<style >


.container-2{
    background-color: black;
    width: 100%;
    height: 100%;
    margin: 10px;

}

.footer-div{
    display: flex;
    justify-content: space-between;
    align-items: center;
    height: 50px;
    width: 100%;
    padding: 20px 10px;
    box-sizing: border-box;

}

p{
    color: red;
}

a{
    text-decoration: none;
    font-family: Arial, Helvetica, sans-serif;
    padding-right: 10px;
    color: red;
}
</style>