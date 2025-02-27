<script lang="ts">
  import Heart from 'svelte-material-icons/HeartOutline.svelte'
</script>

<article class="mx-2 mb-4 px-6 py-3 rounded dark:bg-gray-900/50 relative">
  <p>The Dactyl keyboard is a customizable ergonomic keyboard. Unlike typical keyboards, it contours to the shape of your hand. This tool allows you to configure almost every aspect of the keyboard for maximum comfort and flexibility.</p>
  <p>I recommend you begin with the default preset (<span>Default</span>) and consider the <span>5-Key</span> thumb cluster. They are, in my opinion, a good starting point.</p>
  <p>Before 3D printing your first Dactyl keyboard case, I recommend you:</p>
  <ul class="list-disc pl-4">
    <li>Copy down the current site URL so you can revisit or share your design. The URL is unique to the keyboard you've configured.</li>
    <li>If using PCBs, ensure you have enough clearance between the switches and the ground.</li>
    <li>Find where to buy the parts necessary for the keyboard (switches, keycaps, diodes, wires, microcontrollers, cables, and soldering equipment).</li>
    <li>Take a final review of the model and adjust <span>Height Offset</span> to add clearance under the switches and <span>Wall Thickness</span> for a sturdy case.</li>
    <li>Find a suitable keyboard layout using the <a href="https://config.qmk.fm/#/handwired/dactyl_manuform/5x6/LAYOUT_5x6">QMK Configurator</a> and become familiar with <a href="https://docs.qmk.fm/#/configurator_step_by_step">compiling and flashing</a>.
  </ul>
  <p>There's a lot to making your own keyboard, but it's a fun process. I promise! <Heart class="inline relative top-[-1px] text-teal-500" size="20px" /> </p>
</article>
<style lang="postcss">
 p, ul { @apply mb-1; }
 a { @apply underline text-teal-500; }
 span { @apply rounded px-1 bg-[#99F0DC]/50 dark:bg-teal-500/30; }
</style>
