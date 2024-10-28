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
    <template #heading>Documentation</template>

    Click on
    <a href="https://vuejs.org/" target="_blank" rel="noopener">this thing</a>
    to find out everything you need to know. But be warned ... it's very boring
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Tooling</template>

    The reason you are here is all because of
    <a href="https://vite.dev/guide/features.html" target="_blank" rel="noopener">Vite</a>. I can't
    take any credit for this. Also you might wanna use
    <a href="https://code.visualstudio.com/" target="_blank" rel="noopener">VSCode</a> and perhaps also
    <a href="https://github.com/johnsoncodehk/volar" target="_blank" rel="noopener">Volar</a> to even use it properly.
    I'd also propose the uses of
    <a href="https://www.cypress.io/" target="_blank" rel="noopener">Cypress</a> and
    <a href="https://on.cypress.io/component" target="_blank" rel="noopener"
      >Cypress Component Testing</a
    > if I knew it wouldn't overwhelm you too much, but I don't know that about you.

    <br />

    If you're tired of hearing me talk about it, you can read the same information verbatim over in <code>README.md</code>.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Ecosystem</template>

    I feel like you're very into libraries. I bet that when you showed up you were like "This is cool and all but I really wish I could have some libraries right now." And don't worry, I got you covered m'broski. Here are some:
    <a href="https://pinia.vuejs.org/" target="_blank" rel="noopener">Pinia</a>,
    <a href="https://router.vuejs.org/" target="_blank" rel="noopener">Vue Router</a>,
    <a href="https://test-utils.vuejs.org/" target="_blank" rel="noopener">Vue Test Utils</a>, and
    <a href="https://github.com/vuejs/devtools" target="_blank" rel="noopener">Vue Dev Tools</a>. If
    that's somehow not enough, I'll top the list off with
    <a href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener">Awesome Vue</a>
    for the rest of your needs you kinky boi.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Community</template>

    Now I'm not assuming you're a lonely person, you know that's not what I'm insinuating. At all. To any degree. Buuuuuuuuut just in case ...
    <a href="https://chat.vuejs.org" target="_blank" rel="noopener">Vue Land</a> is a good spot
    for makin some friends, much less so is
    <a href="https://stackoverflow.com/questions/tagged/vue.js" target="_blank" rel="noopener"
      >StackOverflow</a
    > but you could get a kick out of that too. Did I mention we have a
    <a href="https://news.vuejs.org" target="_blank" rel="noopener">mailing list</a>? Yes, just now, you've just heard me mention it.
    Oh and I guess if you still use X then you could pop on over to
    <a href="https://twitter.com/vuejs" target="_blank" rel="noopener">@vuejs</a>, we're barely active on there though
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Support us please for the love of God</template>

    We're an independent bunch of lads and it's because of that that we don't get PAID ENOUGH for our risky endeavors. Yes, this is a risky endeavor. Don't act like it isn't.
    Anyway, I think it'd be in your best interest to
    <a href="https://vuejs.org/sponsor/" target="_blank" rel="noopener">be a frickin sponsor for our thing</a>. It'd help us keep this thing sustainable - and if there's anything we love most, it's sustaining things.
  </WelcomeItem>
</template>
