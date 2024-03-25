<script setup lang="ts">
import landingHero from '@/components/landing/landing-hero.vue';

const features = [
  {
    name: 'Spam report',
    description:
      'Autem reprehenderit aut debitis ut. Officiis harum omnis placeat blanditiis delectus sint vel et voluptatum. Labore asperiores non corporis molestiae.',
  },
  {
    name: 'Compose in markdown',
    description:
      'Illum et aut inventore. Ut et dignissimos quasi. Omnis saepe dolorum. Hic autem fugiat. Voluptatem officiis necessitatibus est.',

  },
  {
    name: 'Email commenting',
    description:
      'Commodi quam quo. In quasi mollitia optio voluptate et est reiciendis. Ut et sunt id officiis vitae perspiciatis. Et accusantium sapiente.',

  },
  {
    name: 'Customer connections',
    description:
      'Deserunt corrupti praesentium quo vel cupiditate est occaecati ad. Aperiam libero modi similique iure praesentium facilis quo cumque quibusdam.',

  },
];
</script>

<template>
  <landing-hero />

  <div class="bg-white py-24 sm:py-32">
    <div class="mx-auto max-w-7xl px-6 lg:px-8">
      <div class="mx-auto grid max-w-2xl grid-cols-1 gap-x-8 gap-y-16 sm:gap-y-20 lg:mx-0 lg:max-w-none lg:grid-cols-3">
        <h2 class="text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl">
          Stay on top of customer support
        </h2>
        <dl class="col-span-2 grid grid-cols-1 gap-x-8 gap-y-16 sm:grid-cols-2">
          <div
            v-for="feature in features"
            :key="feature.name"
          >
            <dt class="text-base font-semibold leading-7 text-gray-900">
              <div class="mb-6 flex h-10 w-10 items-center justify-center rounded-lg bg-indigo-600" />
              {{ feature.name }}
            </dt>
            <dd class="mt-1 text-base leading-7 text-gray-600">
              {{ feature.description }}
            </dd>
          </div>
        </dl>
      </div>
    </div>
  </div>

  <div class="bg-white">
    <div class="mx-auto max-w-7xl py-24 sm:px-6 sm:py-32 lg:px-8">
      <div class="relative isolate overflow-hidden bg-gray-900 px-6 pt-16 shadow-2xl sm:rounded-3xl sm:px-16 md:pt-24 lg:flex lg:gap-x-20 lg:px-24 lg:pt-0">
        <svg
          viewBox="0 0 1024 1024"
          class="absolute left-1/2 top-1/2 -z-10 h-[64rem] w-[64rem] -translate-y-1/2 [mask-image:radial-gradient(closest-side,white,transparent)] sm:left-full sm:-ml-80 lg:left-1/2 lg:ml-0 lg:-translate-x-1/2 lg:translate-y-0"
          aria-hidden="true"
        >
          <circle
            cx="512"
            cy="512"
            r="512"
            fill="url(#759c1415-0410-454c-8f7c-9a820de03641)"
            fill-opacity="0.7"
          />
          <defs>
            <radialGradient id="759c1415-0410-454c-8f7c-9a820de03641">
              <stop stop-color="#7775D6" />
              <stop
                offset="1"
                stop-color="#E935C1"
              />
            </radialGradient>
          </defs>
        </svg>
        <div class="mx-auto max-w-md text-center lg:mx-0 lg:flex-auto lg:py-32 lg:text-left">
          <h2 class="text-3xl font-bold tracking-tight text-white sm:text-4xl">
            Boost your productivity.<br>Start using our app today.
          </h2>
          <p class="mt-6 text-lg leading-8 text-gray-300">
            Ac euismod vel sit maecenas id pellentesque eu sed consectetur. Malesuada adipiscing sagittis vel nulla.
          </p>
          <div class="mt-10 flex items-center justify-center gap-x-6 lg:justify-start">
            <a
              href="#"
              class="rounded-md bg-white px-3.5 py-2.5 text-sm font-semibold text-gray-900 shadow-sm hover:bg-gray-100 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-white"
            >Get started</a>
            <a
              href="#"
              class="text-sm font-semibold leading-6 text-white"
            >Learn more <span aria-hidden="true">→</span></a>
          </div>
        </div>
        <div class="relative mt-16 h-80 lg:mt-8">
          <img
            class="absolute left-0 top-0 w-[57rem] max-w-none rounded-md bg-white/5 ring-1 ring-white/10"
            src="https://tailwindui.com/img/component-images/dark-project-app-screenshot.png"
            alt="App screenshot"
            width="1824"
            height="1080"
          >
        </div>
      </div>
    </div>
  </div>
  <div class="bg-white py-24 sm:py-32">
    <div class="mx-auto max-w-7xl px-6 lg:px-8">
      <div class="mx-auto max-w-2xl lg:mx-0">
        <h2 class="text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl">
          We approach the workplace as something that adds to our lives and adds value to world.
        </h2>
        <p class="mt-6 text-base leading-7 text-gray-600">
          Diam nunc lacus lacus aliquam turpis enim. Eget hac velit est euismod lacus. Est non placerat nam arcu. Cras purus nibh cursus sit eu in id. Integer vel nibh.
        </p>
      </div>
      <div class="mx-auto mt-16 flex max-w-2xl flex-col gap-8 lg:mx-0 lg:mt-20 lg:max-w-none lg:flex-row lg:items-end">
        <div class="flex flex-col-reverse justify-between gap-x-16 gap-y-8 rounded-2xl bg-gray-50 p-8 sm:w-3/4 sm:max-w-md sm:flex-row-reverse sm:items-end lg:w-72 lg:max-w-none lg:flex-none lg:flex-col lg:items-start">
          <p class="flex-none text-3xl font-bold tracking-tight text-gray-900">
            250k
          </p>
          <div class="sm:w-80 sm:shrink lg:w-auto lg:flex-none">
            <p class="text-lg font-semibold tracking-tight text-gray-900">
              Users on the platform
            </p>
            <p class="mt-2 text-base leading-7 text-gray-600">
              Vel labore deleniti veniam consequuntur sunt nobis.
            </p>
          </div>
        </div>
        <div class="flex flex-col-reverse justify-between gap-x-16 gap-y-8 rounded-2xl bg-gray-900 p-8 sm:flex-row-reverse sm:items-end lg:w-full lg:max-w-sm lg:flex-auto lg:flex-col lg:items-start lg:gap-y-44">
          <p class="flex-none text-3xl font-bold tracking-tight text-white">
            $8.9 billion
          </p>
          <div class="sm:w-80 sm:shrink lg:w-auto lg:flex-none">
            <p class="text-lg font-semibold tracking-tight text-white">
              We’re proud that our customers have made over $8 billion in total revenue.
            </p>
            <p class="mt-2 text-base leading-7 text-gray-400">
              Eu duis porta aliquam ornare. Elementum eget magna egestas.
            </p>
          </div>
        </div>
        <div class="flex flex-col-reverse justify-between gap-x-16 gap-y-8 rounded-2xl bg-indigo-600 p-8 sm:w-11/12 sm:max-w-xl sm:flex-row-reverse sm:items-end lg:w-full lg:max-w-none lg:flex-auto lg:flex-col lg:items-start lg:gap-y-28">
          <p class="flex-none text-3xl font-bold tracking-tight text-white">
            401,093
          </p>
          <div class="sm:w-80 sm:shrink lg:w-auto lg:flex-none">
            <p class="text-lg font-semibold tracking-tight text-white">
              Transactions this year
            </p>
            <p class="mt-2 text-base leading-7 text-indigo-200">
              Eu duis porta aliquam ornare. Elementum eget magna egestas. Eu duis porta aliquam ornare.
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
  /* No custom styles needed */
</style>
