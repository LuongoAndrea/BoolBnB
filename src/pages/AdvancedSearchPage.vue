<template>
  <div class="allcont">
    <header>
      <HeaderComponent></HeaderComponent>
    </header>
    <div class="navholder">
      <div class="search">
        <div class="row">
          <div class="col">
            <div id="searchsmart"></div>
          </div>
        </div>
      </div>
      <div id="smartnavop">
        <div class="smartnav categorie">
          <ul>
            <li class="contain emerald">
              <input type="radio" name="categoria" id="open_space" checked />
              <span class="checkmark">
                <span class="checkedicon"
                  ><i class="fa-solid fa-person-shelter"></i>
                </span>
              </span>
            </li>
            <li class="contain emerald">
              <input type="radio" name="categoria" id="case_intere" />
              <span class="checkmark">
                <span class="checkedicon"
                  ><i class="fa-solid fa-house"></i>
                </span>
              </span>
            </li>
            <li class="contain emerald">
              <input type="radio" name="categoria" id="villa_campagna" />
              <span class="checkmark">
                <span class="checkedicon"
                  ><i class="fa-solid fa-tree-city"></i>
                </span>
              </span>
            </li>
            <li class="contain emerald">
              <input type="radio" name="categoria" id="villa_mare" />
              <span class="checkmark">
                <span class="checkedicon"
                  ><i class="fa-solid fa-house-flood-water"></i>
                </span>
              </span>
            </li>
            <li class="contain emerald">
              <input type="radio" name="categoria" id="industriale" />
              <span class="checkmark">
                <span class="checkedicon"
                  ><i class="fa-solid fa-warehouse"></i>
                </span>
              </span>
            </li>
            <li class="contain emerald">
              <input type="radio" name="categoria" id="contemporaneo" />
              <span class="checkmark">
                <span class="checkedicon"
                  ><i class="fa-solid fa-building"></i>
                </span>
              </span>
            </li>
            <li class="contain emerald">
              <input type="radio" name="categoria" id="romano" />
              <span class="checkmark">
                <span class="checkedicon"
                  ><i class="fa-solid fa-building-columns"></i>
                </span>
              </span>
            </li>
          </ul>
        </div>
        
        <div class="smartnav servizi">
          <ul>
            <li class="contain sangria">
              <input type="checkbox" name="wifi" id="wifi" />
              <span class="checkmark">
                <span class="checkedicon"
                  ><i class="fa-solid fa-wifi"></i>
                </span>
              </span>
            </li>
            <li class="contain sangria">
              <input type="checkbox" name="fan" id="fan" />
              <span class="checkmark">
                <span class="checkedicon"
                  ><i class="fa-solid fa-fan"></i>
                </span>
              </span>
            </li>
            <li class="contain sangria">
              <input type="checkbox" name="garage" id="garage" />
              <span class="checkmark">
                <span class="checkedicon"
                  ><i class="fa-solid fa-square-parking"></i>
                </span>
              </span>
            </li>
            <li class="contain sangria">
              <input type="checkbox" name="piscina" id="piscina" />
              <span class="checkmark">
                <span class="checkedicon"
                  ><i class="fa-solid fa-person-swimming"></i>
                </span>
              </span>
            </li>
            <li class="contain sangria">
              <input type="checkbox" name="idromassaggio" id="idromassaggio" />
              <span class="checkmark">
                <span class="checkedicon"
                  ><i class="fa-solid fa-water-ladder"></i>
                </span>
              </span>
            </li>
            <li class="contain sangria">
              <input type="checkbox" name="portineria" id="portineria" />
              <span class="checkmark">
                <span class="checkedicon"
                  ><i class="fa-solid fa-bell-concierge"></i>
                </span>
              </span>
            </li>
            <li class="contain sangria">
              <input type="checkbox" name="sauna" id="sauna" />
              <span class="checkmark">
                <span class="checkedicon"
                  ><i class="fa-solid fa-spa"></i>
                </span>
              </span>
            </li>
            <li class="contain sangria">
              <input type="checkbox" name="palestra" id="palestra" />
              <span class="checkmark">
                <span class="checkedicon"
                  ><i class="fa-solid fa-dumbbell"></i>
                </span>
              </span>
            </li>
            <li class="contain sangria">
              <input type="checkbox" name="tennis" id="tennis" />
              <span class="checkmark">
                <span class="checkedicon"
                  ><i class="fa-solid fa-table-tennis-paddle-ball"></i>
                </span>
              </span>
            </li>
            <li class="contain sangria">
              <input type="checkbox" name="golf" id="golf" />
              <span class="checkmark">
                <span class="checkedicon"
                  ><i class="fa-solid fa-golf-ball-tee"></i>
                </span>
              </span>
            </li>
            <li class="contain sangria">
              <input type="checkbox" name="giardino" id="giardino" />
              <span class="checkmark">
                <span class="checkedicon"
                  ><i class="fa-brands fa-pagelines"></i>
                </span>
              </span>
            </li>
            <li class="contain sangria">
              <input type="checkbox" name="patio" id="patio" />
              <span class="checkmark">
                <span class="checkedicon"
                  ><i class="fa-solid fa-shop"></i>
                </span>
              </span>
            </li>
            <li class="contain sangria">
              <input type="checkbox" name="mare" id="mare" />
              <span class="checkmark">
                <span class="checkedicon"
                  ><i class="fa-solid fa-water"></i>
                </span>
              </span>
            </li>
            <li class="contain sangria">
              <input type="checkbox" name="security" id="security" />
              <span class="checkmark">
                <span class="checkedicon"
                  ><i class="fa-solid fa-person-military-pointing"></i>
                </span>
              </span>
            </li>
          </ul>
        </div>
        <div class="smartnav altri_filtri">
          <div class="row">
            <div class="col-6 labels">Numero mimimo stanze</div>
            <div class="col-6 lineasinistra labels">Posti letto</div>
          </div>
          <div class="row">
            <div class="col-6">
              <ul>
                <li class="rosegold">
                  <input type="radio" name="stanze" id="" checked />
                  <span class="checkmark2">
                    <span class="checkedicon"
                      ><i class="fa-solid fa-3"></i>
                    </span>
                  </span>
                </li>
                <li class="rosegold">
                  <input type="radio" name="stanze" id="" />
                  <span class="checkmark2">
                    <span class="checkedicon"
                      ><i class="fa-solid fa-6"></i>
                    </span>
                  </span>
                </li>
                <li class="rosegold">
                  <input type="radio" name="stanze" id="" />
                  <span class="checkmark2">
                    <span class="checkedicon"
                      ><i class="fa-solid fa-9"></i>
                    </span>
                  </span>
                </li>
                <li class="rosegold">
                  <input type="radio" name="stanze" id="" />
                  <span class="checkmark2">
                    <span class="checkedicon"
                      ><i class="fa-solid fa-plus"></i>
                    </span>
                  </span>
                </li>
              </ul>
            </div>
            <div class="col-6 lineasinistra">
              <ul>
                <li class="rosegold">
                  <input type="radio" name="letti" id="" checked />
                  <span class="checkmark2">
                    <span class="checkedicon"
                      ><i class="fa-solid fa-2"></i>
                    </span>
                  </span>
                </li>
                <li class="rosegold">
                  <input type="radio" name="letti" id="" />
                  <span class="checkmark2">
                    <span class="checkedicon"
                      ><i class="fa-solid fa-4"></i>
                    </span>
                  </span>
                </li>
                <li class="rosegold">
                  <input type="radio" name="letti" id="" />
                  <span class="checkmark2">
                    <span class="checkedicon"
                      ><i class="fa-solid fa-6"></i>
                    </span>
                  </span>
                </li>
                <li class="rosegold">
                  <input type="radio" name="letti" id="" />
                  <span class="checkmark2">
                    <span class="checkedicon"
                      ><i class="fa-solid fa-plus"></i>
                    </span>
                  </span>
                </li>
              </ul>
            </div>
          </div>
        </div>
        <div class="smartnav categorie">
          <ul>
            <li class="">
              <h3>slider controllo distanza da aggiungere</h3>
            </li>
          </ul>
        </div>
      </div>
      <div class="btnopen">
        <div class="contain3">
          <input
            @click="functionOpener()"
            type="checkbox"
            name="filter_open_closer"
            id="filter_open_closer"
            checked
          />
          <span class="checkmark3down"
            ><i class="fa-solid fa-chevron-down"></i
          ></span>
          <span class="checkmark3upper"
            ><i class="fa-solid fa-chevron-up"></i
          ></span>
        </div>
      </div>
    </div>
  </div>

  <div class="container maincont">
    <div class="row">
      <div class="col-12 col-md-8">
        <div class="row gy-4">
          <div
            v-if="array2.length > 0"
            v-for="(apartment, index) in array2"
            :key="index"
            class="col-6 col-md-12 card_apartment"
          >
            <router-link :to="`/apartment/${apartment.slug}`">
              <div class="imgcont">
                <a href="#" class="cardapartments row">
                  <div class="col-12 col-md-6">
                    <img
                      id="imgeneric"
                      :src="`${store.imgBasePath}${apartment.cover_img}`"
                      alt=""
                    />
                  </div>

                  <div class="col-12 col-md-6">
                    <div class="row">
                      <div class="col-12">
                        <div class="text_infob">
                          <h1>{{ apartment.title }}</h1>
                          <h3>
                            <i class="fa-solid fa-location-dot"></i>
                            {{ apartment.address }}
                          </h3>
                          <h3>
                            <i class="fa-solid fa-euro-sign"></i>
                            {{ apartment.price }}/Notte
                          </h3>
                          <div class="d-flex">
                            <h4>
                              <i class="fa-solid fa-bed"></i>
                              {{ apartment.bed_number }}
                            </h4>
                            <h4>
                              <i class="fa-solid fa-door-open"></i>
                              {{ apartment.room_number }}
                            </h4>
                            <h4>
                              <i class="fa-solid fa-toilet"></i>
                              {{ apartment.bath_number }}
                            </h4>
                            <h4>
                              <i class="fa-brands fa-codepen"></i>
                              {{ apartment.mq_value }}
                            </h4>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </a>
              </div>
            </router-link>
          </div>
        </div>
      </div>
      <div v-if="this.array2.length == 0" class="col-12 col-md-8">
        <h1>Cerca un appartamento</h1>
      </div>
      <div class="col-12 col-md-4">
        <div class="wholefilter">
          <div id="search"></div>
          <h2>categorie:</h2>

          <ul class="category d-flex flex-wrap gap-3">
            <li v-for="(category, index) in categories" :key="index">
              <label :for="category.slug">{{ category.name }}</label>
              <input
                @click="setCategories(category.id)"
                type="radio"
                name="categoria"
                :id="'category_' + category.id"
              />
            </li>
          </ul>

          <hr />
          <h2>servizi:</h2>
          <ul class="services d-flex flex-wrap gap-3">
            <li v-for="(service, index) in services">
              <label :for="service.slug">{{ service.title }}</label>
              <input
                @click="setServices(service.id)"
                type="checkbox"
                name="wi-fi"
                :id="'service_' + service.id"
              />
            </li>
          </ul>
          <!-- <button @click="">Send</button> -->

          <hr />
          <h2>stanze:</h2>
          <ul class="stanze d-flex gap-3">
            <li>
              <label for="tre">3</label>
              <input @click="setRooms" type="radio" name="stanze" id="rooms3" />
            </li>
            <li>
              <label for="seii">6</label>
              <input @click="setRooms" type="radio" name="stanze" id="rooms6" />
            </li>
            <li>
              <label for="nove">9</label>
              <input @click="setRooms" type="radio" name="stanze" id="rooms9" />
            </li>
            <li>
              <label for="moltii">più</label>
              <input
                @click="setRooms"
                type="radio"
                name="stanze"
                id="rooms00"
              />
            </li>
          </ul>

          <hr />
          <h2>letti:</h2>
          <ul class="beds d-flex gap-3">
            <li>
              <label for="due">2</label>
              <input @click="setBeds" type="radio" name="beds" id="beds2" />
            </li>
            <li>
              <label for="quattro">4</label>
              <input @click="setBeds" type="radio" name="beds" id="beds4" />
            </li>
            <li>
              <label for="sei">6</label>
              <input @click="setBeds" type="radio" name="beds" id="beds6" />
            </li>
            <li>
              <label for="molti">più</label>
              <input @click="setBeds" type="radio" name="beds" id="beds00" />
            </li>
          </ul>

          <hr />
          <h2>Raggio:</h2>
          <ul class="kmrange d-flex gap-3">
            <li>
              <label for="five">5km</label>
              <input
                @click="setKilometers"
                type="radio"
                name="kmvar"
                id="five"
              />
            </li>
            <li>
              <label for="ten">10km</label>
              <input
                @click="setKilometers"
                type="radio"
                name="kmvar"
                id="ten"
              />
            </li>
            <li>
              <label for="twenty">20km</label>
              <input
                @click="setKilometers"
                type="radio"
                name="kmvar"
                id="twenty"
                checked
              />
            </li>
            <li>
              <label for="fifty">50km</label>
              <input
                @click="setKilometers"
                type="radio"
                name="kmvar"
                id="fifty"
              />
            </li>
            <li>
              <label for="hundred">100km</label>
              <input
                @click="setKilometers"
                type="radio"
                name="kmvar"
                id="hundred"
              />
            </li>
          </ul>
          <input
            @change="setKilometers2"
            type="range"
            class="d-block"
            id="range"
            name="range"
            min="5"
            max="100"
            value="20"
            oninput="this.nextElementSibling.value = this.value"
          />
          <output>20</output> km
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import { store } from "../store";
import axios from "axios";
import HeaderComponent from "../components/HeaderComponent.vue";
import CardComponent from "../components/AdvancedSearch/CardComponent.vue";
import FilterLargeComponent from "../components/FilterLargeComponent.vue";

