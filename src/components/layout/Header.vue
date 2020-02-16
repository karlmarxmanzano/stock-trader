<template>
	<nav class="navbar navbar-expand-lg navbar-light bg-light">
	 	<div class="container">
	 		<router-link
    			tag="a"
    			class="navbar-brand"
				:to="{ path: 'home' }">Stock Trader</router-link>
			<button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
		    	<span class="navbar-toggler-icon"></span>
			</button>

			<div class="collapse navbar-collapse" id="navbarSupportedContent">
		    	<ul class="navbar-nav mr-auto">
		    		<router-link
		    			tag="li"
		    			class="nav-item"
						:to="{ path: 'home' }"
						active-class="active"
		    			exact><a class="nav-link">Home</a></router-link>
		    		<router-link
		    			tag="li"
		    			class="nav-item"
						:to="{ path: 'portfolio' }"
						active-class="active"
		    			exact><a class="nav-link">Portfolio</a></router-link>
		    		<router-link
		    			tag="li"
		    			class="nav-item"
						:to="{ path: 'stocks' }"
						active-class="active"
		    			exact><a class="nav-link">Stocks</a></router-link>
		    	</ul>
				<ul class="navbar-nav">
		    		<li class="nav-item"><a class="nav-link" href="#">End Day</a></li>
		    		<li class="nav-item dropdown">
		        		<a 
		        			class="nav-link dropdown-toggle" 
		        			href="#" 
		        			id="navbarDropdown" 
		        			role="button" 
		        			data-toggle="dropdown" 
		        			aria-haspopup="true" 
		        			aria-expanded="false">Save and Load</a>
			        	<div class="dropdown-menu" aria-labelledby="navbarDropdown">
			        		<a class="dropdown-item" href="#">Save</a>
			        		<a class="dropdown-item" href="#">Load</a>
			        	</div>
		    		</li>
				</ul>
			</div>
	 	</div>
	</nav>
</template>