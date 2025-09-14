# CNNs and RNNs

Specialized neural network architectures for specific data types.

**Convolutional Neural Networks (CNNs)**:
- **Convolutional Layers**: Apply filters to detect features (edges, textures)
- **Pooling Layers**: Reduce spatial dimensions while preserving important features
- **Architecture**: Alternating conv-pool layers followed by fully connected layers
- **Key Advantages**: Parameter sharing, translation invariance, hierarchical feature learning

**CNN Applications**:
- Image classification and recognition
- Object detection and segmentation
- Medical image analysis
- Autonomous vehicle perception

**Recurrent Neural Networks (RNNs)**:
- **Recurrent Connections**: Maintain memory of previous inputs
- **Long Short-Term Memory (LSTM)**: Specialized cells to handle long-term dependencies
- **Gated Recurrent Units (GRUs)**: Simplified LSTM variant
- **Bidirectional RNNs**: Process sequences in both directions

**RNN Applications**:
- Natural language processing (sentiment analysis, machine translation)
- Time series prediction (stock prices, weather forecasting)
- Speech recognition
- Music generation

**Common Challenges**:
- CNNs: Require large amounts of labeled data
- RNNs: Vanishing gradients, difficulty with very long sequences