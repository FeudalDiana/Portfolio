<img src="https://github.com/user-attachments/assets/d72bb18e-6730-4de9-b897-7088cd1c1dbc" class="profile">

<h3>Diana McRae – Gameplay Engineer</h3>

Hi, I'm Diana, also known as [*FeudalDiana*](https://www.roblox.com/users/17443035/profile). I started developing on Roblox in 2016 and have been working professionally since 2018, shaping a range of experiences. I specialize in roleplay games and have extensive expertise in designing competitive combat systems.

<div style="clear:both"></div>

---

## Westeros World
<div class="cv-entry">
    <strong>Lead Engineer</strong>
    <span></span>
    <em>Dec 2021 - May 2024</em>
</div>
<div class="cv-entry">
    <strong>Gameplay Engineer</strong>
    <span></span>
    <em>Jun 2021 - Dec 2021</em>
</div>

A medieval roleplay game centered around combat and resource management. During my time on the project, I led the development team, overseeing the game's direction and introducing new features.

#### Notable contributions include:
- Horse riding system for map traversal.
- Group based capture-point system where players battle for control of castles and villages.
- Mini-map system to help players find their way around the map and find their friends.
- Full rework of sword combat, prioritising exploit prevention and latency reduction to improve accessibility for players in different regions.

<div class="image-group">
    <img src="https://github.com/user-attachments/assets/6c0d044e-8e95-49d6-85e5-fadf59fb0458" >
    <img src="https://github.com/user-attachments/assets/467ca431-6736-439e-8063-f55f80c9d376" >
</div>

<div class="yt-embed">
    <iframe src="https://www.youtube.com/embed/PbyfpXBeaj4?si=NXKOAcXm6mQJSZ97&amp;clip=UgkxywMXTc4rVy_AZDR5-e9qxhYwlRrUEG23&amp;clipt=EPiwXRifk2A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
    <div>Footage of a combat in separate battleground game in which factions battle one another.</div>
</div>

---

## Viking Sagas
<div class="cv-entry">
    <strong>Lead Engineer</strong>
    <span></span>
    <em>Jan 2022 - May 2022</em>
</div>

Inspired from the historical mythical Viking Sagas. <br/>
Played a key role in establishing the group and the creation of new innovative systems to support its experiences.

#### Notable contributions include:
- Developed a new combat system featuring complex animations, networking and exploit prevention.
- Built core systems such as the datastore, inventory and economy.
  
<div class="image-group">
    <img src="https://github.com/user-attachments/assets/b10ba64c-0d06-4811-b8c5-7d5c0ba478fc" >
    <img src="https://github.com/user-attachments/assets/5ad58dd7-9279-4402-af25-28784bebea8b" >
    <img src="https://github.com/user-attachments/assets/e5f07c05-854b-49c2-8c24-b1b180ad0b08" >
</div>

---

## King's Landing
<div class="cv-entry">
    <strong>Lead Engineer</strong>
    <span></span>
    <em>Jul 2020 - Jun 2021</em>
</div>
<div class="cv-entry">
    <strong>Gameplay Engineer</strong>
    <span></span>
    <em>Oct 2018 - Feb 2019</em>
</div>

Competitive medieval kingdom roleplay game where players join large, community-led factions to compete for the prestigious crown in the game, granting control over the city.
#### Notable contributions include:
- In-depth battleground system allowing users to customize maps, spawn locations, weapon selection, and score and round settings.
- Overhauled the weapon system to introduce weapon stamina, allowing for parrying and dashing mechanics.

<div class="image-group">
    <img src="https://github.com/user-attachments/assets/05818857-24f2-4d8e-96f7-75a0b83c0177" >
</div>

---

## Contact Me

If you want to get in touch you can contact me at [*diana0mcrae@gmail.com*](mailto:diana0mcrae@gmail.com) or find me over at Discord [@FeudalDiana](https://discord.com/users/970120357262548993)


<div id="lightbox"><img></div>
<script type="text/javascript">
    const lightbox = document.getElementById("lightbox");
    let timeout = null;
    for (img of document.querySelectorAll("img")) {
        if (img == lightbox.children[0]) { continue; }
        img.addEventListener("click", (e) => {            
            e.preventDefault();
            e.stopPropagation();
            if (timeout) cancelTimeout(timeout);
            console.log(e.target.src)
            lightbox.children[0].src = e.target.src;
            lightbox.style.display = "flex";
            setTimeout(() => { lightbox.style.opacity = 1; }, 10)
        })
    }
    lightbox.addEventListener("click", (e) => {
        e.preventDefault();
        e.stopPropagation();
        lightbox.style.opacity = 0;
        if (timeout) cancelTimeout(timeout);
        timeout = setTimeout(() => {
            timeout = null;
            lightbox.style.display = "none";
        }, 125)
    })
</script>
