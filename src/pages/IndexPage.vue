<template>
  <q-page class="pen">
    <section class="top">
      <header class="header">
        <div class="logo">
          <svg width="189" height="24" viewBox="0 0 189 24" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M5.6 22.936C0.864 22.296 0.288 16.216 0.288 12.44C0.288 7.864 1.632 1.848 6.88 0.727999C7.584 0.599998 9.536 0.535999 10.4 0.631998C13.056 0.887999 15.136 2.072 16.224 3.96C16.48 4.344 16.8 5.176 16.928 5.624C17.28 7 16.8 8.664 15.808 9.592L15.456 9.912L16 10.488C17.824 12.184 18.848 14.296 18.976 16.472C19.04 18.296 18.496 19.8 17.344 21.016C16.512 21.912 15.552 22.456 14.24 22.84L13.728 22.968H9.824C7.68 22.968 5.792 22.968 5.6 22.936ZM11.072 5.08L10.816 4.792L10.944 5.176C11.008 5.464 11.04 5.816 11.072 6.456L11.104 7.352H11.232C11.296 7.352 11.424 7.352 11.456 7.32C11.616 7.224 11.68 6.904 11.616 6.424C11.52 5.784 11.392 5.4 11.072 5.08ZM10.976 13.72C10.816 13.528 10.496 13.304 10.496 13.368C10.496 13.368 10.56 13.528 10.656 13.72C10.88 14.232 10.944 14.584 10.912 15.512C10.88 15.928 10.848 16.376 10.848 16.472C10.816 16.632 10.816 16.664 10.976 16.664C11.328 16.696 11.392 16.696 11.488 16.632C11.968 16.28 11.648 14.424 10.976 13.72ZM26.04 0.631998C28.088 0.535999 29.72 1.08 30.744 2.168C31.128 2.584 31.32 2.936 31.576 3.544C31.736 4.024 31.736 4.056 31.736 4.856C31.736 5.336 31.704 8.536 31.672 11.96L31.64 18.232L31.512 18.808C31.16 20.184 30.552 21.24 29.688 22.072C28.824 22.872 28.536 22.968 26.456 23C25.336 23 24.952 23 24.664 22.936C23.512 22.68 22.52 22.072 21.912 21.24C20.056 18.84 19.512 13.944 20.408 7.8C20.952 4.248 21.592 0.823999 26.04 0.631998ZM50.2155 0.727999C51.3355 1.08 52.1355 2.2 52.3915 3.32C52.5835 4.088 52.6155 5.56 52.4235 6.52C52.1675 7.832 51.4635 8.824 50.4715 9.336C49.8635 9.624 49.3835 9.72 48.6155 9.688H47.9755V12.856C47.9755 16.504 47.9435 17.624 47.8155 18.392C47.6875 19.416 47.3035 20.504 46.7595 21.336C46.4715 21.816 45.7355 22.584 45.4475 22.712C44.9675 22.936 43.9115 23.064 42.6635 23C42.0555 22.968 41.8315 22.936 41.4795 22.84C38.5355 21.848 37.9275 17.912 37.7675 15.256C37.7035 14.232 37.7035 12.152 37.7675 11.032C37.7995 10.584 37.7995 10.2 37.7995 10.2C37.7675 10.2 37.5435 10.232 37.2875 10.296C36.9355 10.392 36.6155 10.424 36.2955 10.424C33.8955 10.424 32.9035 8.248 32.8075 6.168C32.7435 4.632 33.1275 3.256 33.8635 2.136C34.3755 1.4 35.2715 0.759998 35.9755 0.631998C36.1995 0.599998 38.2155 0.599998 43.0795 0.599998H49.8635L50.2155 0.727999ZM58.645 22.936C53.909 22.296 53.333 16.216 53.333 12.44C53.333 7.864 54.677 1.848 59.925 0.727999C60.629 0.599998 62.581 0.535999 63.445 0.631998C66.101 0.887999 68.181 2.072 69.269 3.96C69.525 4.344 69.845 5.176 69.973 5.624C70.325 7 69.845 8.664 68.853 9.592L68.501 9.912L69.045 10.488C70.869 12.184 71.893 14.296 72.021 16.472C72.085 18.296 71.541 19.8 70.389 21.016C69.557 21.912 68.597 22.456 67.285 22.84L66.773 22.968H62.869C60.725 22.968 58.837 22.968 58.645 22.936ZM64.117 5.08L63.861 4.792L63.989 5.176C64.053 5.464 64.085 5.816 64.117 6.456L64.149 7.352H64.277C64.341 7.352 64.469 7.352 64.501 7.32C64.661 7.224 64.725 6.904 64.661 6.424C64.565 5.784 64.437 5.4 64.117 5.08ZM64.021 13.72C63.861 13.528 63.541 13.304 63.541 13.368C63.541 13.368 63.605 13.528 63.701 13.72C63.925 14.232 63.989 14.584 63.957 15.512C63.925 15.928 63.893 16.376 63.893 16.472C63.861 16.632 63.861 16.664 64.021 16.664C64.373 16.696 64.437 16.696 64.533 16.632C65.013 16.28 64.693 14.424 64.021 13.72ZM78.285 22.936C76.205 22.648 74.541 21.048 73.709 18.52C73.229 17.016 72.973 14.968 72.973 12.44C72.973 8.184 74.157 2.488 78.701 0.952C79.309 0.759998 80.013 0.664 81.005 0.599998C85.101 0.439999 88.141 1.784 89.933 4.536C91.821 7.48 92.397 12.888 91.309 17.304C90.605 20.024 89.261 22.968 86.093 22.968C85.357 22.968 84.941 22.872 84.397 22.648C84.013 22.456 83.405 22.072 83.405 21.976C83.405 21.976 83.469 21.848 83.565 21.72C84.813 20.088 85.261 18.104 85.261 16.088C85.229 14.84 85.133 14.328 84.813 13.144C84.525 12.216 84.525 12.28 85.005 12.152L85.389 12.024L84.557 11.992C84.109 11.992 83.725 11.96 83.725 11.992C83.725 11.992 83.853 12.056 84.045 12.12L84.333 12.248L84.461 12.6C84.845 13.912 84.973 14.904 84.941 16.312C84.877 18.136 84.429 19.64 83.597 20.824C83.277 21.336 82.541 22.008 82.125 22.264C81.165 22.84 79.501 23.096 78.285 22.936ZM83.821 9.368C83.789 10.2 83.789 10.328 83.917 10.488C84.013 10.552 84.045 10.584 84.365 10.552C84.589 10.52 84.781 10.488 84.845 10.456C84.973 10.392 85.005 10.136 84.909 9.656C84.781 8.856 84.397 7.832 84.237 7.832C84.013 7.832 83.885 8.344 83.821 9.368ZM97.7865 22.936C96.6665 22.68 95.6425 22.072 95.0345 21.24C93.1785 18.84 92.6345 13.944 93.5305 7.8C94.0745 4.248 94.7145 0.823999 99.1625 0.631998C101.21 0.535999 102.842 1.08 103.866 2.168C104.634 3 104.858 3.768 104.858 4.888C104.858 5.336 104.826 7.608 104.826 9.912C104.794 12.216 104.794 14.136 104.762 14.168C104.73 14.168 104.57 14.232 104.378 14.296C103.162 14.68 101.594 15.448 100.698 16.344C100.378 16.632 100.346 16.664 100.602 16.504C102.746 14.936 105.274 14.072 107.546 14.072C108.154 14.072 108.762 14.136 109.306 14.264C111.386 14.744 112.122 16.952 112.122 18.872C112.122 19.736 112.122 19.864 111.994 20.152C111.546 21.432 110.33 22.392 108.666 22.872L108.186 23.032H103.162C99.0985 23.032 98.0745 23 97.7865 22.936ZM117.583 22.936C116.463 22.68 115.439 22.072 114.831 21.24C112.975 18.84 112.431 13.944 113.327 7.8C113.871 4.248 114.511 0.823999 118.959 0.631998C121.007 0.535999 122.639 1.08 123.663 2.168C124.431 3 124.655 3.768 124.655 4.888C124.655 5.336 124.623 7.608 124.623 9.912C124.591 12.216 124.591 14.136 124.559 14.168C124.527 14.168 124.367 14.232 124.175 14.296C122.959 14.68 121.391 15.448 120.495 16.344C120.175 16.632 120.143 16.664 120.399 16.504C122.543 14.936 125.071 14.072 127.343 14.072C127.951 14.072 128.559 14.136 129.103 14.264C131.183 14.744 131.919 16.952 131.919 18.872C131.919 19.736 131.919 19.864 131.791 20.152C131.343 21.432 130.127 22.392 128.463 22.872L127.983 23.032H122.959C118.895 23.032 117.871 23 117.583 22.936ZM133.347 19.544C133.219 19.064 133.059 17.912 132.931 16.568C132.483 11.736 132.803 7.224 133.763 4.6C134.499 2.616 135.875 1.208 138.019 0.727999C138.595 0.599998 138.595 0.599998 142.627 0.599998H146.691L147.235 0.759998C149.379 1.336 150.435 2.776 150.435 5.048C150.435 7.832 148.259 8.856 145.795 9.08C144.835 9.144 144.387 9.144 142.627 9.016C141.923 8.952 141.443 8.92 141.123 8.92C140.643 8.92 140.451 8.984 140.259 9.144C140.131 9.272 140.099 9.336 140.131 9.496C140.131 9.688 140.131 9.688 140.419 9.688C140.611 9.72 140.899 9.624 141.571 9.432C142.275 9.24 142.531 9.176 142.691 9.208C142.947 9.24 145.923 9.24 146.179 9.208C146.403 9.176 146.403 9.176 146.691 9.432C147.203 9.912 147.587 10.808 147.587 11.512C147.587 12.568 146.915 13.72 146.051 14.104C145.443 14.392 145.027 14.488 144.163 14.488C143.235 14.488 142.435 14.36 141.155 14.072C140.771 13.976 140.515 13.944 140.323 13.944C139.971 13.944 139.907 14.104 139.907 14.488C139.907 14.936 140.003 15.48 140.067 15.704C140.195 15.896 140.355 15.992 140.707 15.992C140.899 15.992 141.123 15.96 141.443 15.896C142.403 15.672 143.651 15.576 144.707 15.576C146.819 15.576 149.539 16.12 150.019 18.552C150.179 19.256 150.051 20.024 149.699 20.728C149.219 21.752 148.259 22.488 147.011 22.84L146.595 22.968H141.635C138.915 22.968 136.579 22.968 136.451 22.936C134.979 22.648 133.635 20.984 133.347 19.544ZM157.262 23.064C155.214 23.064 153.87 22.424 152.878 20.472C151.918 18.584 151.47 15.512 151.63 11.864C151.758 8.984 152.206 5.528 152.686 4.024C153.262 2.136 154.734 0.855999 156.526 0.599998C157.006 0.535999 164.398 0.567999 165.102 0.664C168.558 1.016 170.734 3.768 170.734 7.256C170.734 9.4 169.774 11.512 168.014 12.792C167.79 12.92 167.662 13.048 167.662 13.048C167.662 13.048 167.79 13.144 167.95 13.24C169.07 13.88 169.902 15.512 170.094 17.496C170.318 19.512 169.678 21.4 168.558 22.168C167.822 22.68 166.574 22.968 165.23 22.968C163.982 22.968 163.086 22.744 162.254 22.168C161.774 21.848 161.358 21.336 161.454 21.208C162.222 20.088 162.67 18.232 162.51 16.76C162.51 16.408 162.446 16.088 162.446 16.024C162.414 15.928 162.478 15.864 162.606 15.704C162.99 15.256 163.022 15.096 162.702 15C162.286 14.904 162.318 14.808 162.318 16.216C162.318 17.976 162.158 18.936 161.774 20.024C161.23 21.368 160.334 22.776 158.798 22.968C158.414 23.032 157.838 23.064 157.262 23.064ZM162.318 7.352V9.176H162.542C162.894 9.208 163.118 9.176 163.47 9.016C163.726 8.888 163.822 8.824 163.95 8.632C164.174 8.28 164.206 8.056 164.142 7.608C164.046 7.032 163.758 6.552 163.342 6.104C162.99 5.752 162.446 5.4 162.382 5.464C162.35 5.496 162.318 6.328 162.318 7.352ZM179.86 9.304C179.668 9.368 179.412 9.592 179.412 9.752C179.412 9.912 179.636 10.04 179.956 10.072C180.18 10.104 180.18 10.104 180.372 10.488C180.916 11.48 181.524 12.056 182.516 12.344C182.932 12.504 183.348 12.536 184.564 12.472C186.42 12.472 188.084 14.104 188.564 15.832C188.98 17.304 188.66 19.032 187.668 20.344C186.676 21.688 185.332 22.456 183.316 22.872C182.996 22.936 182.324 22.968 178.996 22.968C176.852 22.968 174.964 22.968 174.804 22.936C173.684 22.744 172.82 21.912 172.468 20.632C172.308 20.152 172.34 18.968 172.468 18.392C172.884 16.92 173.812 15.736 174.996 15.128C175.124 15.064 175.316 14.968 175.38 14.968C175.444 14.968 175.764 15.096 176.116 15.288C177.204 15.8 178.452 16.152 179.572 16.248C180.052 16.28 180.148 16.376 180.212 16.632C180.308 17.272 180.724 17.496 181.3 17.304C181.716 17.144 181.844 16.984 181.844 16.632C181.844 16.152 181.684 16.056 180.82 16.056C177.748 16.056 174.708 14.776 172.948 12.184C170.804 8.952 171.7 5.144 175.124 2.648C177.3 1.08 180.084 0.344 182.836 0.631998C185.46 0.887999 187.444 2.488 188.244 4.856C188.596 5.848 188.756 7.48 188.596 8.28C188.148 10.488 186.068 12.28 183.796 12.28C182.708 12.28 181.908 11.96 181.204 11.288C180.788 10.84 180.436 10.264 180.308 9.624C180.212 9.272 180.18 9.24 179.86 9.304Z" fill="black"/>
          </svg>

        </div>
        <div class="nav">
          <a href="#" @click.prevent="collection.scrollIntoView({ behavior: 'smooth' })" class="text-16 text-dark text-nunito">About balls</a>
          <a href="#" @click.prevent="ballsmap.scrollIntoView({ behavior: 'smooth' })" class="text-16 text-dark">Ballsmap</a>
