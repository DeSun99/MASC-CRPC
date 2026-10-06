# MASC: A Multi-Agent Self-Calibration Framework with Latent Construct Alignment for Consistent Client Role-Playing in Psychological Counseling

> **Code and data are coming soon.**
>
> This repository currently provides a high-level overview of MASC and CRPC-Bench. The implementation, evaluation pipeline, and research resources are being prepared for release.

## Overview

Reliable client simulation for psychological counseling requires more than fluent responses. A simulated client should preserve stable profile and personality characteristics while expressing appropriate turn-level changes in psychological state, communicative action, and emotion.

**MASC** is a Multi-Agent Self-Calibration framework designed to improve the psychological coherence of client role-playing in multi-turn counseling conversations. It combines construct-guided generation, collaborative multi-agent refinement, consistency verification, and memory-based revision in a closed calibration loop.

We also introduce **CRPC-Bench**, a Client Role-Playing Consistency Benchmark for evaluating both stable session-level characteristics and evolving turn-level psychological dynamics.

## Highlights

- **Latent construct alignment** across profile information, Big-Five personality traits, psychological state, communicative action, and emotion expression.
- **Multi-agent debate** for generating and collaboratively refining candidate client responses.
- **Voting-based calibration** for detecting mismatches between intended and expressed psychological constructs.
- **Retry memory** for converting previous inconsistencies into targeted feedback for subsequent revisions.
- **Unified consistency evaluation** at both the session and dialogue-turn levels.

## Framework

MASC follows a closed self-calibration loop:

1. Infer the target turn-level latent constructs from the current dialogue context.
2. Generate and refine candidate responses through multi-agent debate.
3. Verify candidate responses using consistency-aware voting.
4. Record construct-level mismatches and revise the response when necessary.
5. Commit the calibrated response to the conversation history.

## CRPC-Bench

CRPC-Bench organizes client role-playing consistency into two complementary levels:

- **Session level:** profile information, receptivity, and Big-Five personality traits.
- **Turn level:** psychological state, communicative action, and emotion expression.

Dataset access and evaluation resources will be provided after the required licensing, privacy, and release reviews are complete.

## Release Plan

- [ ] Paper and citation information
- [ ] Core MASC implementation
- [ ] Multi-agent debate and calibration modules
- [ ] CRPC-Bench evaluation pipeline
- [ ] Configuration and reproducibility examples
- [ ] Data access instructions, subject to license and privacy review

## Code and Data

The source code and research data are currently being prepared for release.

**Coming soon. Stay tuned!**

## Responsible Use

This project is intended for research on conversational simulation, client role-playing, and counselor training. It is not a medical device, diagnostic system, or substitute for qualified mental-health professionals. Generated conversations must not be interpreted as clinical advice.

## Acknowledgements

This project builds on prior research in consistent client simulation for motivational interviewing. Complete acknowledgements and third-party resource notices will be included with the public release.

## Citation

Citation information will be added when the accompanying paper is publicly available.
