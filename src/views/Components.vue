[<template>
  <div class="components">
    This is an components page
    <div>
      <Button text="button test" size="small" loading disabled/>
    </div>
    <div>
      <Input value="test input"/>
    </div>
  </div>
</template>

<script>
import Button from '@/components/Button/'
import Input from '@/components/Input/'

export default {
  name: 'Components',
  components: { Button, Input }
}
</script>
]
