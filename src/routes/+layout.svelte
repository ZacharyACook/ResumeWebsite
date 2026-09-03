<script lang="ts">
	import './layout.css';
	import favicon from '$lib/assets/favicon.svg';
	let { children } = $props();
</script>

<main>
  <nav class = "Navbar">  
    <a href="/">𝚉𝚊𝚌𝚑𝚊𝚛𝚢 𝙰. 𝙲𝚘𝚘𝚔</a>
    <a href="/projects" style="font-size: 1.5rem;">𝙿𝚛𝚘𝚓𝚎𝚌𝚝𝚜</a>
  </nav>
  
  <background class = "Background"> </background>
  
  <div class = "Content">  
    <p>
      𝙲𝚘𝚗𝚝𝚊𝚌𝚝 𝚖𝚎 𝚊𝚝 𝚖𝚢...
      <a href="mailto:ZacharyCook911@gmail.com" target="_blank" rel="noopener noreferrer">𝙴𝚖𝚊𝚒𝚕</a>,
      <a href="https://www.linkedin.com/in/zachary-cook-027a26363/" target="_blank" rel="noopener noreferrer">𝙻𝚒𝚗𝚔𝚎𝚍𝙸𝚗</a>
    </p>
  </div>
</main>

<style> 
.Navbar {
position: relative;
display: flex;
align-items: left;
justify-content: left;
flex-wrap: nowrap;
flex-shrink: 0;
flex: 1;
min-width: 300px;
/*location*/
z-index: 1000;
top: 1rem;
left: -1rem;
width: 80%;
height: 8%;
/* Cosmetics*/
background-color: #183A37;
border-radius: 2vmax;
}

.Navbar a {
  color: #E9F1F7;
  font-size: 1.5rem;
  font-weight: bold;
  margin: 0 0.5rem;
  padding-left: 2rem;
}

.Navbar a:hover {
    -webkit-text-stroke: 1px #0a19186d;
}

.Background {
position: fixed;
z-index: -1;
top: 0;
left: 0;
width: 100%;
height: 100%;
background-color: #01111a;
}

.Content {
position: relative;
display: flex;
align-items: left;
justify-content: left;
flex-wrap: nowrap;
flex-shrink: 0;
flex: 1;
/*location*/
z-index: 1000;
top: 1.4rem;
left: -1rem;
width: 90%;
height: 8%;
/* Cosmetics*/
background-color: #183A37;
border-radius: 2vmax;
color: #E9F1F7;
padding: .2rem;
padding-left: 2.5rem;
font-weight: bold;
}

.Content a:hover {
  -webkit-text-stroke: 1px #0a19186d;
}

</style>
<svelte:head><link rel="icon" href={favicon} /></svelte:head>
{@render children()}
