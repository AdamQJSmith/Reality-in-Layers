# Reality-in-Layers

## The "Why"

This project does not aim to invent new philosophical categories. The ideas of thinkers like John Searle and Karl Popper are powerful, but academic frameworks can often feel dense and clumsy when used as practical tools for communication.

The goal of this project is to create a framework that prioritizes **elegance and utility** over exhaustive philosophical rigor.

## Our Contribution: A Practical Map

This framework is a "workbench diagram" that separates the "what" from the "how" to allow for a more productive conversation.

**The "What": The Four Layers of Reality**
The map first identifies four fundamental, ontologically distinct layers of reality—realms that categorize where everything that exists resides—each filtering and enabling the others:
1.  **Layer 1: Physical (L1):** The bedrock of mind-independent matter and energy.
2.  **Layer 2: Biological (L2):** Living systems that are foundational to and constrain our experience.
3.  **Layer 3: Subjective (L3):** The irreducible, first-person reality of "what it's like" to be a conscious being.
4.  **Layer 4: Intersubjective (L4):** The shared reality of abstract constructs like language, logic, and culture.

**The "How": The Process of Objectification**
Separate from these layers, this is the human activity where knowledge is forged. The process draws evidence from any of the four layers, adapts tools based on each layer's unique texture (with flexibility for cross-layer integration, e.g., weaving biological insights into subjective moral theories), and produces shareable artifacts (e.g., theories, norms) that reside in Layer 4. It uses tools from Layer 4 (logic, language) to build claims that can withstand public scrutiny and consensus.

By clearly separating the ontologically distinct layers of reality from the cross-layer process of validation, this framework provides an elegant map that helps us understand why different fields have different methods, without ranking them in a hierarchy of "objectivity."

```mermaid
graph TD;
    subgraph "The Four Layers of Reality (The 'What')"
        L1["<b>L1: Physical</b><br/>(Matter, energy, physical law)"]
        L2["<b>L2: Biological</b><br/>(Living systems, biological laws, senses, neural infrastructure)"]
        L3["<b>L3: Subjective</b><br/>(Conscious experience)"]
        L4["<b>L4: Intersubjective</b><br/>(Language, logic, theories, norms)"]
    end

    subgraph "The Process of Objectification<br/>(The 'How')"
        direction LR
        P["<b>The Process</b><br/>A human activity of:<br/>- Formulating claims<br/>- Applying logical/formal tools<br/>- Public scrutiny & debate<br/>- Consensus-building"]
    end

    L1 -- "<b>Is Foundational To</b>" --> L2
    L2 -- "<b>Enables & Constrains</b>" --> L3
    L3 -- "Articulates into" --> L4
    
    L1 -- "Physical Evidence" --> P
    L2 -- "Sensory Evidence" --> P
    L3 -- "Experiential Evidence" --> P
    L4 -- "Abstract Evidence<br/>(e.g. a formal system)" --> P
    L4 -- "Provides Tools<br/>(Logic, Language)" --> P
    
    P --> |"Produces Artifacts"| L4
    P --> |"Objective Knowledge"| K[Knowledge Claim]
```
