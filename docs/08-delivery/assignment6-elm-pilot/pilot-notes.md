# Assignment 6 — ELM Local Model Pilot

## Environment
- Runtime: Ollama 0.34.0
- Coding agent installed: Aider 0.86.2
- Models tested: qwen2.5-coder:7b, qwen2.5:7b, starcoder2:7b
- Qwen models: Q4_K_M, approximately 7.6B parameters
- StarCoder2:7b: separate model family; detailed quantization not verified here

## Recorded runs
- qwen2.5-coder:7b corrected analysis: 491.6 seconds.
- qwen2.5:7b analysis: 688.6 seconds.
- starcoder2:7b broad run: interrupted after excessive repetitive output.
- starcoder2:7b focused run: 9974.5 seconds; returned unrelated Workflow Foundation documentation.

## Observations
- Qwen2.5-Coder produced a partially relevant workflow inventory but did not satisfy the requested report structure.
- Qwen2.5 produced use-case/workflow mappings that still require validation.
- StarCoder2 produced repetitive malformed output in one run and irrelevant output in another.
- The initial prompt-only baseline is preserved separately.
- The corrected Qwen analyses used five specification files, not the complete ELM specification set.

## Limitations
- No ELM application code was generated.
- No frontend, backend, database, integration, or build tests were performed.
- Workflow identifiers and mappings have not been fully validated against the authoritative traceability matrix.
- These runs do not establish a successful coding-agent implementation or a definitive overall model winner.

## Next steps
1. Confirm the assigned module code, specification path, and mentor approval requirements.
2. Validate the useful model output against the authoritative ELM specifications.
3. Complete the required implementation and tests only after the assignment requirements and approval gates are clear.
4. Record any further model trials with reproducible inputs and runtimes.
5. Submit only reviewed work through a personal fork and appropriate pull request.
