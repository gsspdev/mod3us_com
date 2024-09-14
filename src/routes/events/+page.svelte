<script lang="ts">
  const events = [
    { date: 'Dec 31, 2023', venue: 'Underground Club Berlin' },
    { date: 'Jan 15, 2024', venue: 'Techno Fest London' },
    // Add more events
  ];
</script>

<div class="min-h-screen bg-dark-bg text-white font-mono p-8">
  <h2 class="text-3xl mb-6">Events</h2>
  <ul class="space-y-4">
    {#each events as event}
      <li>
        <span class="text-neon-pink">{event.date}</span> - {event.venue}
      </li>
    {/each}
  </ul>
</div>

