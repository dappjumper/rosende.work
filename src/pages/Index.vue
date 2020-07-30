<template>
  <Layout>
    <h1 class="logo">Tobias<span>Andersen</span></h1>
    <h2 class="subtitle"><b>Say hi:</b> tobias@andersen.work</h2>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'Portfolio'
  }
}
</script>

<style>
.home-links a {
  margin-right: 1rem;
}
.logo, .subtitle {
  text-align:center;
  font-size:6rem;
  font-weight:200;
  color:#fafafa;
  text-shadow:0px 0px 3rem rgba(0,0,0,0.2);
}
.subtitle {
  font-size:2rem;
}
.logo span{
  margin-left:-1rem;
  position:relative;
  top:3rem;
  font-weight:600;
}

@media only screen and (max-width: 700px) {
  .logo {
    font-size:12vw;
  }
  .logo span {
    top:5vw;
    margin-left:0rem;
  }
}

</style>
