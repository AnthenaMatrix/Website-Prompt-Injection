# Website Prompt Injection
Website Prompt Injection is a concept that allows for the injection of prompts into an AI system via a website's. This technique exploits the interaction between users, websites, and AI systems to execute specific prompts that influence AI behavior.


# How it Works
The process involves hiding prompts within the frontend code of a website, typically in a manner that remains invisible to human users. When a user requests the AI to access or interpret the content of the website, the AI system inadvertently reads the concealed prompts embedded within the website's frontend. 
If successful, the AI executes the injected prompt, leading to desired outcomes as dictated by the injected prompt.


# Purpose
The primary purpose of Website Prompt Injection is to demonstrate the potential vulnerabilities of AI systems when interacting with web-based interfaces. By showcasing this concept, we aim to raise awareness about the importance of robust security measures in AI systems, particularly in scenarios involving user-generated content and external interactions.


# Implementation
To implement Website Prompt Injection attack:
- Embed the desired prompt within the frontend code of the website, ensuring it remains hidden from human users, but notAI systems. You can use one of our html examples in this repository
- Ensure that the AI system interacts with the website's frontend code to interpret the content. This can be done by asking GPT4 or other systems to read the website and provide a summary.
- Upon reading the hidden prompt, the AI system should execute the specified action, influencing its behavior based on the injected prompt.


# Injection HTML Examples

### Injection Example 1: CSS Hidden Elements by Display

This example demonstrates Website Prompt Injection by embedding the prompt directly within the HTML markup of the webpage. The `<h2>` element containing the prompt is hidden from users using inline CSS (`display: none;`). Despite being hidden, the prompt is still accessible to AI systems that parse the webpage's content, allowing for interaction based on the injected prompt.

### Injection Example 2: CSS Hidden Elements

This example hides the `<h2>` element containing the prompt using CSS by setting its visibility to hidden. This ensures that the prompt is included in the HTML markup but remains invisible to users.

### Injection Example 3: JavaScript Injection

In this example, JavaScript is used to dynamically inject the prompt into the HTML content after the page has loaded. The `<h2>` element containing the prompt is created programmatically and appended to the document body, ensuring that it is present in the DOM but not visible to users.

### Injection Example 4: Comments

This example embeds the prompt within an HTML comment, making it invisible to users while remaining accessible to AI systems that parse HTML content.

### Injection Example 5: Data Attributes

In this example, the prompt is stored within a custom data attribute (`data-prompt`) of a `<div>` element. While the prompt is included in the HTML markup, it is not visible to users.


# Disclaimer
Website Prompt Injection is a proof-of-concept demonstration and should only be used for educational and research purposes. Engaging in unauthorized access or manipulation of AI systems without proper authorization is illegal and unethical. We do not condone the use of this technique for malicious purposes.


# License
This project is licensed under the MIT License.


# Support AnthenaMatrix
Bitcoin: bc1qxvvtgz0vf3n2cuxt0suvf39jleegpt9wawxazn

Ethereum: 0xE73E90779B3e8F6D65306B40E02878f437408b4E

BNB: 0xE73E90779B3e8F6D65306B40E02878f437408b4E

Dogecoin: D827LpfJu9pcVc3Kky82sTrNnsE7pLGqeV

Solana: AJtGEJvoVoS2eeqeHQvf7usRs2nSQM1yLtBSdKp1KBY5
