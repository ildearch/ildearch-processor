# Processador EICMC
### E*xtendidas*
### I*nstrucoes do* 
### C*omputador do*
### *IC*MC

[![en](https://img.shields.io/badge/lang-en-red.svg)](./README.md)

Essa é uma tentativa em deselvolver uma versao atualizada do 
[Processador-ICMC](https://github.com/simoesusp/Processador-ICMC), com
uma arquitetura similar.

Esse projeto tem como objetivo:
- extender a arquitetura atual;
- usar código em HDL nao especifica de editor;
- adicionar testbenches para os componentes mais complexos (provavelmente usando o ModelSim para simular, mas tudo em VHDL)
- adicionar esquematicos dos componentes (no mínimo do processador)
- criar um pacote em VHDL do microprocessador;
- criar/recriar components de hardware como:
  - placa de video (de VGA, seguindo esses  [timings](http://www.tinyvga.com/vga-timing), basado
  [nesse video do Ben Eater](https://www.youtube.com/watch?v=AHYNxpqKqwo))
  - interface serial (novamente, baseado [nesse video do Ben Eater](https://www.youtube.com/watch?v=7aXbh9VUB3U))
  - interface PS/2 (adivinha, baseado [nesse outro video do Ben Eater](https://www.youtube.com/watch?v=l7rce6IQDWs))
  - placa de som ([talvez?](https://en.wikipedia.org/wiki/Sound_card), algumas FPGAs tem saida de audio...)
- criar macro components que nao dependem da FPGA (microprocessador, placa de video, interface serial, ...) que podem ser 
escolhidos para serem adicionados na entidade top-level.

## Atualmente Implementado

Nada ;)
