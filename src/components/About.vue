<template>
  <div id="about">
    <div class="text">
      <h2>About Me</h2>
      <p>
        Hello, I'm Gabriela, a 27-year-old from São Paulo, Brazil. I graduated
        in Physics from São Paulo State University in 2018, with the support of
        a scholarship from the São Paulo Research Foundation (FAPESP). After an
        enriching research internship in Brno, Czech Republic, I joined ChatGuru
        in 2021 as a Customer Success member. Intrigued by programming, I
        transitioned to become a Frontend Developer. Now, as I seek new
        opportunities, I'm focused on perfecting pixel-perfect designs and
        enhancing website accessibility.
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
    p {
      margin-top: 20px;
      line-height: 25px;
      text-align: justify;
    }
  }
  h2 {
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
