# TicTacToe-GNN 🎮

TicTacToe-GNN is an AI-powered Tic Tac Toe game built using a Graph Neural Network (GNN) model. The AI provides intelligent move suggestions to enhance gameplay, offering a challenging experience even for seasoned players.



[![Deploy on Colab](https://img.shields.io/badge/Deploy-Google_Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)](https://colab.research.google.com/drive/1YhllCzI6p3VS3NRTKqo6mkPvCgi_7HHA?usp=sharing)


[![Deploy on Hugging Face](https://img.shields.io/badge/Deploy-Hugging%20Face-ffd500?style=for-the-badge&logo=huggingface&logoColor=white)](https://huggingface.co/spaces/lekhsisodiya/GNNTicTacToe)

## Technologies Used 🛠️
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![PyTorch Geometric](https://img.shields.io/badge/PyTorch%20Geometric-3498DB?style=for-the-badge&logo=pyg&logoColor=white)
![IPyWidgets](https://img.shields.io/badge/IPyWidgets-000000?style=for-the-badge&logo=jupyter&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter%20Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

## UI Appearance 🖼️
![TicTacToe-GNN UI](https://github.com/lekh-ai/GNN-Based-Tic-Tac-Toe/blob/main/GNN%20TTT.png)

## Features ✨
- **AI-Powered Gameplay**: The GNN model suggests optimal moves during gameplay, making it a formidable opponent.
- **Interactive UI**: The game features an interactive interface built with `ipywidgets` for seamless user interaction.
- **Model-Driven Decisions**: The AI makes move decisions based on the current state of the board, using a pre-trained GNN model.


##Graph Neural Network (GNN) Overview 🧠
A Graph Neural Network (GNN) is a deep learning model tailored for graph-structured data, where entities (nodes) and their relationships (edges) are central.

### How It Works:
#### Nodes and Edges: Nodes represent entities, and edges represent their connections.
#### Message Passing: Nodes exchange information with their neighbors to update their features, capturing the graph's structure.
#### Graph Convolution: Like CNNs, GNNs aggregate neighbor information to update node embeddings.
#### Prediction: Final node embeddings are used to make decisions or predictions.

In Tic Tac Toe:
The GNN represents the board as a graph, analyzes connections between moves, and suggests the optimal next move based on the current game state.

## Deployments 🌐

The TicTacToe-GNN project can be deployed locally:

### Local Version
- Runs directly in a Jupyter Notebook.
- Interactive UI built using `ipywidgets` for an engaging gameplay experience.
- Also deployed in huggingface

## Example Gameplay 🧪

- **Starting the Game**: Simply run the notebook to start a new game. The AI will suggest moves for the 'O' player.
- **Player vs AI**: Take turns with the AI to see if you can outsmart the GNN-powered opponent.

## Future Development 🚀

- **Enhanced AI**: Further refine the GNN model to improve move prediction accuracy.
- **Additional Modes**: Introduce different difficulty levels and game modes, such as Player vs Player and AI vs AI.

Contact 📬
For more information or to get in touch, please email lekhsiosdiya@gmail.com
Phone number : 9179041912
