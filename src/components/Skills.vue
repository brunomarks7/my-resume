<template>
  <section class="resume-section p-3 p-lg-5 d-flex align-items-center" id="skills">
    <div class="w-100">
      <h2 class="mb-5">Skills</h2>

      <div class="subheading mb-3">Tecnologias e Ferramentas</div>
      <ul class="list-inline dev-icons">
        <li class="list-inline-item">
          <font-awesome :icon="['fab', 'html5']"/>
        </li>
        <li class="list-inline-item">
          <font-awesome :icon="['fab', 'css3-alt']"/>
        </li>
        <li class="list-inline-item">
          <font-awesome :icon="['fab', 'js-square']"/>
        </li>
        <li class="list-inline-item">
          <font-awesome title="WordPress" :icon="['fab', 'wordpress']"/>
        </li>
        <li class="list-inline-item">
          <font-awesome title="VueJS" :icon="['fab', 'vuejs']"/>
        </li>
        <li class="list-inline-item">
          <font-awesome :icon="['fab', 'node-js']"/>
        </li>
        <li class="list-inline-item">
          <font-awesome :icon="['fab', 'sass']"/>
        </li>
        <li class="list-inline-item">
          <font-awesome :icon="['fab', 'gulp']"/>
        </li>
        <li class="list-inline-item">
          <font-awesome :icon="['fab', 'grunt']"/>
        </li>
        <li class="list-inline-item">
          <font-awesome :icon="['fab', 'npm']"/>
        </li>
        <li class="list-inline-item">
          <font-awesome :icon="['fab', 'yarn']"/>
        </li>
      </ul>

      <div class="subheading mb-3">Workflow</div>
      <ul class="fa-ul mb-0">
        <li>
          <font-awesome class="fa-li" :icon="['fas', 'check']"/>Unix, Docker, VSCode
        </li>
        <li>
          <font-awesome class="fa-li" :icon="['fas', 'check']"/>Mobile-First, Responsive Design
        </li>
        <li>
          <font-awesome class="fa-li" :icon="['fas', 'check']"/>WebPack, Gulp, task runners
        </li>
        <li>
          <font-awesome class="fa-li" :icon="['fas', 'check']"/>UX, Micro-frontend, UI kits
        </li>
        <li>
          <font-awesome class="fa-li" :icon="['fas', 'check']"/>SEO, Performance
        </li>
      </ul>
    </div>
  </section>
</template>
