<template>
  <div>
    <b-jumbotron
      container-fluid
      style="border-radius: 0px; background: #ffffff"
    >
      <div class="container">
        <div class="row">
          <div class="card-body">
            <h3 class="text-jumbo">Reviews</h3>

            <div class="row">
              <div class="col-lg-6">
                <div
                  class="card"
                  style="border-radius: 14px; background: #f9f9f9"
                >
                  <div class="card-body">
                    <div
                      class="d-flex justify-content-between align-items-center"
                    >
                      <div class="d-flex align-items-center">
                        <b-img
                          class="align-baseline"
                          v-bind="mainProps"
                          rounded="circle"
                          alt="Circle image"
                        ></b-img>
                        <div style="padding: 0 10px">
                          <div>
                            <span class="text-review-md">Switch.</span>
                          </div>
                          <div>
                            <span class="text-review-sm mb-2"
                              >December 18, 2020</span
                            >
                          </div>
                        </div>
                      </div>
                      <div class="box-rating">
                        <div
                          class="d-flex justify-content-center align-items-center"
                        >
                          <span class="text-rating-lg">
                            <b-icon
                              icon="star-fill"
                              font-scale="0.3"
                              style="color: #ffb802; margin-bottom: 18px"
                            ></b-icon>
                            7.0
                          </span>
                        </div>
                      </div>
                    </div>

                    <div class="mt-3">
                      <p class="text-comment">
                        It isn't as easy as saying 'Wonder Woman 1984' is a good
                        or bad movie. The pieces are there, and there are
                        moments I adore, but it does come across as a bit of a
                        mess, even though the action sequences are breathtaking.
                        If you're a fan of the original film, you'll be more
                        willing to take the ride, but for those more
                        indifferent, it may be a bit of a blander sit. If you
                        can and are planning to watch it, the theatrical
                        experience is the way to go - there is nothing like
                        seeing these stunning sets, fun action scenes and
                        hearing Zimmer's jaw-dropping score like on the big
                        screen. - Chris dos Santos...
                        <a href="" style="color: #e74c3c">read the rest.</a>
                      </p>
                    </div>
                  </div>
                </div>
              </div>
              <div class="col-lg-6">
                <div
                  class="card"
                  style="border-radius: 14px; background: #f9f9f9"
                >
                  <div class="card-body">
                    <div
                      class="d-flex justify-content-between align-items-center"
                    >
                      <div class="d-flex align-items-center">
                        <b-img
                          class="align-baseline"
                          v-bind="mainProps"
                          rounded="circle"
                          alt="Circle image"
                        ></b-img>
                        <div style="padding: 0 10px">
                          <div>
                            <span class="text-review-md">Switch.</span>
                          </div>
                          <div>
                            <span class="text-review-sm mb-2"
                              >December 18, 2020</span
                            >
                          </div>
                        </div>
                      </div>
                      <div class="box-rating">
                        <div
                          class="d-flex justify-content-center align-items-center"
                        >
                          <span class="text-rating-lg">
                            <b-icon
                              icon="star-fill"
                              font-scale="0.3"
                              style="color: #ffb802; margin-bottom: 18px"
                            ></b-icon>
                            7.0
                          </span>
                        </div>
                      </div>
                    </div>

                    <div class="mt-3">
                      <p class="text-comment">
                        It isn't as easy as saying 'Wonder Woman 1984' is a good
                        or bad movie. The pieces are there, and there are
                        moments I adore, but it does come across as a bit of a
                        mess, even though the action sequences are breathtaking.
                        If you're a fan of the original film, you'll be more
                        willing to take the ride, but for those more
                        indifferent, it may be a bit of a blander sit. If you
                        can and are planning to watch it, the theatrical
                        experience is the way to go - there is nothing like
                        seeing these stunning sets, fun action scenes and
                        hearing Zimmer's jaw-dropping score like on the big
                        screen. - Chris dos Santos...
                        <a href="" style="color: #e74c3c">read the rest.</a>
                      </p>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </b-jumbotron>

    <div class="container">
      <div class="row">
        <div class="card-body">
          <h2 class="text-recommendation">Recommendation Movies</h2>

          <div class="mt-4 d-flex">
            <div class="d-flex justify-content-start flex-wrap">
              <div class="card border-0" style="width: 200px">
                <div class="img-container">
                  <img
                    src="../../assets/img/img-new-mutant.png"
                    class="image card-img-top"
                    width="200px"
                    height="330px"
                    alt="new-mutant"
                  />
                  <div class="overlay">
                    <div
                      class="d-flex justify-content-center align-items-center mb-5"
                    >
                      <b-icon
                        icon="star-fill"
                        font-scale="2"
                        style="color: #ffb802"
                      ></b-icon>
                      <span class="text-rating ml-3">7.0</span>
                    </div>
                    <label
                      class="text-content d-flex justify-content-center align-items-center mb-5"
                      >Action</label
                    >
                    <b-button class="btn-view" pill variant="danger" size="sm">
                      View
                    </b-button>
                  </div>
                </div>

                <div class="px-1" style="background: #1e232b">
                  <h6>The New Mutant</h6>
                  <span class="year" style="color: #929292">2020</span>
                </div>
              </div>
              <div class="card border-0 ml-3" style="width: 200px">
                <div class="img-container">
                  <img
                    src="../../assets/img/img-soul.png"
                    class="image card-img-top"
                    width="200px"
                    height="330px"
                    alt="soul"
                  />
                  <div class="overlay">
                    <div
                      class="d-flex justify-content-center align-items-center mb-5"
                    >
                      <b-icon
                        icon="star-fill"
                        font-scale="2"
                        style="color: #ffb802"
                      ></b-icon>
                      <span class="text-rating ml-3">7.0</span>
                    </div>
                    <label
                      class="text-content d-flex justify-content-center align-items-center mb-5"
                      >Action</label
                    >
                    <b-button class="btn-view" pill variant="danger" size="sm">
                      View
                    </b-button>
                  </div>
                </div>

                <div class="px-1" style="background: #1e232b">
                  <h6>Soul</h6>
                  <span class="year" style="color: #929292">2020</span>
                </div>
              </div>
              <div class="card border-0 ml-3" style="width: 200px">
                <div class="img-container">
                  <img
                    src="../../assets/img/img-tenet.png"
                    class="image card-img-top"
                    width="200px"
                    height="330px"
                    alt="tenet"
                  />
                  <div class="overlay">
                    <div
                      class="d-flex justify-content-center align-items-center mb-5"
                    >
                      <b-icon
                        icon="star-fill"
                        font-scale="2"
                        style="color: #ffb802"
                      ></b-icon>
                      <span class="text-rating ml-3">7.0</span>
                    </div>
                    <label
                      class="text-content d-flex justify-content-center align-items-center mb-5"
                      >Action</label
                    >
                    <b-button class="btn-view" pill variant="danger" size="sm">
                      View
                    </b-button>
                  </div>
                </div>

                <div class="px-1" style="background: #1e232b">
                  <h6>Tenet</h6>
                  <span class="year" style="color: #929292">2020</span>
                </div>
              </div>
              <div class="card border-0 ml-3" style="width: 200px">
                <div class="img-container">
                  <img
                    src="../../assets/img/img-old-guard.png"
                    class="image card-img-top"
                    width="200px"
                    height="330px"
                    alt="old-guard"
                  />
                  <div class="overlay">
                    <div
                      class="d-flex justify-content-center align-items-center mb-5"
                    >
                      <b-icon
                        icon="star-fill"
                        font-scale="2"
                        style="color: #ffb802"
                      ></b-icon>
                      <span class="text-rating ml-3">7.0</span>
                    </div>
                    <label
                      class="text-content d-flex justify-content-center align-items-center mb-5"
                      >Action</label
                    >
                    <b-button class="btn-view" pill variant="danger" size="sm">
                      View
                    </b-button>
                  </div>
                </div>

                <div class="px-1" style="background: #1e232b">
                  <h6>Old Guard</h6>
                  <span class="year" style="color: #929292">2020</span>
                </div>
              </div>
              <div class="card border-0 ml-3" style="width: 200px">
                <div class="img-container">
                  <img
                    src="../../assets/img/img-project-power.png"
                    class="image card-img-top"
                    width="200px"
                    height="330px"
                    alt="project-power"
                  />
                  <div class="overlay">
                    <div
                      class="d-flex justify-content-center align-items-center mb-5"
                    >
                      <b-icon
                        icon="star-fill"
                        font-scale="2"
                        style="color: #ffb802"
                      ></b-icon>
                      <span class="text-rating ml-3">7.0</span>
                    </div>
                    <label
                      class="text-content d-flex justify-content-center align-items-center mb-5"
                      >Action</label
                    >
                    <b-button class="btn-view" pill variant="danger" size="sm">
                      View
                    </b-button>
                  </div>
                </div>

                <div class="px-1" style="background: #1e232b">
                  <h6>Project Power</h6>
                  <span class="year" style="color: #929292">2020</span>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      mainProps: {
        blank: true,
        blankColor: "rgba(30, 35, 43, 0.21)",
        width: 48,
        height: 48,
        class: "m1",
      },
    };
  },
};
</script>

<style>
.text-recommendation {
  font-size: 14px;
  font-weight: 600;
  line-height: 17.07px;
  color: #ffffff;
  text-transform: uppercase;
}

.text-jumbo {
  font-size: 14px;
  font-weight: 600;
  line-height: 17.07px;
  color: #ff0000;
  text-transform: uppercase;
}

.text-review-md {
  font-size: 14px;
  font-weight: 700;
  line-height: 17.07px;
  color: #1e232a;
  text-transform: uppercase;
}

.text-review-sm {
  font-size: 12px;
  font-weight: 400;
  line-height: 14.63px;
  color: #666666;
}

.box-rating {
  width: 97px;
  height: 52px;
  border-radius: 7px;
  background: rgba(196, 196, 196, 0.28);
}

.text-rating-lg {
  font-size: 36px;
  font-weight: 600;
  line-height: 43.88px;
  color: #000000;
}

.text-comment {
  font-size: 13px;
  font-weight: 400;
  line-height: 19.5px;
  color: #000000;
  text-align: justify;
}
</style>
