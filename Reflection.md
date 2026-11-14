
# Reflection on AI-Assisted Documentation

### 1. What were the strengths and weaknesses of using AI to generate the documentation?
The primary strength of using AI was the speed at which it generated boilerplate Markdown structures. It immediately provided the standard sections expected in a professional README (Overview, Installation, Example Usage). The weakness was that the AI initially generated code blocks without specifying how to install the required R packages, and it occasionally missed the correct syntax for nested lists. I had to manually revise the "Installation" section to include the `install.packages()` command.

### 2. How did the AI assist you in following best practice standards for R Markdown?
The AI helped structure the `.Rmd` file by suggesting the YAML header format (title, author, output format) and correctly separating the code into specific "chunks" with the ```{r} syntax. This ensured that the R code was clearly distinguished from the plain text explanations, which is the core best practice of R Markdown. 

### 3. What ethical practices did you apply when using the AI tool?
I followed strict ethical guidelines by disclosing the use of ChatGPT in the README file and explicitly listing the exact prompts used. I did not copy the AI's output blindly; I manually validated the Markdown syntax by previewing the files to ensure there were no broken links or rendering errors. Furthermore, I did not upload any real or proprietary data to the AI; I used only the simulated, built-in Iris dataset.