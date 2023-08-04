# Detecção de Tons de Vermelho em Vídeos usando Algoritmo em Python

Este projeto tem como objetivo desenvolver um algoritmo capaz de detectar diferentes tons de vermelho em vídeos, permitindo uma análise mais precisa dessas áreas específicas. O algoritmo foi desenvolvido em Python e utiliza as bibliotecas OpenCV e NumPy.

## Pré-requisitos

Para executar o algoritmo, é necessário ter o Python instalado no sistema, juntamente com as bibliotecas OpenCV e NumPy. Caso ainda não possua essas bibliotecas, você pode instalá-las utilizando o gerenciador de pacotes pip:

```
pip install opencv-python
pip install numpy
```

## Como usar o algoritmo

1. Faça o download ou clone este repositório para o seu computador.
2. Certifique-se de ter os vídeos que deseja analisar no mesmo diretório que o código Python.
3. Abra o arquivo do código Python em um editor de texto ou IDE de sua preferência.
4. No código, localize as variáveis `path` em ambas as partes e ajuste o caminho para o diretório onde estão os vídeos. Por exemplo:

```python
path = "C:/Users/SeuUsuario/Desktop/Caminho/Para/Seu/Diretorio/De/Videos/"
```

5. Execute o código Python e aguarde a detecção dos tons de vermelho nos vídeos.
6. Ao exibir o vídeo, apenas as regiões vermelhas serão mostradas.

## Atenção

- O código foi desenvolvido para funcionar com vídeos no formato .mp4. Verifique se seus vídeos estão nesse formato para um funcionamento adequado.
- O algoritmo utiliza três faixas diferentes de vermelho para adaptar-se a diversas situações. Caso deseje ajustar os níveis de vermelho, você pode modificar as variáveis `vermelho_escuro1`, `vermelho_claro1`, `vermelho_escuro2`, `vermelho_claro2`, `vermelho_escuro3` e `vermelho_claro3` no código.

## Conclusão

Espero que este projeto seja útil para a detecção de tons de vermelho em vídeos e possa ser uma base para o desenvolvimento de aplicações mais complexas. Caso tenha dúvidas ou precise de ajuda, fique à vontade para entrar em contato.

**Obrigado pela utilização deste algoritmo!**

Autor: Ademar Castro
Contato: ademar.castro.curriculo@gmail.com