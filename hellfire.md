### configurar o compilador na máquina local

    download versão x64
    export PATH=$PATH:~/gcc-4.6.1/bin

### configurar o simulador

    make noc_3x2

### compilar uma aplicação (dentro do hellfire os)

    make sem_test

### para simular, use os passos:

  1. copiar os arquivos `bin` para o diretório `objects` do simulador: `cp codeX.bin ../mpsoc_sim/objects`
  2. simular a execução: `./mpsoc_sim 3 s`
  3. verificar a saída (arquivos `stdoutxx.txt` no diretório `reports`)
