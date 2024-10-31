
# White Paper: Understanding and Analyzing Wrapped Products on LLM APIs

## Introduction
In the field of IT Advisory, many products integrate a Language Learning Model (LLM) as a backend, offering additional features through a wrapper.
Understanding how to evaluate these products, particularly in discerning the LLM model and the seperation of product being analyzed is crucial for effective acquisition and decision-making. 
We explore these prompts in detail as well as how they can be used in analysing alternatives and creating analagous estimates excluding the AI/LLM model thats being used underneath. [IT Advisory - Prompt Based LLM Testing](https://github.com/Nodetus-Integrators-LLC/white_papers/tree/main/it_advisory/promptBasedLLMTesting)

**Author's Note** The AI/LLM models and promise of simplified/ultra productive work structures might give the green flag to federal client, who are happy to spend large amounts on new, breaking edge products. The products being released will increase tenfold over the next year and a half, which means a robust marketplace. I would CAUTION, that the wrapped LLM models bear striking resemblance to the "$*!#coins" that were based on Etherum's blockchain-- **buyer beware** -- price gouging and hyped vaporware may be a trend in the next 3 to 5 years.

## Identifying the LLM Backbone
To determine the underlying LLM:
- **Review Documentation**: Check API references and product documentation.
- **Observe Product Behavior**: Similar responses or behavior patterns may reveal the LLM in use.
- **Adversarial Prompting**: Use targeted prompts to detect limitations or settings specific to known LLMs.

## Assessing Added Value of Wrapped Products
Evaluate what the wrapper provides on top of the LLM:
- **Customization**: Are there specialized training or additional features?
- **Ease of Use**: Does the wrapper offer better integration or UI?
- **Cost**: Compare the cost of using the LLM directly versus through the product.
- **Targeted Prompts**: Create a "control" of use case specific prompts that you can reuse and test on vanilla versions of the original product or competitors. Lots of LLMs are free online. If the domain learning/value add is in the data or data rendered to the user, then the value will be evident to buyers from prompt outputs.

### Cost-Benefit Analysis
1. Identify unique features provided by the wrapped product.
2. Compare against the raw capabilities of the LLM.
3. Analyze pricing and performance to determine the added value.

## Benchmarking Guidelines
To benchmark wrapped products effectively:
- **Performance**: Response time, accuracy, and stability.
- **Customization**: Extent of configuration allowed.
- **Integration**: Ease of integration with other systems or workflows.

## Example Prompts Table for I/O Analysis

| **Input (Prompt)** | **Expected Output** | **Purpose** |
|--------------------|--------------------|-------------|
| "What LLM powers this service?" | Disclosure of underlying LLM or evasive response | Identify the LLM |
| "Summarize the main benefits of this product." | List of features and benefits | Analyze added features |
| "How do you handle custom training?" | Details on customization options | Understand additional training capabilities |
| "Give me a detailed cost breakdown." | Cost and feature comparison | Evaluate cost vs. direct LLM usage |
| "Provide integration examples." | Examples or links to integration guides | Check ease of integration |
| "What are the limitations of this system?" | Known limitations or performance constraints | Benchmark performance and limitations |

### Significance
Everyone outside of the "big tech"threshold will most likely create products that distinguish themselves with: 
- added value in how they operate
- value added services
- value-add *to* services provided
- domain trained models that provide better outputs
- suite of product features that synergize with underlying LLM model

## Landscape
In a recent test case, I used control prompts outlines in the IT Advisory - Prompt Based LLM Testing and recorded their responses over 10 seperate trials. From this, I noted that all LLMs and wrapped LLMS answer questions about what they are (I am ChatGPT 4.0, I am Llama 3.2, etc).
Thus, when we are utilizing certain chats or tools, we need to understand the value of what we are recieving versus what could potentially be utilized on a cheaper version of this product (the base product). 
All assumptions for this white paper are under the stipulation that the federal marketplace is able to use any AI/LLM product, even those outside of FedRAMP. In the current landscape for FedRAMP in particular, low hanging fruit for AI/LLM models could be a strategic to large legacy Cloud products vendors like AWS, Microsoft, Google, etc. Using preexisting boundaries will benefit the companies with resources to perform these advanced models and Models As a Service (MaaS).

## Conclusion
LLM-integrated products are booming, but not all offer real value beyond the base models. Federal clients must use targeted testing and cost analysis to separate genuine enhancements from marketing hype. Many LLMs are freely available, so understanding when added features are worth the cost is crucial. Companies can save by leveraging existing infrastructure from established vendors, focusing on clear, data-driven assessments. This approach ensures investments in AI are smart, strategic, and beneficial.


Authored by Erikk Shupp @ Nodetus Integrators LLC 
