<template>
  <section class="resume-section p-3 p-lg-5 d-flex align-items-center" id="about">
    <div class="w-100">
      <h1 class="mb-0">
        Bruno
        <span class="name">Marques</span>
      </h1>
      <div class="subheading mb-5">
        Santos, SP, Brasil - 
        <a
          href="mailto:brunomarks@gmail.com"
        >brunomarks@gmail.com</a>
      </div>
      <p
        class="lead mb-5"
      >
      Sou desenvolvedor Front-End, FullStack. 
      Atualmente tenho trabalhado com VueJS, PHP, WordPress, WooCommerce e GraphQL. Entrego código de qualidade, com um criterioso QA.
      </p>
      <p class="lead mb-5">
        Atuo como consultor para uma PropTech do ramo imobiliário chamada <a href="https://github.com/LokeCarlsson/gridsome-starter-resume"
          target="_blank"
          rel="noopener noreferrer">Apê11</a>. Sou fundador do Bazar Indiano e realizo alguns projetos como <strong>freelancer</strong>.
      </p>
      <div class="social-icons">
        <a href="https://linkedin.com/in/lokecarlsson" target="_blank" rel="noopener noreferrer">
          <font-awesome :icon="['fab', 'linkedin']"/>
        </a>
        <a href="https://github.com/brunomarks7" target="_blank" rel="noopener noreferrer">
          <font-awesome :icon="['fab', 'github']"/>
        </a>
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
.social-icons a {
  cursor: pointer;
  display: inline-block;
  height: 3.5rem;
  width: 3.5rem;
  background-color: var(--secondary);
  color: #fff !important;
  border-radius: 100%;
  text-align: center;
  font-size: 1.5rem;
  line-height: 3.5rem;
  margin-right: 1rem;

  @media (max-width: 380px) {
    margin-right: 0.5rem;
  }

  @media (max-width: 350px) {
    margin-right: 0.2rem;
  }
}
.name {
  color: #41b883;
}
.social-icons a:last-child {
  margin-right: 0;
}

.social-icons a:hover {
  background-color: var(--primary);
}
</style>
