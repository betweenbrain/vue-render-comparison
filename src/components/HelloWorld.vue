<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String,
  },
  render(createElement) {
    const children = [
      createElement('h1', this.msg),
      createElement('p', {
        domProps: {
          innerHTML:
            'For a guide and recipes on how to configure / customize this project,<br> check out the <a href="https://cli.vuejs.org" target="_blank" rel="noopener">vue-cli documentation</a>.',
        },
      }),
      createElement('h3', 'Installed CLI Plugins'),
      createElement('ul', [
        createElement('li', [
          createElement('a', {
            attrs: {
              href:
                'https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-babel',
              target: '_blank',
              rel: 'noopener',
            },
          }, 'babel'),
        ]),
        createElement('li', [
          createElement('a', {
            attrs: {
              href:
                'https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-eslint',
              target: '_blank',
              rel: 'noopener',
            },
          }, 'eslint'),
        ]),
      ]),

      createElement('h3', 'Essential Links'),
      createElement('ul', [
        createElement('li', [
          createElement('a', {
            attrs: {
              href:
                'https://vuejs.org',
              target: '_blank',
              rel: 'noopener',
            },
          }, 'Core Docs'),
        ]),
        createElement('li', [
          createElement('a', {
            attrs: {
              href:
                'https://forum.vuejs.org',
              target: '_blank',
              rel: 'noopener',
            },
          }, 'Forum'),
        ]),
        createElement('li', [
          createElement('a', {
            attrs: {
              href:
                'https://chat.vuejs.org',
              target: '_blank',
              rel: 'noopener',
            },
          }, 'Community Chat'),
        ]),
        createElement('li', [
          createElement('a', {
            attrs: {
              href:
                'https://twitter.com/vuejs',
              target: '_blank',
              rel: 'noopener',
            },
          }, 'Twitter'),
        ]),
        createElement('li', [
          createElement('a', {
            attrs: {
              href:
                'https://news.vuejs.org',
              target: '_blank',
              rel: 'noopener',
            },
          }, 'News'),
        ]),
      ]),

      createElement('h3', 'Ecosystem'),
      createElement('ul', [
        createElement('li', [
          createElement('a', {
            attrs: {
              href:
                'https://router.vuejs.org',
              target: '_blank',
              rel: 'noopener',
            },
          }, 'vue-router'),
        ]),
        createElement('li', [
          createElement('a', {
            attrs: {
              href:
                'https://vuex.vuejs.org',
              target: '_blank',
              rel: 'noopener',
            },
          }, 'vuex'),
        ]),
        createElement('li', [
          createElement('a', {
            attrs: {
              href:
                'https://github.com/vuejs/vue-devtools#vue-devtools',
              target: '_blank',
              rel: 'noopener',
            },
          }, 'vue-devtools'),
        ]),
        createElement('li', [
          createElement('a', {
            attrs: {
              href:
                'https://vue-loader.vuejs.org',
              target: '_blank',
              rel: 'noopener',
            },
          }, 'vue-loader'),
        ]),
        createElement('li', [
          createElement('a', {
            attrs: {
              href:
                'https://github.com/vuejs/awesome-vue',
              target: '_blank',
              rel: 'noopener',
            },
          }, 'awesome-vue'),
        ]),
      ]),
    ];

    return createElement(
      'div',
      {
        attrs: {
          class: 'hello',
        },
      },
      children,
    );
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
