<script>
export default {
  setup() {
    return {
      bios: [
        {
          id: 1,
          bio: "Me voilà revenu sur mes ambitions de départ « développeur », ma carrière m'aura pourtant mené sur d'autres chemins, de l'électricité à l'électromécanique, suivis de 15 ans dans le secteur du Nucléaire. Aujourd'hui c'est grâce à la mutation de mon ex-épouse dans la région de Poitiers, que cette opportunité à vue le jour. J'ai dû démissionner pour un rebondissement inattendu. Du Nucléaire ou j'ai passé la majeure partie de ma carrière, je garde la rigueur, la qualité de travail et la sûreté qui m'ont forgé un savoir-faire et des compétences techniques multi-domaines, tel que la rédaction de cahiers des charges, le suivi de projets, etc.",
        },
        {
          id: 2,
          bio: "Ces dernières, j'en suis sûr, me seront très utiles à l'avenir ! Ces compétences et ma motivation sont donc disponibles, pour qui saura les apprécier ! ",
        },
      ],
    };
  },
};
</script>

<template>
  <div class="block sm:flex sm:gap-10 mt-10 sm:mt-20">
    <!-- About profile image -->
    <div class="w-full sm:w-1/4 mb-7 sm:mb-0">
      <img src="@/assets/images/profile.jpeg" class="rounded-xl w-96" alt="" />
    </div>

    <!-- About details -->
    <div class="w-full sm:w-3/4 text-left">
      <p
        v-for="bio in bios"
        :key="bio.id"
        class="font-general-regular mb-4 text-ternary-dark dark:text-ternary-light text-lg">
        {{ bio.bio }}
      </p>
    </div>
  </div>
</template>
