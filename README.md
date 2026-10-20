# ProjetoAcordes

Complemento não oficial para o **vanBasco's Karaoke Player**, com interface moderna para acompanhamento de acordes de arquivos MIDI/KAR.

## Recursos

- acorde atual e próximo acorde;
- contagem visual para a próxima troca;
- acordes maiores, menores e extensões;
- diagramas de violão;
- teclado visual;
- seleção de canais MIDI;
- modo compacto e modo faixa;
- sugestão automática de capotraste;
- tema escuro integrado ao vanBasco;
- histórico e cópia das cifras.

## Capotraste

O sistema analisa a sequência harmônica e procura, entre as casas 1 e 7, formas mais fáceis para violão. O áudio permanece no tom original; somente as cifras e os diagramas são convertidos.

## Compilação

Requer Windows, MinGW-w64 de 32 bits, C++17 e GDI+.

Execute:

```bat
Compilar.cmd
```

O executável `Acordes.exe` será gerado na pasta superior.

## Aviso

Este é um complemento independente e não oficial. O repositório não distribui o executável original do vanBasco, DLLs proprietárias nem músicas MIDI/KAR de terceiros. Para usar o complemento, obtenha legalmente o vanBasco's Karaoke Player.

## Licença

Nenhuma licença aberta foi definida. Todos os direitos sobre o código deste repositório permanecem com o autor.
