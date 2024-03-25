#   План десйтвие для верстки
##  зависимость сайта 
*   html
*   css
    *   font-awesome
    *   fontello
*   javascript
    *   Librery
        *   fansybox
        *   Splide v4
*   instrumen
## создаем нужные папки
*   папки
    *   theme_name
    *   dist/
    *   font/
    *   icon/
    *   image/
    *   stylus/
    *   part/
    *   root/
## создаем нужные файлы
*   **файлы**
    *   **dist**/index.html
    *   **dist**/style.css
    *   **dist**/script.css
    *   **stylus/part**/header.styl
    *   **stylus/part**/footer.styl
    *   **stylus/part**/hero.styl
    *   **stylus/part**/music_tool.styl
    *   **stylus/part**/skide.styl
    *   **stylus/root**/body.styl
    *   **stylus/root**/normilize.styl
    *   **stylus/root**/root.styl
    *   **stylus/root**/variable.styl
    *   **stylus**/style.styl

## Реализация верстки
*  **index.html**
    *   созданы блоки и подблоки
    *   подключаем стили
    *   подключаем скрипты
    *   добавили Данный header
    *   использовано тех БЭМ
    *   добавлено все атрибуты

*   **шрифты**
    *   [ DMsans ]('https://fonts.google.com/') 
```git
git clone https://github.com/halil-95/component.git 
```
*
   icon [fontello]('https://fontello.com/') 
    

```git
git clone https://github.com/halil-95/component.git 
```

[генератор для фривтоф](https://transfonter.org/)


*   **variable for git** 
    *   all  ` all export `
        *   export Нужен для того чтобы мы добавили c помощи  этого знака $ в переменный
    ```git
        export mess="some message for commit "
        export teg=" -a 'v.1' -m '$mess'"
    ```
внутри **alias** мы будем полбзоватся **export** 

    ```git
    alias gs="git status"
    alias gadd="git add .;git status; git commit -m '$mess'; git tag -a '$teg';git push origin main;git push origin1 main; git status "
    alias gpush1="git push origin alter-main;gitq
     push origin1 alter-main; git status"
    alias gls="git log --stat"
    alias gl="git log"
    alias gc="git checkout -B main"
    alias gc1="git checkout -B alter-main"
    ```