# Resume

## Contacts

- Name: _Denis Losik_

- Email: _[beafraidnotlearning@mail.ru](mailto:beafraidnotlearning@mail.ru)_

- Phone: _375333513734_

## About me

My goals and wishes:

- I want to see the result of my work and have opportunities for creativity.
- My dream is to talk about my work as a hobby.
- I hope to be in a team where I will progress and become one of the best specialists in my field.

Why i decided to become a web developer:

- I've been looking for a programming area, that would really interest me for a long time. Only when I helped develop a site to one of my friends. I realized that I want to continue to do this. From that moment on, I am looking for development opportunities in the area of web-development.
- I believe that The Rolling Scopes School courses are a great opportunity to become a high-class developer and I will definitely take advantage of it.

## Skills

- HTML/CSS
- JavaScript
- C#/ASP.NET
- MySQL

## Code examples

```
function solveSudoku(matrix) {
    function SearchElement(matrixSudoku){
        const ARRAY = [1, 2, 3, 4, 5, 6, 7, 8, 9];
        const LENGTH = ARRAY.length;
        let condition = true;
        for(let i = 0; i < LENGTH; i++){
            for(let j = 0; j < LENGTH; j++){
                if(matrixSudoku[i][j] == 0){
                for(let k = 0; k < LENGTH; k++){
                    condition = true;
                    for(let n = 0; n < LENGTH; n++){
                    if(matrixSudoku[i][n] == ARRAY[k] || matrixSudoku[n][j] == ARRAY[k] || matrixSudoku[Math.floor(i / 3) * 3 + n % 3][Math.floor(j / 3) * 3 + Math.floor(n / 3)] == ARRAY[k]){
                        condition = false;
                    }
                    }
                    if(condition){
                    matrixSudoku[i][j] = ARRAY[k];
                    if(SearchElement(matrixSudoku)){
                        return true;
                    }
                    else{
                        matrixSudoku[i][j] = 0;
                    }
                    }
                }
                return false;
                }
            }
        }
        return true;
    }
    SearchElement(matrix);
    return matrix;
}
```

## Work experience

_My courses and trainings completed:_

- [Курс по HTML](https://ru.code-basics.com/languages/html)
- [Курс по CSS](https://ru.code-basics.com/languages/css)
- [Курс по Javascript](https://ru.code-basics.com/languages/javascript)
- [Онлайн обучение Javascript](https://learn.javascript.ru/)
- [Книга о Javascript](https://exploringjs.com/es6/)
