# Reality-in-Layers

## The "Why"

This project does not aim to invent new philosophical categories. The ideas of thinkers like John Searle and Karl Popper are powerful, but academic frameworks can often feel dense and clumsy when used as practical tools for communication.

The goal of this project is to create a framework that prioritizes **elegance and utility** over exhaustive philosophical rigor.

## Our Contribution: A Practical Map

This framework is a "workbench diagram" that separates the "what" from the "how" to allow for a more productive conversation.

**The Four Layers of Reality**
The framework identifies four ontological layers that categorize where everything exists, each filtering and enabling the others:
1.  **Layer 1: Physical (L1):** Matter, energy, physical law.
2.  **Layer 2: Biological (L2):** Living systems, biological laws, senses, neural infrastructure.
3.  **Layer 3: Subjective (L3):** Conscious experience.
4.  **Layer 4: Intersubjective (L4):** Language, logic, theories, norms.

**The Process of Objectification**
This process draws evidence from the four layers, integrates across layers (e.g., biological insights into subjective theories), and produces artifacts that reside in Layer 4. It uses tools from Layer 4 to formulate claims, conduct scrutiny, and build consensus.

This framework shows why fields use different methods and how objectivity works across layers.

```mermaid
graph TD;
    subgraph "The Four Layers of Reality"
        L1["<b>L1: Physical</b><br/>(Matter, energy, physical law)"]
        L2["<b>L2: Biological</b><br/>(Living systems, biological laws, senses, neural infrastructure)"]
        L3["<b>L3: Subjective</b><br/>(Conscious experience)"]
        L4["<b>L4: Intersubjective</b><br/>(Language, logic, theories, norms)"]
    end

    subgraph "The Process of Objectification"
        direction LR
        P["<b>The Process</b><br/>- Formulate claims<br/>- Apply tools<br/>- Scrutiny & debate<br/>- Build consensus"]
    end

    L1 -- "Is Foundational To" --> L2
    L2 -- "Enables & Constrains" --> L3
    L3 -- "Articulates into" --> L4
    
    L1 -- "Physical Evidence" --> P
    L2 -- "Sensory Evidence" --> P
    L3 -- "Experiential Evidence" --> P
    L4 -- "Abstract Evidence<br/>(e.g. a formal system)" --> P
    L4 -- "Provides Tools<br/>(Logic, Language)" --> P
    
    P --> |"Produces Artifacts"| L4
    P --> |"Objective Knowledge"| K[Knowledge Claim]
```
