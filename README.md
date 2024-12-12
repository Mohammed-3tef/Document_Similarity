# Document Similarity

A high-performance C++ program for computing the similarity between text documents. Designed for tasks such as plagiarism detection, duplicate content analysis, and document clustering, this tool delivers accuracy and efficiency for both small and large datasets.

---

## 🌟 Features

- **Multiple Similarity Metrics**: Includes algorithms like cosine similarity, Jaccard similarity, and more.
- **Text Preprocessing**: Handles tokenization, case normalization, stopword removal, and stemming.
- **Scalable**: Optimized for handling large datasets and multiple comparisons.
- **Configurable**: Easily extend or modify to suit specific text analysis needs.

---

## 📂 Project Structure

```
Document_Similarity/
├── src/                # Source code files
├── include/            # Header files
├── samples/            # Example input documents
├── build/              # Directory for compiled files (generated)
├── Makefile            # Build system configuration
├── README.md           # Project documentation
└── LICENSE             # License information
```

---

## 🚀 Getting Started

### Prerequisites

Before using the program, ensure you have the following installed:
- **C++17 or newer**: Required for compilation.
- **Make**: For building the project.
- **CMake** *(optional)*: For advanced build configuration.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Mohammed-3tef/Document_Similarity.git
   cd Document_Similarity
   ```

2. Compile the program:
    - Using `Make`:
      ```bash
      make
      ```
    - Using `CMake`:
      ```bash
      mkdir build && cd build
      cmake ..
      make
      ```

3. The executable file will be created in the `build/` or project root directory.

---

## 👨‍💻 Contributing

We welcome contributions from the community! To contribute:
1. Fork the repository.
2. Create a feature branch: ``git checkout -b feature-name``
3. Commit your changes: ``git commit -m "Add feature or fix a bug"``
4. Push to your fork and open a pull request.

---

## ✍️ Authors:

- **Name**: Mohammed Atef Abd El-Kader
- **ID**: 20231143
- **Version**: 1.0
- **Date**: 15 Nov. 2024

---

## 📝 License

This project is licensed under the [MIT License](https://github.com/Mohammed-3tef/Document_Similarity/blob/main/LICENSE). You are free to use, modify, and distribute this software under the terms of the license.