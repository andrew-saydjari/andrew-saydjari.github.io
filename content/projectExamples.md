+++
title = "Selected Projects"

description = ""
sort_by = "none"
weight = 0
render = true
redirect_to = ""
transparent = false

[extra]
+++
### DECaPS2: The Dark Energy Camera Plane Survey DR2
<div class="columns is-desktop" style="object-fit:contain">
    <div style="position: relative; width: 100%; padding-bottom: 25%;">
        <div id="aladin-lite-div" frameborder="0" style="position: absolute; width: 100%; height: 100%;"></div>
        <script type="text/javascript" src="https://aladin.cds.unistra.fr/AladinLite/api/v3/latest/aladin.js" charset="utf-8"></script>
        <script type="text/javascript">
        let aladin;
        A.init.then(() => {
            aladin = A.aladin('#aladin-lite-div', {survey: "P/DECaPS/DR2/color", fov:132, cooFrame:"galactic",target: "303 +0", projection: "AIT"});
        });
        aladin.setBackgroundColor("rgb(0, 0, 0)")
        </script>
    </div>
</div>

<div style="font-size: 18px;">
I led the data reduction for the second and final release of the Dark Energy Camera Plane Survey (DECaPS2). We provide a catalog of 3.32 billion sources in our survey footprint that covers 6.5% of the sky. We developed new methods well-suited to photometry in the Galactic plane, developed improved measures of photometric depth adapted to crowded-fields, and validate our pipeline extensively with synthetic star tests. For more, see our project <a href="http://decaps.skymaps.info/" target="_blank">website</a>. <strong>Tip:</strong> See how far you can zoom in! (be patient)
</div>

### APOGEE Spectral Decomposition

<img src="/img/SB3.gif" width="800" alt="SB3 Deblending">

<div style="font-size: 18px;">
   I developed and applied a new pipeline to the reduce SDSS-V APOGEE spectra that separates each visit into a linear combination of the most probable contributions from the sky, star, and ISM. This component separation approach to spectral reduction represents a paradigm shift from commiting to single point estimates (of the telluric absorption, sky emission lines, etc.) to marginalzing over our uncertainty about the contribution of each component to the overall spectrum in a joint fit that produces dense posteriors. The goals of this project are to measure the strong diffuse interestellar band near 15273 Å, discover new DIBs, reduce biases in stellar parameter and abundance measurements, and obtain robust parameter measurements of spectroscopic multiples.
</div>

### Diffuse Interstellar Band in Gaia DR3 RVS Spectra
<video width="800" height="800" controls autoplay loop muted>
    <source src="/img/localBubble.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>

<br>
<div style="font-size: 18px;">
   I developed and applied a new pipeline to the Gaia (DR3) RVS spectra to measure the diffuse interstellar band (DIB) near 862.1 nm. This method marginalized over stellar types, avoiding false detections of stellar residuals as DIB detections, as in the public Gaia catalog. This analysis allowed us to show that there were no statistically significant detections of DIBs in the Local Bubble. For more, see our project <a href="https://faun.rc.fas.harvard.edu/saydjari/GaiaDIB/" target="_blank">website</a>.
</div>

### High Angular Resolution 3D Dust Mapping

<img src="/img/highResCompare.gif" width="500" alt="DECaPS versus Bayestar19">

<br>
<div style="font-size: 18px;">
   I extended a previous dustmaping methodology using <a href="https://github.com/gregreen/bayestar" target="_blank">bayestar</a> and am combinining that with deep, high-quality NIR photometry from DECaPS2 (see above) to achieve an extraordinarily high angular resolution 3D dust map, 5x the resolution of the 2D Planck dust map! Through this careful statistical inference, we expect to see ~ pc scale structures several kpc away in nearby spiral arms of the Galaxy. The GIF above shows the improvement in angular resolution acheived by our 3D dust map compared to a previous version (Bayestar19) and the video below shows only a 4° x 4° region in the footprint of the map, which will cover the entire southern Galactic plane!
</div>

<video width="500" controls autoplay loop muted>
    <source src="/img/reversed_med_res.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>


    






