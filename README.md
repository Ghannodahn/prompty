# Prompty: AI Prompt Optimization Suite

Prompty is a collection of specialized AI assistants (GPTs) designed to help users craft clear, effective, and structured prompts for various AI tasks. Each Prompty variant focuses on a specific domain, ensuring optimized interactions and consistent results.

## Core Principles

-   **Clarity and Structure:** Generate well-organized prompts using Markdown.
-   **Specificity:** Define behavior, intent, and capabilities explicitly.
-   **Best Practices:** Incorporate established prompt engineering techniques.
-   **User Guidance:** Assist users in refining their goals and instructions.

## Prompty Components

### 1. Prompty McPromptyFace (`prompty-prompt`)
[Custom GPT](https://chatgpt.com/g/g-67eee3011e908191af19e7592b41400c-prompty-mcpromptface) | [Project Instructions](components/prompty-prompt/prompty-prompt.inst.md)

-   **Purpose:** General-purpose prompt optimization.
-   **Behavior:** Acts as an expert prompt writer, knowledgeable about various LLMs (ChatGPT, Gemini, Claude). Asks clarifying questions to ensure understanding before generating prompts.
-   **Capabilities:** Creates structured instruction sets defining AI behavior, intent, and capabilities. Emphasizes clarity and avoids hallucination. Generates prompts in a Canvas using Markdown.

### 2. Prompty McProjectFace (`prompty-gptproject`)
[Custom GPT](https://chatgpt.com/g/g-67eeea27909881918b8cd54ec372f69c-prompty-mcprojectface) | [Project Instructions](components/prompty-gptproject/prompty-gptproject.inst.md)

-   **Purpose:** Generating standardized instructions for GPT Projects.
-   **Behavior:** Operates as a systematic and precise prompt engineer. Uses a professional, instructional tone and follows a strict template. Does not include clarifying questions in the final output.
-   **Capabilities:** Produces high-quality, reusable Project Instructions documents defining task scope, behavior, and expectations for AI agents. Ensures outputs align with best practices for GPT Projects.

### 3. Prompty Image (`prompty-image`)
[Custom GPT](https://chatgpt.com/g/g-67f1fcb816188191a0f848d4104aa148-prompty-mcjourneyface) | [Project Instructions](components/prompty-image/prompty-image.inst.md)

-   **Purpose:** Assisting with the generation and refinement of prompts for image creation models.
-   **Behavior:** (Details to be defined - likely focuses on visual description, style guidance, and parameterization for models like Midjourney or DALL·E).
-   **Capabilities:** (Details to be defined - likely includes translating concepts into effective image prompts, suggesting stylistic variations, and structuring prompts for specific image AI platforms).
*Note: The specific instructions for `prompty-image` were not provided in the context.*

### 4. Deep Research Prompt Assistant (`prompty-research`)
[Custom GPT](https://chatgpt.com/g/g-67eeca4dcdc88191b69e74283663d83e-prompty-mcresearchface) | [Project Instructions](components/prompty-research/prompty-research.inst.md)

-   **Purpose:** Crafting optimized prompts for ChatGPT's Deep Research mode.
-   **Behavior:** Acts as a subject matter expert in AI prompt construction for research. Guides users to translate needs into precise, context-aware prompts.
-   **Capabilities:** Facilitates context anchoring, domain specificity, role-based output framing (academic, journalistic, etc.), and incorporates methods like few-shot learning. Educates users on prompt refinement.

## Prompty Utilities

### 1. Prompty Asset Generator (`prompty-media`)
[Project Instructions](components/util/prompty-media/prompty-media.inst.md)

-   **Purpose:** Automating the creation of media and support assets for the Prompty suite.
-   **Behavior:** Operates as a GPT-based content generator specializing in deployable assets. Maintains a clear, structured, professional tone.
-   **Capabilities:** Generates images/prompts (Midjourney, DALL·E), web assets (TSX/React), marketing media, text content (docs, changelogs), data files (JSON, CSV), and other media. Ensures assets are reusable, versioned, and compatible with target platforms (ChatGPT, Perplexity, Gemini, Claude, etc.).

## Usage

Each Prompty component is designed to be used as a custom GPT or integrated into relevant workflows to improve the quality and consistency of AI interactions within its specialized domain.
