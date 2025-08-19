```markdown
# 📸 Projeto DNC - Redução de Dimensionalidade em Imagens

Este projeto tem como objetivo demonstrar a redução de dimensionalidade em imagens, convertendo imagens coloridas (RGB) em escala de cinza e em preto e branco (binarização).  

O código foi desenvolvido em Python para ser executado no Google Colab e implementa as funções de conversão utilizando PIL + NumPy.

---

## 🔍 Conceito

Uma imagem colorida possui 3 canais de cor (R, G, B).  
Quando transformamos em escala de cinza, reduzimos para 1 único canal (0–255), aplicando a fórmula de luminância:  

```

Y = 0.299 \* R + 0.587 \* G + 0.114 \* B

```

Na binarização, aplicamos um limiar (threshold):  
- Pixels acima do valor → 255 (branco)  
- Pixels abaixo → 0 (preto)  

---

## 📂 Estrutura do Projeto

```

├── Projeto\_DNC.ipynb     # Notebook principal (Google Colab)
├── README.md             # Documentação
└── exemplo.png           # Exemplo de imagem (opcional)

````

---

## ⚙️ Tecnologias Utilizadas

- Python 3.x  
- [NumPy](https://numpy.org/)  
- [Pillow (PIL)](https://pillow.readthedocs.io/)  
- [Matplotlib](https://matplotlib.org/)  
- Google Colab  

---

## 🚀 Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/aacobos/Reducao_de_Dimensionalidade_em_Imagens.git
   cd Reducao_de_Dimensionalidade_em_Imagens
````

2. Abra o notebook no Google Colab:

   * Faça upload do arquivo `.ipynb` para o Colab.
   * Ou abra diretamente pelo link compartilhável do GitHub.

3. Execute as células:

   * Clique o **Escolher arquivos** no Colab.
   * O código abrirá a imagem, converterá para **escala de cinza** e depois para **binarizada**.

---

## 🖼️ Exemplo de Saída

Original → Escala de Cinza 
Original → Binarizada

<img width="818" height="495" alt="image" src="https://github.com/user-attachments/assets/f07a3627-0817-4f91-9dbd-b08d002c535f" />

---

## ✨ Funcionalidades

* [x] Upload de imagens no Colab
* [x] Conversão para escala de cinza
* [x] Conversão para binarização (0 ou 255)
* [x] Exibição lado a lado para comparação
