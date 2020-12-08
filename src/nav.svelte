<main>

 <!-- Navbar -->
 <nav class="mainNav">
    <div class="flex-container">
        <div class="nav-btn frontEndNav">
            <a href="./">Schedule</a>
        </div>
        <div class="nav-btn">
            <a href="./">Patients</a>
        </div>
        <div class="nav-btn">
            <a href="./">Billing</a>
        </div>
        <div class="nav-btn">
            <a href="./">Reports</a>
        </div>
        <div class="nav-btn">
            <a href="./">Team</a>
        </div>
        <div class="nav-btn farEndNav">
            <a href="./">Settings</a>
        </div>
        <div class="navFiller">
            <a href="./">Sign out</a>

        </div>
    </div>
    
    
</nav>


</main> 
    
   


<style>


nav {
	z-index: 3;
}

.mainNav .flex-container {
	display: flex;
	flex-direction: row;
}

.nav-btn {
	padding: 20px;
	cursor: pointer;
	background: rgb(192, 192, 192);
	border-right: 2px solid rgb(227, 233, 224);
	border-radius: 5px;
	z-index: 3;
}

.nav-btn:hover {
	transform: translateY(1px);
	background: rgb(189, 189, 189);
}

a {
	color: rgb(104, 104, 104);
	font-family: 'Josefin Sans', sans-serif;
	font-weight: 300;
	letter-spacing: .3rem;
	z-index: 3;
}

a:hover {
	text-decoration: none;
}

.frontEndNav {
	border-radius: 0px 5px 5px 0px;
}
.farEndNav {
	border-radius: 5px 0px 0px 5px;
}

.navFiller {
	flex-grow: 1;
	background: rgb(192, 192, 192);
	z-index: 3;
}

.navFiller a {
	color: rgb(241, 241, 241);
	float: right;
	padding: 10px;
	margin-top: 11px;
	
}
</style>
   