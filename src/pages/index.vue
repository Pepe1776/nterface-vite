<script setup lang="ts">
import { useUserStore } from '~/stores/user'

const user = useUserStore()
const name = ref(user.savedName)

const router = useRouter()
const go = () => {
  if (name.value)
    router.push(`/hi/${encodeURIComponent(name.value)}`)
}

const { t } = useI18n()
</script>

<template>
  <div>
    <Navbar />
    <Main />
    <Features />
    <Hero />
    <Form />
    <Footerb />
  </div>
</template>

<route lang="yaml">
meta:
  layout: home
</route>
