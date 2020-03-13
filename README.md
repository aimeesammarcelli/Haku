### Haku 🐉
Haku is a SCSS framework.



#What my framework provide you ?

Here is the list of classes you can use :


**Basic columns :**

```
.col-1 //From 1 to 12
```


**Medias queries for 3 screens sizes :**

Large screen size :

```
.lg-1 //From 1 to 1O
```

Medium screen size :

```
.md-1 //From 1 to 8
```

Small screen size :

```
.sm-1 //From 1 to 4
```


**Flex: 

```
.flex
```

Align

```
.align-..
```

Direction

```
.direction-..
```

Wrap

```
.flex-wrap
.flex-nowrap
```

Justify content

```
.flex--justify-..
```

Colors

```
.background-color-..
.text-color-..
```

Typographie

```
.decoration-none
..:hover
..:visited
.text-..
```

Margin Padding

```
.m-t-..
.m-b-..
.m-r-..
.m-l-..

.p-t-..
.p-b-..
.p-r-..
.p-l-..
```

Shadow

```
.shadow-..
```

**Exemple :**

```
    <section class="cards button-border m-t-55 button-radius">

        <div class="text-cards direction-columns text-align-center">
            <h2>Card Title</h2>
            <p>I am a very simple card. I am good at containing small bits of information. I am convenient because I require little markup to use effectively.</p>
        </div>

        <div class="buttons-cards direction-row text-justify-center p-b-20">
            <a href="#" class="m-r-20"> I'm the first link</a>
            <a href="#"> I'm the second link</a>
        </div>
    </section>
```
