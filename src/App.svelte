<script>
   
    import Metric from "./metric.svelte";
    import Time from './time.svelte';
    import Placement from "./placement.svelte"
    import Rejected from "./rejectedreasons.svelte";
  

</script>

<div class="main-container">
    <Metric />
    <Time/>
    <Placement/>
    <div class="container2">
        <h1 class="h1">Reject Reasons</h1>
       <Rejected/>
    </div>
</div>

<style>
    .main-container {
     
        width: 1520px;
        height: 1800px;
        margin-left:0px;
        margin-top:-165px;
    }

    .container2 {
        width: 1400px;
        height: 450px;
   
        margin-top: 120px;
        margin-left:40px;
        background-color: white;
    }
 .h1{
    font-size: 17px;
    font-weight: bold;
    margin-left: 10px;

 }
  
</style>
