# Prompt Injection Attack Techniques Against AI Endpoints

## Overview

This repository, part of the **Hack The Box AI Red Teamer Path**, focuses on **Prompt Injection** attacks targeting **AI endpoints**. Prompt injection manipulates AI model inputs to achieve unintended or malicious behaviors. This project explores how prompt injection can exploit vulnerabilities in AI systems, demonstrating attack techniques, their impact, and strategies to mitigate these risks.

---

## Table of Contents

1. [Introduction to Prompt Injection](intro.md)

---

## Objectives

- Investigate prompt injection attacks on AI endpoints.
- Demonstrate common attack techniques and their impact.
- Share mitigation strategies to secure AI models from prompt injection.

## What is Prompt Injection?

Prompt injection occurs when malicious instructions are embedded within an AI model's input, altering its behavior. This can lead to data leaks, system manipulation, or unintended model responses. It exploits the fact that LLMs generate outputs based solely on the input prompts.

## Security Risks

Prompt injection attacks can:
- Leak sensitive data.
- Manipulate model behavior.
- Hijack AI systems to perform malicious actions.

## OWASP & Security Considerations

Prompt injection is a significant risk identified in **OWASP Top 10 for LLM Applications (2025)**, specifically under:
- **LLM01:2025 Prompt Injection**
- **LLM02:2025 Sensitive Information Disclosure**

For more details, refer to the [OWASP Top 10 for LLM Applications](https://genai.owasp.org/resource/owasp-top-10-for-llm-applications-2025/).

## Mitigation Strategies

- **Sanitize Inputs**: Validate all user inputs before passing them to the model.
- **Set Boundaries**: Restrict the model’s output scope to prevent manipulation.
- **Authentication**: Implement strong user authentication.
- **Monitor**: Regularly monitor AI behavior for abnormal activity.

## Project Structure

- **Demonstrations**: Examples of prompt injection techniques.
- **Exploit Techniques**: Breakdown of how prompt injection manipulates AI models.
- **Mitigation**: Best practices to secure AI endpoints.
