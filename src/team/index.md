---
pageClass: careers
sidebar: false
aside: false
page: true
#footer: false
editLink: false
stackOverflowLink: false
prev: false
next: false
---

<script setup>
import SwagTeam from "../components/team/SwagTeam.vue";
</script>

<!-- HERO -->
<SwagHero class="my-30">
    <template #label>Our crew</template>
    <template #title>Driven by empathy, guided by innovation.</template>
    <template #content><p>Meteor is Shopware’s open source design system – The Shopware Design Language builds it’s foundation, the system helps us create elegant, delightful, and accessible personal experiences that empower and inspire all of Shopware's merchants and shoppers.</p></template>
    <template #links>
    <SwagBtn href="#GetToKnow" class="--primary --sm" icon="long-arrow-right" icon-at="end">Get started</SwagBtn>
    <SwagBtn href="/what-is-new.html" class="--primary --subtle --with-border --sm --transparent">See what's new</SwagBtn>
    </template>
    <template #image><img src="/home/hub-hero-min.png" /></template>
</SwagHero>
<div style="margin-top:450px;"></div>
<SwagTeam />




