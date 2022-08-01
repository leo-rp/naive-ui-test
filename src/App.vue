<template >	
	<n-message-provider>	
		<Login />
		<HelloWorld msg="the Vue3 + Naive-ui  test WSS!" />				
		<Calendar />
		<Table />
		<Calendar_n />	
	</n-message-provider>
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



