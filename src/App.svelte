<script>
	import Nav from './nav.svelte';
</script>

<main>
<Nav/>


<section class="wrapper">

	<div class="main-view boxfill">
		<h3 class="patient-name">John Smith</h3>
		<h4 class="complaint">Low Back Pain</h4>
		<p class="notes"> Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quaerat sunt vel itaque voluptatum dignissimos, ipsam quisquam, adipisci magnam eos, deserunt magni libero cum ab natus nulla quibusdam temporibus illum. Eos ratione vero veritatis atque, ab eligendi culpa, dolore doloremque explicabo vel minus dolorum saepe? Cum excepturi repellat voluptatum aspernatur ut ea repudiandae esse voluptate fugit unde quidem incidunt ab quae quasi, autem dolore aliquam placeat? Pariatur temporibus dolorem maxime molestias, obcaecati velit vel ullam. Nulla id eum eius neque, dicta ipsum ipsam inventore voluptas? Impedit magnam sint rem laudantium odio aspernatur similique hic laboriosam aperiam molestiae cum explicabo nostrum, cumque temporibus error dolores sequi quas porro quisquam. Consequuntur aliquid qui totam. Id amet reprehenderit non aut pariatur, facere, doloribus est natus neque cum atque dolore mollitia vero nesciunt ipsam facilis assumenda quas nisi possimus! Voluptas sit quae est ipsa possimus perferendis iure vero quidem itaque! Doloremque repellat ex, recusandae, non vel illum magnam pariatur tempora nostrum perspiciatis enim ad sunt ea beatae cupiditate porro officiis, iure explicabo. Eos quo similique deleniti rerum neque porro accusamus, harum assumenda perspiciatis! Ducimus id fugit deleniti et nesciunt, ratione assumenda voluptatem ab obcaecati debitis quis! Hic, est amet cumque asperiores minima officia quis dolores praesentium aperiam quo consequuntur perferendis at eveniet beatae dolorum incidunt quasi neque debitis dignissimos saepe. Eaque velit soluta a repellendus, similique placeat, incidunt necessitatibus deleniti quia, illo nulla fuga suscipit quam omnis adipisci iusto amet vel facilis dicta ab consequuntur eos debitis. Nemo incidunt at iusto aut error nisi cupiditate facilis dolor! Molestias ullam nobis libero cupiditate labore iusto natus. Rem, possimus consequatur explicabo inventore quos minima. Commodi dolore provident, ex culpa amet voluptate rem recusandae enim, esse odit a non, repellendus consectetur ab earum incidunt aspernatur rerum reprehenderit quidem sunt. Voluptatum nisi quos exercitationem asperiores illum neque reprehenderit quisquam. </p>

	</div>
	<div class="right-slot-top boxfill"></div>
	<div class="right-slot-bottom boxfill"></div>




</section>




</main>

<style>

/* .boxfill img {
	z-index: 5;
} */

.notes {
	margin-left: 45px;
	margin-right: 45px;
	line-height: 2rem;

}

.patient-name {
	margin-top: 100px;
	margin-left: 45px;
	font-size: 3rem;
	font-weight: 100;
	letter-spacing: .4rem;
}

.complaint {
	margin-left: 45px;
	font-weight: 300;
	font-size: 1.5rem;
}

.wrapper {
	margin-top: -61px;
	display: grid;
	grid-template-columns: repeat(3,1fr);
	gap: 10px;
	grid-auto-rows: minmax(100px, auto);
	width: 100vw;
	height: 100vh;
}

.main-view {
	grid-column: 1 / 3;
	grid-row: 1/3;
}


.boxfill {
	background:rgb(223, 223, 223);
	/* border: 1px solid black; */
}
</style>