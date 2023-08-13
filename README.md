Здраво! 
=========


Добродошао на званични репозиторијум Петљиног курса **Савремена вештачка интелигенција**!
Овде можеш да пронађеш пратеће материјале за лекције које се обрађују и техничке смернице за подешавање окружења. 

Курс **Савремена вештачка интелигенција** је доступан на Петљином порталу на адреси [https://petlja.github.io/specit4_ai/](https://petlja.github.io/specit4_ai/). 


О материјалима
=================
Сви материјали су у форми Jupyter свески и садрже делове кода који ће ти помоћи да боље разумеш теме које се 
обрађују на курсу. Да би могао сасвим лепо да их испратиш, пожељно је да пре тога прођеш одговарајуће лекције. 
Ако те занима само технички део курса, важно је да прво прођеш лекције које се односе на библиотеке NumPy и Matplotlib, остале садржаје можеш махом прегледати редоследом којим желиш. 



Платформа Google Colab 
========================

Практични рад на проблемима вештачке интелигенције подразумева рад са великим бројем библиотека. Свака од ових библиотека, даље, има своје верзије од којих су неке прилагођене оперативним системима и захтевне за конфигурисање. Да бисмо избегли компликације које могу да настану услед ових околности, сваки од материјала смо повезали са платформом [Google Colab](https://research.google.com/colaboratory/). Ова платформа омогућава да се кодови извршавају у облаку у окружењу које је лако подестити за удобан рад. Више о самој платформи можеш прочитати у лекцији курса са истим именом или на званичном сајту платформе. Пошто је ово прилично популарна платформа, на вебу можеш пронаћи и многе друге корисне информације. 

На почетку сваког материјала видећеш беџ са натписом `Google Colab`. Довољно је да кликнеш на њега да би се садржај отворио у овом окружењу. Пре тога не заборави да се пријавиш на свој Google налог. 


Преузимање материјала на локални рачунар 
===========================================

Покретање материјала са локалног рачунара може донети многа корисна искуства тако да је сасвим у реду ако се определиш и за овај вид коришћења материјала. 

На почетку је потребно да инсталираш окружење Anaconda, популарно окружење језика Python у заједници која се бави машинским учењем и науком о подацима. Ово окружење долази са великим бројем већ инсталираних пакета и алатом за руковање пакетима `conda` који ће ти омогућити лаку инсталацију свих других потребних пакета. На званичном сајту заједнице Anaconda можеш да преузмеш верзију подесну за свој оперативни систем. Ево и [линка](https://www.anaconda.com/download). 

Уз библиотеке NumPy, Matplotlib и Pandas које ће бити подржане основном инсталацијом окружења Anaconda, биће ти потребна и библиотека TensorFlow и библиотека Transformers. 

За инталације библиотеке TensorFlow могу ти бити корисни следећи линкови:
- [https://www.tensorflow.org/install](https://www.tensorflow.org/install)
- [https://anaconda.org/conda-forge/tensorflow](https://anaconda.org/conda-forge/tensorflow)

За инсталацију библиотеке Transformers можеш да пратиш следеће смернице:
- [https://huggingface.co/docs/transformers/installation](https://huggingface.co/docs/transformers/installation)


Све свеске можеш прегледати у окружењу Jupyter које долази као саставни део платформе Anaconda. Након што преузмеш материјале, довољно је да се у терминалу позиционираш у радни директоријум и извршиш команду `jupyter notebook`. Она ће отворити корени директоријум у прозору веб прегледача, најчешће на адреси која је облика `localhost:8888`, из кога даље можеш да покрећеш свеске које желиш. Имај на уму да ће ти за примере који користе неуронске мреже требати и нешто више меморије за чување модела.

Садржај репозиторијума
===============

Репозиторијум, као што примећујеш, садржи датотеке:
- 03-библиотека_numpy.ipynb
- 03-библиотека_matplotlib.ipynb
- 04-експлоративна_анализа_података.ipynb
- 06-линеарна_регресија.ipynb
- 06-градијентни_спуст.ipynb
- 07-aлгоритам_к_најближих_суседа.ipynb
- 10-мрежа_VGG_16_и_задатак_класификације_слика.ipynb
- 10-трансформери_и_језички_задаци.ipynb
- 11-к_средина.ipynb

Редни бројеви материјала су везани за редне бројеве секција у којима се обрађују, немој да те збуни што нису узастопни јер немају све секције пратеће вежбе. 


Желимо ти пуно успеха и открића у овој сазнајној авантури!

Све коментаре или проблеме можеш слободно поделити на нашем форуму: ТОДО


Твој,

Петља тим
