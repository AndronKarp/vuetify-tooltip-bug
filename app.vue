<template>
  <VApp>
    <VTooltip v-for="n in 3" :key="n">
      <template #activator="{ props }">
        <VIcon v-bind="props" icon="mdi-information" />
      </template>

      Tooltip content
    </VTooltip>
  </VApp>
</template>
