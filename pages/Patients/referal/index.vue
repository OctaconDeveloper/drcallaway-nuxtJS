<template>
  <div>
    <body
      class="vertical-layout vertical-menu-modern 2-columns  navbar-floating footer-static  "
      data-open="click"
      data-menu="vertical-menu-modern"
      data-col="2-columns"
    >
      <header></header>
      <sidebar></sidebar>

      <div class="app-content content">
        <div class="content-overlay"></div>
        <div class="header-navbar-shadow"></div>
        <div class="content-wrapper">
          <div class="content-header row justify-content-center">
            <div class="content-header-left col-md-5 col-12 mb-2">
              <div class="row breadcrumbs-top">
                <div class="col-12">
                  <h4 class="content-header-title float-left mb-0">Referal</h4>
                </div>
              </div>
            </div>
          </div>
          <div class="content-body">
            <section class="page-users-view">
              <div class="row justify-content-center">
                <!-- account start -->
                <div class="col-12 col-md-5 col-lg-5">
                  <div class="card justify-content-center">
                    <div class="card-header">
                      <!-- <div class="card-title">Help</div> -->
                    </div>
                    <div class="card-body">
                      <div class="row">
                        <div class="col-12">
                          <p>
                            Refer your family and freinds and enjoy Drcallaway
                            incentives.
                          </p>
                        </div>
                        <div class="col-12 col-sm-12 col-md-12 col-lg-12">
                          <fieldset>
                            <div class="row">
                              <div class="col-12">
                                <div class="form-group">
                                  <label for="accountTextarea"
                                    >Subscriber Id:</label
                                  >
                                  <input
                                    id="basicInput"
                                    type="text"
                                    class="form-control"
                                    placeholder=""
                                  />
                                </div>
                              </div>
                              <div class="col-12">
                                <div class="form-group">
                                  <label for="accountTextarea"
                                    >Family/Freind's Email:</label
                                  >
                                  <input
                                    id="basicInput"
                                    type="text"
                                    class="form-control"
                                    placeholder=""
                                  />
                                </div>
                              </div>
                              <div class="col-12">
                                <div class="form-group">
                                  <label for="accountTextarea">Message:</label>
                                  <textarea
                                    id="accountTextarea"
                                    class="form-control"
                                    rows="3"
                                  ></textarea>
                                </div>
                              </div>
                            </div>
                          </fieldset>
                        </div>

                        <div class="col-12 d-flex justify-content-start">
                          <nuxt-link
                            to="referralmessage"
                            class="btn btn-primary"
                            ><i class="feather"></i> Send Invite</nuxt-link
                          >
                          <!--  <button class="btn btn-outline-danger"><i class="feather icon-"></i> Cancel</button> -->
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </section>
          </div>
        </div>
      </div>
      <!-- END: Content-->

      <div class="sidenav-overlay"></div>
      <div class="drag-target"></div>

      <footer></footer>
    </body>
  </div>
</template>
<script>
import Header from '~/components/customer/header'
import Footer from '~/components/customer/footer'
import SideBar from '~/components/customer/sidebar'

export default {
  name: 'Dashboard',
  components: {
    Header,
    Footer,
    SideBar
  }
}
</script>
<style scoped>
.other-link {
  position: fixed;
  bottom: 0;
  left: 0;
}
</style>