export default {
  name: "AdvancedSearchPage",
  components: {
    HeaderComponent,
    CardComponent,
    FilterLargeComponent,
  },
  data() {
    return {
      store,
      varroom: "",
      varkm: "20", //base 20km
      varcat: null,
      distanza: "",
      categories: [],
      services: [],
      filteredServices: [],
      filteredServicesVerification: [],
      servicesWaitingRoom: [],
      minRooms: null,
      minBeds: null,
      maxBeds: null,
      array1: [],
      array2: [],
      array3: [],
      loading: true,
      latitudine: "",
      longitudine: "",
      options: {
        idleTimePress: 100,
        minNumberOfCharacters: 0,
        searchOptions: {
          key: "h7cAdo65F2uuetiST0o1pnUygRaWDuuX",
          language: "it-IT",
          limit: 5,
        },
        autocompleteOptions: {
          key: "h7cAdo65F2uuetiST0o1pnUygRaWDuuX",
          language: "it-IT",
        },
        noResultsMessage: "No results found.",
      },
    };
  },
  methods: {
    setKilometers2() {
      let range = document.getElementById("range");
      console.log(parseInt(range.value));
      this.varkm = parseInt(range.value);
      this.array2 = [];
      this.getProducts();
    },
    setKilometers() {
      let km5 = document.getElementById("five");
      let km10 = document.getElementById("ten");
      let km20 = document.getElementById("twenty");
      let km50 = document.getElementById("fifty");
      let km100 = document.getElementById("hundred");

      if (km5.checked) {
        //                    console.log('5km selected');
        this.varkm = 5;
        this.array2 = [];
        this.getProducts();
      } else if (km10.checked) {
        //                   console.log('10km selected');
        this.varkm = 10;
        this.array2 = [];
        this.getProducts();
      } else if (km20.checked) {
        //                   console.log('20km selected');
        this.varkm = 20;
        this.array2 = [];
        this.getProducts();
      } else if (km50.checked) {
        //                    console.log('50km selected');
        this.varkm = 50;
        this.array2 = [];
        this.getProducts();
      } else if (km100.checked) {
        //                    console.log('100km selected');
        this.varkm = 100;
        this.array2 = [];
        this.getProducts();
      }
    },
    setCategories(category) {
      let addCategory = document.getElementById(`category_${category}`);
      console.log(addCategory);

      if (addCategory.checked) {
        this.varcat = category;
        this.getProducts();
      }
    },
    setServices(service) {
      let addService = document.getElementById(`service_${service}`);
      console.log(addService);
      if (addService.checked) {
        let serviceArr = { ...this.services.filter((el) => el.id == service) };
        let serviceObj = serviceArr[0];
        this.filteredServices.push(serviceObj.id);
        this.getProducts();
        // this.filtriServizi();
      } else if (!addService.checked) {
        let serviceArr = { ...this.services.filter((el) => el.id == service) };
        let serviceObj = serviceArr[0];
        this.filteredServices.splice(
          this.filteredServices.indexOf(serviceObj),
          1
        );
        // this.filtriServizi();
        this.getProducts();
      }
      console.log(this.filteredServices);
    },
    setRooms() {
      const rooms3 = document.getElementById("rooms3");
      const rooms6 = document.getElementById("rooms6");
      const rooms9 = document.getElementById("rooms9");
      // const rooms00 = document.getElementById('rooms00');

      rooms3.checked ? (this.minRooms = 3) : "";
      rooms6.checked ? (this.minRooms = 6) : "";
      rooms9.checked ? (this.minRooms = 9) : "";

      // rooms00.checked ? this.minRooms = 3 : '';

      console.log(this.minRooms);
      this.getProducts();
    },
    setBeds() {
      const beds3 = document.getElementById("beds2");
      const beds6 = document.getElementById("beds4");
      const beds9 = document.getElementById("beds6");
      // const beds00 = document.getElementById('beds00');

      beds3.checked ? (this.minBeds = 2) : "";
      beds6.checked ? (this.minBeds = 4) : "";
      beds9.checked ? (this.minBeds = 6) : "";
      // beds00.checked ? console.log('b00') : '';

      console.log(this.minBeds);
      this.getProducts();
    },
    functionOpener() {
      document.getElementById("filter_open_closer").onchange = (e) => {
        let checked = e.target.checked;
        if (checked) {
          document.getElementById("smartnavop").style.opacity = "1";
          document.getElementById("smartnavop").style.height = "269px";
        } else {
          document.getElementById("smartnavop").style.opacity = "0";
          document.getElementById("smartnavop").style.height = "0px";
        }
      };
    },
    initSearchBox() {
      // let ttSearchBox = new tt.plugins.SearchBox(tt.services, this.options);
      let ttSearchBox = new tt.plugins.SearchBox(tt.services, this.options);
      // console.log(ttSearchBox);

      let searchBoxHTML = ttSearchBox.getSearchBoxHTML();
      document.getElementById("search").appendChild(searchBoxHTML);
      // console.log(searchBoxHTML);

      ttSearchBox.on("tomtom.searchbox.resultsfound", function (data) {
        // console.log(data);
      });

      ttSearchBox.on("tomtom.searchbox.resultselected", (data) => {
        //       console.log(data);
        let lat = data.data.result.position.lat;
        this.latitudine = lat;
        // console.log("latitudine", this.latitudine);

        let lng = data.data.result.position.lng;
        this.longitudine = lng;
        // console.log("longitudine", this.longitudine);

        this.getProducts();
        // this.array2 = [];
      });
    },
    getLatLongDist(lat2, long2) {
      let unit = "K";
      var radlat1 = (Math.PI * this.latitudine) / 180; //lat1 aka latitudine mappa
      //                 console.log('radlat1',radlat1);

      var radlat2 = (Math.PI * lat2) / 180; //lat2 aka latitudine di ogni singolo appartamento
      //                  console.log('radlat2',radlat2);

      var theta = this.longitudine - long2; //long1(longitudine mappa) - long2(longitudine appartamento)
      var radtheta = (Math.PI * theta) / 180;
      var dist =
        Math.sin(radlat1) * Math.sin(radlat2) +
        Math.cos(radlat1) * Math.cos(radlat2) * Math.cos(radtheta);
      if (dist > 1) {
        dist = 1;
      }
      dist = Math.acos(dist);
      dist = (dist * 180) / Math.PI;
      dist = dist * 60 * 1.1515;
      if (unit == "K") {
        dist = dist * 1.609344;
      }

      this.distanza = "";
      this.distanza = dist;
      //                 console.log('distanza variabile globale',this.distanza);
      // return dist;
    },
    getProducts() {
      axios.get(`${this.store.apiBaseUrl}/apartments`).then((res) => {
        this.array1 = [];
        this.array2 = [];
        this.array1 = res.data.results; //array 1 chiamata tutti gli appartamenti axios
        this.array1.forEach((item) => {
          let lat2 = item.lat;
          let long2 = item.long;

          this.getLatLongDist(lat2, long2);
          if (this.distanza <= this.varkm) {
            this.array2.push(item);
          }
        });
        console.log(this.array2);
        //filter by category
        if (!(this.varcat == null)) {
          console.log("sei entrato nel filtro Categoria");
          this.array2 = this.array2.filter(
            (item) => item.category_id == this.varcat
          );
        }
        //filter by services
        if (this.filteredServices.length > 0) {
          console.log("sei entrato nel filtro Servizi");
          // this.array2 = this.filterServices(this.array2, this.filteredServices);
          this.array2.forEach((item) => {
            this.filteredServicesVerification = [];
            item.services.forEach((el) => {
              this.filteredServicesVerification.push(el.id);
            });
            // console.log(this.filteredServices);
            // console.log(this.filteredServices);
            // console.log(this.filteredServicesVerification);
            let verification = this.filteredServices.every((elem) =>
              this.filteredServicesVerification.includes(elem)
            );
            // console.log(verification);
            if (verification) {
              this.servicesWaitingRoom.push(item);
            }
          });
          console.log(this.servicesWaitingRoom);
          this.array2 = this.servicesWaitingRoom;
          this.servicesWaitingRoom = [];
        }

        //filter by rooms
        if (!(this.minRooms == null)) {
          console.log("sei entrato nel filtro Camere");
          console.log(this.array2);
          this.array2 = this.array2.filter(
            (item) => item.room_number >= this.minRooms
          );
        }

        //filter by beds
        if (!(this.minBeds == null)) {
          console.log("sei entrato nel filtro Letti");
          console.log(this.array2);
          this.array2 = this.array2.filter(
            (item) => item.bed_number >= this.minBeds
          );
        }
        this.loading = false;
      });
    },
    getServices() {
      axios.get(`${this.store.apiBaseUrl}/services`).then((res) => {
        this.services = res.data.results; //array 1 chiamata tutti gli appartamenti axios
        console.log(this.services);
      });
    },
    getCategories() {
      axios.get(`${this.store.apiBaseUrl}/categories`).then((res) => {
        this.categories = res.data.results; //array 1 chiamata tutti gli appartamenti axios
        console.log(this.categories);
      });
    },
  },
  mounted() {
    this.getCategories();
    this.getServices();
    // this.getProducts();
    this.initSearchBox();
    // this.initSearchBoxsmart();
  },
};
</script>

