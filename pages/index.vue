<template>
  <div>
    <AppHeader />
    <hr>
    <div class="overviewSection">
      <div class="overviewHeading">Overview</div>
      <OverView />
    </div> 
    <div class="walletAssetsSection">
      <div class="assetHeading">Assets in Wallet</div>
      <WalletAssets />
    </div>
  </div>
</template>

<script>
import AppHeader from '../components/AppHeader.vue'
import OverView from '../components/OverView.vue'
import WalletAssets from '../components/WalletAssets.vue'

export default {
  name: 'IndexPage',
  component: {
    AppHeader,
    OverView,
    WalletAssets
  }
}
</script>

<style>
* {
  box-sizing: border-box;
  padding: 0;
  margin: 0;
}

.overviewSection{
  margin: 3rem 8rem;
}

.overviewHeading{
  color: black;
  font-size: 1.5rem;
  font-weight: 700;
}

.walletAssetsSection{
  margin: 0 8rem;
}

.assetHeading{
  color: gray;
  font-size: 1rem;
  font-weight: 600;
}
</style>