<template>
  <b-footer
    padding="y-4 y-md-5"
    margin="t-5"
    background-color="body-tertiary"
    class="bd-footer"
  >
    <Container
      type="xl"
      padding="y-4 y-md-5 x-4 x-md-3"
      text-color="body-secondary"
    >
      <Row>
        <Col
          col="12 lg-4"
          offset="lg-1"
          margin="b-3"
        >
          <b-h level="5">Links</b-h>
          <Row>
            <!-- First Column -->
            <Col col="6">
              <b-ul unstyled>
                <b-li margin="b-2">
                  <Anchor text-color="body-secondary" link-underline="0 100-hover dark" href="/introduction/self">Profile</Anchor>
                </b-li>
                <b-li margin="b-2">
                  <Anchor text-color="body-secondary" link-underline="0 100-hover dark" href="/introduction/hobby">Hobby</Anchor>
                </b-li>
                <b-li margin="b-2">
                  <Anchor text-color="body-secondary" link-underline="0 100-hover dark" href="/introduction/past">Past</Anchor>
                </b-li>
              </b-ul>
            </Col>
            <!-- Second Column -->
            <Col col="6">
              <b-ul unstyled>
                <b-li margin="b-2">
                  <Anchor text-color="body-secondary" link-underline="0 100-hover dark" href="/introduction/future">Future</Anchor>
                </b-li>
                <b-li margin="b-2">
                  <Anchor text-color="body-secondary" link-underline="0 100-hover dark" href="/introduction/drone">Drone</Anchor>
                </b-li>
                <b-li margin="b-2">
                  <Anchor text-color="body-secondary" link-underline="0 100-hover dark" href="/introduction/next">Next</Anchor>
                </b-li>
              </b-ul>
            </Col>
          </Row>
        </Col>           
      </Row>
    </Container>
  </b-footer>
</template>