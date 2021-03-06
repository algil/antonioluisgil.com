<template>
  <div>
    <h2 class="text-3xl font-bold text-center">About me</h2>
    <h3 class="mt-4 text-2xl font-bold text-brand">Biography</h3>
    <p class="mt-2">
      I am a software developer with 10+ years of experience using different
      technologies. During my career, I've worked as a full-stack developer, both
      in the Frontend and in the Backend, although in the latest years I'm
      focusing on Frontend architectures.
    </p>
    <p class="mt-4">
      Paying attention to the detail to ensure that users always perceive the
      best experience possible is one of my key objectives. For this reason, I
      keep on learning and developing skills that let me achieve this such as
      VueJS and other Frontend frameworks, CSS, NodeJS, etc.
    </p>
    <p class="mt-4">
      I believe that a close and productive collaboration between developers and
      designers is the key to success, and I think I am the ideal person to get
      the most out of it.
    </p>

    <h3 class="mt-8 text-2xl font-bold text-brand">Work experience</h3>
    <div class="mt-2 flex flex-col md:flex-row">
      <div class="text-secondary md:w-48">2018 - Current</div>
      <div class="flex-1">
        <h3 class="font-semibold">Senior developer</h3>
        <p class="text-sm text-secondary">FMIT Solutions - Málaga</p>
        <ul class="mt-2 ml-4 mr-8 list-disc">
          <li>
            Building a NodeJS RESTFul API for online store of Daimler (Mercedes
            Benz)
          </li>
        </ul>
      </div>
    </div>
    <div class="mt-4 flex flex-col md:flex-row">
      <div class="text-secondary md:w-48">2016 - 2018</div>
      <div class="flex-1">
        <h3 class="font-semibold">Senior Frontend Developer</h3>
        <p class="text-sm text-secondary">Ibistic Technologies Spain – Málaga</p>
        <ul class="mt-2 ml-4 mr-8 list-disc">
          <li>
            Built an expense application used by the Danish and Norwegian
            Government, developed with AngularJS and Typescript.
          </li>
          <li>
            Improved the initial application architecture removing duplicated
            code and splited in modules with a mono-repository aproach.
          </li>
          <li>
            Migrated the builder process from Grunt to Gulp and then begin the
            process to migrate to Webpack in a second interaction.
          </li>
        </ul>
      </div>
    </div>
    <div class="mt-4 flex flex-col md:flex-row">
      <div class="text-secondary md:w-48">2007 - 2016</div>
      <div class="flex-1">
        <h3 class="font-semibold">Senior Developer and Frontend Team Lead</h3>
        <p class="text-sm text-secondary">CSC (Computer Science Corporation) - Málaga</p>
        <ul class="mt-2 ml-4 mr-8 list-disc">
          <li>2014 - 2015 AngularJS applications development</li>
          <li>2013 - 2014 Java Swing Frontend Team Leader</li>
          <li>2007 - 2014 Java Swing application development</li>
        </ul>
      </div>
    </div>

    <h3 class="mt-8 text-2xl font-bold text-brand">Education</h3>
    <div class="mt-2 flex flex-col md:flex-row">
      <div class="text-secondary md:w-48">2016</div>
      <div class="flex-1">
        <h3 class="font-semibold">Master Web Engineering VI Edition - RIATec</h3>
        <p class="text-sm text-secondary">Málaga University</p>
      </div>
    </div>
    <div class="mt-4 flex flex-col md:flex-row">
      <div class="text-secondary md:w-48">2005 - 2007</div>
      <div class="flex-1">
        <h3 class="font-semibold">Certificate of Higher Education on Software Development</h3>
        <p class="text-sm text-secondary">IES Politécnico Jesús Marín - Málaga</p>
      </div>
    </div>

    <h3 class="mt-8 text-2xl font-bold text-brand">Additional training</h3>
    <div class="mt-2 flex flex-col md:flex-row">
      <div class="text-secondary md:w-48">Current</div>
      <div class="flex-1">
        <h3 class="font-semibold">Continuous training in online platforms and courses</h3>
        <p class="text-sm text-secondary">Platzi – Egghead – VueMastery – VueSchool</p>
      </div>
    </div>
    <div class="mt-4 flex flex-col md:flex-row">
      <div class="flex text-secondary md:w-48 md:flex-col">
        2014
        <span class="ml-1 text-sm md:m-0">(80 hours)</span>
      </div>
      <div class="flex-1">
        <h3 class="font-semibold">AngularJS and Bootstrap course</h3>
        <p class="text-sm text-secondary">HRCS - Málaga</p>
      </div>
    </div>
    <div class="mt-4 flex flex-col md:flex-row">
      <div class="flex text-secondary md:w-48 md:flex-col">
        2006 - 2007
        <span class="ml-1 text-sm md:m-0">(620 hours)</span>
      </div>
      <div class="flex-1">
        <h3 class="font-semibold">J2SE/J2EE Application Development</h3>
        <p class="text-sm text-secondary">FORMAN - Málaga</p>
      </div>
    </div>

    <h3 class="mt-8 text-2xl font-bold text-brand">Professional skills</h3>
    <div class="mt-2 flex flex-col justify-between md:flex-row">
      <div class="flex flex-col md:w-1/2 md:pr-8">
        <div class="flex justify-between items-center">
          <p class="font-semibold">Javascript</p>
          <div class="flex">
            <icon-star class="h-5 w-5 fill-current text-brand" />
            <icon-star class="h-5 w-5 fill-current text-brand" />
            <icon-star class="h-5 w-5 fill-current text-brand" />
            <icon-star class="h-5 w-5 fill-current text-brand" />
            <icon-star class="h-5 w-5 fill-current text-disabled" />
          </div>
        </div>
        <div class="flex justify-between">
          <p class="font-semibold">Typescript</p>
          <div class="flex">
            <icon-star class="h-5 w-5 fill-current text-brand" />
            <icon-star class="h-5 w-5 fill-current text-brand" />
            <icon-star class="h-5 w-5 fill-current text-brand" />
            <icon-star class="h-5 w-5 fill-current text-brand" />
            <icon-star class="h-5 w-5 fill-current text-disabled" />
          </div>
        </div>
        <div class="flex justify-between">
          <p class="font-semibold">Vue JS</p>
          <div class="flex">
            <icon-star class="h-5 w-5 fill-current text-brand" />
            <icon-star class="h-5 w-5 fill-current text-brand" />
            <icon-star class="h-5 w-5 fill-current text-brand" />
            <icon-star class="h-5 w-5 fill-current text-brand" />
            <icon-star class="h-5 w-5 fill-current text-brand" />
          </div>
        </div>
        <div class="flex justify-between">
          <p>Angular JS</p>
          <div class="flex">
            <icon-star class="h-5 w-5 fill-current text-brand" />
            <icon-star class="h-5 w-5 fill-current text-brand" />
            <icon-star class="h-5 w-5 fill-current text-brand" />
            <icon-star class="h-5 w-5 fill-current text-brand" />
            <icon-star class="h-5 w-5 fill-current text-brand" />
          </div>
        </div>
        <div class="flex justify-between">
          <p>Angular</p>
          <div class="flex">
            <icon-star class="h-5 w-5 fill-current text-brand" />
            <icon-star class="h-5 w-5 fill-current text-brand" />
            <icon-star class="h-5 w-5 fill-current text-brand" />
            <icon-star class="h-5 w-5 fill-current text-disabled" />
            <icon-star class="h-5 w-5 fill-current text-disabled" />
          </div>
        </div>
        <div class="flex justify-between">
          <p class="font-semibold">HTML5 &amp; CSS3</p>
          <div class="flex">
            <icon-star class="h-5 w-5 fill-current text-brand" />
            <icon-star class="h-5 w-5 fill-current text-brand" />
            <icon-star class="h-5 w-5 fill-current text-brand" />
            <icon-star class="h-5 w-5 fill-current text-brand" />
            <icon-star class="h-5 w-5 fill-current text-disabled" />
          </div>
        </div>
        <div class="flex justify-between">
          <p>Node &amp; Express</p>
          <div class="flex">
            <icon-star class="h-5 w-5 fill-current text-brand" />
            <icon-star class="h-5 w-5 fill-current text-brand" />
            <icon-star class="h-5 w-5 fill-current text-brand" />
            <icon-star class="h-5 w-5 fill-current text-brand" />
            <icon-star class="h-5 w-5 fill-current text-disabled" />
          </div>
        </div>
        <div class="flex justify-between">
          <p>Java</p>
          <div class="flex">
            <icon-star class="h-5 w-5 fill-current text-brand" />
            <icon-star class="h-5 w-5 fill-current text-brand" />
            <icon-star class="h-5 w-5 fill-current text-brand" />
            <icon-star class="h-5 w-5 fill-current text-brand" />
            <icon-star class="h-5 w-5 fill-current text-brand" />
          </div>
        </div>
      </div>
      <div class="flex flex-col md:w-1/2 md:pr-8">
        <div class="flex justify-between">
          <p>Android</p>
          <div class="flex">
            <icon-star class="h-5 w-5 fill-current text-brand" />
            <icon-star class="h-5 w-5 fill-current text-brand" />
            <icon-star class="h-5 w-5 fill-current text-disabled" />
            <icon-star class="h-5 w-5 fill-current text-disabled" />
            <icon-star class="h-5 w-5 fill-current text-disabled" />
          </div>
        </div>
        <div class="flex justify-between">
          <p>C#</p>
          <div class="flex">
            <icon-star class="h-5 w-5 fill-current text-brand" />
            <icon-star class="h-5 w-5 fill-current text-brand" />
            <icon-star class="h-5 w-5 fill-current text-disabled" />
            <icon-star class="h-5 w-5 fill-current text-disabled" />
            <icon-star class="h-5 w-5 fill-current text-disabled" />
          </div>
        </div>
        <div class="flex justify-between">
          <p>PHP &amp; Laravel</p>
          <div class="flex">
            <icon-star class="h-5 w-5 fill-current text-brand" />
            <icon-star class="h-5 w-5 fill-current text-brand" />
            <icon-star class="h-5 w-5 fill-current text-brand" />
            <icon-star class="h-5 w-5 fill-current text-disabled" />
            <icon-star class="h-5 w-5 fill-current text-disabled" />
          </div>
        </div>
        <div class="flex justify-between">
          <p>WordPress</p>
          <div class="flex">
            <icon-star class="h-5 w-5 fill-current text-brand" />
            <icon-star class="h-5 w-5 fill-current text-brand" />
            <icon-star class="h-5 w-5 fill-current text-brand" />
            <icon-star class="h-5 w-5 fill-current text-disabled" />
            <icon-star class="h-5 w-5 fill-current text-disabled" />
          </div>
        </div>
        <div class="flex justify-between">
          <p>SQL</p>
          <div class="flex">
            <icon-star class="h-5 w-5 fill-current text-brand" />
            <icon-star class="h-5 w-5 fill-current text-brand" />
            <icon-star class="h-5 w-5 fill-current text-brand" />
            <icon-star class="h-5 w-5 fill-current text-disabled" />
            <icon-star class="h-5 w-5 fill-current text-disabled" />
          </div>
        </div>
        <div class="flex justify-between">
          <p>Gulp / Webpack</p>
          <div class="flex">
            <icon-star class="h-5 w-5 fill-current text-brand" />
            <icon-star class="h-5 w-5 fill-current text-brand" />
            <icon-star class="h-5 w-5 fill-current text-brand" />
            <icon-star class="h-5 w-5 fill-current text-brand" />
            <icon-star class="h-5 w-5 fill-current text-disabled" />
          </div>
        </div>
        <div class="flex justify-between">
          <p>Testing frameworks</p>
          <div class="flex">
            <icon-star class="h-5 w-5 fill-current text-brand" />
            <icon-star class="h-5 w-5 fill-current text-brand" />
            <icon-star class="h-5 w-5 fill-current text-brand" />
            <icon-star class="h-5 w-5 fill-current text-disabled" />
            <icon-star class="h-5 w-5 fill-current text-disabled" />
          </div>
        </div>
      </div>
    </div>

    <div class="mt-8 flex flex-col md:flex-row">
      <div class="md:w-1/2">
        <h3 class="text-2xl font-bold text-brand">Personal qualities</h3>
        <ul class="mt-2">
          <li>Team work</li>
          <li>Attention to details</li>
          <li>Versatile</li>
        </ul>
      </div>
      <div class="mt-8 md:w-1/2 md:mt-0">
        <h3 class="text-2xl font-bold text-brand">Languages</h3>
        <p class="mt-2"><span class="font-semibold">English:</span> Basic spoken and fluent written</p>
        <p><span class="font-semibold">Spanish:</span> Mother Tongue</p>
      </div>
    </div>
  </div>
</template>

<script>
import IconStar from '@/components/icons/icon-star.vue'

export default {
  components: {
    IconStar
  },

  head: {
    title: 'About me - Antonio Gil'
  }
}
</script>
