<template>
 <PageLayout type="three-columns">
  <template #header>
   <ShareHeaderDocs />
  </template>
  <template #start>
   <ViewState
    v-slot="navigation"
    src="route://meta"
    path="navigation"
   >
    
   </ViewState>
  </template>
  <template #end>
   <Toc
    selector="#content"
    display="none lg-block print-none"
    color="teal-700"
   >
    <Localization>
     <template #en>
      On this page
     </template>
     <template #ja>
      項目
     </template>
    </Localization>
   </Toc>
  </template>
  <template #default>
   <b-div
    id="content"
   >
    <slot />
   </b-div>
  </template>
  <template #footer>
   <ShareFooter />
  </template>
 </PageLayout>
</template>

