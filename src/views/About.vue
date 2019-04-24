<template>
  <div class="about">
    <h1>This is an about page</h1>
    <p v-html="content" />
  </div>
</template>

<script>
export default {
  data() {
    return {
      content: `
      <pre style="max-width:100%;overflow-x:auto;"><code class="javascript hljs" codemark="1"><span class="hljs-built_in">console</span>.log(<span class="hljs-string">'Hello js'</span>)</code></pre><pre style="max-width:100%;overflow-x:auto;"><code class="java hljs" codemark="1">System.out.println(<span class="hljs-string">"Hello"</span>)</code></pre><p align="center" style="text-align: center;"><img style="max-width: 100%; width: 729px; height: 577.391px;" src="https://refactoring.guru/images/refactoring/content/refactoring.png" class=""><br></p><p><br></p><pre style="max-width:100%;overflow-x:auto;"><code class="css hljs" codemark="1"><span class="hljs-selector-class">.page-enter-active</span>, <span class="hljs-selector-class">.page-leave-active</span> {
  <span class="hljs-attribute">transition</span>: opacity .<span class="hljs-number">5s</span>;
}
<span class="hljs-selector-class">.page-enter</span>, <span class="hljs-selector-class">.page-leave-to</span> {
  <span class="hljs-attribute">opacity</span>: <span class="hljs-number">0</span>;
}</code></pre><p><br></p><pre style="max-width:100%;overflow-x:auto;"><code class="java hljs" codemark="1">System.out.println(<span class="hljs-string">"Hello"</span>)</code></pre><p><img style="max-width: 100%; width: 729px; height: 577.391px;" src="https://refactoring.guru/images/refactoring/content/refactoring.png" class=""><br></p><p><br></p>
      `
    }
  }
}
</script>
