<script>
  export let dark;
</script>

<div class="flex items-center flex-center gap-4">
  <button
    class={"specialBtn" +
      (dark ? "bg-[#181b34] border border-slate-50 rounded-lg px-5 py-2" : "")}
  >
    <p class="text-base sm:text-lg md:text-xl">Contact us</p>
  </button>
  <button class="specialBtnDark">
    <p class="text-base sm:text-lg md:text-xl">Get Started &rarr;</p></button
  >
</div>
