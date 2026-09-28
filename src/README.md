# Yz Tutorial  

>[!note] WIP

The first Yz "large" program, used mainly for dogfooding purposes. 

Shows a `Yz>` prompt and offer options. 

## Run

- Add the [Yz compiler](https://github.com/oscarryz/yz-docs) to the path. 

```bash
cd src
yzc run . 
```
Output: 

```
 oooooo   oooo
 `888.   .8'
  `888. .8'     oooooooo
   `888.8'     d'""7d8P
    `888'        .d8P'
     888       .d8P'  .P
    o888o     d8888888P

Yz :: v0.0.1 :: a language where everything is a block of code

async by default · structural typing · no null · nothing to install

type examples or documentation · tab completes · enter runs
___________________________________________________________________

Yz> help

commands:

examples — browse runnable snippets
docs     — open a topic in the side column
           about the yzc compiler
compile  —
run      — re-run the last snippet
clear    — empty the screen
help     — this list
exit     —

Yz>
```
