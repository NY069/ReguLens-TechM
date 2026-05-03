# ReguLens - AI Regulatory Compliance Platform

ReguLens is a sophisticated AI compliance audit platform designed to help organizations navigate complex regulatory frameworks such as the EU AI Act, NIST AI RMF, and ISO 42001. It leverages a tri-agent architecture to provide verified, traceable, and persona-aware answers to regulatory questions.

## Features

*   **Tri-Agent Pipeline**: A robust system comprising Retrieval, Synthesis, and Critic agents to ensure accuracy and prevent hallucinations.
    *   **Agent I (Retrieval)**: Ingests and semantically searches regulatory documents.
    *   **Agent II (Synthesis)**: Generates context-grounded, persona-aware answers.
    *   **Agent III (Critic)**: Verifies claims against source context using Natural Language Inference (NLI).
*   **Advanced Features**: Includes Query Decomposition, AI Model Fairness Validation, and Multi-modal input processing.
*   **Live Data Ingestion (Agent IV)**: Monitors and ingests real-time regulatory updates from sources like EUR-Lex and NIST CSRC.
*   **Interactive Demo**: A live voice-enabled dashboard showcasing claim verification and persona-based analysis.
*   **Enterprise-Grade Aesthetic**: Designed with a dark, authoritative visual identity, precise typography, and purposeful animations.

## Deployment

This website is designed to be self-contained and compatible with GitHub Pages. To deploy:

1.  **Create a new GitHub repository.**
2.  **Upload the `index.html` and `README.md` files** to the root of your repository.
3.  **Create an empty file named `.nojekyll`** in the root of your repository.
4.  **Enable GitHub Pages** for your repository, selecting the `main` branch (or your primary branch) as the source.

Your ReguLens demo website will be live at `https://<your-username>.github.io/<your-repository-name>/`.

## Technologies Used

*   **HTML5, CSS3, JavaScript**: For the core structure, styling, and interactive elements.
*   **Google Fonts**: Syne (display) and DM Sans (body) for typography.
*   **Web Speech API**: For the voice demo functionality.
*   **IntersectionObserver**: For scroll-triggered animations.

## Contact

For more information, please refer to the project documentation or contact the ReguLens team.
