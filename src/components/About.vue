<template>
    <div>
        <h1 class="content-title"><font-awesome-icon icon="user-circle" class="icon"/> About</h1>
        <div>
            <div class="about">
              <div class="me">
                <h2><font-awesome-icon icon="pen" class="icon"/> Name</h2>
                <p class="text">Hara</p>
              </div>

              <div class="me">
                <h2><font-awesome-icon icon="user-clock" class="icon"/> age</h2>
                <p class="text">26</p>
              </div>

              <div class="me">
                <h2><font-awesome-icon icon="map-pin" class="icon"/> Address</h2>
                <p class="text">Kanagawa</p>
              </div>
            </div>
        </div>
    </div>
</template>


<style>
.about{
    display:inline-flex;
    padding-left: 5%;
    padding-right: 5%;
}

.resent{
  margin-top: 50px;
}

.me{
    margin:0 50px;
}


@media screen and (max-width: 768px){
	.about {
		flex-direction: column;
	}

	.me {
    margin: 0 auto;
	}
}
</style>