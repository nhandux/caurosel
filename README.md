 $('#cus_services12').owlCarousel({
                          loop: true,
                          margin: 10,
                          responsiveClass: true,
                          autoplay: true,
                          autoplayTimeout: 3000,
                          smartSpeed: 1200,
                          responsive: {
                            0: {
                              items: 1,
                               autoplayTimeout: 200000,
                              nav: true
                            },
                            550: {
                               items: 2,
                                nav: true
                            },
                              600: {
                              items: 3,
                              autoplayTimeout: false,
                              nav: false
                            },
                            800: {
                              items: 3,
                              autoplayTimeout: false,
                              nav: false
                            },
                            1000: {
                              items: 3,
                              nav: true,
                              loop: true,
                              autoplayTimeout: 20000,
                              margin: 20
                            }
                          }
                        })
