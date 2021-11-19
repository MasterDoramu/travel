<template>
  <div class="home">
    <Ticket/>
  </div>
</template>

<script>
// @ is an alias to /src
import Ticket from '@/components/ticket/Ticket.vue'

export default {
  name: 'First',
  components: {
    Ticket
  }
}
</script>
