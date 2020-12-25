<template>
  <v-container>
    <v-row class="text-center" justify="center">
      <v-col cols="12">
        <v-img
          :src="require('../assets/logo.jpg')"
          class="my-3"
          contain
          height="200"
        />
      </v-col>

      <v-col class="mb-4">
        <h1 class="display-2 font-weight-bold mb-3">
          Merry Christmas!
        </h1>

        <p class="subheading font-weight-regular">
          I wish you a merry christmas, Alfred!
        </p>

        <br />

        <p>
          我们在一起做过许多项目……
          <br />
          你可能忘了，你是因为什么在知乎上找到我的：
          <a href="https://github.com/samzhangjy/OnlineBookstore" target="blank">
            在线书店
          </a>
          <br />
          然后我们一起做过售卖衣服的项目，也就是你弟弟的作业……
          <br />
          在那之后，我们做过一个<a href="https://github.com/AlfredDuan/Scraper" target="_blank">爬虫项目</a>，<br />
          涉及到多进程，多线程，进程锁，进程通信等等我们都没有涉及过的知识……<br />
          那次项目让我们都受益良多。
          <br />
          在之后，你进入了新单位，而我则利用上次项目的知识开发了<a href="https://github.com/BaiduSpider/BaiduSpider" target="_blank">BaiduSpider</a>。
          <br />
          直到现在，我们都在学习新知识……<br /><br /><br />
        </p>
        <p class="subheading">
          为此，我写了一首诗，用于庆祝今年的圣诞节，希望你喜欢……
        </p>
        <br /><v-divider></v-divider><br />
        <h1 class="font-weight-bold mb-3">
          Merry Christmas to Alfred Duan
        </h1>
        <p>By Sam Zhang</p>
        <i>
          Mind, hand, always on,<br />
          Error, warning we will fix,<br />
          Ruby, Python, JavaScript,<br />
          Runoob, W3C, we are always LEARNING.<br />
          Yarn, npm, pip, it's time for libs!<br />
          <br />
          Code, code, day and night, <br />
          Hyperlinks, container, and there comes the site. <br />
          Run, debug, fix, our daily life. <br />
          Internet and the Web, we are the constructors!<br />
          Search, search, Google and GitHub,<br />
          Tutorials, blogs, all the learning resources!<br />
          Make, make, we build!<br />
          ASP.NET, WinUI and ELECTRON!<br />
          So good, so nice, so inter-est-ing!<br />
        </i><br /><br /><br />
        <v-divider></v-divider><br /><br />
        <h2 class="font-weight-bold mb-3">
          最后，祝你有一个快乐的圣诞节！圣诞节快乐！！
        </h2>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
  export default {
    name: 'HelloWorld',

    data: () => ({
      ecosystem: [
        {
          text: 'vuetify-loader',
          href: 'https://github.com/vuetifyjs/vuetify-loader',
        },
        {
          text: 'github',
          href: 'https://github.com/vuetifyjs/vuetify',
        },
        {
          text: 'awesome-vuetify',
          href: 'https://github.com/vuetifyjs/awesome-vuetify',
        },
      ],
      importantLinks: [
        {
          text: 'Documentation',
          href: 'https://vuetifyjs.com',
        },
        {
          text: 'Chat',
          href: 'https://community.vuetifyjs.com',
        },
        {
          text: 'Made with Vuetify',
          href: 'https://madewithvuejs.com/vuetify',
        },
        {
          text: 'Twitter',
          href: 'https://twitter.com/vuetifyjs',
        },
        {
          text: 'Articles',
          href: 'https://medium.com/vuetify',
        },
      ],
      whatsNext: [
        {
          text: 'Explore components',
          href: 'https://vuetifyjs.com/components/api-explorer',
        },
        {
          text: 'Select a layout',
          href: 'https://vuetifyjs.com/getting-started/pre-made-layouts',
        },
        {
          text: 'Frequently Asked Questions',
          href: 'https://vuetifyjs.com/getting-started/frequently-asked-questions',
        },
      ],
    }),
  }
</script>
