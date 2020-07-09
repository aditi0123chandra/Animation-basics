<template>
    <section class="about">
    <br>
    <br><br>
    <h1 v-scrollanim>ABOUT US</h1>
    <br>
    <h3 v-scrollanim>
      <br />The School of Engineering and technology (SET) is an open platform
      for <br />diverse voices where teaching runs parallel to the real world
      <br />distinguished and students are groomed to join the global workforce.
      SET is <br />distinguished as one of the top-ranked engineering schools in
      <br />India. The students at SET benefit through the professional grooming
      of <br />renowned faculty and industry experts having experience of
      <br />tackling pressing engineering problems. Students discover their
      passion in <br />one of the various offered Engineering majors at the
      <br />School of Engineering and technology. A student-centric pedagogy,
      <br />project-based approach and design-driven curriculum provides
      <br />students with an inclination for complex problem solving, design,
      <br />innovation, and a passion for learning. The mission of the School of
      <br />Engineering and technology through its various programmes is to
      educate <br />wellintegrated individuals who possess technical and social
      competence to <br />succeed in professional arenas and design solutions
      <br />for global problems.
    </h3>
      <button>Our Faculties</button> <br /><br />
      <button>Our Students</button>
    </section>
</template>

<script>
  export default {};
</script>

<style lang="scss" scoped>
  .about {
    position: relative;
    width: 100%;
    min-height: 100vh;

  .h3 {
      font-size: 1.2rem;
      padding: 10px 20px;
    }
  }

  .before-enter {
    opacity: 0;
    transform: translateY(100px);
    transition: all 2s ease-out;
  }

  .enter {
    opacity: 1;
    transform: translateY(0px);
  }
</style>