<!--          <a href="#" @click.prevent="team.scrollIntoView({ behavior: 'smooth' })" class="text-16 text-dark">Team</a>-->
          <a href="#" @click.prevent="faq.scrollIntoView({ behavior: 'smooth' })" class="text-16 text-dark">FAQ</a>
          <a href="#" @click.prevent="social.scrollIntoView({ behavior: 'smooth' })" class="text-16 text-dark">Social</a>
        </div>
        <q-space/>
        <div class="social justify-between">
          <a href="#">
            <img src="~assets/ds.png" alt="">

          </a>
          <a href="#">
            <img src="~assets/tw.png" alt="">
          </a>
<!--          <a href="#" class="btn outline small">Connect wallet</a>-->

        </div>
        <div class="menu-toggle" @click="menuVisible=true">
          <q-icon name="menu" color="white" size="20px"/>
        </div>
      </header>
      <div class="container">
        <div class="text-center mb-40">
          <p class="big-title ">bitballers</p>
        </div>
        <div class="row q-col-gutter-lg">
          <div class="col-12 col-md-6">
            <div class="card w-padding  ">
              <p class="text-24 q-mb-xl">     Lorem ipsum dolor sit amet, consectetur adipiscing elit. A congue lorem suspendisse morbi
                nam a est dolor. Vestibulum erat sollicitudin laoreet rhoncus dictums</p>
              <a href="#" class="btn">Buy now</a>
          </div>
          </div>
          <div class="col-12 col-md-6">
            <q-img src="~assets/top-img.png"/>
          </div>
        </div>

      </div>
      <div class="container">

        <div class="row q-col-gutter-lg">
          <div class="col-12 ">
            <div class="card w-padding  ">
              <p class="text-24 q-mb-xl">     Lorem ipsum dolor sit amet, consectetur adipiscing elit. A congue lorem suspendisse morbi
                nam a est dolor. Vestibulum erat sollicitudin laoreet rhoncus dictums</p>
              <q-input outlined type="textarea" class="q-mb-lg" v-model="base64"/>
              <p v-if="decodedMessage" class="q-mt-lg">{{decodedMessage}}</p>
              <a href="#" @click.prevent="decode" class="btn">Decode</a>
            </div>
          </div>

        </div>

      </div>
