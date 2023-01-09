<template>
  <div class="container" style="background: #1e232b">
    <div style="width: 100%; height: 4rem; background: #1e232b"></div>

    <Slider></Slider>

    <div style="width: 100%; height: 4rem; background: #1e232b"></div>

    <span class="red-line"></span>
    <div class="d-flex justify-content-between align-items-center">
      <div>
        <h1>Discover Movies</h1>
      </div>
      <div>
        <b-button pill size="sm" style="background: #ff0000"
          >Popularity</b-button
        >
        <b-button pill size="sm" style="background: rgba(0, 0, 0, 0.2)"
          >Release Date</b-button
        >
      </div>
    </div>

    <div class="mt-3 d-flex">
      <div class="d-flex justify-content-start flex-wrap">
        <div class="card border-0" style="width: 200px">
          <div class="img-container">
            <img
              src="../assets/img/img-ww84.png"
              class="image card-img-top"
              width="200px"
              height="330px"
              alt="ww84"
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
            <h6>Wonder Woman 1984</h6>
            <span class="year" style="color: #929292">2020</span>
          </div>
        </div>
        <div class="card border-0 ml-3" style="width: 200px">
          <div class="img-container">
            <img
              src="../assets/img/img-belowzero.png"
              class="image card-img-top"
              width="200px"
              height="330px"
              alt="below-zero"
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
                <span class="text-rating ml-3">6.4</span>
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
            <h6>Below Zero</h6>
            <span class="year" style="color: #929292">2021</span>
          </div>
        </div>
        <div class="card border-0 ml-3" style="width: 200px">
          <div class="img-container">
            <img
              src="../assets/img/img-thelittlethings.png"
              class="image card-img-top"
              width="200px"
              height="330px"
              alt="little-things"
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
                <span class="text-rating ml-3">6.3</span>
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
            <h6>The Little Things</h6>
            <span class="year" style="color: #929292">2021</span>
          </div>
        </div>
        <div class="card border-0 ml-3" style="width: 200px">
          <div class="img-container">
            <img
              src="../assets/img/img-outsidewar.png"
              class="image card-img-top"
              width="200px"
              height="330px"
              alt="outside-wire"
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
                <span class="text-rating ml-3">6.5</span>
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
            <h6>Outside The Wire</h6>
            <span class="year" style="color: #929292">2021</span>
          </div>
        </div>
        <div class="card border-0 ml-3" style="width: 200px">
          <div class="img-container">
            <img
              src="../assets/img/img-blackwater.png"
              class="image card-img-top"
              width="200px"
              height="330px"
              alt="abyss"
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
                <span class="text-rating ml-3">5.1</span>
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
            <h6>Black Water: Abyss</h6>
            <span class="year" style="color: #929292">2020</span>
          </div>
        </div>
        <!-- 2nd line -->
        <div class="card border-0 mt-3" style="width: 200px">
          <div class="img-container">
            <img
              src="../assets/img/img-breach.png"
              class="image card-img-top"
              width="200px"
              height="330px"
              alt="breach"
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
                <span class="text-rating ml-3">4.6</span>
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
            <h6>Breach</h6>
            <span class="year" style="color: #929292">2021</span>
          </div>
        </div>
        <div class="card border-0 mt-3 ml-3" style="width: 200px">
          <div class="img-container">
            <img
              src="../assets/img/img-soul.png"
              class="image card-img-top"
              width="200px"
              height="330px"
              alt="breach"
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
                <span class="text-rating ml-3">8.3</span>
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
        <div class="card border-0 mt-3 ml-3" style="width: 200px">
          <div class="img-container">
            <img
              src="../assets/img/img-hoobsshaw.png"
              class="image card-img-top"
              width="200px"
              height="330px"
              alt="hoobs"
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
                <span class="text-rating ml-3">6.9</span>
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
            <h6>Fast & Furious Present</h6>
            <span class="year" style="color: #929292">2019</span>
          </div>
        </div>
        <div class="card border-0 mt-3 ml-3" style="width: 200px">
          <div class="img-container">
            <img
              src="../assets/img/img-thecroods.png"
              class="image card-img-top"
              width="200px"
              height="330px"
              alt="the-croods"
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
                <span class="text-rating ml-3">7.6</span>
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
            <h6>The Croods: A New Age</h6>
            <span class="year" style="color: #929292">2020</span>
          </div>
        </div>
        <div class="card border-0 mt-3 ml-3" style="width: 200px">
          <div class="img-container">
            <img
              src="../assets/img/img-vanguard.png"
              class="image card-img-top"
              width="200px"
              height="330px"
              alt="vanguard"
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
                <span class="text-rating ml-3">6.3</span>
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
            <h6>Vanguard</h6>
            <span class="year" style="color: #929292">2020</span>
          </div>
        </div>
      </div>
    </div>

    <div style="width: 100%; height: 4rem; background: #1e232b"></div>
  </div>
</template>

<script>
export default {
  name: "Home",
};
</script>

<style>
.red-line {
  display: flex;
  justify-content: start;
  align-items: flex-start;
  background: #e74c3c;
  width: 112px;
  height: 6px;
}

h1 {
  font-size: 24px;
  font-weight: 600;
  line-height: 29.26px;
  color: #e5e5e5;
}

.btn-view {
  width: 107px;
  height: 32px;
}

.text-rating {
  font-size: 24px;
  font-weight: 600;
  line-height: 29.26px;
  color: #ffffff;
}

.text-content {
  font-size: 18px;
  font-weight: 600;
  line-height: 21.94px;
  color: #ffffff;
}
</style>
