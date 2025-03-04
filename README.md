# Esteganografia em C

Projeto para ocultar e extrair texto de imagens em formato **PGM**. Usa bits menos significativos dos pixels para inserir dados sem comprometer a aparência da imagem.

## Funcionalidades
- **Leitura/Escrita** de arquivos PGM e textos
- **Cálculo** automático dos parâmetros de esteganografia (**b** e **d**)
- **Codificação** (oculta texto na imagem)
- **Decodificação** (extrai texto da imagem esteganografada)
- **Modo Verborrágico** para depuração detalhada

## Como Usar
1. **Compilar**:  
   `gcc -o esteganografia esteganografia.c`
2. **Executar**:  
   `./esteganografia`
3. **Escolher** a operação desejada (codificar, decodificar etc.)

## Estrutura de Arquivos
- **esteganografia.c**: Implementa todas as funções (LeDesenho, Codifica, etc.)
- **arquivo.pgm**: Imagem em formato PGM (ASCII)
- **texto.txt**: Texto a ser ocultado ou extraído

---