<!--      <div class="top-blur"></div>-->
    </section>
    <section id='collection' ref="collection" class="section-green">
      <div class="container">
        <div class="text-center mb-40">
        <p class="title collection  text-center">ABOUT balls</p>
        </div>
        <p class="text-28 subtitle text-center ">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut eget sed egestas purus, ultricies cursus tristique at. In cras id pharetra scelerisque. Ullamcorper.</p>
        <Splide :options="collectionSliderOptions" aria-label="auctions" class="slider-w-padding w-transform">
          <SplideSlide v-for="(i,index) in 3" :key="i">
            <div class="card w-shadow">
              <img :src="`slider/slider${i}.png`" alt="">
            </div>
          </SplideSlide>
        </Splide>
      </div>
    </section>

<!--    <section class="section-blue">-->
<!--      <div class="text-center mb-40">-->
<!--      <p class="title rare-collection  text-center">rare collection</p>-->
<!--      </div>-->
<!--      <Splide :options="rareCollectionSliderOptions" aria-label="auctions" class="slider-w-padding ">-->
<!--        <SplideSlide v-for="(i,index) in 6" :key="i">-->
<!--          <div class="big-card">-->
<!--            <div class="image">-->
<!--              <img src="~assets/tt.png" alt="">-->
<!--            </div>-->
<!--            <div class="flex column items-start">-->
<!--              <p class="text-16 text-pink text-weight-bolder no-margin">81% Chance drop</p>-->
<!--              <p class="text-48">THE Optimus PINUS</p>-->
<!--              <p class="text-16 text-white no-margin">Current bid:</p>-->
<!--              <p class="text-48 ">25 ETH</p>-->
<!--              <q-space/>-->
<!--              <a href="#" class="btn">BUY NOW</a>-->
<!--            </div>-->
<!--          </div>-->
<!--        </SplideSlide>-->
<!--      </Splide>-->

