<template>
  <div class="table scrollit">
    <table class="table-fixed">
      <thead>
        <tr>
          <th class="w-2/12">Asset</th>
          <th class="w-2/12">Symbol</th>
          <th class="w-2/12">Contract Address</th>
          <th class="w-2/12">Quantity</th>
          <th class="w-2/12">Price</th>
          <th class="w-2/12">Value</th>
        </tr>
      </thead>
      <tbody>
        <tr><!-- new row -->
          <td>Ethereum</td>
          <td>ETH</td>
          <td>-</td>
          <td>0.002190327432393876</td>
          <td>$2,647.68</td>
          <td>$5.80</td>
        </tr>
        <tr><!-- new row -->
          <td>PKG Token</td>
          <td>PKG</td>
          <td>0xea5f88e54d982cbb0c441cde4e79bc305e5b43bc</td>
          <td>241</td>
          <td>$0.000008</td>
          <td>$0.00</td>
        </tr>
        <tr><!-- new row -->
          <td>Pareto Network Token</td>
          <td>PARETO</td>
          <td>0xea5f88e54d982cbb0c441cde4e79bc305e5b43bc</td>
          <td>10</td>
          <td>$0.000172</td>
          <td>$0.00</td>
        </tr>
        <tr><!-- new row -->
          <td>KickToken</td>
          <td>KICK</td>
          <td>0xea5f88e54d982cbb0c441cde4e79bc305e5b43bc</td>
          <td>888888</td>
          <td>-</td>
          <td>-</td>
        </tr>
        <tr><!-- new row -->
          <td>Instadapp</td>
          <td>INST</td>
          <td>0xea5f88e54d982cbb0c441cde4e79bc305e5b43bc</td>
          <td>10000000</td>
          <td>-</td>
          <td>-</td>
        </tr>
      </tbody>
    </table>
  </div>
</template>

<script>
export default {
  name: "WalletAssets",
};
</script>

<style>
.table{
  margin: 1.5rem 0;
}

table{
width: 100%;
border-radius: 8px;
box-shadow: 0 2px 2px 0 rgba(0, 0, 0, 0.1), 0 2px 6px 0 rgba(0, 0, 0, 0.19);
}

tr{
  border-bottom: 0.5px solid rgb(224, 224, 224);
}

th{
  text-align: left;
  color: gray;
  font-weight: 500;
}

th, td{
  padding: 1rem;
  overflow: hidden;
  text-overflow: ellipsis;
  white-space: nowrap;
}

th:hover, td:hover{
  overflow: visible;
  white-space: pre-wrap;
}
/*
th, td{
  padding: 1rem;
}

.scrollit{
  overflow-x:auto
}
*/
td{
  font-weight: 600;
  color: black;
}
</style>
