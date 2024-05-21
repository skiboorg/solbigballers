<script setup>
const faqs = [
  {title:'Lorem ipsum dolor sit amet, consectetur adipiscing elit.',text:'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Tempus aliquet etiam ullamcorper et euismod nunc. Nunc purus amet convallis risus. Nibh magna ornare elit, rutrum scelerisque ornare diam leo, lacinia. Convallis auctor faucibus blandit pellentesque vel aliquam dui ante.'},
  {title:'Lorem ipsum dolor sit amet, consectetur adipiscing elit.',text:'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Tempus aliquet etiam ullamcorper et euismod nunc. Nunc purus amet convallis risus. Nibh magna ornare elit, rutrum scelerisque ornare diam leo, lacinia. Convallis auctor faucibus blandit pellentesque vel aliquam dui ante.'},
  {title:'Lorem ipsum dolor sit amet, consectetur adipiscing elit.',text:'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Tempus aliquet etiam ullamcorper et euismod nunc. Nunc purus amet convallis risus. Nibh magna ornare elit, rutrum scelerisque ornare diam leo, lacinia. Convallis auctor faucibus blandit pellentesque vel aliquam dui ante.'},
  {title:'Lorem ipsum dolor sit amet, consectetur adipiscing elit.',text:'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Tempus aliquet etiam ullamcorper et euismod nunc. Nunc purus amet convallis risus. Nibh magna ornare elit, rutrum scelerisque ornare diam leo, lacinia. Convallis auctor faucibus blandit pellentesque vel aliquam dui ante.'},
  {title:'Lorem ipsum dolor sit amet, consectetur adipiscing elit.',text:'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Tempus aliquet etiam ullamcorper et euismod nunc. Nunc purus amet convallis risus. Nibh magna ornare elit, rutrum scelerisque ornare diam leo, lacinia. Convallis auctor faucibus blandit pellentesque vel aliquam dui ante.'},
]

const rm = [
  {title:'Concept',text:'Augue aliquam bibendum aliquet tellus. Amet velit vitae urna purus dictumst pellentesque tempus lectus.'},
  {title:'Concept',text:'Augue aliquam bibendum aliquet tellus. Amet velit vitae urna purus dictumst pellentesque tempus lectus.'},
  {title:'Concept',text:'Augue aliquam bibendum aliquet tellus. Amet velit vitae urna purus dictumst pellentesque tempus lectus.'},
  {title:'Concept',text:'Augue aliquam bibendum aliquet tellus. Amet velit vitae urna purus dictumst pellentesque tempus lectus.'},
]
</script>

<template>
<q-page class="wolf">

  <div class="container-wolf">
    <div class="flex items-center justify-center mb-90">
      <a href="#" class="t-24 q-mr-lg">How it works</a>
      <a href="#" class="t-24 q-mr-lg">Why Us</a>
      <a href="#" class="t-24">Roadmap</a>
    </div>
    <p class="text-chido text-center t-186">GET YOUR OWN</p>
    <div class="flex items-center justify-center mb-150">
      <a href="#" class="white-btn">Forward</a>
    </div>

    <q-img src="~assets/wolf/wolf.png"  class="mb-220" />
  </div>
  <div class="container mb-220">
    <p class="t-96 text-chido text-center">FAQ</p>
    <q-list class="wolf-faq-list">
      <q-expansion-item :label="item.title"
                        group="faq"
                        header-class="faq-text-32   q-py-md"
                        v-for="(item,index) in faqs" :key="index"

      >
        <div class="wolf-faq-list-text text-weight-medium">{{item.text}}</div>
      </q-expansion-item>
    </q-list>
  </div>
  <div class="container-wolf">
    <p class="t-96 text-chido text-center  ">ROADMAP</p>

    <div class="wolf-roadmap">
      <svg class="line mb-80" width="1280" height="2" viewBox="0 0 1280 2" fill="none" xmlns="http://www.w3.org/2000/svg">
        <line y1="1.26782" x2="1280" y2="1.26782" stroke="white" stroke-dasharray="12 12"/>
      </svg>
    <div class="wolf-roadmap-grid">
      <div class="wolf-roadmap-grid-item" v-for="i in rm">
        <p class="text-chido t-32">{{i.title}}</p>
        <p>{{i.text}}</p>
      </div>
    </div>
    </div>
  </div>

</q-page>
</template>

<style scoped>

</style>
