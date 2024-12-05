<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <!-- Personal Info Section -->
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Personal Info</template>
    <p><strong>Mubashir Hussain</strong></p>
    <p><strong>Phone:</strong> +923228430133</p>
    <p>
      <strong>Email:</strong>
      <a href="mailto:mubashirhusssaindev@gmail.com">mubashirhusssaindev@gmail.com</a>
    </p>
    <p>
      <strong>LinkedIn:</strong>
      <a href="https://linkedin.com/in/mubashirhussainkhadim" target="_blank" rel="noopener"
        >linkedin.com/in/mubashirhussainkhadim</a
      >
    </p>
  </WelcomeItem>

  <!-- Technical Skills Section -->
  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Technical Skills</template>
    <p>
      <strong>Languages and Databases:</strong> PHP, Laravel, JavaScript, TypeScript, HTML, CSS,
      Bootstrap, Angular, Livewire, jQuery, Vue.js
    </p>
    <p>
      <strong>Visualization Tools:</strong> Laravel Herb, Forge, Envoyer, Composer, Artisan CLI,
      Blade Templating
    </p>
  </WelcomeItem>

  <!-- Current Role Section -->
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Current Role</template>
    <p><strong>Laravel Developer at Soft Access Ltd</strong> (June 2024 – Present)</p>
    <ul>
      <li>
        Developed dynamic and scalable web applications using Laravel and Livewire, ensuring
        seamless functionality and user experience.
      </li>
      <li>
        Collaborated with cross-functional teams to deliver optimized solutions tailored to project
        requirements, focusing on clean and efficient code.
      </li>
      <li>
        Integrated advanced Laravel tools like Herb, Forge, and Envoyer for deployment, performance
        optimization, and workflow automation.
      </li>
    </ul>
  </WelcomeItem>

  <!-- Previous Experience Section -->
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Previous Experience</template>

    <h4>Full Stack Laravel Developer at Asian Solution Ltd</h4>
    <p><em>January 2023 – June 2024</em></p>
    <ul>
      <li>
        Built and maintained robust web applications by leveraging Angular for the frontend and
        Laravel for the backend, ensuring high-quality, responsive designs.
      </li>
      <li>
        Collaborated with teams to develop feature-rich applications that adhered to industry best
        practices and client requirements.
      </li>
      <li>
        Implemented effective debugging and testing strategies to ensure software reliability and
        maintainability.
      </li>
    </ul>

    <h4>PHP Developer at Khadim Hospital</h4>
    <p><em>January 2020 – January 2023</em></p>
    <ul>
      <li>
        Led frontend and backend development projects, enhancing the hospital’s online systems for
        improved patient engagement and operational efficiency.
      </li>
      <li>
        Successfully integrated healthcare systems and third-party tools, improving functionality
        and streamlining workflows.
      </li>
      <li>
        Implemented SEO strategies to increase online visibility and ensured security measures to
        protect sensitive patient data.
      </li>
      <li>
        Maintained the hospital's website for optimal performance and responsiveness across devices.
      </li>
    </ul>
  </WelcomeItem>

  <!-- Projects Section -->
  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Projects</template>
    <p>
      These projects highlight your extensive experience in developing and maintaining dynamic,
      responsive websites across a wide range of industries:
    </p>
    <ul>
      <li>
        azmobiles.co.uk, fonedoctors.co.uk, foodeliciousbristol.co.uk, glossopphones.co.uk,
        indusfone.co.uk, instantmobilefix.co.uk, kwikfixfones.co.uk, mabileware.co.uk,
        mobilebitz.co.uk, mobilewhiz.co.uk, phoneandpcfixbeverley.co.uk, phonekinggrantham.co.uk,
        qaswa.co.uk, quickfixmobiles.co.uk, repairshub.co.uk, softaccess.co.uk,
        tangocommunication.co.uk, werepairanyphone.co.uk, and westendrepairs.co.uk.
      </li>
    </ul>
    <p>
      Your contributions included backend and frontend development using PHP, Laravel, and
      WordPress, optimizing site performance, and ensuring smooth functionality across different
      devices.
    </p>
  </WelcomeItem>

  <!-- Education Section -->
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Education</template>
    <ul>
      <li><strong>AI Developer Certificate from IBM</strong> (2024)</li>
      <li>
        <strong>Bachelor’s in Computer Science</strong> from Ranchi University and Government
        College, Faisalabad (January 2017 – December 2021).
      </li>
    </ul>
  </WelcomeItem>

  <!-- Contact Section -->
  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Contact</template>
    <p>
      Feel free to connect with me via
      <a href="https://linkedin.com/in/mubashirhussainkhadim" target="_blank" rel="noopener"
        >LinkedIn</a
      >
      or email me at
      <a href="mailto:mubashirhusssaindev@gmail.com" target="_blank" rel="noopener"
        >mubashirhusssaindev@gmail.com</a
      >.
    </p>
  </WelcomeItem>

  <!-- Support Vue Section (Optional) -->
  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Support Vue</template>
    <p>
      As an independent project, Vue relies on community backing for its sustainability. You can
      help us by
      <a href="https://vuejs.org/sponsor/" target="_blank" rel="noopener">becoming a sponsor</a>.
    </p>
  </WelcomeItem>
</template>
