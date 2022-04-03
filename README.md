<h1 align="center">Patrao Lang</h1>
<p align="center">
<a href="https://www.npmjs.com/package/gurulang"><img alt="Build" src="https://img.shields.io/badge/npm-gurulang-orange"/></a>

</p>
<p align="center">
  <b>Patrao lang is a fun programming language forked from BhaiLang :)</b>
</p>
<p align="center">
Do checkout the online <a href="https://bnhede.github.io/patraolang/">Patrao Lang PlayGround</a>.
</p>
<br>

<h2 align="center">Installation</h2>

```
npm i -g patraolang
```

<h2 align="center">Usage</h2>

<h4 align="left">Create a new file (<code>test.patrao</code>)</h4>


<h4 align="left">Edit the file with a text editor.

```
Ae patrao
  Sang patrao "Hello Patrao";
Boren patrao

```

<h4 align="left">Run</h4>

```
patraolang test.patrao
```

<h4 align="left">Output</h4>

```
Hello Patrao
```

<h2 align="center">Documentation</h2>

<h3 align="center">General</h3>
<p align="center"><code>Ae patrao</code> is the entrypoint for the program and all program must end with <code>Boren patrao</code>. Anything outside of it will be ignored.</p>

```

This will be ignored

Ae patrao
// Write code here
Boren patrao

This too
```

<h3 align="center">Variables</h3>
<p align="center">Variables can be declared using <code>choy patrao</code>.</p>

```

Ae patrao
  choy patrao a = 10;
  choy patrao b = "two";
  choy patrao c = 15;
  a = a + 1;
  b = 21;
  c *= 2;
Boren patrao
```

<h3 align="center">Types</h3>
<p align="center">Numbers and strings are like other languages. Null values can be denoted using <code>goddo</code>. <code>khoren</code> and <code>fott</code> are the boolean values.</p>

```

Ae patrao
  choy patrao a = 10;
  choy patrao b = 10 + (15*20);
  choy patrao c = "two";
  choy patrao d = 'ok';
  choy patrao e = goddo;
  choy patrao f = khoren;
  choy patrao g = fott;
Boren patrao
```

<h3 align="center">Built-ins</h3>
<p align="center">Use <code>Sang patrao</code> to print anything to console.</p>

```
Ae patrao
  Sang patrao "Hello World";
  choy patrao a = 10;
  {
    choy patrao b = 20;
    choy patrao a + b;
  }
  Sang patrao 5, 'ok' , khoren , fott;
Boren patrao
```

<h3 align="center">Conditionals</h3>
<p align="center">Patraolang supports simple if else construct , <code>patrao jar</code> block will execute if condition is <code>khoren</code> and <code>najalear patrao</code> block will execute if condition is <code>fott</code>.</p>

```

Ae patrao
  Sang patrao a = 10;
  patrao jar (a < 25) jalear{
   Sang patrao "a is less than 25";
  } najalear patrao {
   Sang patrao "a is greater than or equal to 25";
  }
Boren patrao
```

<h3 align="center">Loops</h3>
<p align="center">Statements inside <code>patrao joparen</code> blocks are executed as long as a specified condition evaluates to <code>khoren</code>. If the condition becomes <code>fott</code>, statement within the loop stops executing and control passes to the statement following the loop. Use <code>puro jalen patrao</code> to break the loop and <code className="language-cpp">parat ghuvya patrao</code> to continue within loop.</p>


```
Ae patrao
  Sang patrao a = 0;
  patrao joparen (a < 10) {
   a += 1;
   patrao jar (a == 5) jalear{
    Sang patrao "patraoan mhanle ", a;
    parat ghuvya patrao;
   }
   guru eega (a == 6) aadre{
    puro jalen patrao;
   }
   Sang patrao a;
  }
  Sang patrao "done";
Boren patrao
```











