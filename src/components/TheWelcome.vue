cd<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Personal Details</template>

    Am a Kenyan citizen by birth.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Education Background</template>

    Primary certificates.
    <br>
    Secondary certificates.
    <br>
    Bachelor degree.
    <br />
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Experience</template>
    PHP Beginner W3schools.
    <br>
    Network Security, Alison Online.
    </br>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Skills and Attribute</template>

    Alison Online Course certificate.
    <br>
    Rapid Skies training.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Referee</template>
    John Jack, Principal ZIwani Secondary.
    <br>
    Margrate Waithera, Lecturer Pwani University.
    </br>
  </WelcomeItem>
</template>
