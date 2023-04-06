<div class="background">
	<div class="layout">
		<slot />
	</div>
</div>

<style>
	.background {
		position: absolute;
		inset: 0;
		background: color green;	}
    .layout {
         width:100%;
    max-width: 1024px;
     margin: 0 auto;}
</style>
