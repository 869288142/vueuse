<script setup lang="ts">
import { contributors, coreTeamMembers } from '../../../contributors'
</script>
<template>
  <h2 op50 font-normal pt-5 pb-2>
    Meet The Team
  </h2>
  <div grid="~ sm:cols-2 md:cols-3 lg:cols-4 gap-x-3 gap-y-20 items-center" p-10>
    <TeamMember
      v-for="c of coreTeamMembers"
      :key="c.github"
      :data="c"
    />
  </div>
</template>

<script setup lang="ts">

</script>
