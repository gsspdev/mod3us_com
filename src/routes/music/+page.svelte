<script lang="ts">
  const tracks = [
    { title: 'Deep Synth Waves', link: 'https://soundcloud.com/yourtrack1' },
    { title: 'Cyber Pulse', link: 'https://soundcloud.com/yourtrack2' },
    // Add more tracks
  ];
</script>

<div class="min-h-screen bg-dark-bg text-white font-mono p-8">
  <h2 class="text-3xl mb-6">Music</h2>
  <ul class="space-y-4">
    {#each tracks as track}
      <li>
        <a href="{track.link}" target="_blank" class="hover:text-neon-green">
          {track.title}
        </a>
      </li>
    {/each}
  </ul>
</div>