<style lang="scss" scoped>
@use "../assets/styles/partials/variables" as *;

.wholefilter {
  background-color: rgb(204, 221, 221);
  padding: 5px 20px 20px 20px;
  border-radius: 20px;
  h2 {
    margin-top: 10px;
    text-transform: capitalize;
  }
  li {
    label {
      font-size: 1.1rem;
    }
    input {
      margin: 0px 5px;
    }
  }
}

@media screen and (max-width: 800px) {
  .wholefilter {
    display: none;
    opacity: 0;
  }
}

@media screen and (min-width: 800px) {
  .navholder {
    display: none;
    opacity: 0;
  }
}

@media screen and (min-width: 800px) {
  .maincont {
    display: flex;
    margin-top: 50px !important;
  }
}

@media screen and (max-width: 800px) {
  #imgeneric {
    height: 160px;
  }
}

.maincont::-webkit-scrollbar {
  display: none;
}

footer {
  z-index: 1;
}

.text_infoa {
  padding: 10px 15px;
  color: $darkgrey;
  h1 {
    width: 100%;
    white-space: nowrap;
    overflow: hidden;
    font-size: 1.6rem;
    text-overflow: ellipsis;
    font-weight: 800;
    text-transform: uppercase;
    margin-bottom: 0;
  }
  h4 {
    width: 100%;
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis;
    margin-bottom: 0;
  }
}
.text_infob {
  display: flex;
  flex-direction: column;
  gap: 10px;
  padding: 10px 5px;
  color: $darkgrey;
  h1 {
    width: 100%;
    font-size: 1.5rem;
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis;
    font-weight: 800;
  }
  h3 {
    width: 100%;
    font-size: 1.3rem;
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis;
    font-weight: 800;
  }
  h4 {
    font-size: 0.9rem;
    width: 100%;
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis;
    font-weight: 800;
    margin: 0;
  }
}
.allcont {
  top: -1px;
  z-index: 100;
  position: fixed;
  width: 100%;
}
.maincont {
  z-index: 50;
  margin-top: 128px;
  padding-top: 40px;
  padding-bottom: 10px;
  overflow-y: scroll;

  @keyframes cardapartment {
    0% {
      opacity: 0;
      width: 500px;
    }
    100% {
      opacity: 1;
      width: 100%;
    }
  }

  .card_apartment {
    transition: ease-in-out 200ms;
    animation-name: cardapartment;
    animation-duration: 1s;
    border-radius: 20px;
    .imgcont {
      transition: all 250ms;
      filter: brightness(0.8);
      &:hover {
        filter: brightness(1.1);
      }
      position: relative;
      box-shadow: 0px 3px 5px rgba(0, 0, 0, 0.2);
      .row {
      }
      img {
        // border-radius: 20px 20px 0px 0px;
        object-fit: cover;
        height: 250px;
        width: 100%;
      }
    }
    .img_case {
      height: 250px;
      overflow: hidden;
      border-radius: 20px;
      img {
      }
    }
  }
}

