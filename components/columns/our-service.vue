<template>
    <HeroRow
     margin="y-3"
     size="md-8"
     justify-content="start"
    >
     <b-p text-color="body-tertiary">
      <b>Table of Contents</b>
     </b-p>
     <b-p headings="3">
      Elevate your services with our comprehensive solutions.
     </b-p>
    </HeroRow>
    <Row>
     <Col col="md-5">
      <Card
       relative-height="100"
       class="hover:-un-translate-y-0.5"
      >
       <CardImgTop
        src="/unsplash/image/500x280/profile.jpg"
        alt="Image Description"
        style="height: 280px; object-fit: cover;"
       />
   
       <CardBody>
        <CardTitle>
         Introduction of oneself
        </CardTitle>
        <CardText text-color="secondary">
         自己紹介についてのページです。
        </CardText>
       </CardBody>
   
       <CardFooter>
        <CardLink
         icon="bi:chevron-right"
         icon-end
         to="/introduction/self"
         stretched-link
        >
         Profile
        </CardLink>
       </CardFooter>
      </Card>
     </Col>
   
     <Col col="md">
      <Card
       relative-height="100"
       class="hover:-un-translate-y-0.5"
      >
       <CardImgTop
        src="/unsplash/image/500x280/hobby.jpg"
        alt="Image Description"
        style="height: 280px; object-fit: cover;"
       />
   
       <CardBody>
        <CardTitle>Hobby</CardTitle>
        <CardText text-color="secondary">
         趣味についてのページです。
        </CardText>
       </CardBody>
   
       <CardFooter>
        <CardLink
         icon="bi:chevron-right"
         icon-end
         to="/introduction/hobby"
         stretched-link
        >
         Hobby
        </CardLink>
       </CardFooter>
      </Card>
     </Col>
   
     <Col>
      <Card
       relative-height="100"
       class="hover:-un-translate-y-0.5"
      >
       <CardImgTop
        src="/unsplash/image/500x280/dream.jpg"
        alt="Image Description"
        style="height: 280px; object-fit: cover;"
       />
   
       <CardBody>
        <CardTitle>
         Dreams for the future
        </CardTitle>
        <CardText text-color="secondary">
         将来の夢についてのページです。
        </CardText>
       </CardBody>
   
       <CardFooter>
        <CardLink
         icon="bi:chevron-right"
         icon-end
         to="/introduction/future"
         stretched-link
        >
         Future
        </CardLink>
       </CardFooter>
      </Card>
     </Col>
    </Row>
   </template>
   