<template >
  <n-config-provider>
    <n-loading-bar-provider>
      <n-message-provider>
        <n-notification-provider>
          <n-dialog-provider>
            <div class="wrapper">
				<HelloWorld msg="the Vue3 + Naive-ui  test WSS!" />				
			</div>	
			<div class="wrapper">
				<Login />
			</div>	
			<div class="wrapper">
				<Calendar />
			</div>	
			<div class="wrapper">
				<Table />
			</div>
			<div class="wrapper">
				<Calendar_n />
			</div>			
          </n-dialog-provider>
        </n-notification-provider>
      </n-message-provider>
    </n-loading-bar-provider>
  </n-config-provider>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Login from './components/Login.vue'
import Calendar from './components/Calendar.vue'
import Calendar_n from './components/Calendar_n.vue'
import Table from './components/Table.vue'


 
export default {
  name: 'App',

  components: {
   HelloWorld,
   Login,
   Calendar,
   Calendar_n,
   Table
  
   
  
  },

  data: () => ({
    //
  }),
};
</script>



