<template>
   <HeroRow text-alignment="center">
       <b-h level="2">
           The Future of Drones
       </b-h>
       <b-p text-color="secondary">
           私は今後さらにドローン需要が高まると思っています。
       </b-p>
   </HeroRow>
   <Row gutter="x-3" columns="1 md-2" class="justify-content-center">
       <Col class="col-md-8 mx-auto">
           <Card relative-height="100" class="un-transition-all un-ease-in-out hover:-un-translate-y-0.5"
               background-color="transparent">
               <Background img-src="/unsplash/image/480x220/drone.jpg" 
               style="height: 400px;"
               :overlay="true" overlay-color="white" overlay-alpha="0.6" :img-parallax="0.1" rounded>
                   <CardBody>
                       <CardTitle text-color="dark" headings="1">
                           About Drones
                       </CardTitle>
                       <CardText text-color="dark">
                           ドローンについてのページです。
                       </CardText>
                   </CardBody>
                   <CardFooter>
                       <CardLink stretched-link to="/introduction/drone">
                           Drone page
                           <BIcon margin="s-1" small icon="bi:chevron-right" />
                       </CardLink>
                   </CardFooter>
               </Background>
           </Card>
       </Col>
   </Row>
</template>