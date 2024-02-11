<template>
    <div>
        <Header />
        <div>Signed in:</div>
        <div>Email: {{ auth.user.email }}</div>
        <div>Uid: {{ auth.user.uid }}</div>
    </div>
</template>

<script setup>
definePageMeta({
  middleware: ['auth'],
})

import { useAuthStore } from '~/store/useAuth';

  const auth = useAuthStore()
</script>