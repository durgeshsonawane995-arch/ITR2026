# CSS Grid

CSS Grid is a 2-dimensional layout system used to arrange items in rows and columns.It helps create complex web layouts easily.

Example:-

HTML

<div class="container">
    <div class="item">1</div>
    <div class="item">2</div>
    <div class="item">3</div>
    <div class="item">4</div>
</div>

CSS

.container{
    display: grid;
    grid-template-columns: 100px 100px;
    grid-template-rows: 100px 100px;
    gap: 10px;
}

.item{
    background-color: lightblue;
    border: 1px solid black;
    text-align: center;
}

    This code creates a 2X2 CSS Grid with four items arranged in rows and columns,each having a size of 100px X 100px and a 10px gap between them.

    