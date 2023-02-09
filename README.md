# QA инжир 
# Небольшой рассказ о себе
Общий опыт в ручном тестировании два года 10 месяцев. Офицальный трудовой стаж два года. Работал на крупном проекте входящим в топ 10 маркетплейсов РФ.
Основа моей работы максимум практических знаний и немного теории. Чтобы владеть теорией тестирования, достаточно посмотреть несколько видео на ютуб, а практическго применения этих методик, принципов, методологий - никто не дает. Я же могу гордиться тем, что покинув прошлое место работы обучил четверых джунов и сделал их асами на практике.


Будущие рабодатели, если вы не хотите набирать к себе в команду "специалистов", которые местерски выучили теорию и ничерта не понимают в практике
![Без имени-1](https://user-images.githubusercontent.com/124851355/217710195-16a5008d-ce36-49bf-bca4-31f295f205e1.png)

![1619918838516](https://user-images.githubusercontent.com/124851355/217707470-61e27d14-0e27-4d73-901c-51834a0ed386.png)


//fancybox
$('.fancybox').fancybox({
    padding : 0,
    openEffect  : 'elastic'
});

//Реклама в сплывающем окне

// Проверим, есть ли запись в куках о посещении посетителя
  // Если запись есть - ничего не делаем
  /*function advertisingPopUp(){
  if (!$.cookie('was')) {

    // Покажем всплывающее окно
	$.fancybox.open([
        {
            type: 'inline',
            href : '#advertising-popUp'
        }
    ], {
        maxWidth	: 550,
		maxHeight	: 450,
		fitToView	: false,
		width		: '70%',
		height		: '80%',
		autoSize	: false,
		closeBtn	: true,
		closeClick  : false,
		openEffect	: 'elastic',
		closeEffect	: 'none',
		padding		:  0,
    	helpers     : { 
        overlay : {closeClick: false} // prevents closing when clicking OUTSIDE fancybox
   		}
    });

  }
  // Запомним в куках, что посетитель к нам уже заходил
  $.cookie('was', true, {
    expires: 1,
    path: '/'
  }); 

  }//advertisingPopUp
setTimeout(advertisingPopUp, 5000);
