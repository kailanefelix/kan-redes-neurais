# 🔮 Pykan Neural Networks

## Pykan 

![image](https://github.com/kailanefelix/kan-redes-neurais/assets/89281114/991ff334-77b5-4a2b-ade4-037555d3e444)


Redes de Kolmogorov-Arnold (KANs) são uma proposta de arquitetura de rede neural inspirada no teorema de representação de Kolmogorov-Arnold. Essa abordagem é considerada uma alternativa promissora às Perceptrons de Múltiplas Camadas (MLPs) usadas em modelos de aprendizado profundo.

### 📈 Características Principais

- **Funções de Ativação Aprendíveis**: Em vez de ter funções de ativação fixas nos nós (neurônios), as redes KAN têm funções de ativação aprendíveis nos efeitos (pesos).
- **Sem Peso Linear**: Todas as variáveis de peso são substituídas por funções univariadas parametrizadas como spline.
- **Desempenho e Interpretabilidade**: As redes KAN demonstraram melhor desempenho e interpretabilidade em comparação com as MLPs em tarefas de ajuste de dados e resolução de equações diferenciais parciais.

### 📚 Recursos Úteis
- [Repositório do projeto original com a implementação do modelo](https://github.com/KindXiaoming/pykan)
- Vídeos explicando a teoria de funcionamento do modelo:
  - [Kolmogorov Arnold Networks (KAN) Paper Explained - An exciting new paradigm for Deep Learning?](https://www.youtube.com/watch?v=7zpz_AlFW2w&t=3s)
  - [Was "Machine Learning 2.0" All Hype? The Kolmogorov-Arnold Network Explained](https://www.youtube.com/watch?v=xLnQtLpPH-Y)
  - [Why the world NEEDS Kolmogorov Arnold Networks](https://www.youtube.com/watch?v=vzUkThsQa9E)
  - [Didn't Graduate Guide to: Kolmogorov-Arnold Networks](https://www.youtube.com/watch?v=3XAW0kqbH2Q)
- Artigos e explicações adicionais:
  - [Aliger - Inteligência Artificial: Redes de Kolmogorov Arnold (KANs)](https://aliger.com.br/inteligencia-artificial-redes-de-kolmogorov-arnold-kans-aliger/)
  - [Towards Data Science - Kolmogorov Arnold Networks (KAN)](https://towardsdatascience.com/kolmogorov-arnold-networks-kan-e317b1b4d075?gi=eca7a0811510)
  - [arXiv - Kolmogorov-Arnold Networks](https://arxiv.org/abs/2404.19756)

## 📥 Instalação

Pykan pode ser instalado via PyPI ou diretamente do GitHub.

### Pré-requisitos

- Python 3.9.7 ou superior
- pip

### Instalação via GitHub

1. Crie e ative um ambiente virtual:

    ```sh
    python -m venv pykan-env
    source pykan-env/bin/activate  # No Windows use `pykan-env\Scripts\activate`
    ```

2. Instale o Pykan do GitHub:

    ```sh
    pip install git+https://github.com/KindXiaoming/pykan.git
    ```

### Instalação via PyPI

1. Crie e ative um ambiente virtual:

    ```sh
    python -m venv pykan-env
    source pykan-env/bin/activate  # No Windows use `pykan-env\Scripts\activate`
    ```

2. Instale o Pykan do PyPI:

    ```sh
    pip install pykan
    ```

### Opcional, mas Recomendado: Criar um Ambiente Virtual para o Projeto

#### Para quem usa Conda

1. Crie e ative um ambiente virtual:

    ```sh
    conda create --name pykan-env python=3.9.7
    conda activate pykan-env
    ```

2. Instale o Pykan:

    ```sh
    pip install git+https://github.com/KindXiaoming/pykan.git  # Para instalação via GitHub
    # ou
    pip install pykan  # Para instalação via PyPI
    ```

3. Instale os requirements:

    ```sh
    pip install -r requirements.txt
    ```

#### Para quem não usa Conda

1. Crie e ative um ambiente virtual:

    ```sh
    python -m venv pykan-env
    source pykan-env/bin/activate  # No Windows use `pykan-env\Scripts\activate`
    ```

2. Instale o Pykan:

    ```sh
    pip install git+https://github.com/KindXiaoming/pykan.git  # Para instalação via GitHub
    # ou
    pip install pykan  # Para instalação via PyPI
    ```

3. Instale os requirements:

    ```sh
    pip install -r requirements.txt
    ```
