<script setup>
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
    <template #heading>About Us</template>

    CorpMindsDigital Team provides you with all information you need to get started.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Training Programs</template>

    This section is served and bundled with training programs provided by our company
    
    <br />

    More instructions are available in <code>https://CorpMindsDigital.com</code>.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Why Choose Us</template>
    Your best choice for spcially crafted trainings will make your team members shine in their respective roles. Experience the difference.

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Testimonials & Results</template>
    Feel free to validate the credibility for our trainings and its impact. We are really happy to serve for your training needs like our existing customers.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Contact Us</template>
    As independent advisors, we bring a fresh perspective and value-driven strategies to your training journey.
    </WelcomeItem>
</template>