<!--    </section>-->
    <section id='ballsmap' ref="ballsmap" class="section-pink">
      <div class="text-center mb-40">
        <p class="title   text-center">ballsMAP</p>
<!--        <Splide :options="roadmapSliderOptions" aria-label="auctions" class="slider-w-padding ">-->
<!--          <SplideSlide v-for="(i,index) in 6" :key="i">-->
<!--            <div class="roadmap-card">-->
<!--              <div class="roadmap-card__line"></div>-->
<!--              <div class="flex items-center q-mb-lg">-->
<!--                <svg class="q-mr-md" width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">-->
<!--                  <rect width="24" height="24" rx="6" fill="white"/>-->
<!--                  <path d="M7 12.1428L10.5714 15.7142L17 9.28564" stroke="#003773" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"/>-->
<!--                </svg>-->
<!--                <p class="no-margin text-16 text-white text-weight-bolder ">Q4 2021</p>-->
<!--              </div>-->
<!--              <p class="text-52 q-mb-lg text-left">concept and design</p>-->
<!--              <p class="text-16 text-white text-left">-->
<!--                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Tempus aliquet etiam ullamcorper et euismod nunc. Nunc purus amet convallis risus. Nibh magna ornare elit, rutrum scelerisque ornare diam leo, lacinia. Convallis auctor faucibus blandit pellentesque vel aliquam dui ante.-->
<!--              </p>-->

<!--            </div>-->
<!--          </SplideSlide>-->
<!--        </Splide>-->


      </div>
      <div class="roadmap-container">
        <div class="row q-col-gutter-xl">
          <div class="col-12 col-md-6 rm" v-for="i in 4" :key="i">
            <div class="roadmap-card">
              <div class="roadmap-card__line"></div>
              <div class="flex items-center q-mb-lg">
                <svg class="q-mr-md" width="21" height="21" viewBox="0 0 21 21" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <rect x="0.16217" y="0.168945" width="20.2736" height="20.2736" rx="5.06841" fill="black"/>
                  <path d="M6.07532 10.4264L9.09223 13.4434L14.5227 8.01291" stroke="white" stroke-width="2.53421" stroke-linecap="round" stroke-linejoin="round"/>
                </svg>

                <p class="no-margin text-16 text-dark text-weight-bolder ">Q4 2021</p>
              </div>
              <p class="text-52 q-mb-lg text-left">concept and design</p>
              <p class="text-16 text-dark text-left">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Tempus aliquet etiam ullamcorper et euismod nunc. Nunc purus amet convallis risus. Nibh magna ornare elit, rutrum scelerisque ornare diam leo, lacinia. Convallis auctor faucibus blandit pellentesque vel aliquam dui ante.
              </p>

            </div>
          </div>

        </div>
      </div>

    </section>
<!--    <section id='team' ref="team" class="section-pink-next">-->
<!--      <div class="text-center mb-40">-->
<!--        <p class="title team  text-center">team</p>-->
<!--        <div class="team-grid">-->
<!--          <div class="team-card">-->
<!--            <div class="card pink mb-40">-->
<!--              <img src="~assets/t1.png" alt="">-->
<!--            </div>-->
<!--            <p class="text-16 text-accent text-weight-bolder">Art director</p>-->
<!--            <p class="text-52 text-white text-center">aibulat</p>-->
<!--            <p class="text-16 text-accent text-center text-weight-regular">The one man team managing our marketing studio</p>-->
<!--            <div class="social justify-center">-->
<!--              <a href="#">-->
<!--                <img src="~assets/ds.png" alt="">-->

<!--              </a>-->
<!--              <a href="#">-->
<!--                <img src="~assets/tw.png" alt="">-->
<!--              </a>-->
<!--            </div>-->
<!--          </div>-->
<!--          <div class="team-card">-->
<!--            <div class="card blue mb-40">-->
<!--              <img src="~assets/t2.png" alt="">-->
<!--            </div>-->
<!--            <p class="text-16 text-blue text-weight-bolder">Art director</p>-->
<!--            <p class="text-52 blue text-center">daniel</p>-->
<!--            <p class="text-16 text-blue text-center text-weight-regular">The one man team managing our marketing studio</p>-->
<!--            <div class="social justify-center">-->
<!--              <a href="#">-->
<!--                <img src="~assets/ds-b.png" alt="">-->

<!--              </a>-->
<!--              <a href="#">-->
<!--                <img src="~assets/tw-b.png" alt="">-->
<!--              </a>-->
<!--            </div>-->
<!--          </div>-->
<!--          <div class="team-card">-->
<!--            <div class="card green mb-40">-->
<!--              <img src="~assets/t3.png" alt="">-->
<!--            </div>-->
<!--            <p class="text-16 text-green text-weight-bolder">Art director</p>-->
<!--            <p class="text-52 green text-center">aibulat</p>-->
<!--            <p class="text-16 text-green text-center text-weight-regular">The one man team managing our marketing studio</p>-->
<!--            <div class="social justify-center">-->
<!--              <a href="#">-->
<!--                <img src="~assets/ds-g.png" alt="">-->

