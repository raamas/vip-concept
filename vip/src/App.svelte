<script>
	import Header from "./components/Header.svelte"
import Notes from "./components/Notes.svelte"
import Login from "./pages/Login.svelte"
	import Menu from "./pages/Menu.svelte"
</script>
<Header/>
<div class="main">
	<div class="screen">
		<Login></Login>
	</div>
	<div class="screen">
		<Menu></Menu>
	</div>
	<div class="notes">
		<Notes/>
	</div>
</div>
<style>
.main{
	display:flex;
	flex-direction: column;
	justify-content: center;
	align-items: center;
	background: #e4f1ee;
}
.screen{
	width: 360px;
	height: 640px;
	background: var(--light);
	border-radius: 15px;
	margin: 1em;
}
.notes{
	display:flex;
	justify-content: center;
	align-items: center;
}
.screen:nth-of-type(2){
	background: var(--grey);
}
</style>