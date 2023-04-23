 <!-- Sessão 01: Construindo Layouts -->

<!-- Exercício 01 -->

[x] Crie um container com cor de background verde;
[x] Quando atigir MD, deve ficar azul;

<div class="bg-green-500 md:bg-blue-400">

<!-- Exercício 02 -->

[x] Crie um container com três divs no HTML;
[x] Deixe as divs internas inline utlizando o display;
[x] Todas devem ter backgrounds diferentes;
`

<div class="container bg-red-100 m-6 p-6">
<div class="bg-purple-300 inline-block">Div 1</div>
<div class="bg-blue-300 inline-block">Div 2</div>
<div class="bg-green-300 inline-block">Div 3</div>
</div>
`
<!-- Exercício 03 -->

[x] Crie um container com a altura determinada;
[x] Posicione uma div dentro deste container no canto inferior direto;

 <!-- Exercício 04 -->

`<div class="container h-10 m-6 bg-blue-400 relative">

  <p>Exercício 03</p>
  Container
  <div class="absolute bottom-0 right-0 bg-teal-300">
    Conteudo no canto direito
  </div>
</div>
`
 <!-- Exercício 05 -->

[x] Crie 3 elementos;
[x] Cada um deve sobrepor o outro no HTML por meio do Z-index;
[x] Incluir cores diferentes;

`  <div class="container relative">
      <div class="bg-pink-800 h-20 w-20 p-6 absolute z-10">Posição 1</div>
      <div class="bg-pink-500 h-20 w-20 p-6 absolute m-8">Posição 2</div>
      <div class="bg-purple-500 h-20 w-20 p-6 absolute m-20">Posição 3</div>
    </div>`

 <!-- Sessão 02: Flexbox com Tailwind -->

 <!-- Exercício 05 -->

[x] Crie um container com flex;
[x] Layout colunar;
[x] Seis items com cores diferentes;