<!--              </a>-->
<!--              <a href="#">-->
<!--                <img src="~assets/tw-g.png" alt="">-->
<!--              </a>-->
<!--            </div>-->
<!--          </div>-->

<!--        </div>-->
<!--      </div>-->


<!--    </section>-->
    <section id='faq' ref="faq" class="section-green w-bg">
      <div class="container">
        <div class="text-center mb-40">
          <p class="title  text-center">FAQ</p>
        </div>
        <q-list class="faq-list">
          <q-expansion-item :label="item.title"
                            group="faq"
                            header-class="text-32 q-py-md"
                            v-for="(item,index) in faqs" :key="index"

          >
            <div class="faq-list-text text-weight-medium">{{item.text}}</div>
          </q-expansion-item>
        </q-list>
      </div>
    </section>
    <section id='social' ref="social" class="section-blue">
      <div class="text-center mb-40">
        <p class="title    text-center">unfollow us</p>
      </div>
      <p class="text-28 subtitle text-center">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut eget sed egestas purus, ultricies cursus tristique at. In cras id pharetra scelerisque. Ullamcorper.
      </p>
      <div class="social justify-center">
        <a href="#">
          <img src="~assets/ds-b-b.png" alt="">

        </a>
        <a href="#">
          <img src="~assets/tw-b-b.png" alt="">
        </a>
      </div>
      <img src="~assets/cir-b.png" class="decor cir-b" alt="">
<!--      <img src="~assets/cir-s.png" class="decor cir-s" alt="">-->
      <img src="~assets/face.png" class="decor face" alt="">
    </section>
