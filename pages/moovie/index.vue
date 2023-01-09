<template>
  <div class="container" style="background: #1e232b">
    <div style="width: 100%; height: 4rem; background: #1e232b"></div>

    <span class="red-line"></span>
    <h1>Movies</h1>

    <div class="mt-3 d-flex">
      <div
        class="card"
        style="width: 35rem; height: 30rem; background: rgba(30, 35, 42, 0)"
      >
        <ul class="list-group list-group-flush">
          <li class="list-group-item" style="background: #1e232b">
            <span style="color: #e5e5e5">Sort Result By</span>
          </li>
        </ul>
        <div class="d-flex justify-content-center align-items-center">
          <b-dropdown
            id="dropdown-1"
            text="Popularity"
            class="m-md-2"
            size="sm"
            style="width: 202px"
          >
            <b-dropdown-item>Popularity Ascending</b-dropdown-item>
            <b-dropdown-item>Popularity Descending</b-dropdown-item>
            <b-dropdown-item>Release Date Ascending</b-dropdown-item>
            <b-dropdown-item>Release Date Descending</b-dropdown-item>
            <b-dropdown-item>Rating Ascending</b-dropdown-item>
            <b-dropdown-item>Rating Decending</b-dropdown-item>
          </b-dropdown>
        </div>
        <ul class="list-group list-group-flush">
          <li class="list-group-item" style="background: #1e232b">
            <span style="color: #e5e5e5">Genres</span>
          </li>
        </ul>
        <div class="py-2">
          <div class="row">
            <div class="col-lg-12">
              <div class="mr-2">
                <div
                  class="d-flex justify-content-between align-items-center"
                  v-for="option in options"
                  :key="option.value"
                >
                  <span class="px-3 text-filter">{{ option.text }}</span>
                  <b-form-checkbox
                    class="mt-1"
                    v-model="selected"
                    :value="option.value"
                    :aria-describedby="ariaDescribedby"
                    name="flavour-3a"
                  >
                  </b-form-checkbox>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="d-flex justify-content-start flex-wrap">
        <!-- 1st line -->
        <div class="card border-0 ml-3" style="width: 210px">
          <div class="img-container">
            <img
              src="../../assets/img/img-ww84.png"
              class="image card-img-top"
              width="210px"
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
              <nuxt-link to="moovie/detail">
                <b-button class="btn-view" pill variant="danger" size="sm">
                  View
                </b-button>
              </nuxt-link>
            </div>
          </div>

          <div class="px-1" style="background: #1e232b">
            <h6>Wonder Woman 1984</h6>
            <span class="year" style="color: #929292">2020</span>
          </div>
        </div>
        <div class="card border-0 ml-3" style="width: 210px">
          <div class="img-container">
            <img
              src="../../assets/img/img-belowzero.png"
              class="image card-img-top"
              width="210px"
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
        <div class="card border-0 ml-3" style="width: 210px">
          <div class="img-container">
            <img
              src="../../assets/img/img-thelittlethings.png"
              class="image card-img-top"
              width="210px"
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
        <div class="card border-0 ml-3" style="width: 210px">
          <div class="img-container">
            <img
              src="../../assets/img/img-outsidewar.png"
              class="image card-img-top"
              width="210px"
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
        <!-- 2nd line -->
        <div class="card border-0 mt-3 ml-3" style="width: 210px">
          <div class="img-container">
            <img
              src="../../assets/img/img-blackwater.png"
              class="image card-img-top"
              width="210px"
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
        <div class="card border-0 mt-3 ml-3" style="width: 210px">
          <div class="img-container">
            <img
              src="../../assets/img/img-breach.png"
              class="image card-img-top"
              width="210px"
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
        <div class="card border-0 mt-3 ml-3" style="width: 210px">
          <div class="img-container">
            <img
              src="../../assets/img/img-soul.png"
              class="image card-img-top"
              width="210px"
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
        <div class="card border-0 mt-3 ml-3" style="width: 210px">
          <div class="img-container">
            <img
              src="../../assets/img/img-hoobsshaw.png"
              class="image card-img-top"
              width="210px"
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

        <!-- 3rd line -->
        <div class="card border-0 mt-3 ml-3" style="width: 210px">
          <div class="img-container">
            <img
              src="../../assets/img/img-thecroods.png"
              class="image card-img-top"
              width="210px"
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
        <div class="card border-0 mt-3 ml-3" style="width: 210px">
          <div class="img-container">
            <img
              src="../../assets/img/img-vanguard.png"
              class="image card-img-top"
              width="210px"
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
        <div class="card border-0 mt-3 ml-3" style="width: 210px">
          <div class="img-container">
            <img
              src="../../assets/img/img-tenet.png"
              class="image card-img-top"
              width="210px"
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
                <span class="text-rating ml-3">7.3</span>
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
        <div class="card border-0 mt-3 ml-3" style="width: 210px">
          <div class="img-container">
            <img
              src="../../assets/img/img-wolf.png"
              class="image card-img-top"
              width="210px"
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
                <span class="text-rating ml-3">5.9</span>
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
            <h6>100% Wolf</h6>
            <span class="year" style="color: #929292">2020</span>
          </div>
        </div>
      </div>
    </div>

    <div class="mt-4 d-flex justify-content-center align-items-center">
      <b-button class="red-button" pill size="sm">
        <label class="text-button">Load More </label>
      </b-button>
    </div>

    <div style="width: 100%; height: 4rem; background: #1e232b"></div>
  </div>
</template>

<script>
export default {
  name: "MovieList",
  data() {
    return {
      selected: [],
      options: [
        { text: "Action", value: "action", checked: true },
        { text: "Adventure", value: "adventure" },
        { text: "Animation", value: "animation" },
        { text: "Comedy", value: "comedy" },
        { text: "Crime", value: "crime" },
        { text: "Documentary", value: "documentary" },
        { text: "Drama", value: "drama" },
        { text: "Family", value: "family" },
        { text: "Fantasy", value: "fantasy" },
        { text: "History", value: "history" },
        { text: "Horror", value: "horror" },
      ],
      images: [
        {
          img: "../../assets/img/img-ww84.png",
          title: "Wonder Woman 1984",
          year: "2020",
        },
      ],
    };
  },
};
</script>

<style lang="css">
.red-line {
  display: flex;
  justify-content: start;
  align-items: flex-start;
  background: #e74c3c;
  width: 112px;
  height: 6px;
}

.text-filter {
  font-size: 14px;
  font-weight: 400;
  line-height: 17.07px;
  color: #ffffff;
}

h1 {
  font-size: 36px;
  font-weight: 600;
  line-height: 43.88px;
  color: #e5e5e5;
}

h6 {
  margin-top: 5px;
  margin-bottom: 0;
  font-size: 16px;
  font-weight: 600;
  line-height: 19.5px;
  color: #e5e5e5;
}

.year {
  font-size: 14px;
  font-weight: 400;
  line-height: 17.07px;
}

.red-button {
  background: #ff0000;
  width: 151px;
}

.text-button {
  font-size: 14px;
  font-weight: 600;
  line-height: 5px;
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
