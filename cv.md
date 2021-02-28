# Yuliya Kalitsinskaya

e-mail: (yulikaliti@gmail.com)

tel: +375 255 088 934

## Profile

Front-end developer with 2 years experience building and maintaining responsive website in the energy industry.

I do not need a work permit in Poland (I have a valid Pole Card).

I am looking for a company willing to offer me a placement among their developers. In return, I would offer my full commitment, and be a pleasant and friendly addition to your team.
I am ready for a remote interview.

## Education

- Yanka Kupala State [University](https://en.grsu.by/en/) of Grodno
  Specialization: Applied Mathematics And Informaics
  Qualification - mathematician-programmer
  2001-2006
- SOCIAL HIGH SCHOOL Eliza Orzeszkowa at PMS
  In-depth study of the Polish language and the history of Poland, 2017.
- Training on sites: [w3schools](https://www.w3schools.com/), [freeCodeCamp](https://www.freecodecamp.org/), [developer.mozilla.org](https://developer.mozilla.org/en-US/docs/Learn).

## Skills

HTML, CSS, Javascript, Git, Adobe Photoshop.

## Portfolio

<https://github.com/julikaliti>

Example of a code:

```
/*=============== Slideshow ======================*/
	var images = new Array('./images/slide01.jpg', './images/slide02.jpg', './images/slide03.jpg');
	var nextImage = 0;

	function slideshowFadeIn() {
    $('.slideshow').prepend($('<img class="slideshowImage" src="' + images[nextImage++] + '" style="display:none">').fadeIn(1000, function(){setTimeout(slideshow, 5000);}));
    if(nextImage >= images.length) {
        nextImage = 0;
		}
	}
	function slideshow() {
    if($('.slideshowImage').length != 0) {
        $('.slideshowImage').fadeOut(1000, function(){slideshowFadeIn(); $(this).remove()});
    } else {
        slideshowFadeIn();
    }
	}
	slideshow();
```

## Languages

English B1, Polish C1, Russian native

## Experience

2 years experience building and maintaining responsive internal website of the energy industry

_Wyrażam zgodę na przetwarzanie moich danych osobowych dla potrzeb niezbędnych do realizacji procesu rekrutacji zgodnie z Rozporządzeniem Parlamentu Europejskiego i Rady (UE) 2016/679 z dnia 27 kwietnia 2016 r. w sprawie ochrony osób fizycznych w związku z przetwarzaniem danych osobowych i w sprawie swobodnego przepływu takich danych oraz uchylenia dyrektywy 95/46/WE (RODO)._
