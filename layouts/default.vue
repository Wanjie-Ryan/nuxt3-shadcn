<template>
  <div class="flex items-start">
    <!-- <p>Default Layout Shared across all Page</p> -->

    <div>
      <Sidebar />
    </div>
    <div>
      <slot />
    </div>
    <!-- the slot is used as a placeholder for content that will be injected from the component or page that uses this layout slot allows you to create reusable layout-->
  </div>
</template>
