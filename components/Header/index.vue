<template>
  <div class="container">
    <header>
      <img class="logo" src="https://irp.cdn-website.com/b6e3fb8b/DESKTOP/svg/logotipo-categorize-1.svg">
      <div class="nav-bar">
        <nav>      
          <ul class="nav-links">
            <li><a href="/">Conheça</a></li>
            <li><a href="/">Demo</a></li>
            <li><a href="/">Vendedores</a></li>
            <li><a href="/">Blog</a></li>
            <li><a href="/">FAQ</a></li>
          </ul>
        </nav>
        <a href="#"><button class="btn btn-register">Criar conta</button></a>    
        <a href="#"><button class="btn btn-login">Login</button></a>
      </div>
    </header>
  </div>
</template>

<script>

</script>

<style scoped lang="scss">
.logo {
  height: 4.1rem;
  cursor: pointer;
}

header {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  padding: 30px 10%;
}

.nav-bar {
  display: flex;
  align-items: center; 
}

.nav-links {
  list-style: none;
}

.nav-links li {
  display: inline-block;
  padding: 0 20px;  
}

.nav-links li a {
  transition: all 0.3s ease 0s;
  color: #002868;
  font-weight: 700;
}

.btn {
  padding: 0.6rem 1.2rem;
  border-width: 2px;
  font-style: normal;
  margin: 0.6rem;
  white-space: normal;
  transition: all 0.2s ease-in-out;
  display: inline-flex;
  align-items: center;
  justify-content: center;
  word-break: break-word;
  font-family: merriweather sans,sans-serif;
}

.btn-register {
  background: #002868;
  border-color: #002868;
  color: #fff;
  font-size: 1.2rem;
  font-weight: 700;
  line-height: 1.5;
  border-radius: 100px;

  &.active, &:hover {
    background: #001435;
  }
}

.btn-login {
  background: #04f7f7;
  border-color: #04f7f7;
  color: #000;
  font-size: 1.2rem;
  font-weight: 700;
  line-height: 1.5;
  border-radius: 100px;

  &.active, &:hover {
    background: #03c5c5;
    color: #fff;
  }
}

</style>