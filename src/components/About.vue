<template>
  <div id="about">
    <div class="text">
      <h2>About Me</h2>
      <p>
        My name is Gabriela, I'm 27 years old, raised and born in São Paulo,
        Brazil. I graduated in 2018 as a bachelor's in physics in UNESP - São
        Paulo State University. On my graduation, I was a São Paulo Reserarch
        Foundation (FAPESP) scholarship holder. In august of 2018 I went to Brno
        in Czech Republic with Research Interships Aborad (BEPE), a scholarship
        provided by FAPESP. My journey with development started at 2021 when I
        joined ChatGuru as a Customer Success. I always have been curious about
        programation and started to study WEB development. An oportunity
        appeared to become a FrontEnd Developer and I went for it. I stayed at
        ChatGuru until april 2024 and now I'm looking for new opportunities. I
        started studying accessibility for websites and I'm foccused on pixel
        perfect.
      </p>
    </div>
    <div class="photo">
      <img src="../assets/photo.jpg" alt="Photo of Gabriela." />
    </div>
  </div>
</template>

<script>
export default {
  name: "AboutMe",
};
</script>

<style lang="scss">
#about {
  display: flex;
  justify-content: space-between;
  min-height: 100vh;
  padding: 0 200px;
  align-items: center;
  .text {
    width: 60%;
    p{
      margin-top: 20px;
      line-height: 25px;
      text-align: justify;
    }
  }
  h2{
    color: #325456;
  }
  .photo {
    background-color: #dbe0e0;
    padding: 20px;
    height: 100%;
    border-radius: 5px;
    img {
      height: 300px;
      filter: grayscale(1);
      transition: all 1s ease;
      &:hover {
        filter: none;
      }
    }
  }
}
</style>
