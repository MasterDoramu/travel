<template>
      <b-container>
      <b-row class="border pt-4">
        <b-col  class="d-flex align-items-center">
          <buy-ticket-carousel class="w-100"></buy-ticket-carousel>
        </b-col>
        <b-col>    
          <b-row class="px-4">
            <b-col-12>
              <h3  class="text-start"><b>Метеор «Быстрый»</b></h3>
            </b-col-12>
            <b-col>
            <div class="text-start">
              <small class="text-black-50">Дата отправки</small><br>
              <span >26 октября 2021 г.</span>
            </div>
            </b-col>
            <b-col class="py-3 text-right text-end">
              <h2><b>14:45</b></h2>
            </b-col>
          </b-row>
          <b-row class="border me-0 py-4 px-3 text-start py-3">
            <b-col class="border-end">
              <div class="d-flex flex-column">
                <span class="text-black-50">Вместимость</span>
                <b>24 чел.</b>
              </div>
            </b-col>
            <b-col class="border-end d-flex justify-content-center">
              <div class="d-flex flex-column">
                <span class="text-black-50">Свободных мест</span>
                <b>13</b>
              </div>
            </b-col>
            <b-col class="d-flex justify-content-end">
              <div class="d-flex flex-column">
                <span class="text-black-50">Время в пути</span>
                <b>2 часа</b>
              </div>
            </b-col>
          </b-row>
          <b-col class=" py-3 pe-4 ps-3 text-start">
            <small class="text-muted">
              Пролетев на подводных крыльях по прекрасному Ладожскому озеру,
              вы высадитесь на остров потрясающей красоты. Хотите,
              исследуйте остров самостоятельно,
              хотите – посетите экскурсии. На острове вам предложат пешеходную экскурсию
              по острову и посещение Валаамского монастыря.
            </small>
          </b-col>
          <b-row class="bg-light p-3 me-0">
            <b-row>
              <b-col cols="4 d-flex align-items-end text-start">
                <span>Взрослые /<b> 1800₽</b></span>
              </b-col>
              <b-col cols="4" class="border-bottom text-center">
              </b-col>
              <b-col></b-col>
              <b-col cols="3">
                <b-row>
                  <b-col cols="3 px-0">
                    <b-button variant="primary">
                      <svg width="12" height="2" viewBox="0 0 12 2" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <rect y="0.25" width="12" height="1.5" rx="0.75" fill="white"/>
                      </svg>
                    </b-button>
                  </b-col>
                  <b-col cols="6 px-1">
                    <b-form-input v-model="text" class="text-center fw-bold text-dark">
                    </b-form-input>
                  </b-col>
                  <b-col cols="3 px-0">
                    <b-button variant="primary">
                      <svg width="12" height="12" viewBox="0 0 12 12" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path fill-rule="evenodd" clip-rule="evenodd" d="M6 0C6.19891 0 6.38968 0.0790178 6.53033 0.21967C6.67098 0.360322 6.75 0.551088 6.75 0.75V5.25H11.25C11.4489 5.25 11.6397 5.32902 11.7803 5.46967C11.921 5.61032 12 5.80109 12 6C12 6.19891 11.921 6.38968 11.7803 6.53033C11.6397 6.67098 11.4489 6.75 11.25 6.75H6.75V11.25C6.75 11.4489 6.67098 11.6397 6.53033 11.7803C6.38968 11.921 6.19891 12 6 12C5.80109 12 5.61032 11.921 5.46967 11.7803C5.32902 11.6397 5.25 11.4489 5.25 11.25V6.75H0.75C0.551088 6.75 0.360322 6.67098 0.21967 6.53033C0.0790178 6.38968 0 6.19891 0 6C0 5.80109 0.0790178 5.61032 0.21967 5.46967C0.360322 5.32902 0.551088 5.25 0.75 5.25H5.25V0.75C5.25 0.551088 5.32902 0.360322 5.46967 0.21967C5.61032 0.0790178 5.80109 0 6 0Z" fill="white"/>
                      </svg>
                    </b-button>
                  </b-col>
                </b-row>
              </b-col>
            </b-row>
            <b-row class="pt-3">
              <b-col cols="4 d-flex align-items-end text-start">
                <span>Дети 
                  <svg class="mb-3" width="14" height="14" viewBox="0 0 14 14" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M14 7C14 8.85652 13.2625 10.637 11.9497 11.9497C10.637 13.2625 8.85652 14 7 14C5.14348 14 3.36301 13.2625 2.05025 11.9497C0.737498 10.637 0 8.85652 0 7C0 5.14348 0.737498 3.36301 2.05025 2.05025C3.36301 0.737498 5.14348 0 7 0C8.85652 0 10.637 0.737498 11.9497 2.05025C13.2625 3.36301 14 5.14348 14 7ZM4.809 5.27887C4.78079 5.27926 4.75281 5.27388 4.72675 5.26308C4.7007 5.25227 4.67712 5.23626 4.65746 5.21603C4.6378 5.1958 4.62248 5.17177 4.61243 5.14542C4.60238 5.11906 4.59781 5.09093 4.599 5.06275C4.68125 3.57962 5.89488 3.0625 7.00437 3.0625C8.22587 3.0625 9.34237 3.70125 9.34237 5.0225C9.34237 5.9675 8.78675 6.41725 8.25387 6.82237C7.609 7.3115 7.37013 7.49438 7.37013 8.12263V8.2145C7.37013 8.27252 7.34708 8.32816 7.30605 8.36918C7.26503 8.4102 7.20939 8.43325 7.15138 8.43325H6.44263C6.38521 8.43326 6.33009 8.41069 6.28917 8.37042C6.24825 8.33015 6.22479 8.27541 6.22388 8.218L6.22038 8.02812C6.18713 7.217 6.6535 6.71738 7.24238 6.2895C7.75863 5.901 8.08675 5.6455 8.08675 5.08987C8.08675 4.368 7.53725 4.06787 6.937 4.06787C6.23438 4.06787 5.84062 4.48612 5.76275 5.06012C5.747 5.18 5.65075 5.27887 5.53 5.27887H4.80813H4.809ZM6.84338 10.9165C6.33238 10.9165 5.9605 10.5717 5.9605 10.1054C5.9605 9.62237 6.33238 9.28288 6.84425 9.28288C7.37713 9.28288 7.74375 9.62237 7.74375 10.1054C7.74375 10.5717 7.37625 10.9165 6.84338 10.9165Z" fill="#CED4DA"/>
                  </svg>
                  /<b> 2400₽</b></span>
              </b-col>
              <b-col cols="4" class="border-bottom text-center">
              </b-col>
              <b-col></b-col>
              <b-col cols="3">
                <b-row>
                  <b-col cols="3 px-0">
                    <b-button variant="primary">
                      <svg width="12" height="2" viewBox="0 0 12 2" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <rect y="0.25" width="12" height="1.5" rx="0.75" fill="white"/>
                      </svg>
                    </b-button>
                  </b-col>
                  <b-col cols="6 px-1">
                    <b-form-input v-model="text" class="text-center fw-bold text-dark">
                    </b-form-input>
                  </b-col>
                  <b-col cols="3 px-0">
                    <b-button variant="primary">
                      <svg width="12" height="12" viewBox="0 0 12 12" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path fill-rule="evenodd" clip-rule="evenodd" d="M6 0C6.19891 0 6.38968 0.0790178 6.53033 0.21967C6.67098 0.360322 6.75 0.551088 6.75 0.75V5.25H11.25C11.4489 5.25 11.6397 5.32902 11.7803 5.46967C11.921 5.61032 12 5.80109 12 6C12 6.19891 11.921 6.38968 11.7803 6.53033C11.6397 6.67098 11.4489 6.75 11.25 6.75H6.75V11.25C6.75 11.4489 6.67098 11.6397 6.53033 11.7803C6.38968 11.921 6.19891 12 6 12C5.80109 12 5.61032 11.921 5.46967 11.7803C5.32902 11.6397 5.25 11.4489 5.25 11.25V6.75H0.75C0.551088 6.75 0.360322 6.67098 0.21967 6.53033C0.0790178 6.38968 0 6.19891 0 6C0 5.80109 0.0790178 5.61032 0.21967 5.46967C0.360322 5.32902 0.551088 5.25 0.75 5.25H5.25V0.75C5.25 0.551088 5.32902 0.360322 5.46967 0.21967C5.61032 0.0790178 5.80109 0 6 0Z" fill="white"/>
                      </svg>
                    </b-button>
                  </b-col>
                </b-row>
              </b-col>
            </b-row>
            <b-row class="pt-3">
              <b-col cols="4 d-flex align-items-end text-start">
                <span>Бесплатно 
                  <svg class="mb-3" width="14" height="14" viewBox="0 0 14 14" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M14 7C14 8.85652 13.2625 10.637 11.9497 11.9497C10.637 13.2625 8.85652 14 7 14C5.14348 14 3.36301 13.2625 2.05025 11.9497C0.737498 10.637 0 8.85652 0 7C0 5.14348 0.737498 3.36301 2.05025 2.05025C3.36301 0.737498 5.14348 0 7 0C8.85652 0 10.637 0.737498 11.9497 2.05025C13.2625 3.36301 14 5.14348 14 7ZM4.809 5.27887C4.78079 5.27926 4.75281 5.27388 4.72675 5.26308C4.7007 5.25227 4.67712 5.23626 4.65746 5.21603C4.6378 5.1958 4.62248 5.17177 4.61243 5.14542C4.60238 5.11906 4.59781 5.09093 4.599 5.06275C4.68125 3.57962 5.89488 3.0625 7.00437 3.0625C8.22587 3.0625 9.34237 3.70125 9.34237 5.0225C9.34237 5.9675 8.78675 6.41725 8.25387 6.82237C7.609 7.3115 7.37013 7.49438 7.37013 8.12263V8.2145C7.37013 8.27252 7.34708 8.32816 7.30605 8.36918C7.26503 8.4102 7.20939 8.43325 7.15138 8.43325H6.44263C6.38521 8.43326 6.33009 8.41069 6.28917 8.37042C6.24825 8.33015 6.22479 8.27541 6.22388 8.218L6.22038 8.02812C6.18713 7.217 6.6535 6.71738 7.24238 6.2895C7.75863 5.901 8.08675 5.6455 8.08675 5.08987C8.08675 4.368 7.53725 4.06787 6.937 4.06787C6.23438 4.06787 5.84062 4.48612 5.76275 5.06012C5.747 5.18 5.65075 5.27887 5.53 5.27887H4.80813H4.809ZM6.84338 10.9165C6.33238 10.9165 5.9605 10.5717 5.9605 10.1054C5.9605 9.62237 6.33238 9.28288 6.84425 9.28288C7.37713 9.28288 7.74375 9.62237 7.74375 10.1054C7.74375 10.5717 7.37625 10.9165 6.84338 10.9165Z" fill="#CED4DA"/>
                  </svg>
                  /<b> 0₽</b></span>
              </b-col>
              <b-col cols="4" class="border-bottom text-center">
              </b-col>
              <b-col></b-col>
              <b-col cols="3">
                <b-row>
                  <b-col cols="3 px-0">
                    <b-button variant="primary">
                      <svg width="12" height="2" viewBox="0 0 12 2" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <rect y="0.25" width="12" height="1.5" rx="0.75" fill="white"/>
                      </svg>
                    </b-button>
                  </b-col>
                  <b-col cols="6 px-1">
                    <b-form-input v-model="text" class="text-center fw-bold text-dark">
                    </b-form-input>
                  </b-col>
                  <b-col cols="3 px-0">
                    <b-button variant="primary">
                      <svg width="12" height="12" viewBox="0 0 12 12" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path fill-rule="evenodd" clip-rule="evenodd" d="M6 0C6.19891 0 6.38968 0.0790178 6.53033 0.21967C6.67098 0.360322 6.75 0.551088 6.75 0.75V5.25H11.25C11.4489 5.25 11.6397 5.32902 11.7803 5.46967C11.921 5.61032 12 5.80109 12 6C12 6.19891 11.921 6.38968 11.7803 6.53033C11.6397 6.67098 11.4489 6.75 11.25 6.75H6.75V11.25C6.75 11.4489 6.67098 11.6397 6.53033 11.7803C6.38968 11.921 6.19891 12 6 12C5.80109 12 5.61032 11.921 5.46967 11.7803C5.32902 11.6397 5.25 11.4489 5.25 11.25V6.75H0.75C0.551088 6.75 0.360322 6.67098 0.21967 6.53033C0.0790178 6.38968 0 6.19891 0 6C0 5.80109 0.0790178 5.61032 0.21967 5.46967C0.360322 5.32902 0.551088 5.25 0.75 5.25H5.25V0.75C5.25 0.551088 5.32902 0.360322 5.46967 0.21967C5.61032 0.0790178 5.80109 0 6 0Z" fill="white"/>
                      </svg>
                    </b-button>
                  </b-col>
                </b-row>
              </b-col>
            </b-row>
          </b-row>
          <b-row class="pt-3 pb-3 me-0">
            <b-button
              class="m-0"
              block variant="success">Купить билет 4 200 ₽</b-button>
          </b-row>
        </b-col>
      </b-row>
    </b-container>
</template>

<script>
import BuyTicketCarousel from './BuyTicketCarousel';
import './ticket.scss';

export default {
  name: 'Ticket',
  components: {
    BuyTicketCarousel,
  },
  data() {
    return {
      text: 1,
    }
  }
}
</script>