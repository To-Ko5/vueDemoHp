<template>
  <header class="header">
    <div class="container">
      <h1>DEAL CAFE</h1>
      <nav>
        <ul class="gnav">
          <li><router-link to="/" active-class="active-list" exact>HOME</router-link></li>
          <li><router-link to="/drink" active-class="active-list" exact>DRINK</router-link></li>
          <li><router-link to="/info" active-class="active-list" exact>INFO</router-link></li>
          <li><router-link to="/contact" active-class="active-list" exact>CONTACT</router-link></li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<script></script>


<style lang="sass" scoped>
    .header
          padding: 20px 0
          .container 
                    display: flex
                    justify-content: space-between
                    align-items: baseline
                    .gnav
                        display: flex
                        li
                          margin-left: 10px
                          a
                           &:hover
                                  border-bottom: 2px solid
    .active-list
               border-bottom: 2px solid
</style>