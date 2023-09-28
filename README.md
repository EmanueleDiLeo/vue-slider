Vue Slider
===
Partendo dal markup della versione svolta in js plain, rifare lo slider ma questa volta usando Vue.
Al click su una thumb, visualizzare in grande l’immagine corrispondente
**Bonus:**
1- applicare l’autoplay allo slider: ogni 3 secondi, cambia immagine automaticamente
2- quando il mouse va in hover sullo slider, bloccare l’autoplay e farlo riprendere quando esce

## Svolgimento

1. prendere lo slider vecchio
1. riadattare html con il js usando vue
1. fare un set interval che ogni secondo cambia immagine incrementando il contatore
1. gestire il problema del contatore troppo grande con un if e riportarlo a 0 
1. aggiungere un flag che cambia da vero a falso a seconda su il mouse è dentro o fuori il carosel
1. mettere dentro set interval if con il flag