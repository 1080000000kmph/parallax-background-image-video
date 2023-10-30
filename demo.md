   JavaScript Video Parallax Scrolling | Cross browser compatible - pure js  

![](images/image1.jpg)

Jarallax
========

![](images/image3.jpg)

![](video/local-video.png)

![](images/image6.jpg)

![](images/image5.jpg)

Parallax scrolling effect for background images using **CSS transforms** which cross browser support and compatible for old browsers. Parallax plugin with **NO dependencies**. jQuery supported. **Youtube** and **Vimeo** parallax supported.

![](images/image2.jpg)

Parallax speed options - faster / slower
----------------------------------------

![](images/image3.jpg)

![](images/image5.jpg)

![](images/image4.jpg)

Parallax <img> tag
------------------

Lorizzle ipsum dang sit amizzle, consectetuer adipiscing da bomb. Nullizzle sapien velit, break it down volutpizzle, suscipit quis, ma nizzle vizzle, boom shackalack. Pellentesque izzle tortor. Funky fresh erizzle. Boofron at fo shizzle mah nizzle fo rizzle, mah home g-dizzle i saw beyonces tizzles and my pizzle went crizzle turpis tempizzle pizzle. Maurizzle its fo rizzle pot izzle da bomb. Dang in tortor. Boofron dawg rhoncizzle nisi. In hac habitasse platea dictumst. Donec dapibizzle. Curabitizzle tellizzle bizzle, pretium fo shizzle, mattizzle fo, eleifend vitae, nunc. Go to hizzle suscipit. Integizzle we gonna chung velizzle sizzle shut the shizzle up.

![](images/image3.jpg)

Pot shut the shizzle up i saw beyonces tizzles and my pizzle went crizzle. Check out this check out this bling bling diam my shizz massa tincidunt pellentesque. In izzle black. Vivamizzle shiznit ghetto, crunk sizzle , vulputate mammasay mammasa mamma oo sa, condimentum bling bling, nunc. Pimpin' sizzle amet mauris. Crunk fermentum yippiyo nunc. Morbi vulputate, check it out boom shackalack hizzle facilisizzle, uhuh ... yih! tellus tellivizzle justo, pimpin' condimentizzle lacizzle purizzle sizzle enizzle. Fizzle fermentizzle you son of a bizzle nunc. Pellentesque shizzlin dizzle. In fo for sure platea dictumst. Nizzle sit amizzle dui. Donec my shizz shiznit. Da bomb in i'm in the shizzle. Boofron lobortis, elit get down get down break yo neck, yall suscipit, massa break it down pretium away, quizzle its fo rizzle ipsum we gonna chung izzle its fo rizzle.

Nulla facilisi. Etizzle faucibus cool shiznit. Check out this bling bling arcu izzle fo. Da bomb sure odio izzle ipsum. Curabitizzle adipiscing nibh ma nizzle lectizzle. laoreet, daahng dawg eget eleifend tincidunt, rizzle sizzle bibendizzle orci, check it out placerat you son of a bizzle maurizzle yo mi. Etiam adipiscing, bow wow wow gangsta izzle ma nizzle, tellus nisl lacinia orci, a for sure gangsta mi shiznit mah nizzle.

![](images/image5.jpg)

Crazy aliquizzle mattizzle uhuh ... yih!. Yippiyo pulvinar shiz dolizzle. Pot leo mah nizzle, tempizzle nizzle, that's the shizzle yo mamma, laorizzle in, bow wow wow. Mauris mah nizzle uhuh ... yih! quizzle sure blandizzle dictizzle. Shit owned turpizzle owned sem tincidunt lobortis. Phasellus gangsta cool. Doggy lacinia. Bling bling sheezy shit my shizz. Pellentesque mi. Lorizzle ipsizzle dolizzle gizzle amizzle, break it down its fo rizzle elit. Funky fresh daahng dawg arcu, shiznit egizzle, shit a, shiznit eu, neque. Break yo neck, yall ipsum dolor sit amet, consectetuer adipiscing go to hizzle.

Scale and Opacity
-----------------

Youtube Vimeo and <video> parallax
----------------------------------

Youtube
-------

![](video/local-video.png)

Local video
-----------

Vimeo
-----

Parallax for small blocks
-------------------------

![](images/image6.jpg)

![](images/image2.jpg)

![](images/image3.jpg)

Terry van Prooien

All images taken from [https://freepik.com](https://freepik.com/), [https://pexels.com](https://pexels.com/) and [https://unsplash.com](https://unsplash.com/)

// object-fit polyfill run objectFitImages(); /\* init Jarallax \*/ jarallax(document.querySelectorAll('.jarallax')); jarallax(document.querySelectorAll('.jarallax-keep-img'), { keepImg: true }); /\* init Flickity Carousel + Jarallax inside it \*/ new Flickity( '.carousel', { initialIndex: 1, autoPlay: 3000, pauseAutoPlayOnHover: false, pageDots: false, prevNextButtons: false, wrapAround: true }); jarallax(document.querySelectorAll('.carousel .jarallax'), { elementInViewport: document.querySelectorAll('.carousel') }); /\* init Jarallax with jQuery \*/ // $('.jarallax').jarallax({ // speed: 0.5, // imgWidth: 1366, // imgHeight: 768 // });