<template>
    <div>
      <nav class="navbar navbar-expand-lg navbar-dark bg-dark static-top">
              <div class="container">
                <a class="navbar-brand" href="#">
                  <Logo></Logo>
                </a>
                  
                  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarResponsive" aria-controls="navbarResponsive" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                  </button>
                    
                    <div class="collapse navbar-collapse" id="navbarResponsive">
                      <ul class="navbar-nav ml-auto">
                        <li class="nav-item active">
                          <nuxt-link class="nav-link" to="/">Home
                            <span class="sr-only">(current)</span>
                          </nuxt-link>
                        </li>
                        <li class="nav-item">
                          <nuxt-link class="nav-link" to="/about">About</nuxt-link>
                        </li>
                        <li class="nav-item">
                          <a class="nav-link" href="#">Services</a>
                        </li>
                        <li class="nav-item">
                          <a class="nav-link" href="#">Contact</a>
                        </li>
                      </ul>
                    </div>
              
              </div>
  </nav>
</div>
</template>