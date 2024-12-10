# EmotionDetect

### O EmotionDetect é um projeto que utiliza inteligência artificial para realizar a análise de emoções faciais em imagens. Através da biblioteca DeepFace, o sistema identifica a emoção dominante de uma pessoa em uma foto, como "Feliz", "Triste", "Surpreso", entre outras. O projeto também exibe a imagem original com a emoção detectada sobreposta diretamente nela.

## Funcionalidades:
- Baixa uma imagem de uma URL especificada.
- Realiza análise de emoções faciais usando DeepFace.
- Identifica a emoção dominante da face.
- Exibe a imagem com o texto da emoção sobreposta.

## Pré-requisitos:
Antes de rodar o código, instale as bibliotecas necessárias com o seguinte comando:
```
pip install opencv-python tensorflow requests Pillow
pip install deepface
pip install mtcnn
```
## Como usar:
1. Clone ou baixe o repositório.
2. Instale as dependências mencionadas acima.
3. No script, defina a URL da imagem que deseja analisar.
4. Execute o script e veja o resultado: a emoção dominante será exibida na imagem.

## Licença:
Esse projeto está licenciado sob a MIT License.