header {
  z-index: 100;
}
.btnopen {
  height: 20px;
  width: 300px;
  margin: 0 auto;
  padding: 0;
  border-radius: 0px 0px 20px 20px;
  transition: all 200ms;
  overflow: hidden;
  background-color: rgba(255, 255, 255, 0);
  a {
    color: $grey;
    width: 100%;
  }
}
.lineasinistra {
  border-left: 2px solid $grey;
}
.labels {
  font-weight: 700;
}
.contain3 {
  justify-content: center;
  height: 20px;
  width: 100%;
  display: flex;
  position: relative;
  // border-radius: 50%;
  background-color: $emerald;
  transition: all 200ms;

  cursor: pointer;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  #filter_open_closer {
    opacity: 0;
    cursor: pointer;
    z-index: 100;
    left: 0;
    height: 300px;
    width: 300px;
  }
}
.contain {
  justify-content: center;
  height: 40px;
  width: 50px;
  display: flex;
  position: relative;
  cursor: pointer;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}
.rosegold {
  height: 30px;
  width: 40px;
  padding: 0px 5px;
  display: flex;
  display: block;
  position: relative;
  //   padding-left: 35px;
  //   margin-bottom: 12px;
  cursor: pointer;
  font-size: 22px;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}
/* Hide the browser's default checkbox */
.contain input {
  position: absolute;
  opacity: 0;
  cursor: pointer;
  z-index: 100;
  left: 0;
  height: 40px;
  width: 40px;
  border-radius: 50%;
}
.rosegold input {
  position: absolute;
  opacity: 0;
  cursor: pointer;
  z-index: 100;
  left: 0;
  height: 30px;
  width: 30px;
  border-radius: 10px;
}
.checkmark3down {
  position: absolute;
  left: auto;
  top: -2px;
  color: $white;
  transition: all 200ms;
}
.checkmark3upper {
  position: absolute;
  left: auto;
  top: -2;
  opacity: 0;
  color: $white;
  transition: all 200ms;
}
.checkmark {
  position: absolute;
  display: flex;
  align-items: center;
  justify-content: center;
  top: 0;
  left: 0;
  height: 40px;
  width: 40px;
  border-radius: 50%;
  background-color: $white;
  border: 4px solid $grey;
}
/* Create a custom checkbox */
.checkmark2 {
  position: absolute;
  display: flex;
  align-items: center;
  justify-content: center;
  top: 0;
  left: 0;
  height: 30px;
  width: 30px;
  border-radius: 10px;
  background-color: $white;
  border: 4px solid $grey;
}
.checkedicon {
  font-size: 1.2rem;
  // display: none;
  color: $grey;
  text-align: center;
  transition: all 200ms;
}
// comandi apertura window
.contain3 input:checked ~ .checkmark3upper {
  opacity: 1;
}
.contain3 input:checked ~ .checkmark3down {
  opacity: 0;
}
/* When the checkbox is checked, add a blue background */
.emerald input:checked ~ .checkmark {
  background-color: $emerald;
  border: 4px solid $emerald;
}
.sangria input:checked ~ .checkmark {
  background-color: $sangria;
  border: 4px solid $sangria;
}
.rosegold input:checked ~ .checkmark2 {
  background-color: $rosegold;
  border: 4px solid $rosegold;
}
/* Show the checkmark when checked */
.contain input:checked ~ .checkmark > .checkedicon {
  display: block;
  color: $white;
}
.rosegold input:checked ~ .checkmark2 > .checkedicon {
  display: block;
  color: $white;
}
.smartnav {
  padding: 0px 10px;
  overflow-x: scroll;
  border-bottom: 2px solid $raindrop;
  ul {
    padding-left: 5px;
    display: flex;
    align-items: center;
    height: 60px;
    min-width: fit-content;
    // oro colato

    li {
      input {
      }
      .checkmark {
      }
    }
  }
}
.smartnav::-webkit-scrollbar {
  display: none;
}
.search {
  padding: 10px 10px;
  background-color: $emerald;
  #cerca {
    width: 100%;
    height: 46px;
    border: 2px solid $grey;
    border-radius: 50px;
    padding: 0px 20px;
    font-size: 1.5rem;
    outline: none;
    box-shadow: 0px 2px 5px rgba(0, 0, 0, 0.15);
  }
}

#smartnavop {
  background-color: rgba(255, 255, 255, 0.85);
  overflow: hidden;
  // height: 0px;
  height: 269px;
  transition: ease-in-out 250ms all;
}
</style>
