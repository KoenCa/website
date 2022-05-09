<template>
  <div>

  </div>
</template>

<script setup>
const SECTIONS = [
  {
    id: "aboutSection",
    title: "About",
  },
  {
    id: "educationSection",
    title: "Education",
  },
  {
    id: "workSection",
    title: "Work Experience",
  },
  {
    id: "developmentExperienceSection",
    title: "Development experience",
  },
  {
    id: "sideProjectsSection",
    title: "Side projects",
  },
]

const activeSection = ref(SECTIONS[0].id)
const moveBodyForSidebar = ref(false)

</script>
