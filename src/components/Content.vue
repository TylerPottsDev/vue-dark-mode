<template>
  <div class="content">
    <h3>This is {{mode}} mode</h3>
    <div class="image-grid">
      <div class="col">
        <img src="https://images.unsplash.com/photo-1560617137-b2bbe0e08397?ixlib=rb-1.2.1&q=80&fm=jpg&crop=entropy&cs=tinysrgb&w=1200&h=600&fit=crop&ixid=eyJhcHBfaWQiOjF9" />
      </div>
      <div class="col">
        <img src="https://images.unsplash.com/photo-1561327712-2e0c75a1a6e6?ixlib=rb-1.2.1&q=80&fm=jpg&crop=entropy&cs=tinysrgb&w=1200&h=600&fit=crop&ixid=eyJhcHBfaWQiOjF9" />
      </div>
      <div class="col">
        <img src="https://images.unsplash.com/photo-1560945928-a97ecc4dcfc7?ixlib=rb-1.2.1&q=80&fm=jpg&crop=entropy&cs=tinysrgb&w=1200&h=600&fit=crop&ixid=eyJhcHBfaWQiOjF9" />
      </div>
    </div>
    <p class="para">
      Lorem ipsum, dolor sit amet consectetur adipisicing elit. Quos dolor ad voluptatem consectetur architecto tenetur iure temporibus nam commodi blanditiis expedita eligendi, recusandae, saepe qui cumque eos voluptatibus minus repudiandae excepturi laborum. Voluptatibus enim adipisci sed distinctio! Nobis nihil corrupti ex, magnam quidem minus voluptatibus, voluptate at, fugiat culpa repellat!
    </p>
  </div>
</template>

<script>
export default {
  props: ['mode']
}
</script>

<style>
.content {
  padding: 25px;
}
.content h3 {
  font-size: 28px;
  text-transform: uppercase;
  font-weight: 300;
  margin-bottom: 25px;
}
.image-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 15px;
}

.image-grid .col img {
  width: 100%;
}
.para {
  width: 100%;
  max-width: 600px;
  margin: 25px auto 0px;
}
</style>
