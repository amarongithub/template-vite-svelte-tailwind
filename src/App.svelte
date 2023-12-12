<script>
  let count = 0;

  function increment() {
    count++;
  }
</script>

<div class="flex h-screen flex-col items-center justify-center">
  <p class="text-2xl font-bold">{count}</p>
  <button
    class="mt-4 rounded-lg bg-purple-900 px-4 py-2 text-white"
    on:click={increment}>Click</button
  >
</div>
