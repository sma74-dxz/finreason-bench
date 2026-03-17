# Architecture

## System components

1. Input
- User question
- Context documents or evidence sources

2. Retriever
- Retrieve relevant evidence snippets

3. Reasoner
- Generate a structured answer grounded in retrieved evidence

4. Evaluator
- Check citation support
- Check output format
- Check logical consistency and risk-related constraints

## Design principle
The system should prioritize grounded reasoning and explicit evaluation over fluent but unsupported outputs.