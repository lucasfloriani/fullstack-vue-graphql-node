<template>
  <div>
    <div class="text-center" id="slogan">
      <h1>NameGator</h1>
      <br>
      <h6 class="text-secondary">Gerador de nomes utilizando Vue.js, GraphQL e Node</h6>
    </div>
    <div id="main">
			<DomainList />
    </div>
  </div>
</template>

<script>
import "bootstrap/dist/css/bootstrap.css";
import "font-awesome/css/font-awesome.css";
import DomainList from './components/DomainList';

export default {
	name: "app",
	components: {
		DomainList,
	}
};
</script>

<style>
#slogan {
  margin-top: 30px;
  margin-bottom: 30px;
}
#main {
  background-color: #f1f1f1;
  padding-bottom: 30px;
  padding-top: 30px;
}
</style>
