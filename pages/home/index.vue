<template>
    <section class="p-4">
        <p class="">Hello</p>
        <div class="flex gap-4">
          <BaseInput/>
          <DateInput />
          <FileInput />
        </div>
    </section>
</template>

<script>
import BaseInput from '~/components/Form/baseInput'
import DateInput from '~/components/Form/DateInput'
import FileInput from '~/components/Form/FileInput'

export default {
  name: 'HomeIndex',

  components: { BaseInput, DateInput, FileInput },

  data () {
    return {
        text: 'text',
        name: 'Name'
    }
  }
}
</script>