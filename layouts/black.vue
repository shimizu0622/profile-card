<template>
  <PageLayout
   type="one-columns"
   theme="dark"
   class="bg-dark text-white"
  >
   <template #header>
    <ShareHeaderLanding class="bg-dark text-white" />
   </template>
   <template #default>
    <div class="bg-dark text-white">
      <slot />
    </div>
   </template>
   <template #footer>
    <b-footer
     background-color="dark"
     display="print-none"
     class="bg-dark text-white border-top border-secondary"
    >
     <Container
      padding="x-sgs"
      text-alignment="center sm-start"
      text-color="white"
      class="bg-dark"
     >
      <ShareFooter class="bg-dark text-white" />
     </Container>
    </b-footer>
   </template>
  </PageLayout>
</template>