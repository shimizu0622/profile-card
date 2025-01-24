<template>
   <HeroRow text-alignment="center" margin="y-3">
       <b-p><b>Addendum</b></b-p>
       <b-div headings="2">
           自己紹介の追記です
       </b-div>
   </HeroRow>

   <Row class="justify-content-center">
       <Col class="col-md-5 mx-2">
           <Card relative-height="100">
               <CardImgTop
                   src="/unsplash/image/480x220/kako.jpg"
                   alt="Image Description"
               />
               <CardBody>
                   <CardText>過去について</CardText>
               </CardBody>
               <CardFooter>
                   <CardLink
                       icon="bi:chevron-right"
                       icon-end
                       to="/introduction/past"
                       stretched-link
                   >
                       Read story
                   </CardLink>
               </CardFooter>
           </Card>
       </Col>

       <Col class="col-md-5 mx-2">
           <Card relative-height="100">
               <CardImgTop
                   src="/unsplash/image/480x220/charange.jpg"
                   alt="Image Description"
               />
               <CardBody>
                   
                   <CardText>今後について</CardText>
               </CardBody>
               <CardFooter>
                   <CardLink
                       icon="bi:chevron-right"
                       icon-end
                       to="/introduction/next"
                       stretched-link
                   >
                       Read story
                   </CardLink>
               </CardFooter>
           </Card>
       </Col>
   </Row>
</template>