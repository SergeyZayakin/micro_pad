ВНИМАНИЕ!   
Все файлы подходят для микропада на 25 клавиш - https://aliexpress.ru/item/1005002559266513.html   

**ШАГ 1: Как запрограммировать макропад:** 
1. Зайдите на сайт KBFirmware.com.   
1. В поле Upload закиньте файл winry25tc.json или тот что подходит к вашему микропаду.    
1. Зайдите в раздел Keymap и отредактируйте каждую клавишу в веб-интерфейсе. На панели внизу укажите, какие клавиши нужно было нажимать.     
1. В разделе Macro пропишите макросы и назначьте их на клавиши. Чтобы назначить макрос, сначала запишите его под каким-то номером на экране Macro, а потом в разделе Keymap выберите нужную клавишу и в разделе FN найдите значок M(). Чтобы понять, что означают все эти коды, идите в документацию.    
1. Когда всё готово, зайдите в раздел Compile и нажмите на кнопку Download Hex. Скачается hex-файлик.    
   
Или скачайте уже готовю прошивку - winry25tc.hex с базовыми функциями Python    
    
**ШАГ 2: Как прошить контроллер:**  
1. Скачайте и запустите QMK Toolbox.   
1. Подключите кабель от клавиатуры к компьютеру (но пока что не подключайте к клавиатуре).   
1. На задней панели макропада найдите дырку с кнопкой для прошивки. Зажмите эту кнопку с помощью булавки, иголки или шариковой ручки.   
1. Пока кнопка зажата, подключите провод к клавиатуре. Она потупит несколько секунд, и на экране QMK Toolbox появится сообщение, мол, обнаружена клавиатура.    
1. В QMK Toolbox в поле Local File нажмите Open и найдите только что скачанный hex-файл.   
1. Нажмите Flash. Подождите несколько секунд. 

Источник: https://thecode-media.turbopages.org/thecode.media/s/macropad/