<!--    <section class="bottom">-->
<!--      <div class="container">-->
<!--        <div class="header">-->
<!--          <div class="logo">-->
<!--            <svg width="165" height="24" viewBox="0 0 165 24" fill="none" xmlns="http://www.w3.org/2000/svg">-->
<!--              <path d="M6.048 23.064C6.624 23.064 7.2 23.032 7.584 22.968C8.32 22.872 8.576 22.744 9.12 22.232C10.88 20.568 11.104 18.136 11.104 15.832V14.168H12.128C12.736 14.168 13.376 14.136 13.568 14.104C16.48 13.656 18.624 11.736 19.36 8.92C19.52 8.248 19.584 6.872 19.456 6.104C18.912 3.064 16.928 0.983999 13.856 0.664C13.184 0.599998 5.792 0.535999 5.312 0.599998C3.52 0.855999 2.048 2.168 1.472 4.056C0.992 5.528 0.544 8.984 0.416 11.864C0.256 15.512 0.704 18.584 1.632 20.472C2.656 22.456 4 23.064 6.048 23.064ZM11.104 7.352C11.104 6.328 11.136 5.496 11.168 5.496C11.232 5.4 11.776 5.752 12.128 6.104C12.544 6.552 12.832 7.064 12.896 7.608C12.992 8.056 12.96 8.312 12.736 8.632C12.608 8.824 12.512 8.92 12.256 9.016C11.904 9.208 11.68 9.24 11.328 9.208L11.072 9.176L11.104 7.352ZM20.4295 19.544C20.7175 20.984 22.0615 22.648 23.5335 22.936C23.6615 22.968 25.9975 22.968 28.7175 22.968H33.6775L34.0935 22.84C35.3415 22.488 36.3015 21.752 36.7815 20.728C37.1335 20.024 37.2615 19.256 37.1015 18.552C36.6215 16.12 33.9015 15.576 31.7895 15.576C30.7335 15.576 29.4855 15.672 28.5255 15.896C28.2055 15.96 27.9815 15.992 27.7895 15.992C27.4375 15.992 27.2775 15.896 27.1495 15.704C27.0855 15.48 26.9895 14.936 26.9895 14.488C26.9895 14.104 27.0535 13.944 27.4055 13.944C27.5975 13.944 27.8535 13.976 28.2375 14.072C29.5175 14.36 30.3175 14.488 31.2455 14.488C32.1095 14.488 32.5255 14.392 33.1335 14.104C33.9975 13.72 34.6695 12.568 34.6695 11.512C34.6695 10.808 34.2855 9.912 33.7735 9.432C33.4855 9.176 33.4855 9.176 33.2615 9.208C33.0055 9.24 30.0295 9.24 29.7735 9.208C29.6135 9.176 29.3575 9.24 28.6535 9.432C27.9815 9.624 27.6935 9.72 27.5015 9.688C27.2135 9.688 27.2135 9.688 27.2135 9.496C27.1815 9.336 27.2135 9.272 27.3415 9.144C27.5335 8.984 27.7255 8.92 28.2055 8.92C28.5255 8.92 29.0055 8.952 29.7095 9.016C31.4695 9.144 31.9175 9.144 32.8775 9.08C35.3415 8.856 37.5175 7.832 37.5175 5.048C37.5175 2.776 36.4615 1.336 34.3175 0.759998L33.7735 0.599998H29.7095C25.6775 0.599998 25.6775 0.599998 25.1015 0.727999C22.9575 1.208 21.5815 2.616 20.8455 4.6C19.8855 7.224 19.5655 11.736 20.0135 16.568C20.1415 17.912 20.3015 19.064 20.4295 19.544ZM41.2083 22.808C41.3683 22.872 41.7203 22.936 41.9763 22.968C42.7123 23.032 42.8403 23.032 43.3523 22.968C44.2803 22.872 44.3443 22.84 44.7923 22.36C45.7523 21.4 46.3603 19.608 46.5523 18.232L46.6163 17.816L46.2643 17.112C46.0723 16.728 45.8163 16.152 45.6883 15.864C45.3043 15 44.5683 12.568 44.6323 12.344C44.6643 12.216 44.6643 12.248 44.9203 13.08C45.7203 15.8 47.4803 19.576 49.5923 21.592C50.6483 22.648 51.0963 22.904 52.1843 22.968C52.8563 23.032 53.6883 22.968 54.1683 22.84C55.3843 22.392 56.1843 20.088 56.4083 18.968L56.5363 18.264L56.5683 11.192C56.6323 3.448 56.6323 3.928 56.3123 3.032C55.7043 1.368 54.3603 0.664 52.6963 0.664C51.3203 0.664 50.4883 1.144 49.6883 2.328C49.1443 3.064 48.7603 3.928 48.6323 4.664C48.5683 4.92 48.6003 4.952 48.9203 5.496C49.5283 6.52 50.4563 8.664 50.4243 8.952C50.4243 9.048 50.3923 8.984 50.3283 8.792C49.5603 6.456 46.7763 2.392 44.7603 1.176C44.0563 0.727999 42.9043 0.535999 41.9443 0.695999C40.3443 0.952 39.0963 2.808 38.8723 4.344C38.8403 4.536 38.7763 4.856 38.7122 5.08C38.6163 5.592 38.5203 6.424 38.4243 7.16C37.6242 14.616 38.2003 19.992 39.9603 21.976C40.2483 22.264 40.8243 22.68 41.2083 22.808ZM63.6188 0.631998C59.1708 0.823999 58.5308 4.248 57.9868 7.8C57.0907 13.944 57.6348 18.84 59.4908 21.24C60.0988 22.072 61.0908 22.68 62.2428 22.936C62.5308 23 62.9148 23 64.0348 23C66.1148 22.968 66.4028 22.872 67.2668 22.072C68.1308 21.24 68.7388 20.184 69.0908 18.808L69.2188 18.232L69.2508 11.96C69.2828 8.536 69.3148 5.336 69.3148 4.856C69.3148 4.056 69.3148 4.024 69.1548 3.544C68.8988 2.936 68.7068 2.584 68.3228 2.168C67.2988 1.08 65.6667 0.535999 63.6188 0.631998ZM71.3143 19.96C71.8903 21.656 72.7863 22.744 73.7463 23C74.0983 23.096 75.7623 23.064 76.4023 22.968C77.9703 22.744 80.5303 21.912 81.0743 20.216C81.2663 19.704 81.2983 19.32 81.2983 18.456C81.2983 16.984 80.9463 15.672 80.4343 14.328C80.4343 14.296 80.6583 14.264 80.8823 14.264C81.1063 14.264 81.2983 14.264 81.2983 14.296C81.2983 14.296 81.2343 14.52 81.1703 14.744L81.0423 15.192L81.2023 15.736C81.4583 16.632 81.5863 17.24 81.5863 18.232C81.6503 19.64 81.4263 20.568 80.8823 21.176L80.6583 21.464L80.8183 21.656C81.0743 22.072 81.7783 22.52 82.5143 22.776C82.9943 22.936 83.5703 23 84.9143 23C85.9383 22.968 86.2583 22.968 86.5463 22.872C88.5303 22.328 89.4903 20.6 89.6823 18.616C89.7783 17.88 89.7143 16.536 89.5863 15.768C89.3623 14.648 89.3623 14.328 89.3943 13.432C89.3943 12.76 89.4583 12.408 89.5863 11.8C89.8743 10.424 89.9383 10.008 90.0023 9.432C90.0983 8.696 90.0983 6.584 90.0023 5.944C89.5543 3.032 88.4663 0.599998 85.1703 0.599998C83.7943 0.599998 82.4503 1.144 81.4583 2.136C81.1383 2.424 81.0743 2.52 81.1063 2.616C81.1383 2.68 81.2023 2.968 81.2663 3.224C81.3303 3.48 81.4263 3.992 81.4903 4.344C81.5543 5.176 81.5543 7.96 81.4583 8.888C81.3943 9.72 81.2023 10.776 81.1383 10.84C81.1383 10.872 81.1703 11.096 81.2663 11.352L81.4583 11.832L81.0743 11.864C80.8503 11.896 80.6263 11.928 80.5623 11.928C80.4343 11.96 80.4343 11.96 80.4983 11.864C80.7223 11.64 80.9143 11.096 81.0103 10.616C81.2023 9.304 81.3623 6.584 81.2663 5.208C81.1703 3.896 81.0743 3.192 80.8823 2.808C80.3703 1.72 79.2503 1.016 77.5543 0.695999C77.1063 0.631998 76.7543 0.631998 75.7303 0.631998C73.6503 0.631998 72.3383 0.855999 71.3463 2.904C70.8663 3.896 70.6743 4.792 70.4823 7.032C70.3543 8.408 70.3543 12.696 70.4503 14.104C70.6743 17.176 70.8983 18.616 71.3143 19.96ZM91.492 19.544C91.78 20.984 93.124 22.648 94.596 22.936C94.724 22.968 97.06 22.968 99.78 22.968H104.74L105.156 22.84C106.404 22.488 107.364 21.752 107.844 20.728C108.196 20.024 108.324 19.256 108.164 18.552C107.684 16.12 104.964 15.576 102.852 15.576C101.796 15.576 100.548 15.672 99.588 15.896C99.268 15.96 99.044 15.992 98.852 15.992C98.5 15.992 98.34 15.896 98.212 15.704C98.148 15.48 98.052 14.936 98.052 14.488C98.052 14.104 98.116 13.944 98.468 13.944C98.66 13.944 98.916 13.976 99.3 14.072C100.58 14.36 101.38 14.488 102.308 14.488C103.172 14.488 103.588 14.392 104.196 14.104C105.06 13.72 105.732 12.568 105.732 11.512C105.732 10.808 105.348 9.912 104.836 9.432C104.548 9.176 104.548 9.176 104.324 9.208C104.068 9.24 101.092 9.24 100.836 9.208C100.676 9.176 100.42 9.24 99.716 9.432C99.044 9.624 98.756 9.72 98.564 9.688C98.276 9.688 98.276 9.688 98.276 9.496C98.244 9.336 98.276 9.272 98.404 9.144C98.596 8.984 98.788 8.92 99.268 8.92C99.588 8.92 100.068 8.952 100.772 9.016C102.532 9.144 102.98 9.144 103.94 9.08C106.404 8.856 108.58 7.832 108.58 5.048C108.58 2.776 107.524 1.336 105.38 0.759998L104.836 0.599998H100.772C96.74 0.599998 96.74 0.599998 96.164 0.727999C94.02 1.208 92.644 2.616 91.908 4.6C90.948 7.224 90.628 11.736 91.076 16.568C91.204 17.912 91.364 19.064 91.492 19.544ZM114.069 22.936C115.285 23.096 116.949 22.84 117.909 22.264C118.325 22.008 119.061 21.336 119.381 20.824C120.213 19.64 120.661 18.136 120.725 16.312C120.757 14.904 120.629 13.912 120.245 12.6L120.117 12.248L119.829 12.12C119.637 12.056 119.509 11.992 119.509 11.992C119.509 11.96 119.893 11.992 120.341 11.992L121.173 12.024L120.789 12.152C120.309 12.28 120.309 12.216 120.597 13.144C120.917 14.328 121.013 14.84 121.045 16.088C121.045 18.104 120.597 20.088 119.349 21.72C119.253 21.848 119.189 21.976 119.189 21.976C119.189 22.072 119.797 22.456 120.181 22.648C120.725 22.872 121.141 22.968 121.877 22.968C125.045 22.968 126.389 20.024 127.093 17.304C128.181 12.888 127.605 7.48 125.717 4.536C123.925 1.784 120.885 0.439999 116.789 0.599998C115.797 0.664 115.093 0.759998 114.485 0.952C109.941 2.488 108.757 8.184 108.757 12.44C108.757 14.968 109.013 17.016 109.493 18.52C110.325 21.048 111.989 22.648 114.069 22.936ZM119.605 9.368C119.669 8.344 119.797 7.832 120.021 7.832C120.181 7.832 120.565 8.856 120.693 9.656C120.789 10.136 120.757 10.392 120.629 10.456C120.565 10.488 120.373 10.52 120.149 10.552C119.829 10.584 119.797 10.552 119.701 10.488C119.573 10.328 119.573 10.2 119.605 9.368ZM133.41 22.904C133.698 22.968 134.466 22.968 136.706 22.968H139.618L140.13 22.84C143.234 21.944 145.41 19.416 146.178 16.312C146.626 14.552 146.626 12.984 146.21 10.552C145.474 6.232 143.458 1.56 138.626 0.695999C138.114 0.631998 137.73 0.599998 135.17 0.599998C132.29 0.599998 132.226 0.599998 131.81 0.727999C130.082 1.24 128.962 2.616 128.546 4.76C128.482 5.08 128.45 5.848 128.418 7.864C128.322 13.144 128.45 15.768 128.962 17.88C129.474 20.184 130.914 22.488 133.41 22.904ZM137.154 7.096C138.338 7.832 139.074 11.16 139.074 12.664C139.074 13.784 139.042 13.912 138.658 14.104C138.498 14.168 138.306 14.2 137.954 14.232C137.442 14.232 137.314 14.2 137.154 14.04C137.058 13.944 137.058 13.912 137.154 13.368C137.218 13.016 137.25 12.408 137.282 11.48C137.314 9.656 137.186 8.216 136.962 7.352C136.898 7.064 136.962 7 137.154 7.096ZM154.912 9.304C155.232 9.24 155.264 9.272 155.36 9.624C155.488 10.264 155.84 10.84 156.256 11.288C156.96 11.96 157.76 12.28 158.848 12.28C161.12 12.28 163.2 10.488 163.648 8.28C163.808 7.48 163.648 5.848 163.296 4.856C162.496 2.488 160.512 0.887999 157.888 0.631998C155.136 0.344 152.352 1.08 150.176 2.648C146.752 5.144 145.856 8.952 148 12.184C149.76 14.776 152.8 16.056 155.872 16.056C156.736 16.056 156.896 16.152 156.896 16.632C156.896 16.984 156.768 17.144 156.352 17.304C155.776 17.496 155.36 17.272 155.264 16.632C155.2 16.376 155.104 16.28 154.624 16.248C153.504 16.152 152.256 15.8 151.168 15.288C150.816 15.096 150.496 14.968 150.432 14.968C150.368 14.968 150.176 15.064 150.048 15.128C148.864 15.736 147.936 16.92 147.52 18.392C147.392 18.968 147.36 20.152 147.52 20.632C147.872 21.912 148.736 22.744 149.856 22.936C150.016 22.968 151.904 22.968 154.048 22.968C157.376 22.968 158.048 22.936 158.368 22.872C160.384 22.456 161.728 21.688 162.72 20.344C163.712 19.032 164.032 17.304 163.616 15.832C163.136 14.104 161.472 12.472 159.616 12.472C158.4 12.536 157.984 12.504 157.568 12.344C156.576 12.056 155.968 11.48 155.424 10.488C155.232 10.104 155.232 10.104 155.008 10.072C154.688 10.04 154.464 9.912 154.464 9.752C154.464 9.592 154.72 9.368 154.912 9.304Z" fill="#0056B2"/>-->
<!--            </svg>-->

