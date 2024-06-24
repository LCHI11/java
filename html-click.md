1.Cambia el contenido de la etiqueta h1 con document.querySelector y asigna el siguiente texto: "Hora del Desafío".
let tituloDocumento=document.querySelector ('h1');
titulo.innerHTML="Hora del Desafío";

2.Crea una función que muestre en la consola el mensaje "El botón fue clicado" siempre que se presione el botón "Console".
<button onclick="mostarMensajeEnLaConsola()" class="button">Console</button>
function mostarMensajeEnLaConsola() {console.log('El botón fue clicado');}

3.Crea una función que se ejecute cuando se haga clic en el botón "prompt", preguntando el nombre de una ciudad de Brasil. Luego, muestra una alerta con el mensaje concatenando la respuesta
con el texto: "Estuve en {ciudad} y me acordé de ti".
<button onclick="mostrarAlerta()" class="button">Alert</button>
function mostrarAlerta(){ let ciudad=promt("Por favor, ingresa el nombre de una ciudad de Brasil:");
alert(`Estuve en ${ciudad} de Brasil`);}

4.Crea una función que muestre una alerta con el mensaje: "Yo amo JS" siempre que se presione el botón "Alerta".
<button onclick="alerta()" class="button">Alert</button>
function alerta(){alert("Yo amo JS");}
5.Al hacer clic en el botón "suma", pide 2 números y muestra el resultado de la suma en una alerta.
<button onclick="sumadenumeros()" class="button">suma</button>
function sumadenumeros(){let numero1=parseInt(promt('Ingresar el primer numeo'));
let numero2=parseInt(promt('Ingresar el numero 2'));}
let resultado= numero1 + numero2;
alert(` ${numero1} + ${numero2} = ${resultado}`);}
