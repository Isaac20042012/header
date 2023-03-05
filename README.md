# Isaac20042012

header com HTML e CSS

## header 1
<img src="./IMG/header1.png" alt="header 1"/>

<br>

``` HTML
<nav>
    <a href="#" class="logo">🚀 LOGO</a>
    <ul>
        <li>Sobre</li>
        <li>Serviços</li>
        <li>Dopoimentos</li>
    </ul>
    <a href="#" class="button">Contato</a>
</nav>
```

<br>

``` CSS
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
}

:root {
    font-size: 62.5%;
    --body-bg-color: #161616;
    --nav-bg-color: #121212;
    --nav-text-color: white;
    --button-bg-color: #0052ce;
    --button-text-color: white;
}

body {
    font-size: 1.6rem;
    font-family: 'Roboto', sans-serif;
    background-color: var(--body-bg-color);
}

a {
    text-decoration: none;
    color: var(--nav-text-color);
}

.button {
    display: inline-flex;
    justify-content: center;
    align-items: center;
    padding: 1rem 1.6rem;
    background-color: var(--button-bg-color);
    border-radius: .8rem;
    color: var(--button-text-color);
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: var(--nav-bg-color);
    color: var(--nav-text-color);
    height: 6rem;
    padding: 0 2.4rem;
}

ul {
    display: flex;
    list-style: none;
    gap: 3rem;
}
```

<br>

## header 2

<img src="./IMG/header2.png" alt="header 2">

<br>

o que muda do primeiro é isto.

``` HTML
<nav>
    <a href="#" class="logo">🚀 LOGO</a>
    <ul>
        <li>Sobre</li>
        <li>Serviços</li>
        <li>Dopoimentos</li>
        <li>
            <a href="#" class="button">Contato</a>
        </li>
    </ul>
</nav>
```

<br>

``` CSS
nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: var(--nav-bg-color);
    color: var(--nav-text-color);
    height: 6rem;
    padding: 0 2.4rem;
}

ul {
    display: flex;
    list-style: none;
    gap: 3rem;
    align-items: center;
}
```

<br>

## header 3

<img src="./IMG/header3.png" alt="header 3">

<br>

o que muda do segundo é isto

``` CSS
nav {
    display: flex;
    flex-direction: row-reverse;
    justify-content: space-between;
    align-items: center;
    background-color: var(--nav-bg-color);
    color: var(--nav-text-color);
    height: 6rem;
    padding: 0 2.4rem;
}
```

<br>

## header 4

<img src="./IMG/header4.png" alt="header 4">

<br>

o que muda do terceiro é isto

``` HTML
<nav>
    <ul>
        <li>Sobre</li>
        <li>Serviços</li>
        <li>
            <a href="#" class="logo">🚀 LOGO</a>
        </li>
        <li>Dopoimentos</li>
        <li>
            <a href="#">Contato</a>
        </li>
    </ul>
</nav>
```

<br>

``` CSS
nav {
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: var(--nav-bg-color);
    color: var(--nav-text-color);
    height: 6rem;
    padding: 0 2.4rem;
}
```