<!--          </div>-->
<!--          <div class="nav">-->
<!--            <div class="nav">-->
<!--              <a href="#" @click.prevent="collection.scrollIntoView({ behavior: 'smooth' })" class="text-16 text-blue">Collection</a>-->
<!--              <a href="#" @click.prevent="journey.scrollIntoView({ behavior: 'smooth' })" class="text-16 text-blue">Journey</a>-->
<!--              <a href="#" @click.prevent="team.scrollIntoView({ behavior: 'smooth' })" class="text-16 text-blue">Team</a>-->
<!--              <a href="#" @click.prevent="faq.scrollIntoView({ behavior: 'smooth' })" class="text-16 text-blue">FAQ</a>-->
<!--              <a href="#" @click.prevent="social.scrollIntoView({ behavior: 'smooth' })" class="text-16 text-blue">Social</a>-->
<!--            </div>-->
<!--          </div>-->
<!--          <q-space/>-->
<!--          <div class="social justify-between">-->
<!--            <a href="#">-->
<!--              <img src="~assets/ds-b-s.png" alt="">-->

<!--            </a>-->
<!--            <a href="#">-->
<!--              <img src="~assets/tw-b-s.png" alt="">-->
<!--            </a>-->
<!--          </div>-->
<!--        </div>-->
<!--      </div>-->
<!--    </section>-->

  </q-page>
  <q-dialog persistent
            maximized
            transition-show="slide-left"
            transition-hide="slide-right" v-model="menuVisible">
    <div class="mobile-menu">
      <div class="menu-toggle" @click="menuVisible=false">
        <q-icon name="close" color="white" size="20px"/>
      </div>
      <a href="#collection" @click="menuVisible=false" class="text-52 text-white">About balls</a>
      <a href="#ballsmap" @click="menuVisible=false" class="text-52 text-white">Ballsmap</a>
