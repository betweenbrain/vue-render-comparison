<script>
import HelloWorld from './components/HelloWorld.vue';

export default {
  data() {
    return {
      total: 1000,
    };
  },
  name: 'app',
  components: {
    HelloWorld,
  },
  render(createElement) {
    const elements = [...Array(this.total)];
    const children = elements.map(() => [
      createElement('img', {
        attrs: {
          alt: 'Vue logo',
          src: './assets/logo.png',
        },
      }),
      createElement('HelloWorld', {
        attrs: {
          msg: 'Welcome to Your Vue.js App',
        },
      }),
    ]);

    return createElement(
      'div',
      {
        attrs: {
          id: 'app',
        },
      },
      children,
    );
  },
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
