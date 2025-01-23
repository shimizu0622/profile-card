<template>
    <HeroRow>
     <b-h
      level="1"
      display-headings="3"
      margin="b-5"
     >
      portforio site
      <Typed
       class="text-primary fw-semibold"
       :strings="['innovation.', 'excellence.', 'success.']"
       :type-speed="60"
       :loop="true"
       :back-speed="25"
       :back-delay="1500"
      />
      <br />
      Introducing myself and my future goals
     </b-h>
    </HeroRow>
    <HeroRow
     size="md-10"
     justify-content="start"
    >
     <p class="lead">
      私のポートフォリオサイトにお越しいただき、ありがとうございます。 このサイトでは、私自身についてと将来の目標について紹介しています。
     </p>
    </HeroRow>
   </template>
   