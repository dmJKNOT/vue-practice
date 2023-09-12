<template >
  <!-- Sidebar-->
  <div class="border-end bg-white" id="sidebar-wrapper">
    <div class="sidebar-heading border-bottom bg-light">Content Rater</div>
    <div class="list-group list-group-flush">
      <a class="list-group-item list-group-item-action list-group-item-light p-3" href="movies">Movies</a>
      <a class="list-group-item list-group-item-action list-group-item-light p-3" href="tv">TV</a>
      <a class="list-group-item list-group-item-action list-group-item-light p-3" href="videoGames">Video Games</a>
      <a class="list-group-item list-group-item-action list-group-item-light p-3" href="podcasts">Podcasts</a>
      <a class="list-group-item list-group-item-action list-group-item-light p-3" href="books">Books</a>
    </div>
  </div>
</template>

<script>
export default {
  name: "ContentRaterSidebar"
}
</script>

