# Atalhos Emmet

[Emmet documentation](https://docs.emmet.io/)

`div>p`

```html
  <div>
    <p></p>
  </div>
```
`p.my-class`

```html
<p class="my-class"></p>
```

`div>section+section`

```html
<div>
  <section></section>
  <section></section>
</div>
```

`ul>li+li+li` ou `ul>li*3`

```html
  <ul>
  <li></li>
  <li></li>
  <li></li>
</ul>
```

`p#my-id`

```html
<p id="my-id"></p>
```

`p>lorem10` ou `p>lorem50`

```html
<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sapiente, labore.</p>
```

`section>(main>h2+p)footer>ul>li*3>lorem5` 

Perceba que usei parenteses para agrupar um elemento

```html
<section>
    <main>
      <h2></h2>
      <p></p>
    </main>
    <footer>
      <ul>
        <li>Lorem ipsum dolor sit amet.</li>
        <li>Aut doloremque dolorem sint fugit.</li>
        <li>Adipisci voluptates nihil laudantium praesentium!</li>
      </ul>
    </footer>
  </section>
```
  