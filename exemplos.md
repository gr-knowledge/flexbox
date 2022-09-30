https://www.alura.com.br/artigos/css-guia-do-flexbox?gclid=CjwKCAjw-L-ZBhB4EiwA76YzOZJpMiJAKRDeUpxJMFHu7dZcTOxnaDeJ887C7FIvWBwGWDMZ8eFKAhoC7bcQAvD_BwE

![image](https://user-images.githubusercontent.com/10155481/193273437-5665f333-2e5f-4226-9395-04e15e4f715e.png)

___
```css
{ **display:** flex }   
![image](https://user-images.githubusercontent.com/10155481/193273765-007ca875-5b81-46e1-9015-a19c93a6cac5.png)
```

___
```css
{ **flex-direction:** row | row-reverse | column | column-reverse }
```
![image](https://user-images.githubusercontent.com/10155481/193273996-ae967256-b245-4ef3-8210-30dc242e2658.png)

___
```css
{ **flex-wrap:** nowrap | wrap | wrap-reverse }
```
![image](https://user-images.githubusercontent.com/10155481/193274523-28da9293-34cc-4bfc-81ff-dc7e2008e69a.png)

___
```css
{ **flex-flow:** row nowrap | row wrap | column nowrap | column wrap }
```
_A propriedade **flex-flow** é uma propriedade shorthand (uma mesma declaração inclui vários valores relacionados a mais de uma propriedade) que inclui flex-direction e flex-wrap. Determina quais serão os eixos pricipal e transversal do container. O valor padrão é row nowrap._

___
![image](https://user-images.githubusercontent.com/10155481/193275691-fae9b268-9af1-48ea-bb2a-5b8794dee02e.png)

```css
{ justify-content: flex-start | flex-end | center | space-between | space-around | space-evenly }
```

___
![image](https://user-images.githubusercontent.com/10155481/193275767-57d04090-08f9-46ec-9969-1a9a5f585144.png)

```css
{ align-items: stretch | flex-start | flex-end | center | baseline }

```

___
![image](https://user-images.githubusercontent.com/10155481/193276106-504629a7-21ad-4d13-b2f5-6092d5f5e2d9.png)

```css
align-content: flex-start | flex-end | center | space-between | space-around | stretch
```

# align-content: flex-start | flex-end | center | space-between | space-around | stretch

![image](https://user-images.githubusercontent.com/10155481/193276245-e4285804-ee0e-45f3-8143-92220dbe4345.png)

```css
{ order: <número> } /* o valor padrão é 0 */
```

___ 
![image](https://user-images.githubusercontent.com/10155481/193276340-45e6e476-df28-4a65-81fe-23293141edbb.png)
```css
{ flex-grow: <numero> } /* o valor default(padrão) é 0 */
```
___
### flex-shrink
! Define a habilidade de um flex item de encolher, caso necessário.
```css
{ flex-shrink: <número> } /* o valor padrão é 0 */
```

