<template name="component-name">
  <section class="issue">
    <div class="container">
      <div class="issue__wrap">
        <div class="issue__img-box">
          <img src="" alt="" class="issue__img" />
          <div class="block__overlay"></div>
        </div>
        <div class="issue__content-box">
          <div class="issue__content">
            <h3 class="issue__title">{{ $t("global.subscribe-date") }}</h3>
            <router-link :to="'/'" class="issue__btn">
              {{ $t("global.subscribe-now") }}
            </router-link>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style lang="scss">
@import "home-issue.scss";
</style>
