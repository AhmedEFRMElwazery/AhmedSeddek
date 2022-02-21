var slideIndex = [1, 14];
var slideId = [
  'mySlides1',
  'mySlides2',
  'mySlides3',
  'mySlides4',
  'mySlides5',
  'mySlides6',
];

function plusSlides(n, no) {
  showSlides((slideIndex[no] += n), no);
}

function showSlides(n, no) {
  var i;
  var x = document.getElementsByClassName(slideId[no]);
  if (n > x.length) {
    slideIndex[no] = 1;
  }
  if (n < 1) {
    slideIndex[no] = x.length;
  }
  for (i = 0; i < x.length; i++) {
    x[i].style.display = 'none';
  }
  x[slideIndex[no] - 1].style.display = 'block';
}

// function colorChange(elem) {
//   document.getElementById(elem).style.color = #fcf4a5;
// }

showSlides(14, 0);
showSlides(14, 1);
showSlides(14, 2);
showSlides(14, 3);
showSlides(14, 4);
showSlides(14, 5);
showSlides(14, 6);
showSlides(14, 7);