<!--      <a href="#team" @click="menuVisible=false"  class="text-52 text-white">Team</a>-->
      <a href="#faq" @click="menuVisible=false" class="text-52 text-white">FAQ</a>
      <a href="#social" @click="menuVisible=false" class="text-52 text-white">Social</a>
      <div class="social justify-between">
        <a href="#">
          <q-avatar size="40px">
            <img src="~assets/ds-b-b.png" alt="">
          </q-avatar>


        </a>
        <a href="#">
          <q-avatar size="40px">
            <img src="~assets/tw-b-b.png" alt="">
          </q-avatar>

        </a>

      </div>
<!--      <div>-->
<!--        <a href="#" class="btn">Connect wallet</a>-->
<!--      </div>-->

<!--      <div class="top-blur"></div>-->
    </div>
  </q-dialog>
</template>

<script setup>
import '@splidejs/vue-splide/css'
import '@splidejs/vue-splide/css/core'
import { Splide, SplideSlide } from '@splidejs/vue-splide';
import {ref} from "vue";

const collection = ref('collection')
const ballsmap = ref('ballsmap')
const team = ref('team')
const faq = ref('faq')
const social = ref('social')
const menuVisible = ref(false)



const base64 = ref(null)
const decodedMessage = ref(null)

const collectionSliderOptions ={
  rewind: true,
  pagination:false,
  autoplay:false,
  perPage:3,
  gap:50,
  classes: {
    arrow : 'rectangle-arrow',
    prev  : 'green-prev_arrow',
    next  : 'green-next_arrow',
  },
  breakpoints: {
    1024: {
      perPage: 2,
    },
    768: {
      perPage: 1,
    },
  }
}
const rareCollectionSliderOptions ={
  rewind: false,
  pagination:false,
  autoplay:false,
  perPage:2,
  type   : 'loop',
  perMove    : 1,
  focus      : 'center',
  gap: 40,
  trimSpace  : false,
  classes: {
    arrow : 'rectangle-arrow',
    prev  : 'green-prev_arrow blue',
    next  : 'green-next_arrow blue',
  },
  breakpoints: {
    1300: {
      perPage: 2,
      focus:null
    },
    1024: {
      perPage: 1,
    },
  }
}

const roadmapSliderOptions ={
  rewind: false,
  pagination:false,
  autoplay:false,
  perPage:2.5,
  //type   : 'loop',
  perMove    : 1,
  focus      : 'center',
  gap: 40,
  trimSpace  : false,
  arrows:false,
  classes: {
    // arrow : 'rectangle-arrow',
    // prev  : 'green-prev_arrow',
    // next  : 'green-next_arrow',
  },
  breakpoints: {
    1300: {
      perPage: 1.5,
      focus:null
    },
    1024: {
      perPage: 1,
    },
  }
}

const faqs = [
  {title:'Lorem ipsum dolor sit amet, consectetur adipiscing elit.',text:'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Tempus aliquet etiam ullamcorper et euismod nunc. Nunc purus amet convallis risus. Nibh magna ornare elit, rutrum scelerisque ornare diam leo, lacinia. Convallis auctor faucibus blandit pellentesque vel aliquam dui ante.'},
  {title:'Lorem ipsum dolor sit amet, consectetur adipiscing elit.',text:'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Tempus aliquet etiam ullamcorper et euismod nunc. Nunc purus amet convallis risus. Nibh magna ornare elit, rutrum scelerisque ornare diam leo, lacinia. Convallis auctor faucibus blandit pellentesque vel aliquam dui ante.'},
  {title:'Lorem ipsum dolor sit amet, consectetur adipiscing elit.',text:'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Tempus aliquet etiam ullamcorper et euismod nunc. Nunc purus amet convallis risus. Nibh magna ornare elit, rutrum scelerisque ornare diam leo, lacinia. Convallis auctor faucibus blandit pellentesque vel aliquam dui ante.'},
  {title:'Lorem ipsum dolor sit amet, consectetur adipiscing elit.',text:'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Tempus aliquet etiam ullamcorper et euismod nunc. Nunc purus amet convallis risus. Nibh magna ornare elit, rutrum scelerisque ornare diam leo, lacinia. Convallis auctor faucibus blandit pellentesque vel aliquam dui ante.'},
  {title:'Lorem ipsum dolor sit amet, consectetur adipiscing elit.',text:'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Tempus aliquet etiam ullamcorper et euismod nunc. Nunc purus amet convallis risus. Nibh magna ornare elit, rutrum scelerisque ornare diam leo, lacinia. Convallis auctor faucibus blandit pellentesque vel aliquam dui ante.'},
]

const decode = ()=>{
  try {
    decodedMessage.value = atob(base64.value);
  } catch (e) {
    console.error(e);
    decodedMessage.value = 'Cannot decode base64';
  }
}


</script>
