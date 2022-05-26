<template>
  <section id="resume">
    <h1 class="text-center text-3xl mb-20">Resume</h1>

    <div class="my-10">
      <h2 class="flex items-center text-2xl space-x-5 font-thin">
        <CodeIcon class="h-10" />
        <span>Skills</span>
      </h2>
      <ul class="pl-4 md:pl-20 flex flex-col space-y-2 mt-5 list-disc list-inside">
        <li>
          Professional experience with PHP, JavaScript / jQuery, MySQL and CSS
        </li>
        <li>Knowledge of Vue.js, Tailwind CSS, Git, and Apache</li>
        <li>
          Writing readable, documented code with attention to detail and
          performance
        </li>
        <li>Ability to work in fast-pace environments</li>
        <li>Attentive to detail and minful of perfomance and efficiency</li>
        <li>Troubleshooting and resolving errors in a timely manner</li>
      </ul>
    </div>

    <div class="my-10">
      <h2 class="flex items-center text-2xl space-x-5 font-thin">
        <BriefcaseIcon class="h-10" />
        <span>Professional Employment</span>
      </h2>
      <div class="pl-2 md:pl-16">
        <div class="flex flex-col md:flex-row md:space-x-10 my-5 py-2 px-4">
          <div class="w-44 mb-2 md:mb-0">
            <div class="text-lg font-semibold">Software Developer</div>
            <a href="https://www.scootaround.com">Scootaround Inc.</a>
            <div class="text-gray-600">Jan. 2021 - Present</div>
          </div>
          <ul class="pl-4 md:pl-0 list-disc text-sm">
            <li class="my-2">
              Collaborate with internal and external teams to develop new
              features for clients and staff
            </li>
            <li class="my-2">
              Actively use GitHub for internal code reviews and managing
              pull-requests
            </li>
            <li class="my-2">
              Increased quote intake efficiency over 25% by re-developing
              internal booking page
            </li>
          </ul>
        </div>

        <hr />

        <div class="flex flex-col md:flex-row md:space-x-10 my-5 py-2 px-4">
          <div class="w-44 mb-2 md:mb-0">
            <div class="text-lg font-semibold">Lead Developer</div>
            <a href="https://www.fastoche.ca">Fastoche Canada</a>
            <div class="text-gray-600">Aug. 2016 - Dec. 2020</div>
          </div>
          <ul class="pl-4 md:pl-0 list-disc text-sm">
            <li class="my-2">
              Develop, design, test and maintain web applications for nearly 200
              daycare centres across Canada with more than half in Manitoba
            </li>
            <li class="my-2">
              Developed a batch EFT system using Bambora's API to help process
              over $32,000 a month in transactions
            </li>
            <li class="my-2">
              Deployed a free electronic COVID-19 screening tool that improves
              efficiency, organization and reduce paper usage for over 250
              daycare centres
            </li>
            <li class="my-2">
              Built a parent arrival estimator that allows daycares to better
              prepare children for pickup using Google Maps, Geocoding and
              Directions API
            </li>
            <li class="my-2">
              Create intricate systems such as rate calculation and subsidy
              estimation
            </li>
            <li class="my-2">
              Troubleshoot problems that arise from testing or through customer
              feedback and resolve in a timely manner
            </li>
          </ul>
        </div>

        <hr />

        <div class="flex flex-col md:flex-row md:space-x-10 my-5 py-2 px-4">
          <div class="w-44 mb-2 md:mb-0">
            <div class="text-lg font-semibold">Freelance Developer</div>
            <a href="https://www.fastoche.ca">Self-employed</a>
            <div class="text-gray-600">Feb. 2016 - Aug. 2016</div>
          </div>
          <ul class="pl-4 md:pl-0 list-disc text-sm">
            <li class="my-2">
              Design, develop and deploy website to DigitalOcean
            </li>
            <li class="my-2">
              Meet with clients to understand website requirements
            </li>
            <li class="my-2">
              Maintain client domains, DNS records and MySQL databases
            </li>
          </ul>
        </div>
      </div>
    </div>

    <div class="my-10">
      <h2 class="flex items-center text-2xl space-x-5 font-thin">
        <EducationIcon class="h-10" />
        <span>Education</span>
      </h2>
      <div class="pl-2 md:pl-16">
        <div class="my-5 py-2 px-4">
          <div class="text-lg font-semibold">
            Business of Information Technology
          </div>
          <a href="https://www.rrc.ca/">Red River College</a>
          <div class="text-gray-600">March 2013 - February 2016</div>
        </div>
      </div>
    </div>

    <div class="my-10">
      <h2 class="flex items-center text-2xl space-x-5 font-thin">
        <LightBulbIcon class="h-10" />
        <span>Actively Learning</span>
      </h2>
      <div class="pl-2 md:pl-16 flex items-center mt-5">
        <VueLogo title="Vue.js"/>
        <ElixirLogo class="ml-2 h-12" title="Elixir"/>
        <ReactLogo title="React.js"/>
        <TypeScriptLogo class="ml-3" title="TypeScript"/>
      </div>
    </div>

    <div class="my-10">
      <h2 class="flex items-center text-2xl space-x-5 font-thin">
        <PuzzlePieceIcon class="h-10" />
        <span>Activities & Interests</span>
      </h2>
      <ul class="pl-4 md:pl-20 flex flex-col space-y-2 mt-5 list-disc list-inside">
        <li>
          Volunteer A/V technician for A11yTO - Web Accessibility Conference
        </li>
        <li>Professional Development - Prairie Dev Con & ConFoo</li>
        <li>Reading up on the latest tech releases</li>
        <li>Camping in Manitoba</li>
        <li>Cooking & Baking</li>
        <li>Woodworking</li>
      </ul>
    </div>
  </section>
</template>

<script setup>
  import ElixirLogo from "./icons/ElixirLogo.vue";
  import ReactLogo from "./icons/ReactLogo.vue";
  import VueLogo from "./icons/VueLogo.vue";
  import TypeScriptLogo from "./icons/TypeScriptLogo.vue";
  import CodeIcon from "./icons/CodeIcon.vue";
  import BriefcaseIcon from "./icons/BriefcaseIcon.vue";
  import EducationIcon from "./icons/EducationIcon.vue";
  import LightBulbIcon from "./icons/LightBulbIcon.vue";
  import PuzzlePieceIcon from "./icons/PuzzlePieceIcon.vue";
</script>
