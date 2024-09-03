# BioTutor: Your personalised AI BioTutor!

Unlock the potential of GPT-4 with AI BioTutor, a customisable prompt that delivers a personalised learning experience. Primarily tuned for University of Edinburgh Students studying Bioelectronics with Prof. Adam A. Stokes, but open to anyone who wishes to explore this prompt. 

## Table of Contents
- [Welcome to your personalised AI BioTutor!](#biotutor)
  - [Table of Contents](#table-of-contents)
  - [Why BioTutor?](#why-biotutor)
  - [Requirements and Compatibility](#requirements-and-compatibility)
    - [Recommended](#recommended)
    - [Not Recommended](#not-recommended)
  - [Quick Start Guide](#quick-start-guide)
- [Prompt Formats](#prompt-formats)
- [AI Tutor Personalisation Options](#ai-tutor-personalisation-options)
  - [Commands](#commands)

## Why BioTutor?
BioTutor allows you to:
- Adjust the depth of knowledge to match your learning needs.
- Customise your learning style, communication type, tone, and reasoning framework.
- Import the course guide to ELM enabling you to check your progress against the step by step framework of the course.

## Requirements and Compatibility

### Recommended
- Use the University of Edinburgh ELM (Edinburgh Large-Language Model via elm.edina.ac.uk), or another GPT-4 interface.

### Not Recommended
- Default and Legacy GPT-3.5

## Quick Start Guide
1. Visit [ELM](https://elm.edina.ac.uk/)
2. Import the course guide as a document (Download from the LEARN environment).
3. Copy and paste the contents of BioTutor.json into the prompt.
4. Let BioTutor guide you through your personalised configuration process.
5. Start learning!

# Prompt Format
BioTutor is written in `json` format. 


# AI Tutor Personalisation Options

This section outlines the various configuration options available to students using the AI Tutor. These options can be modified to customise the learning experience.

| Configuration      | Options                                                                                                                                                                      |
|--------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Depth              | 1. Surface level understanding<br>2. Expanded understanding<br>3. Detailed analysis<br>4. Practical application<br>5. Advanced concepts<br>6. Critical evaluation<br>7. Synthesis and integration<br>8. Expert insight<br>9. Specialisation<br>10. "Cutting-edge research"
| Learning Styles    | Sensing, Visual* (requires plugins), Inductive, Active, Sequential, Intuitive, Verbal, Deductive, Reflective, Global                                                         |
| Communication      | Stochastic, Formal, Textbook, Layman, Storytelling, Socratic, Humorous                                                                                                       |
| Tone Styles        | Debate, Encouraging, Neutral, Informative, Friendly                                                                                                                          |
| Reasoning Frameworks| Deductive, Inductive, Abductive, Analogical, Casual                                                                                                                          |
| Update Rate        | Check, Don't check                                                                                                                                        |

## Commands

The AI Tutor supports the following commands:

- `/feedback`: Request feedback from the AI Tutor.
- `/test`: Request a test to assess your knowledge and understanding.
- `/config`: Update your AI Tutor configuration/preferences.
- `/plan`: Create a lesson plan based on your preferences.
- `/search`: Search for specific information (*requires plugins*).
- `/start`: Start the lesson plan.
- `/stop`: Stop the lesson plan.
- `/continue`: Continue the output if it was cut.






