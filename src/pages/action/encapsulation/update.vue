<template>
  <div>
    <save-action :is-add="false" :is-test-case="false" />
  </div>
</template>

<script>
import SaveAction from '../components/SaveAction'

export default {
  name: 'EncapsulationActionUpdate',
  components: {
    SaveAction
  }
}
</script>
