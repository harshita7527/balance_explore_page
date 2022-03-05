<template>
  <div class="overview">
    <div class="netWorth usd">
      <div class="netWorthFigures">
        <div class="heading">Net Worth in USD</div>
        <div class="netWorthFig">$6.00</div>
      </div>
    </div>

    <div class="netWorth eth">
      <div class="netWorthFigures">
        <div class="heading">Net Worth in ETH</div>
        <div class="netWorthFig">0.002192</div>
      </div>
    </div>

    <div class="netWorth">
      <div class="netWorthFigures">
        <div class="heading">Total Balance Change (24H)</div>
        <div class="percent">0%</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "OverView",
};
</script>

<style>
.overview {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  margin-top: 1.5rem;
  margin-bottom: 1.5rem;
}

.netWorth {
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
  align-items: center;
  background: white;
  padding: 1.2rem;
  width: 30%;
  height: 100px;
  border-radius: 8px;
  box-shadow: 0 2px 2px 0 rgba(0, 0, 0, 0.1), 0 2px 6px 0 rgba(0, 0, 0, 0.19);
}

.netWorthFigures {
  margin-right: 2rem;
}

.heading {
  color: gray;
  font-size: 0.8rem;
  font-weight: 600;
}

.netWorthFig {
  color: black;
  font-size: 1.5rem;
  font-weight: 700;
}

.gain {
  color: rgb(132, 219, 161);
}

.lost {
  color: red;
}
</style>
