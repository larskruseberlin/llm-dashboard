# LLM Comparison Dashboard

A lightweight, single-file web application for comparing responses from multiple Large Language Models side-by-side. Send the same prompt to ChatGPT, Claude, Gemini, and Manus simultaneously and analyze their outputs in real-time.

## Features

- **Multi-Model Comparison** — Query four leading LLM providers at once: OpenAI (ChatGPT), Anthropic (Claude), Google (Gemini), and Manus
- **Side-by-Side Display** — View all responses in parallel for easy comparison
- **Comparative Analysis** — Integrated analysis highlighting strengths, differences, and use-case recommendations
- **Clean UI** — Apple-inspired design with smooth animations, backdrop blur effects, and responsive layout
- **Zero Dependencies** — Single HTML file with embedded CSS and JavaScript—no build tools, no npm, no frameworks
- **Privacy-First** — Currently runs in demo mode with mock data; designed for future API integration

## Quick Start

1. Download `llm-dashboard.html`
2. Open it in any modern browser
3. Enter your prompt and click "Compare Models"

No installation, no configuration, no command line—just open and run.

## Current Status

**Demo Mode:** The dashboard currently uses mock responses to demonstrate functionality. API integration for live model queries is planned for future releases.

## Technical Details

- **Architecture:** Self-contained single-file application
- **Stack:** Vanilla HTML5, CSS3, JavaScript (ES6+)
- **Design System:** `-apple-system` font stack, rounded corners, subtle shadows, smooth transitions
- **Browser Support:** Modern browsers with ES6+ support (Chrome, Firefox, Safari, Edge)

## Use Cases

- **Model Selection** — Compare outputs to choose the right LLM for your specific task
- **Prompt Engineering** — Test how different models interpret the same prompt
- **Quality Assessment** — Evaluate response quality, tone, and accuracy across providers
- **Research & Education** — Understand differences in LLM behavior and capabilities

## Future Roadmap

- Live API integration for real-time model queries
- API key management
- Response export functionality
- Custom model configuration
- Response history and comparison tracking

## Design Philosophy

This project follows a minimalist, single-file architecture inspired by the simplicity of early web development—no build complexity, no dependency hell, just clean code that runs everywhere.



## Contributing

Contributions welcome. Please maintain the single-file architecture and zero-dependency approach.
