<template>
    <footer class="mt-5">
        <div class="container pt-5 pb-4">
            <div class="row align-items-center px-4 gx-lg-4 g-md-5 gy-5">
                <div class="col-lg-4 col-md-6 order-lg-0 order-1">
                    <div class="hstack align-items-center flex-wrap gap-3 pe-5">
                        <router-link to="/" class="font-weight-700 font-size-16 text-decoration-none text-dark">
                            Home
                        </router-link>
                        <router-link to="/" class="font-weight-700 font-size-16 text-decoration-none text-dark">
                            About Us
                        </router-link>
                        <router-link to="/" class="font-weight-700 font-size-16 text-decoration-none text-dark">
                            Product & Service
                        </router-link>
                        <router-link to="/" class="font-weight-700 font-size-16 text-decoration-none text-dark">
                            News
                        </router-link>
                        <router-link to="/" class="font-weight-700 font-size-16 text-decoration-none text-dark">
                            Career
                        </router-link>
                        <router-link to="/" class="font-weight-700 font-size-16 text-decoration-none text-dark">
                            Contact Us
                        </router-link>
                    </div>
                </div>
                <div class="col-lg-4 col-md-6 order-0 orderlg-1">
                    <div class="text-center">
                        <div>
                            <img style="height: 55px;" src="/assets/images/logo-espn.png" />
                        </div>
                        <div class="">
                            <img style="height: 45px;" src="/assets/images/logo-elevenia-1.png" />
                            <img class="pt-3" style="height: 38px;" src="/assets/images/nustantrara-black.png" />
                        </div>
                    </div>
                </div>
                <div class="col-lg-3 col-md-6 ms-lg-auto order-2 orderlg-2">
                    <table class="navbar-contact font-weight-400 font-size-12">
                        <tr>
                            <td>
                                <img src="/assets/images/icons/location.svg" />
                            </td>
                            <td>
                                Wisma 46-Kota BNI, Lantai 39, Jl. Jendral Sudirman Kav. 1
                            </td>
                        </tr>
                        <tr>
                            <td>
                                <img class="me-2" src="/assets/images/icons/call.svg" />
                            </td>
                            <td>
                                02139371122
                            </td>
                        </tr>
                        <tr>
                            <td>
                                <img class="me-2" src="/assets/images/icons/mail.svg" />
                            </td>
                            <td>
                                enusantara@elevenia.co.id
                            </td>
                        </tr>
                    </table>
                </div>
                <!-- <div class="col-12">
                    <div class="text-center mt-3 font-weight-400 font-size-12">
                        © 2022 espn all rights reserved
                    </div>
                </div> -->
            </div>
        </div>
        <div class="text-center my-2 font-weight-400 font-size-12">
            © 2022 espn all rights reserved
        </div>
    </footer>
</template>

<script>
export default {
    name: 'Footer'
}
</script>
