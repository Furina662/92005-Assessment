user: ryan
opiniton: you should add link in image card in about page
Modification results：
        <div class="location-card">
            **<a href="https://en.wikipedia.org/wiki/Milford_Sound" target="_blank">**
                <div class="location-image milford-sound"></div> 
                    <div class="location-content">
                        <h3>Milford Sound</h3>       
                        <p class="location-region">Fiordland, South Island</p>
                        <p class="location-description">A stunning fjord surrounded by towering peaks, cascading waterfalls, and pristine rainforest. Known as the "eighth wonder of the world," this UNESCO World Heritage site exemplifies the raw beauty we must protect through Kaitiakitanga.</p>
                    </div>
            **</a>**
        </div>

**Add an <a> to the location-card container so that users can click the entire card to jump instead of clicking on a part of it.**

**The above code is just an example. There are five other codes that are not listed here, but they are modified in the same way.**
-----------------------------------------------------------------------------
user:eric
opition: I think you could use a better looking font for your website
Modification results：
reset.css:
@font-face {
    font-family: 'Oswald';
    src: url('../font/static/Oswald-Regular.ttf') format('truetype');
    font-weight: normal;
    font-style: normal;
}

nav.css/footer.css:
font-family: 'Oswald', sans-serif;
-----------------------------------------------------------------------------
user:eric
opition:i think your footer font is too small
Modification results：
footer.css:
.footer-section p {
    font-size: 22px;
}
.footer-section ul li a {
    font-size: 20px;
}
.footer-bottom p {
    font-size: 18px;
}
.footer-bottom a {
    font-size: 20px;
}