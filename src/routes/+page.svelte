<script>
	import Components from '../lib/Components/Components.svelte';
	import IFrame from '../lib/Components/IFrame.svelte';
	import Page from '../lib/Components/Page.svelte';
	import Subtitle from '../lib/Components/Subtitle.svelte';
	import Title from '../lib/Components/Title.svelte';
</script>

<Page>
	<h1 slot="title" class="w-fit text-7xl xl:text-[110px] font-extrabold font-[Nohemi]">
		Hammond Soul Xperience
	</h1>
	<Subtitle slot="subtitle">
		<p class="md:text-2xl xl:w-1/3">
			<span class="font-bold">Hammond Soul Xperience (HSX)</span> es una banda formada por músicos
			que se conocieron sobre el escenario, en las jam sessions de la
			<span class="font-bold">Jaén Jazzy</span>.
		</p>

		<br />
		<p class="md:text-2xl">
			También estamos en instagram! <a href="https://instagram.com/hsx_band" class="underline"
				>@hsx_band</a
			>
		</p>
	</Subtitle>
</Page>

<Page>
	<Title slot="title">
		<div class="font-title">DEMOS</div>
	</Title>
	<Subtitle slot="subtitle">
		<div class="grid grid-cols-1 lg:grid-cols-2 gap-20">
			<IFrame src="https://www.youtube.com/embed/Dka1qR5ecd0?si=GNWbfpb44j4tH7gT">
				<p slot="description" class="mt-5 text-xl md:text-2xl">
					Concierto completo de la <span class="font-bold">HSX</span> en el Café Número 31, en Úbeda.
				</p>
			</IFrame>

			<IFrame src="https://www.youtube.com/embed/oCxxBpx2z8E?si=XuAp0FpW1TDxlqW3">
				<p slot="description" class="mt-5 text-xl md:text-2xl">
					La <span class="font-bold">HSX</span> en la última Jam Session del curso 2022/2023 de la
					Jazzy. <br />Jaén, 16 Junio 2023
				</p>
			</IFrame>
		</div>
	</Subtitle>
</Page>

<Page>
	<Title slot="title">
		<div class="font-title">BIOGRAFÍA</div>
	</Title>
	<Subtitle slot="subtitle">
		<div class="lg:grid lg:grid-cols-2 xl:justify-stretch text-xl gap-32">
			<aside>
				<img
					src="/assets/hsx.jpg"
					alt="HSX"
					class="overflow-x-clip w-[120%] lg:w-fit scale-125 md:scale-100 md:w-fit my-20 lg:my-0 border-y md:border border-base-content xl:ml-5 xl:hover:-rotate-[1deg] xl:transition-transform xl:rounded-md"
				/>
			</aside>
			<p class="xl:text-justify w-[80%]">
				Aunque con historias personales y musicales dispares, los miembros de HSX comparten un
				desproporcionado, interés por la música de raíces afroamericanas que orbitan alrededor del
				<span class="font-bold">jazz-funk</span>, pero que también se envuelven de soul e incluso la
				bossa nova.
				<br /><br /> Una mezcla explosiva con toques añejos que se decora con retoques
				contemporáneos y, muchas veces, bailables. El repertorio de la banda incluye
				reinterpretaciones de temas clásicos y contemporáneos, además de algunos temas propios.
				<br /><br /> Su sonido se caracteriza por vigorosas bases rítmicas y líneas de bajo, guitarras
				que destilan groove, y la textura sonora inconfundible del órgano Hammond. La banda suele contar
				en sus directos con exquisitas colaboraciones vocales e instrumentales.
			</p>
		</div>
	</Subtitle>
</Page>

<Page>
	<Title slot="title">
		<div class="ml-5 font-title">COMPONENTES</div>
	</Title>
	<Subtitle slot="subtitle">
		<Components />
	</Subtitle>
</Page>
