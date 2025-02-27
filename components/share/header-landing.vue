<template>
    <Navbar expand="lg" background-color="white">
        <Container>
            
            <NavbarToggler />
            <NavbarCollapse>
                <NavbarNavList margin="e-auto">
                    
                    <NavItemDropdown>
                       
                        <DropdownMenu mega relative-width="100" background-color="transparent" border-subtractive
                            class="animated animated-fade-in">
                            <Container>
                                
                            </Container>
                        </DropdownMenu>
                    </NavItemDropdown>
                </NavbarNavList>
                <NavbarNavList flex-direction="row" flex-wrap="wrap" margin="s-md-auto">
                    <NavItem padding="y-2" col="12 lg-auto">
                        <Vr display="none lg-flex" relative-height="100" margin="x-lg-2" text-color="black-50" />
                        <hr class="d-lg-none my-2 text-black-50" />
                    </NavItem>
                    <NavItem col="6 lg-auto">
                        <NavLink pdding="y-2 x-0 x-lg-2" to="https://github.com/simplise/use-bootstrap" target="_blank"
                            rel="noopener">
                            <Icon name="bi:github" class="navbar-nav-svg" />
                        </NavLink>
                    </NavItem>
                </NavbarNavList>
            </NavbarCollapse>
        </Container>
    </Navbar>
</template>
